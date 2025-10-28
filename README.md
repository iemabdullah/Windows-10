# 💻 How to Get Windows RDP Free Using GitHub

Step-by-step guide to create a **Free Windows RDP Server**.  
Works for **Windows 10** and **Windows 11** — secure and legal setup suitable for students, testing, learning, and personal projects.

---

## 🎥 Watch Video
▶️ [Watch the walkthrough video on Google Drive](https://drive.google.com/file/d/1EH7BPiafQPHMWajdY7cXec4tvqu2Q63O/view)

---

## 🚀 Overview
This guide shows an easy workflow to create a **Free Windows RDP** using **GitHub Actions** or **GitHub Codespaces**, along with a secure connection tool like **Tailscale**.

---

## 🧩 Works For
- Students 👩‍🎓  
- Testing & Learning 🧠  
- Personal Projects 🧑‍💻  
- Anyone needing Free RDP for Windows 10/11 ⚙️  

---

## ⚙️ Requirements
- GitHub account  
- Basic familiarity with GitHub Repositories, Actions, or Codespaces  
- Tailscale account (for secure RDP connection)  
- A Base64 tool (online) to decode or encode keys  

---

## 🪜 Step-by-Step Setup

### 1️⃣ Create GitHub Repository
- Go to GitHub and click **New Repository**.  
- Name it anything and click **Create**.

---

### 2️⃣ Open Codespace or Repository Editor
- Open your GitHub Codespace (or use the online repo editor).  
- Create folders like `backend/` and add workflow or script files there.  
- Run your setup commands as required.

---

### 3️⃣ Add Repository Secrets
- Go to **Settings → Secrets → Actions → New Repository Secret**.  
- Paste your Auth Key (or API Key) and save it.  

---

### 4️⃣ Get Base64 Code
- Visit [https://base64.abdullah.nyc.mn/](https://base64.abdullah.nyc.mn/)  
- Paste the given value and click **Decode** to get your Base64 output.

---

### 5️⃣ Create the RDP Workflow
- Use the Base64-decoded value to generate your RDP workflow file.  
- Save the workflow file under `.github/workflows/rdp.yml`.  
- Commit and push it.

---

### 6️⃣ Run the Workflow
- Go to **Actions** tab → choose your workflow → click **Run Workflow**.  
- Wait for it to complete — check logs for **IP address** and **credentials**.

---

### 7️⃣ Connect to Your RDP
- Install **Tailscale** on your PC or phone.  
- Sign in with your account.  
- Open **Remote Desktop Connection**.  
- Enter the **IP address** and **password** from workflow output.  

✅ **Done!**  
Your free Windows 10/11 RDP is now ready.

---

## 🌐 Use Cases
Perfect for:
- Web browsing 🌍  
- Testing applications 🧪  
- Light development 🪶  
- Personal experiments ⚡  

---

## 🔗 Credits & Socials

**⚡ MY SOCIALS & WEB ⚡**

- 💬 Telegram: [t.me/ABDULLAHMETHOD](https://t.me/ABDULLAHMETHOD)  
- 📸 Instagram: [instagram.com/em.abdullah__](https://instagram.com/em.abdullah__)  
- 🌍 Website: [abdullahcoded.blogspot.com](https://abdullahcoded.blogspot.com)

---

© **All rights reserved by Abdullah Coded**
