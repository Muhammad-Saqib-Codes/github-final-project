# 𝐂𝐨𝐧𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐧𝐠 𝐭𝐨 𝐭𝐡𝐞 𝐒𝐢𝐦𝐩𝐥𝐞 𝐈𝐧𝐭𝐞𝐫𝐞𝐬𝐭 𝐏𝐫𝐨𝐣𝐞𝐜𝐭

Welcome! We are excited to transition our workflows from SVN to Git. We welcome community contributions to help build tools that empower and provide financial opportunities for low-income individuals.

---

## 🗺️ 𝐓𝐲𝐩𝐞𝐬 𝐨𝐟 𝐂𝐨𝐧𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧𝐬 𝐖𝐞 𝐖𝐞𝐥𝐜𝐨𝐦𝐞

You can contribute in several ways, from reporting problems to adding new code or features.

### 1. 𝐁𝐮𝐠 𝐑𝐞𝐩𝐨𝐫𝐭𝐬
If you find a calculation error, a crash, or an issue running the script:
* **Check Existing Issues:** Ensure the bug has not already been reported.
* **Open a New Issue:** Use a clear, descriptive title.
* **Provide Context:** Include your Python version and operating system.
* **Describe the Bug:** Explain what you expected to happen versus what actually happened.
* **Provide Reproduction Steps:** Give the exact input numbers (Principal, Rate, Time) that caused the bug.

### 2. 𝐁𝐮𝐠 𝐅𝐢𝐱𝐞𝐬
If you want to resolve an open bug issue:
* **Comment on the Issue:** Let others know you are working on a fix to avoid duplicate work.
* **Write Clean Code:** Ensure your fix specifically addresses the bug without breaking other inputs.
* **Keep PRs Small:** Submit a Pull Request (PR) containing only the code changes needed for that specific fix.

### 3. 𝐃𝐨𝐜𝐮𝐦𝐞𝐧𝐭𝐚𝐭𝐢𝐨𝐧 𝐈𝐦𝐩𝐫𝐨𝐯𝐞𝐦𝐞𝐧𝐭𝐬
Documentation helps our core team adapt to Git and helps users understand the tool. You can contribute by:
* Correcting typos or grammar mistakes in any file.
* Improving instructions in the `README.md`.
* Adding inline code comments or docstrings to clarify complex code logic.

### 4. 𝐄𝐧𝐡𝐚𝐧𝐜𝐞𝐦𝐞𝐧𝐭𝐬 & 𝐅𝐞𝐚𝐭𝐮𝐫𝐞 𝐑𝐞𝐪𝐮𝐞𝐬𝐭𝐬
If you have an idea to make this tool better:
* **Open an Enhancement Issue:** Explain the feature and how it directly serves low-income users or our internal engineering team.
* **Discuss First:** Wait for feedback from the core team before writing code, ensuring the idea aligns with our scope.

---

## 💡 𝐅𝐢𝐧𝐚𝐧𝐜𝐢𝐚𝐥 𝐓𝐨𝐨𝐥 𝐈𝐝𝐞𝐚𝐬 𝐖𝐞 𝐖𝐞𝐥𝐜𝐨𝐦𝐞

We want to expand this repository into a robust suite of accessible financial calculators. We highly welcome contributions focused on these specific concepts:

* **Compound Interest Calculator:** Tools to help users calculate long-term savings growth.
* **Micro-Loan Amortization Schedules:** Scripts that break down monthly principal and interest payments for borrowers.
* **Grace Period Logic:** Features calculating how interest accumulates if a low-income borrower gets a temporary payment holiday.
* **Localization & Currency Support:** Adapting inputs and outputs to support various regional currencies and formatting styles.
* **Command-Line Interface (CLI) Flags:** Allowing advanced users to pass variables directly via the command line (e.g., `--principal 1000 --rate 5 --time 2`).

---

## 🛠️ 𝐒𝐭𝐞𝐩-𝐛𝐲-𝐒𝐭𝐞𝐩 𝐏𝐮𝐥𝐥 𝐑𝐞𝐪𝐮𝐞𝐬𝐭 𝐏𝐫𝐨𝐜𝐞𝐬𝐬

Follow these steps to submit your changes successfully:

1. **Fork the Repository:** Create your own copy of this project on GitHub.
2. **Clone Locally:** Download your fork to your computer using Git.
3. **Create a Branch:** Use a descriptive name for your branch:
   ```bash
   git checkout -b feature/compound-interest
   # OR for bugs:
   git checkout -b fix/calculation-error
   ```
4. **Implement Changes:** Write your code or modify documentation. Adhere to standard Python PEP 8 style guidelines.
5. **Commit Changes:** Write clear, concise commit messages in the present tense:
   ```bash
   git commit -m "Add compound interest calculation function"
   ```
6. **Push and Open PR:** Push the branch to your fork and submit a Pull Request against our `main` branch. 

Thank you for helping us build a more financially inclusive world!
