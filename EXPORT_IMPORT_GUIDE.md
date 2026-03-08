# 📊 Export & Import Guide

Complete guide to backing up and restoring your medication data.

## 🔄 Quick Overview

| Action | What It Does | When to Use |
|--------|-------------|-----------|
| **Export to Excel** | Downloads CSV and JSON files | Monthly backups, sharing with doctor, analysis |
| **Import from File** | Restores previously exported data | Getting data back, switching devices |

---

## 📥 Exporting Your Data

### Step 1: Open Settings Tab

1. Open the Medication Tracker app
2. Tap the **⚙️ Settings** tab

### Step 2: Click Export Button

Click **"📊 Export to Excel"**

Two files automatically download:

#### File 1: CSV File
- **Name:** `medication_tracker_YYYY-MM-DD.csv`
- **Opens in:** Excel, Google Sheets, Numbers, any spreadsheet app
- **Contains:** All entries and medications in table format
- **Best for:** Viewing, analyzing, sharing with healthcare providers

#### File 2: JSON Backup File
- **Name:** `medication_tracker_backup_YYYY-MM-DD.json`
- **Opens in:** Text editor
- **Contains:** Complete backup of all data
- **Best for:** Re-importing into the app

### What's in the Export

**Medication Log Section:**
```
Date | Time | Medication | Dosage | Notes
2024-03-07 | 08:00 | Ibuprofen | 500mg | Taken with food
2024-03-07 | 14:00 | Ibuprofen | 500mg | 
2024-03-07 | 20:00 | Ibuprofen | 500mg | Mild headache
```

**Medication Reference Section:**
```
Name | Purpose | Dosage | Frequency
Ibuprofen | Pain relief | 500mg | 6h pain
Aspirin | Heart health | 81mg | 1x daily
```

**Summary Statistics:**
```
Total Entries: 47
Today's Entries: 3
Total Medications: 5
Export Date: 2024-03-07
```

---

## 📤 Importing Your Data

### Prerequisites

You must have a **JSON backup file** (from a previous export)

### Step 1: Open Settings Tab

1. Open the Medication Tracker app
2. Tap the **⚙️ Settings** tab

### Step 2: Click Import Button

Click **"📥 Import from File"**

### Step 3: Select File

1. Choose the JSON backup file you previously exported
2. File picker opens - navigate to your Downloads folder
3. Select the `medication_tracker_backup_*.json` file

### Step 4: Confirm Import

A confirmation appears showing:
- Number of entries to import
- Number of medications to import

Click **"OK"** to proceed

### Step 5: Data is Restored

✓ Your data is now in the app
- All previous entries are restored
- All medications are restored
- Data is merged (not overwritten)

---

## 🔄 Common Workflows

### Scenario 1: Monthly Backup

**Why:** Keep a history of medication tracking

**How:**
1. First day of each month: Open Settings → "Export to Excel"
2. Save the CSV and JSON files with the date
3. Example: `medication_tracker_2024-03-01.json`

**Result:** You have monthly backups you can reference or restore

---

### Scenario 2: Switch to New Phone

**Why:** Move your medication history to a new device

**How:**

**On Old Phone:**
1. Open the app
2. Go to Settings tab
3. Click "Export to Excel"
4. Save both files (CSV and JSON)
5. Email the JSON file to yourself

**On New Phone:**
1. Download the Medication Tracker app on new phone
2. Go to Settings tab
3. Click "Import from File"
4. Select the JSON file from email
5. All your data is restored!

---

### Scenario 3: Share Data with Doctor

**Why:** Give your healthcare provider a summary of your medication usage

**How:**
1. Open the app
2. Go to Settings tab
3. Click "Export to Excel"
4. Download CSV file
5. Open CSV in Excel or Google Sheets
6. Print or email to your doctor

**What They'll See:**
- All medications taken (dates and times)
- Dosages
- Any notes (side effects, observations)
- Frequency summary

---

### Scenario 4: Reinstall App After Accidental Clear

**Why:** You accidentally cleared all data

**How:**
1. If you previously exported: Import the JSON file
2. All your data comes back!
3. This is why regular exports are important

---

## 💡 Best Practices

### Regular Exports

**Weekly:**
- Quick backup of last week's data
- Minimal effort, maximum safety

**Monthly:**
- Comprehensive backup
- Easy to manage and organize
- Create a folder: `MedicationTracker_Backups/2024-03/`

**Yearly:**
- Archive one full year of data
- Reference for annual health reviews

### File Organization

**Desktop/Computer:**
```
Documents/
└── MedicationTracker_Backups/
    ├── 2024-03/
    │   ├── medication_tracker_backup_2024-03-01.json
    │   └── medication_tracker_2024-03-01.csv
    ├── 2024-02/
    │   └── ...
    └── 2024-01/
        └── ...
```

**Cloud Storage (Optional):**
- Upload JSON backups to Google Drive, OneDrive, or Dropbox
- Provides redundancy (local + cloud)
- Can access from anywhere

### Security Tips

✅ **Keep backups in a safe location**
- Don't leave on public computers
- Password-protect your cloud storage
- Keep a copy on USB drive (encrypted)

✅ **JSON files contain health data**
- Treat like you would medical records
- Don't share unnecessarily
- Delete old backups when no longer needed

---

## 🆘 Troubleshooting

### "Export button doesn't work"
- Make sure you have at least one medication entry
- Try refreshing the app
- Check that browser allows file downloads

### "CSV file opens with weird characters"
- This is normal for some spreadsheet apps
- Try opening in Excel or Google Sheets instead
- Or use a text editor to verify the content

### "Can't find the downloaded files"
- Check your Downloads folder
- On Android: Files app → Downloads
- On iPhone/Mac: Files app or Finder
- On Windows: Check Downloads folder

### "Import says 'Invalid file format'"
- Make sure you're importing the **JSON** file
- Don't try to import the CSV file
- The JSON file should be named `medication_tracker_backup_*.json`

### "Data didn't import"
- Check that the file is a valid JSON backup
- Make sure the file wasn't corrupted
- Try exporting again and re-importing

### "Imported data, but it looks wrong"
- JSON backups capture data at export time
- Any changes after export won't be included
- Re-enter missing entries manually
- Or re-import an older backup

---

## 📋 What Gets Exported/Imported

### YES - Included:
✅ All medication entries (date, time, dosage, notes)
✅ All medications in reference
✅ Frequencies and schedules
✅ All custom notes
✅ Complete history

### NO - Not Included:
❌ App settings (like dark mode, if added in future)
❌ User preferences
❌ Passwords (app doesn't use them)
❌ Browser cache or cookies

---

## 🎯 When to Export

**Must Export When:**
- Updating to new version of the app
- Switching to a new phone
- Deleting the app
- Monthly/regular backup routine

**Should Export When:**
- You've reached a milestone (100 entries, 3 months of tracking)
- Before a doctor's appointment
- For sharing with healthcare provider
- For your own records

**Don't Need to Export When:**
- Making daily entries
- Updating your app (if using GitHub Pages - auto-syncs)
- On same device with same app version

---

## 💼 For Healthcare Providers

If you want to share your medication history with your doctor:

1. **Export to CSV** (not JSON - CSV is more readable)
2. **Open in Excel or Google Sheets**
3. **Print or Save as PDF**
4. **Add notes:**
   - Any side effects
   - Missed doses
   - Changes in dosage
   - Questions for doctor
5. **Share with healthcare provider**

---

## 📞 Backup Support

**Questions about backing up?**
- Re-read this guide
- Check the README.md for general help
- Try exporting/importing with a small amount of test data first

**Issues with a backup file?**
- Don't panic - your data is still on the phone
- Export again to create a fresh backup
- Try importing in a fresh instance

---

## ✅ Backup Checklist

- [ ] I've exported my data at least once
- [ ] I know where my backups are stored
- [ ] I have backups on more than one device
- [ ] I've tested importing a backup
- [ ] I do monthly exports
- [ ] I organize backups by date

---

**Your health data is important. Regular backups ensure you never lose your medication history!** 💊
