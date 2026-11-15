# Crew Leave Tracker

Plans and tracks crew leave on a yacht: rotation order for deck and interior, flexible leave for the sous chef, leave balances, flight bookings, optional travel days, and a monthly and 12-month calendar.

**Open the app:** https://pelorus-capital-projects.github.io/crew-leave-tracker/

## Login

The app opens behind a username and password, set up the first time you open it on each device (or brought across by restoring a backup file on the setup screen). You get 8 one-time recovery codes at setup: **Forgot password?** on the sign-in screen lets you set a new password with your username and one code. Make a fresh set any time under **Settings → New recovery codes**.

Only salted hashes (PBKDF2-SHA256) of the password and codes are saved, never the words themselves. The login stops other people opening the app on your device; it does not encrypt the data stored in the browser or in backup files.

## Your data

- Nothing you enter is sent anywhere. Crew and leave are saved in the browser you use, on that device only.
- Use **Backup → Download backup file** regularly, and **Choose backup file** to restore or to move your data to another device or browser.
- This public copy contains no crew names or leave records. Load your own with **Choose backup file**.

## Updating the app

Replace `index.html` with the new version (Add file → Upload files → Commit changes). Your saved data is not affected.

Pelorus Capital Projects
