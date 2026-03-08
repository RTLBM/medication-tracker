# 💊 Medication Tracker

A secure, private medication tracking web app that runs entirely in your browser. Perfect for tracking medications, pain meds, and supplements with intelligent reminders.

## ✨ Features

- **📝 Easy Daily Logging** - Log medications in seconds with date, time, dosage, and notes
- **🔔 Smart Reminders** - Get notified when medications are due or overdue
- **📊 History & Tracking** - View all past medication entries with search and filters
- **📋 Medication Reference** - Keep a list of your medications with purpose, dosage, and frequency
- **⏰ Flexible Scheduling** - Supports fixed schedules (2x daily, 3x daily) and interval-based (every 6 hours)
- **🔒 100% Private** - All data stored locally on your device, never sent to servers
- **📱 Mobile-First** - Optimized for phones, works on iOS and Android
- **🌐 No Internet Required** - Works completely offline
- **⚙️ Data Management** - Clear entries, medications, or start fresh anytime

## 🚀 Quick Start

### Visit the App
Simply open this link on any device with a browser:
```
https://yourusername.github.io/medication-tracker/
```

### Add to Home Screen (Mobile App Experience)

**On Android:**
1. Open the link in Chrome
2. Tap the **3-dot menu** (top right)
3. Tap **"Install app"** or **"Add to Home Screen"**
4. The app now appears as an icon on your home screen

**On iPhone:**
1. Open the link in Safari
2. Tap the **Share button** (square with arrow)
3. Tap **"Add to Home Screen"**
4. The app now appears as an icon on your home screen

## 📖 How to Use

### 1. Set Up Your Medications (Reference Tab)

First, add all medications to your reference list:
- **Medication Name** (required) - e.g., "Ibuprofen", "Aspirin"
- **Purpose/Notes** (optional) - Why is it taken? e.g., "Pain relief", "Blood pressure"
- **Typical Dosage** (optional) - Normal dose, e.g., "500mg", "1 tablet"
- **Frequency** (optional) - How often? See frequency options below

### 2. Log Daily Doses (Log Tab)

When a medication is taken:
1. **Medication Name** - Start typing, autocomplete suggests previous medications
2. **Date** - When was it taken (defaults to today)
3. **Time** - What time (24-hour format)
4. **Dosage** - How much, e.g., "500mg", "1 tablet", "2 capsules"
5. **Notes** - Any observations, e.g., "taken with food", "mild headache"
6. Tap **"✓ Log Medication"**

### 3. Check Reminders (Log Tab Banner)

The app automatically shows:
- **🟢 Green Banner** - Medication is ready to take now
- **🔴 Red Banner** - Medication is overdue
- **⬜ No Banner** - All medications are up to date

### 4. View History (History Tab)

- See all logged doses
- Search by medication name
- Filter by: All Time, Today, Last 7 Days, Last 30 Days
- Delete incorrect entries

### 5. Manage Data (Settings Tab)

- **Export to Excel** - Download all data as CSV and JSON backup
- Clear all medication entries
- Clear all medications from reference
- Factory reset (clear everything)
- **Import from File** - Restore previously exported data

## ⏰ Frequency Options

### Fixed Schedule Medications

Use these for regular schedules:
- **"1x daily"**, **"once daily"** - Once per day at 9 AM
- **"2x daily"**, **"twice daily"** - 9 AM and 9 PM
- **"3x daily"**, **"three times"** - 9 AM, 2 PM, 9 PM
- **"4x daily"**, **"four times"** - 8 AM, 12 PM, 4 PM, 8 PM

### Interval-Based Medications (Pain Meds, As-Needed)

Use these for pain medications, antacids, or as-needed doses:
- **"6h pain"** or **"6h"** or **"every 6 hours"** or **"q6h"** - Every 6 hours from last dose
- **"4h"** or **"4h pain"** - Every 4 hours from last dose
- **"8h"** - Every 8 hours from last dose
- **"12h"** - Every 12 hours from last dose

**Example:**
- Logged at 2:15 PM with frequency "6h pain"
- Next reminder due at 8:15 PM (6 hours later)
- Tracks from actual dose time, not fixed clock times

## 🔒 Privacy & Security

✅ **Your Data is Private**
- All medication data stored locally on YOUR device
- Nothing uploaded to the cloud
- Nothing sent to any server
- GitHub only hosts the app code, not your data
- Your personal medication history stays 100% private

✅ **Works Offline**
- No internet connection required
- Works on airplane mode
- Perfect for privacy-conscious users

✅ **No Accounts**
- No login required
- No email, username, or password
- Complete anonymity

## 💾 Backing Up Your Data

### Automatic Cloud Backup (GitHub Pages)

When hosting on GitHub Pages, your app is always accessible, and your data persists automatically across updates.

### Manual Export to Excel/CSV

**From Settings Tab:**
1. Open the app
2. Go to **Settings** tab
3. Click **"📊 Export to Excel"**
4. Two files download automatically:
   - **CSV file** - Open in Excel, Google Sheets, or any spreadsheet app
   - **JSON file** - Backup file for re-importing into the app

**What's Included:**
- All medication entries (date, time, medication, dosage, notes)
- All medication references (name, purpose, dosage, frequency)
- Summary statistics (total entries, today's count, etc.)

### Restore from Backup

**To import previously exported data:**
1. Open the app
2. Go to **Settings** tab
3. Click **"📥 Import from File"**
4. Select the JSON backup file you downloaded
5. Confirm the import
6. Data is merged (not overwritten)

### Paper Backup

For extra safety, consider keeping a paper backup of:
- Medication names and dosages
- Current schedule/frequency
- Any critical entries

## 🆘 Troubleshooting

### Data Disappeared After Update
- Browser local storage is device-specific
- If you updated the file, old data may be in a different storage location
- Solution: Use the same browser and device, or manually re-add medications

### App Won't Open
- Clear browser cache: Settings → Browser → Clear Cache
- Try a different browser (Firefox, Chrome, Safari)
- Ensure JavaScript is enabled in browser settings

### Reminders Not Showing
- Ensure frequency is spelled correctly (see Frequency Options above)
- Open the Log tab to see reminders (they only show there)
- Add at least one medication to Reference tab

### Can't Add to Home Screen
- Make sure you're using Safari (iPhone) or Chrome (Android)
- Try a different browser if your default doesn't support it

## 📱 Supported Devices

- ✅ iPhone (iOS 12+) - Use Safari
- ✅ Android (Chrome, Firefox, Samsung Internet)
- ✅ iPad - Use Safari
- ✅ Any device with a modern browser

## 🔧 Technical Details

- **Built with:** HTML5, CSS3, JavaScript
- **Storage:** Browser LocalStorage API
- **No Backend:** Runs entirely in your browser
- **No Tracking:** No analytics, no ads, no tracking
- **Open Source:** Code available on GitHub

## 📝 License

This project is free to use for personal health tracking.

## ⚠️ Medical Disclaimer

This app is a **tracking tool only**, not a medical device. Always follow your doctor's or pharmacist's instructions for medication use. In case of medical emergency, call 911 or your local emergency number.

---

## 🙋 Support & Feedback

If you encounter issues or have suggestions:
1. Check the Troubleshooting section above
2. Ensure your browser is up to date
3. Try a different browser to isolate issues

## 🎯 Common Use Cases

### Pain Management
Use interval-based frequencies like "6h pain" to track doses of pain medication with flexible timing.

### Daily Supplements
Use fixed schedules like "2x daily" for vitamins, supplements, or regular medications.

### Mixed Schedule
Add both types - daily medications on fixed schedules and pain meds on intervals.

### Doctor's Instructions
Follow exactly what your doctor or pharmacist recommends for frequency and dosage.

---

**Stay healthy! 💊**
