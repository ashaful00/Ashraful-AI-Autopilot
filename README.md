# Ashraful AI Autopilot — Android starter (v1.0 UI preview)

This is a native Kotlin + Jetpack Compose Android Studio project scaffold.

## What is included
- Professional dark UI (black + blue)
- Dashboard with a target of 20 unique videos/day
- Planned Instagram, Facebook and YouTube connection cards
- Placeholder workspace cards for content, editing and scheduling

## What is NOT implemented yet
This preview does not generate videos, access Google Flow, edit media, connect social accounts, or publish posts. Those require separate integrations and authorization:
- Meta Graph API / Instagram publishing permissions and a linked Facebook Page
- YouTube Data API OAuth consent and channel authorization
- A secure backend for token storage, job queues and scheduled publishing
- A supported video-generation workflow; do not assume Google Flow has a public generation API

Never put API secrets or long-lived social tokens directly in the Android app.

## Build
1. Install Android Studio on a computer.
2. Open this project folder.
3. Let Android Studio sync Gradle.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).

Application ID: `com.ashraful.autopilot`
Minimum Android: 8.0 (API 26)
Target SDK: 35

A compiled APK is not included in this ZIP; this is the starter source project.
