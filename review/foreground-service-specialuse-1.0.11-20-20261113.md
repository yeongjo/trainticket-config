# Foreground service demonstration: 1.0.11 (20)

Recorded on 2026-11-13 on a Galaxy S23 running Android 16. This is an optimized release build of the 1.0.11 (20) source, installed as the separate development package `com.theqoo.gichapyo.dev` with a debug signing key and test ads. The Play bundle uses `com.theqoo.gichapyo`, the upload signing key and production ad configuration.

The recording shows an existing user-selected Seoul–Busan journey being monitored: the user starts monitoring through the confirmation dialog, one check completes, the ongoing notification is shown, the user stops monitoring from the notification, then starts and stops it from the app. Runtime inspection confirms `foregroundServiceType=0x40000000` (specialUse).

The video preserves the recorded sequence and timing. Unrelated notifications and status icons are covered with black rectangles for privacy; frame rate and compression are reduced. It does not demonstrate a successful reservation or uninterrupted 24-hour operation. After recording, the user's existing watch was restarted with its original 10-minute interval and reward deadline.
