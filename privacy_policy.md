# Drift Privacy Policy

Last updated: 2026-03-19

`Drift` is an Android app designed to help users reduce continuous short-video browsing through reminders and friction overlays. This policy explains what the app processes, why it does so, and how that data is handled.

## 1. Summary

- `Drift` works primarily on your device.
- The app does not currently upload your short-video page content, chat content, or account content to the developer.
- The app uses Android accessibility access to identify supported short-video pages and support the leave flow you trigger inside the app.
- Android system backup is disabled for the current first-release configuration.

## 2. Information The App Processes

The app may process the following categories of information on your device:

- current foreground app and page information needed to identify supported short-video contexts
- your guard settings, including configured limits and selected supported apps
- local usage and guard status records used to show history and runtime state inside the app
- foreground notification state used while guarding is active

This processing is used only for the app's short-video guard features.

## 3. Why Accessibility Access Is Used

`Drift` uses Android AccessibilityService only for these purposes:

- identify supported short-video pages
- show reminders or friction overlays in those contexts
- help perform a back action when you choose `退出`
- if you separately enable the optional `自动暂停视频` feature, attempt a single pause gesture when the overlay appears

The app does not present accessibility access as a tool to control your whole phone or monitor unrelated content.

## 4. Data Sharing And Upload

As of the current version reviewed for release:

- the app does not declare the Android `INTERNET` permission
- the app does not intentionally upload your page content, chat content, account content, or local usage records to the developer
- the app does not sell your personal data

If a future version adds cloud features, analytics, crash reporting, or account systems, this policy must be updated before release.

## 5. Local Storage

The app stores some information locally on your device so guarding can work, including:

- rules and guard preferences
- supported app selections
- local usage or guard history shown inside the app
- runtime state needed to keep guarding stable

## 6. Android System Backup

For the current first-release configuration, Android system backup is disabled.

## 7. Permissions

The app may request the following Android permissions or accesses:

- Accessibility access, to identify supported short-video pages and support the leave flow
- Notification permission, to show guard-related notifications
- Foreground service permission, to keep guard-related reminders and overlays reliable while guarding is enabled
- Battery optimization exemption or background-related settings, as optional stability enhancements on some devices
- Boot completed access, to help restore guard-related behavior after device restart or app update when applicable

## 8. Your Choices

You can:

- disable accessibility access in Android settings
- disable notifications in Android settings
- skip optional stability enhancement steps during onboarding
- pause guarding inside the app
- clear app storage or uninstall the app to remove locally stored app data from the device

Disabling required access such as accessibility will limit or stop core guard features.

## 9. Children

`Drift` is not specifically directed to children.

## 10. Changes To This Policy

This policy may be updated if the product's data practices change. The latest version should be made available before the updated version is distributed.

## 11. Contact

For privacy or support questions, contact:

- `blocknose313@gmail.com`
