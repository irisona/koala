# Android Activity Demo

This Android demo runs Koala in the foreground (i.e., when the app is in focus).

## Setup

1. Replace `String ACCESS_KEY = "..."` inside
   [MainActivity.java](koala-activity-demo-app/src/main/java/ai/picovoice/koalaactivitydemo/MainActivity.java)
   with your AccessKey generated by [Picovoice Console](https://console.picovoice.ai/).

```java
private static final String ACCESS_KEY = "YOUR_ACCESS_KEY_HERE";
```

2. Add  `pvTestingAccessKey = "..."` inside `local.properties`
   with your AccessKey generated by [Picovoice Console](https://console.picovoice.ai/).

```console
pvTestingAccessKey=YOUR_ACCESS_KEY_HERE
```

3. Open the project in Android Studio and run the demo on your device or simulator.