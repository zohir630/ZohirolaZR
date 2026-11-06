# Zohirola (chat demo)

An Android chat app built on the MQTT Chat SDK (Real-time messaging, one-on-one chat, photos, voice notes, stickers, calls).

- Package: `com.zohirola.mqtt`
- Developer: [zohir630](https://github.com/zohir630)

## Important
The chat SDK (`com.telifoun.mqttchat:*`) is a closed-source commercial library and the chat runs on its cloud service. The `appId` and `appSecret` in `mApplication.java` are the shared demo credentials from the original demo project. They are for testing only. For your own app, create your own account with the SDK vendor and replace them.

## Build
Use the **Build APK** GitHub Actions workflow, or run `./gradlew assembleDebug` (JDK 11).
