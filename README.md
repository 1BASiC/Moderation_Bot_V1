<div align="center">
  <h1>🛡️ Advanced Discord Moderation Bot</h1>
  <p><strong>Developed with ❤️ by DraGoN3DD</strong></p>
  <p>A fully-featured, dual-language Discord bot designed to keep your server safe and organized.</p>
</div>

## ✨ Key Features | المميزات الأساسية
* 🌐 **Dual Language (AR/EN):** Toggle the bot's language instantly via a dedicated UI button. (دعم كامل للغتين العربية والإنجليزية).
* 🛡️ **Smart Moderation:** Safe hierarchy checks to prevent unauthorized actions against admins/higher roles. (حماية ذكية للرتب العليا).
* ⏳ **Temporary Punishments:** Support for temporary mutes, vcmutes, and warnings using standard background tasks. (عقوبات مؤقتة تفك تلقائياً).
* ⚠️ **Advanced Warning System:** Auto-generates warning roles (warn 1, warn 2) and removes them automatically when a warning is cleared. (نظام إنذارات متطور مع صنع رتب تلقائية).
* 🔊 **Voice Channel Management:** Move all users, specific users, or server-mute members easily. (تحكم كامل بالرومات الصوتية).
* 🤖 **Auto-Role System:** Automatically assign configured roles to new members upon joining. (نظام رتب تلقائية للأعضاء الجدد).
* ⚡ **Fully Slash Commands:** Modern and clean interaction using Discord's native slash commands. (اعتماد كلي على أوامر السلاش الحديثة).

---

## 🛠️ Prerequisites
Before running the bot, you must have the following installed on your computer/host:
1. **Python** (Download from python.org and make sure to check "Add Python to PATH" during installation).
2. **Required Libraries**: Open your Terminal or CMD and run the following command to install the required packages:
   `pip install -r requirements.txt`

## ⚙️ Setup Instructions
1. Find the file named `.env.example` and rename it to `.env`.
   - Open the `.env` file and replace the placeholder text with your actual Discord Bot Token.
2. Ensure you have enabled the **Privileged Gateway Intents** (Server Members Intent & Message Content Intent) in your Discord Developer Portal.

## 🚀 How to Run
Once the setup is complete, open your terminal in the bot's folder and run the following command:
`python main.py`
The bot will start, sync its commands, and show a "Ready" message in the console!

## 📜 Commands List
**🛠️ Moderation:**
- `/kick`, `/ban`, `/unban` - Standard moderation commands with hierarchy protection.
- `/mute`, `/unmute` - Text muting (requires a `Muted` role).
- `/timeout`, `/untimeout` - Discord's native timeout feature.
- `/clear` - Purge bulk messages.

**⚠️ Warnings System:**
- `/warn` - Warn a user (supports temporary warnings with duration).
- `/warns` - Display warnings for a specific user or the entire server.
- `/unwarn` - Remove a specific warning or clear all warnings for a user.

**🔊 Voice Channels:**
- `/move all`, `/move user`, `/moveme` - Advanced voice channel moving commands.
- `/vcmute`, `/vcunmute` - Server mute users in voice channels (supports temporary duration).

**⚙️ Settings & Auto Role:**
- `/autorole add`, `/autorole remove`, `/autorole list` - Manage roles assigned automatically to new members.
- `/help` - Show all commands with a button to toggle the bot's language (Arabic/English).

## 📞 Support & Contact
If you have any questions or need help with the setup, feel free to contact me on Discord!
**Discord:** `dragon3dd`

---
---

## 🛠️ متطلبات التشغيل (عربي)
قبل تشغيل البوت، يجب أن تتأكد من توفر الآتي في جهازك أو الاستضافة:
1. **لغة بايثون (Python)**: (قم بتحميلها من موقع python.org وتأكد من تفعيل خيار "Add Python to PATH" أثناء التثبيت).
2. **المكتبات المطلوبة**: افتح موجه الأوامر (CMD) أو التيرمنال واكتب هذا الأمر لتثبيت المكتبات اللازمة:
   `pip install -r requirements.txt`

## ⚙️ طريقة الإعداد (Setup)
1. ابحث عن ملف `.env.example` وقم بتغيير اسمه ليصبح `.env` فقط.
   - افتح ملف `.env` وضع توكن البوت (Bot Token) الخاص بك داخله.
2. تأكد من تفعيل خيارات **Privileged Gateway Intents** (خياري Members و Message Content) من موقع مطوري ديسكورد (Developer Portal).

## 🚀 طريقة التشغيل
بعد الانتهاء من الإعداد، افتح موجه الأوامر (Terminal) داخل مجلد البوت واكتب الأمر التالي:
`python main.py`
سيشتغل البوت، ويقوم بتفعيل الأوامر، وتظهر لك رسالة نجاح التشغيل في الشاشة السوداء!

## 📜 قائمة الأوامر
**🛠️ أوامر الإدارة:**
- `/kick`, `/ban`, `/unban` - أوامر الإدارة الأساسية مع نظام حماية الرتب.
- `/mute`, `/unmute` - إعطاء ميوت كتابي (يتطلب وجود رتبة باسم `Muted` في السيرفر).
- `/timeout`, `/untimeout` - نظام التايم أوت الرسمي من ديسكورد.
- `/clear` - مسح الرسائل دفعة واحدة.

**⚠️ نظام الإنذارات:**
- `/warn` - إعطاء إنذار (يدعم الإنذارات المؤقتة بالدقائق).
- `/warns` - عرض إنذارات شخص معين أو عرض قائمة بجميع المنذرين في السيرفر.
- `/unwarn` - حذف إنذار محدد عن عضو، أو مسح جميع إنذاراته.

**🔊 الرومات الصوتية:**
- `/move all`, `/move user`, `/moveme` - أوامر متقدمة لنقل وسحب الأعضاء في الرومات الصوتية.
- `/vcmute`, `/vcunmute` - إعطاء ميوت سيرفر (Server Mute) للأعضاء في الرومات الصوتية (يدعم الوقت المؤقت).

**⚙️ الإعدادات والرتب التلقائية:**
- `/autorole add`, `/autorole remove`, `/autorole list` - إدارة الرتب التي تُعطى تلقائياً للأعضاء الجدد عند دخولهم السيرفر.
- `/help` - عرض قائمة الأوامر مع زر لتغيير لغة البوت (عربي/إنجليزي) للسيرفر.