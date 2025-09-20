# mowthelawn
Fűnyírás emlékeztető

A simple lawn mowing reminder application hosted on GitHub Pages that uses Google Apps Script as a backend API.

## Features

- ✅ Add new lawn mowing reminders with title, due date, notes, and priority
- ✅ View all your reminders with visual status indicators
- ✅ Mark reminders as completed
- ✅ Delete reminders you no longer need
- ✅ Overdue reminder notifications
- ✅ Responsive design that works on mobile and desktop
- ✅ Graceful fallback to demo mode when API is unavailable

## Usage

The application automatically calls the Google Apps Script backend to manage your reminders. If the API is temporarily unavailable, it will fall back to demo mode using local browser storage.

## Technical Details

- Frontend: Pure HTML, CSS, and JavaScript hosted on GitHub Pages
- Backend: Google Apps Script (called as an API)
- No build process required - ready to deploy
- CORS-enabled API calls with error handling
