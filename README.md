# 📝 Task Creation Test Web App

A simple web application that sends task data to **Google Sheets** using **Google Apps Script Web App**.

This project is used for testing task submission functionality before integrating into a full admin dashboard system.

---

## 🚀 Features

- White & Purple Card UI
- Task Creation Form:
  - Task Name
  - Description
  - Priority
  - User
- Sends data to Google Sheets
- Connected via Google Apps Script Web App

---

## 🛠 Tech Stack

- HTML
- CSS
- JavaScript (Fetch API)
- Google Apps Script
- Google Sheets
- GitHub Pages (Deployment)

---

# 🌍 How to Deploy This Web App

## Step 1 — Upload to GitHub

1. Create a new repository on GitHub
2. Name it (example: `task-test-app`)
3. Make it **Public**
4. Upload your file and make sure it is named: index.html

5. Click **Commit changes**

---

## Step 2 — Enable GitHub Pages

1. Go to your repository
2. Click **Settings**
3. Click **Pages**
4. Under **Source**:
   - Select: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

Wait 30–60 seconds.

GitHub will generate your live site URL: https://yourusername.github.io/task-test-app/

---

# 🔗 Connecting to Google Apps Script

Make sure your Google Apps Script Web App is deployed properly:

1. Open Google Apps Script
2. Click **Deploy → Manage deployments**
3. Select your Web App
4. Configure:
   - Execute as: **Me**
   - Who has access: **Anyone**
5. Copy the Web App URL (must end in `/exec`)
6. Paste it inside `index.html`:

```javascript
const webAppUrl = "PASTE_YOUR_WEB_APP_URL_HERE";


---

If you want, I can also:

- Make a more **professional developer-style README**
- Add screenshots section
- Add architecture diagram section
- Make it look like a real portfolio project

Just tell me your goal (school project, internship test, portfolio, etc.).
