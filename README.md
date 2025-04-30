# **Connecting VS Code to GitHub (Without Git Bash)**
This guide explains how to **push code directly from VS Code to GitHub** without using Git Bash.  

## **Prerequisites**
- [VS Code](https://code.visualstudio.com/) installed.
- A [GitHub](https://github.com/) account.
- [Git](https://git-scm.com/downloads) installed (VS Code uses it in the background).

---

## **Step 1: Install the GitHub Extension in VS Code**
1. Open **VS Code**.
2. Go to the **Extensions** tab (`Ctrl+Shift+X` or `⌘+Shift+X`).
3. Search for **"GitHub Pull Requests and Issues"** (by GitHub) and install it.

![VS Code GitHub Extension](https://i.imgur.com/xyz123.png) *(Example image)*

---

## **Step 2: Sign in to GitHub Inside VS Code**
1. Click the **Accounts** icon in the bottom-left corner (or open **Command Palette** with `Ctrl+Shift+P` and type `GitHub: Sign In`).
2. Choose **GitHub** and follow the authentication steps (you may need to log in via browser).

---

## **Step 3: Initialize a Git Repository**
1. Open your project folder in **VS Code**.
2. Open the **Source Control** tab (`Ctrl+Shift+G` or `⌘+Shift+G`).
3. If your project isn’t a Git repo yet, click **"Initialize Repository"**.

![Initialize Git Repo](https://i.imgur.com/abc456.png)

---

## **Step 4: Commit Changes**
1. Make changes to your files.
2. Go to the **Source Control** tab.
3. **Stage changes** by clicking the **+ (Stage Changes)** next to each file.
4. Enter a **commit message** and click **✓ Commit**.

![Commit Changes in VS Code](https://i.imgur.com/def789.png)

---

## **Step 5: Push to GitHub**
### **Option A: If the repo is already on GitHub**
1. Click the **"..." (More Actions)** in the **Source Control** tab.
2. Select **Push** (or use the **Sync icon 🔄**).

### **Option B: If the repo is NOT on GitHub yet**
1. Click **"Publish to GitHub"** in the **Source Control** tab.
2. Choose **Private** or **Public**.
3. Confirm, and your code will be pushed to a **new GitHub repo**.

![Publish to GitHub](https://i.imgur.com/ghi012.png)

---

## **Step 6: Manage Branches & Pull Requests (Optional)**
- **Create a new branch**: Click the branch name in the bottom-left corner.
- **Pull & Sync changes**: Use the **Sync icon 🔄**.
- **Create a Pull Request (PR)**: Use the **GitHub Pull Requests extension**.

---

## **Troubleshooting**
❌ **"Git not found" error?**  
→ Ensure Git is installed and added to PATH ([Git Download](https://git-scm.com/downloads)).

❌ **Authentication failed?**  
→ Re-login via **VS Code Accounts** or use a [Personal Access Token (PAT)](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

---

## **Conclusion**
✅ **No Git Bash needed** – Everything is done in VS Code!  
✅ **Commit, push, and sync** directly from the editor.  
✅ **Manage branches, PRs, and issues** without leaving VS Code.  

🚀 **Happy coding!**  

