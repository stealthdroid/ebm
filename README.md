## 📲 Install Termux

> ❗ **Do NOT install Termux from the Play Store** — it's outdated and not supported.  
✅ Download the latest version from **F-Droid**:

🔗 [Install Termux via F-Droid](https://f-droid.org/en/packages/com.termux/)

---

## 🛠 Step-by-Step Installation (Termux)

Follow these steps **one by one**:

### 1. Update Termux packages
```
pkg update && pkg upgrade -y
```

### 2. Install Python and Git
```
pkg install python git -y
```

### 3. Install required Python modules
```
pip install pycryptodome
pip install pycrypto
pip install requests
```

### 4. Clone this repository
```
git clone https://github.com/stealthdroid/ebm
cd ebm
```

### 5. Run the bot
```
python ebm.py
```

---

## 📋 Notes

- Ensure your Termux has **storage permissions** if needed:
```
termux-setup-storage
```

- If `pycrypto` fails, you can skip it or use `pycryptodome` as a replacement.

---

## 💬 Support

For help, updates, or reporting bugs, join the Telegram channel:  
🔗 [https://t.me/ScriptsByHanan](https://t.me/ScriptsByHanan)

---

## 🧑‍💻 Developer

GitHub: [@stealthdroid](https://github.com/stealthdroid)
