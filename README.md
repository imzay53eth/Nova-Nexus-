# Nova-Nexus-
# 🤖 Staff Management Bot

A comprehensive Discord staff management system built with `discord.py`. Features license verification, shift attendance tracking, leave requests, positive/negative points system, and automated weekly performance reports.

## ✨ Features

- 🔐 **License System** — Generate and verify unique staff licenses with secure passcodes
- 🕐 **Attendance Tracking** — Sign in/out for shifts with early sign-out detection and review
- 🏝️ **Break Requests** — Staff can request time off; Heads approve/reject; LOA role auto-assigns & expires
- ⭐ **Points System** — Track positive and negative points with full history logs
- 📊 **Weekly Reports** — Auto-generated every Friday showing attendance % and point trends
- 📢 **Announcements** — Send news and resignation announcements to your server
- 💬 **Direct Messaging** — Heads can message users; user replies forwarded to staff channel
- 📝 **Audit Logs** — Full history of all staff actions and changes

## 🛡️ Permissions
- **Heads:** Full access — manage licenses, review requests, give points, send messages
- **Staff:** Sign in/out, request breaks, view license & points, submit announcements

## 🚀 Setup
1. Create a `.env` file with your bot token: `DISCORD_BOT_TOKEN=your_token_here`
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python bot.py`
