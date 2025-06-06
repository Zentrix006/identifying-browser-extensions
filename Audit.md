# 📄 Task 7: Browser Extension Audit & Cleanup

## ✅ Step-by-Step Actions Taken

### 1. Accessed Chrome Extension Manager
- URL: `chrome://extensions/`

### 2. Reviewed Installed Extensions:
| Extension Name           | Permissions                                    | Status       |
|--------------------------|------------------------------------------------|--------------|
| Honey                    | "Read and change all your data..."             | Removed      |
| Grammarly                | "Read data on all websites"                    | Kept (trusted) |
| Screenshot Master        | "Access all sites"                             | Removed      |
| uBlock Origin            | "Read site data"                               | Kept (safe)  |
| Video Downloader Plus    | "Access YouTube, Facebook, all tabs"           | Removed      |

---

### 3. Removal Justification
- ❌ **Honey**: Wasn't being used and had wide permissions across all websites.
- ❌ **Screenshot Master**: Required full site access and wasn’t open-source.
- ❌ **Video Downloader Plus**: Flagged in community reports as potentially tracking behavior.

---

### 4. Post-Action Cleanup
- ✅ Restarted the browser.
- ✅ Verified only trusted extensions remained.
- ✅ Cross-checked each remaining extension’s permissions and reviews.

---

## 🔐 What Makes an Extension Suspicious?
- It requests **“Read and change all your data on websites”**.
- It’s not from a **verified developer**.
- It has **poor or fake-looking reviews**.
- It runs in **background mode persistently** without user interaction.

---

## 📚 Key Takeaways
- Extensions can act as spyware if permissions are abused.
- Always review permissions during install.
- Prefer open-source, well-reviewed, and regularly updated extensions.
- **Less is more** — install only what you absolutely need.

---

## 🛡️ Security Tip
Use your browser’s **“Incognito” mode settings** to disable most extensions during private sessions for added privacy.


