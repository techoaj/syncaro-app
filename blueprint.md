
# Project Blueprint

## Overview

This project is a Flutter mobile app that acts as a WebView container for a given website URL. It also integrates Firebase Analytics to track user engagement, specifically which URLs are being viewed.

## Features

*   **WebView:** Displays a web page within the app.
*   **URL Input:** A text field for users to enter a website URL.
*   **Analytics:** Firebase Analytics is used to track which URLs are loaded.

## Current Plan

1.  **Add Dependencies:** Add `webview_flutter`, `firebase_core`, and `firebase_analytics` to `pubspec.yaml`.
2.  **Configure Firebase:** Set up Firebase for the Android and iOS platforms.
3.  **Implement WebView Screen:** Create the main screen with a `TextField` for the URL, a button, and the `WebView` widget.
4.  **Integrate Analytics:** Log an event to Firebase Analytics every time a new URL is loaded.
