# Sangeetha v1.0.2

<a href="https://github.com/NareshMRN/Sangeetha-releases/releases/latest">
  <img src="https://tachibanagenerallaboratories.github.io/images/badges/GitHub/get-it-on-github.png" width="160" alt="Get it on GitHub">
</a>
[![Get it on Website](https://img.shields.io/badge/Get_it_on-Website-0052FF?style=for-the-badge&logo=vercel)](https://thesangeetha.vercel.app/download)

## 🚀 Release Notes — Sangeetha (v1.0.2 & Latest Updates)

### 📌 Summary
This update introduces key bug fixes across the Android App, connects the Web Frontend Contact Form to the reports backend system, improves authentication flows, and optimizes APK asset distribution via GitHub Releases.

### 📱 Android App Improvements (android)
* **Navigation & Shell Enhancements:** Improved app shell (`app_shell.dart`) navigation and bottom tab routing for a smoother user experience.
* **Authentication & Logout Flow:** Refactored `login_screen.dart`, `forgot_password_screen.dart`, and `account_settings_screen.dart` to handle login state, password reset OTPs, and clean logout redirects without getting stuck on wrong screens.
* **UI & Theme Fixes:** Updated Android XML style configurations for improved dark mode compatibility and Android SDK support.
* **Settings Cleanup:** Streamlined the settings menu and removed redundant options in `settings_screen.dart`.

### 🌐 Frontend Web Application (frontend)
* **Contact Form Dashboard Integration:** Overhauled the Contact Us page (`app/contact/page.js` & `contact.css`) to seamlessly submit inquiry and report messages directly into the backend reports dashboard.
* **Newsletter Component:** Enhanced `NewsletterForm.js` component for user subscriptions.
* **Reels Component Updates:** Upgraded `ReelsCard.js` with improved preview cards and interaction handling.
* **Blog & Firebase Updates:** Applied minor stability fixes to `app/blog/page.js` and updated `lib/firebase.js` configurations.

### 📦 Distribution & APK Releases
* **GitHub Release Direct Downloads:** Updated frontend download buttons to point directly to public GitHub Release assets for v1.0.2 (`sangeetha-armeabi-release.apk`, `sangeetha-arm64-bit-release.apk`).
