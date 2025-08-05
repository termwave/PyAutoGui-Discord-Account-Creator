<h1 align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&pause=1000&color=00FF00&vCenter=true&multiline=true&width=435&lines=Hey+%F0%9F%91%8B%2C+I'm+Termwave.;I+Create+Ultimate+Tools.+" alt="Typing SVG" /></h1>

# 🧠 Ultimate Discord Account Generator

```
 █    ██  ██▓  ▄▄▄█████▓ ██▓ ███▄ ▄███▓ ▄▄▄     ▄▄▄█████▓▓█████ 
 ██  ▓██▒▓██▒  ▓  ██▒ ▓▒▓██▒▓██▒▀█▀ ██▒▒████▄   ▓  ██▒ ▓▒▓█   ▀ 
▓██  ▒██░▒██░  ▒ ▓██░ ▒░▒██▒▓██    ▓██░▒██  ▀█▄ ▒ ▓██░ ▒░▒███   
▓▓█  ░██░▒██░  ░ ▓██▓ ░ ░██░▒██    ▒██ ░██▄▄▄▄██░ ▓██▓ ░ ▒▓█  ▄ 
▒▒█████▓ ░██████▒▒██▒ ░ ░██░▒██▒   ░██▒ ▓█   ▓██▒ ▒██▒ ░ ░▒████▒
░▒▓▒ ▒ ▒ ░ ▒░▓  ░▒ ░░   ░▓  ░ ▒░   ░  ░ ▒▒   ▓▒█░ ▒ ░░   ░░ ▒░ ░
░░▒░ ░ ░ ░ ░ ▒  ░  ░     ▒ ░░  ░      ░  ▒   ▒▒ ░   ░     ░ ░  ░
 ░░░ ░ ░   ░ ░   ░       ▒ ░░      ░     ░   ▒    ░         ░   
   ░         ░  ░        ░         ░         ░  ░           ░  ░
```

> 💣 Semi-automated Discord account generator with manual captcha solving & inbox verification.
> 🔒 verifies emails, and stores working tokens.

---

## 🚀 Features

- ✅ Discord account creation via browser automation
- 📧 Email verification via `incognitomail.co`
- ⚙️ Configurable with custom domain support (`termwave.in`)
- 🔔 Desktop notifications using NotifyPy
- 🎨 PyQt6-based animated splash screens
- ⌨️ Auto keyboard automation (pyautogui, keyboard)
- 💡 Terminal color logging
- 🔔 Enter Key is Need to be Pressed

---

## ⚙️ Requirements

Install everything with:

```bash
pip install -r req.txt
```

Or manually:

```bash
pip install requests psutil colorama pystyle keyboard pyautogui PyQt6 notify-py urllib3 httpx
```

---

## 🛠 Usage

```bash
python term.py
```

On first run, you’ll be prompted for number of accounts to generate. Captcha and email verification require manual input when prompted.

---

## 📥 Output

Generated tokens saved to `tokens.txt` as:

```
email:password:token
```

---

## 👨‍💻 Author

- 🧬 Created by: **[`Termwave`](https://termwave.in)**
- 📎 Discord: `mfxe`
- 💻 License: [MIT](https://opensource.org/licenses/MIT)
- ⚡ Website: [termwave.in](https://termwave.in) | [termwave.space](https://termwave.space)

---

### 💬 Terminal Quote

```bash
[termwave] ➤ "Hack the planet. Or at least the Discord rate limiter."
```

---

> ⚡ Feel free to fork, tweak, or contribute. Stay safe — and don’t abuse this tool.  

> ⚠️ This tool is for educational and testing purposes only. Don’t abuse Discord’s TOS.

### 📡 IncognitoMail Setup & Access

#### 🛠 1. Setup Your Custom Domain (Required First)

To receive mail on your own domain (e.g. `termwave.in`):

1. Go to [https://incognitomail.co/](https://incognitomail.co/)
2. Navigate to the **⚙️ Settings** tab
3. Under **Custom Domain**, enter: `termwave.in`
4. Add the following MX record in your domain DNS:

```
Host: @  
Value: mail.incognitomail.co  
Priority: 10
```

---

#### 📥 2. Access Your Inbox

After setting up your domain:

1. Go to [https://incognitomail.co/](https://incognitomail.co/)
2. Navigate to the **⚙️ Settings** tab
3. Under **Custom Domain**, enter: `termwave.in`
4. Click **Create Custom Email ID**
5. Enter your email ID (e.g. `verify@termwave.in`)
6. (Optional) Enter your token/password if required
7. Click `Create` to open your inbox
