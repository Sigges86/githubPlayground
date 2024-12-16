# 🚀 **GitHub Playground**

Welcome, my brothers **Isak** and **Daniel**! 👋  

This is our **playground** to learn **IT development** together. We'll focus on the basics of **HTML, CSS, JavaScript**, and introduce **TypeScript** for **automated testing** with **Playwright**.  

---

## 🎯 **What You Will Learn**  

| Technology       | Purpose                                   |
|------------------|-------------------------------------------|
| **HTML**         | Build the **structure** of web pages.     |
| **CSS**          | Make web pages **look good**.             |
| **JavaScript**   | Add **interactivity** to websites.        |
| **TypeScript**   | Write clean, maintainable code.           |
| **Playwright**   | Automate testing across multiple browsers.|

---

## 🛠️ **Step 1: Install Git**  

We use **Git** to manage and save changes to our code. It helps us collaborate and keeps track of every version.

### ✅ **How to Install Git**:  
1. Go to [**Git's official site**](https://git-scm.com/).  
2. Download the installer for your operating system (Windows, Mac, or Linux).  
3. Follow the installation steps.

### 🔍 **Verify Installation**:  
Run this command in your terminal:  
```bash
git --version
```
If you see a version number, Git is installed correctly 🎉.  

---

## 🌟 **Step 2: Install Node.js and NPM**  

**Node.js** allows us to run JavaScript outside the browser, and **NPM** (Node Package Manager) lets us install tools like Playwright.  

### ✅ **How to Install Node.js**:  
1. Go to the [**Node.js official site**](https://nodejs.org/).  
2. Download the **LTS version** (Long-Term Support).  
3. Follow the installation steps to complete the setup.

### 🔍 **Verify Installation**:  
Run the following commands in the terminal:  
```bash
node --version
npm --version
```
If both commands return version numbers, Node.js and NPM are installed successfully 🎉.

---

## 🧬 **Step 3: Clone This Project**  

To get started, **clone** (download) this project from GitHub.

1. Open your terminal.  
2. Navigate to the folder where you want to save the project:  
   ```bash
   cd Documents
   ```  
3. Clone the repository:  
   ```bash
   git clone https://github.com/YOUR-USERNAME/githubPlayground.git
   ```  
   Replace `YOUR-USERNAME` with the repository owner’s username or link.

4. Move into the project folder:  
   ```bash
   cd githubPlayground
   ```

---

## ⚙️ **Step 4: Install Playwright**  

Playwright allows us to test our web pages automatically.

### 🚀 **Set Up Playwright**:  
Run this command inside the project folder:  
```bash
npm init playwright@latest
```

This command will:  
- Install Playwright as a dependency.  
- Set up a **Playwright configuration file**.  
- Install supported browsers (Chromium, Firefox, WebKit).

---

## 🔍 **Step 5: Verify Playwright Installation**  

1. Check Playwright version:  
   ```bash
   npx playwright --version
   ```

2. Run default tests to confirm everything works:  
   ```bash
   npx playwright test
   ```

You’ll see Playwright open browsers, run tests, and display results. ✅  

---

## 🔄 **Step 6: Folder Structure After Installation**  

After installing Playwright, your project folder will look like this:  

```plaintext
githubPlayground/
│
├── package.json         # Project configuration
├── playwright.config.ts # Playwright settings
├── tests/               # Folder for test files
│   └── example.spec.ts  # Example Playwright test
├── node_modules/        # Installed tools and libraries
└── .gitignore           # Ignore unnecessary files
```

---

## 💻 **Step 7: Write Your First Test**  

1. Open the `tests/example.spec.ts` file created during setup.  
2. Replace its content with the following:  

```typescript
import { test, expect } from '@playwright/test';

test('Example Test', async ({ page }) => {
  // Go to the website
  await page.goto('https://example.com');

  // Verify the title of the page
  const title = await page.title();
  expect(title).toBe('Example Domain');
});
```

3. Run the test:  
   ```bash
   npx playwright test
   ```

Playwright will open the browser, visit the site, and check if the title is correct. 🎉

---

## 🐞 **Step 8: Debugging Tests**  

If you want to **see the browser** while tests run, use the `--headed` flag:  
```bash
npx playwright test --headed
```

This will launch the browser visually, so you can watch the test in action.

---

## 🎓 **Next Steps: Learn and Explore**  

Here’s what you can do next:
1. **Experiment** with HTML, CSS, and JavaScript files in this project.
2. Write more Playwright tests to practice automation.
3. Ask questions and learn together!

---

## 📖 **Resources to Learn More**  

- Playwright Docs: [https://playwright.dev/docs/intro](https://playwright.dev/docs/intro)  
- HTML/CSS Tutorials: [https://www.w3schools.com/](https://www.w3schools.com/)  
- JavaScript Guide: [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  

---

## 🎉 **Let’s Get Coding!**  

You now have everything you need to start coding, testing, and learning. If you get stuck, just ask me! 🤓  

**Happy Coding, Isak and Daniel! 💻✨** 🚀  