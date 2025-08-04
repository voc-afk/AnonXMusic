<h2 align="center">
    ──「 ᴀɴᴏɴ ダ ᴍᴜsɪᴄ 」──
</h2>

<p align="center">
  <img src="https://telegra.ph/file/56d1760224589ee370186.jpg">
</p>

<p align="center">
<a href="https://github.com/voc-afk/AnonXMusic/stargazers"><img src="https://img.shields.io/github/stars/voc-afk/AnonXMusic?color=black&logo=github&logoColor=black&style=for-the-badge" alt="Stars" /></a>
<a href="https://github.com/voc-afk/AnonXMusic/network/members"> <img src="https://img.shields.io/github/forks/voc-afk/AnonXMusic?color=black&logo=github&logoColor=black&style=for-the-badge" /></a>
<a href="https://github.com/voc-afk/AnonXMusic/blob/master/LICENSE"> <img src="https://img.shields.io/badge/License-MIT-blueviolet?style=for-the-badge" alt="License" /> </a>
<a href="https://www.python.org/"> <img src="https://img.shields.io/badge/Written%20in-Python-orange?style=for-the-badge&logo=python" alt="Python" /> </a>
<a href="https://github.com/voc-afk/AnonXMusic/commits/voc-afk"> <img src="https://img.shields.io/github/last-commit/voc-afk/AnonXMusic?color=blue&logo=github&logoColor=green&style=for-the-badge" /></a>
</p>

<p align="center">
  <img src="https://telegra.ph/file/36be820a8775f0bfc773e.jpg">
</p>


## 🍪 Avoiding Bans

### Option 1: Premium API
```env
API_URL=https://tgmusic.fallenapi.fun
API_KEY=your-secret-key
```
📌 Get keys: [Contact @AshokShau](https://t.me/AshokShau) or [@FallenApiBot](https://t.me/FallenApiBot)

## Option 2: Cookies

# **📜 Using Cookies for Authentication**  

### **🔹 Method: Netscape HTTP Cookie File**  
To authenticate requests using browser cookies, follow these steps:  

> ⚠️ **Important Note:**  
> - Always use a **secondary account** for generating cookies.  
> - Once cookies are uploaded, **do not log in again** on that account—it may invalidate the session prematurely.  

---

## **📌 Step 1: Export Cookies in Netscape Format**  
Use a browser extension to export cookies as a **`cookies.txt`** file in **Netscape HTTP format**:  

### **🌐 Recommended Extensions:**  
| Browser | Extension | Download Link |  
|---------|-----------|---------------|  
| **Chrome** | `Get cookies.txt` | [Chrome Web Store](https://chromewebstore.google.com/detail/get-cookiestxt-clean/ahmnmhfbokciafffnknlekllgcnafnie) |  
| **Firefox** | `cookies.txt` | [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/cookies-txt/) |  

### **📥 How to Export:**  
1. Install the extension.  
2. Navigate to the target website (YouTube.com) and log in.  
3. Click the extension icon and select **"Export cookies.txt"**.  
4. Save the file.  

---

## **📌 Step 2: Upload Cookies to a Paste Service**  
Host your `cookies.txt` on a text-sharing service:  

### **🔗 Recommended Paste Services:**  
- **[BatBin](https://batbin.me)** (Recommended, no login required)  
- **[PasteBin](https://pastebin.com)** (Requires account for long-term pastes)  

### **📤 Upload Steps:**  
1. Open the paste service.  
2. Copy-paste the **entire content** of `cookies.txt`.  
3. Click **"Create Paste"** and copy the URL.  

---

## **📌 Step 3: Set the Environment Variable**  
Add the paste URL to your **`COOKIES_URL`** environment variable.  

### **⚙️ Example:**  
```env
COOKIES_URL=https://batbin.me/abc123, https://pastebin.com/raw/xyz456
```  
*(Supports multiple URLs separated by commas)*  

---

### **❓ Troubleshooting**  
🔸 **Session Invalid?** → Generate new cookies and avoid logging in elsewhere.  
🔸 **403 Errors?** → Ensure cookies are fresh and not expired.

---

### **✅ Best Practices**  
✔ **Rotate cookies** periodically to avoid bans.  
✔ **Use private/incognito mode** when generating cookies.  
✔ **Monitor session activity** to detect early invalidation.  

---

#### **🎉 Enjoy using cookies!**

---

## 🖇 Generating Pyrogram String Session

<p>
<a href="https://telegram.tools/session-string-generator#pyrogram"><img src="https://img.shields.io/badge/Generate%20On%20Site-blueviolet?style=for-the-badge&logo=appveyor" width="200""/></a>
<a href="https://t.me/strgen_bot"><img src="https://img.shields.io/badge/TG%20String%20Gen%20Bot-blueviolet?style=for-the-badge&logo=appveyor" width="200""/></a>
</p>

##

<h3 align="center">
    ─「 ᴅᴇᴩʟᴏʏ ᴏɴ ʜᴇʀᴏᴋᴜ 」─
</h3>

<p align="center"><a href="https://dashboard.heroku.com/new?template=https://github.com/voc-afk/AnonXMusic"> <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

##

<h3 align="center">
    ─「 ᴅᴇᴩʟᴏʏ ᴏɴ ʟᴏᴄᴀʟ ʜᴏsᴛ/ ᴠᴘs 」─
</h3>

- Get your [Necessary Variables](https://github.com/voc-afk/AnonXMusic/blob/master/sample.env)
- Upgrade and Update by :
`sudo apt-get update && sudo apt-get upgrade -y`
- Install Ffmpeg & Python by :
`sudo apt-get install python3-pip ffmpeg -y`
- Install pip by :
`sudo pip3 install -U pip`
- Clone the repository by :
`git clone https://github.com/voc-afk/AnonXMusic && cd AnonXMusic`
- Install requirements by :
`pip3 install -U -r requirements.txt`
- Fill your variables in the env by :
`vi sample.env`<br>
Press `I` on the keyboard for editing env<br>
Press `Ctrl+C` when you're done with editing env and `:wq` to save the env<br>
- Rename the env file by :
`mv sample.env .env`
- Install tmux to keep running your bot when you close the terminal by :
`sudo apt install tmux && tmux`
- Finally run the bot by :
`bash start`
- For getting out from tmux session : Press `Ctrl+b` and then `d`<br>
━━━━━━━━━━━━━━━━━━━━

##

<h3 align="center">
    ─「 sᴜᴩᴩᴏʀᴛ 」─
</h3>

<p align="center">
<a href="https://telegram.me/DevilsHeavenMF"><img src="https://img.shields.io/badge/-Support%20Group-blue.svg?style=for-the-badge&logo=Telegram"></a>
</p>

##

<p align="center">
<a href="https://telegram.me/FallenAssociation"><img src="https://img.shields.io/badge/-Support%20Channel-blue.svg?style=for-the-badge&logo=Telegram"></a>
</p>

- <b> _sᴩᴇᴄɪᴀʟ ᴛʜᴀɴᴋs ᴛᴏ [ᴛᴇᴀᴍ ʏᴜᴋᴋɪ](https://github.com/TeamYukki) ғᴏʀ [ʏᴜᴋᴋɪ ᴍᴜsɪᴄ ʙᴏᴛ](https://github.com/TeamYukki/YukkiMusicBot)_ </b>
