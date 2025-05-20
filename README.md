# 🟢 Simple Node.js App with GitHub Actions CI/CD

This is a basic Node.js project that includes:

- A simple function (`add`) in `index.js`
- A test suite using **Jest**
- A GitHub Actions CI/CD pipeline that:
  - Runs tests on every push to the `main` branch
  - Deploys the app to a remote Linux VM via SSH

---

## 🧠 What This App Does

This is a basic example of a function:

```js
function add(a, b) {
  return a + b;
}
