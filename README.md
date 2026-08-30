# Peptide Tracker App

A mobile-friendly web application for tracking peptide doses, managing vial inventory, and setting reminders.

## Features

- 📅 **Today Dashboard** - Quick view and record today's peptide doses
- 🗓️ **Calendar** - Visual calendar showing recorded doses and reminders
- 📦 **Inventory Management** - Track vial stock levels and expiration dates
- 🧾 **History** - View all recorded doses with timestamp
- 🔔 **Reminders** - Set daily, weekday, or custom reminders
- ⚙️ **Settings** - Manage peptides and app preferences

## How to Use

1. Open `index.html` in a web browser
2. The app stores all data locally in your browser using localStorage
3. Navigate between sections using the bottom navigation bar

### Recording a Dose

1. Go to the "Today" tab
2. Click the "+" button on any peptide card
3. Enter the amount and unit
4. Click "✓ Mark Taken"

### Managing Inventory

1. Go to the "Inventory" tab
2. Click "+ Add Vial" to add new vials
3. Track remaining amounts and expiration dates
4. Set low inventory warnings

### Setting Reminders

1. Go to "Calendar" or the "More" tab
2. Click "🔔 Add Reminder"
3. Select peptide, time, and frequency
4. Save reminder

## Data Storage

All data is stored locally in your browser's localStorage. No data is sent to external servers.

## Disclaimer

This app is for personal tracking only. It does not provide medical recommendations or reconstitution instructions. Always consult appropriate documentation and healthcare providers.

## Browser Compatibility

Works on modern browsers (Chrome, Firefox, Safari, Edge) on desktop and mobile devices.
