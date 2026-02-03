# DroidCo

**DroidCo** is a lightweight, browser-based chat application that transmits data over sound waves. Inspired by the "Matrix" aesthetic, it allows devices to communicate via microphone and speakers without needing an internet connection, Bluetooth, or Wi-Fi pairing.

This project is a fork/customization based on the powerful [ggwave](https://github.com/ggerganov/ggwave) library.

## 🚀 Features

* **Data-over-Audio:** Send and receive text messages using sound.
* **Zero Config:** No pairing required. Just open the app on two devices and place them near each other.
* **Matrix UI:** Custom dark/green terminal aesthetic.
* **Custom Controls:**
    * **Protocol Selection:** Choose between Audible (Normal, Fast, Fastest) and Ultrasound (Hidden/Inaudible) transmission modes.
    * **Volume Control:** Adjustable transmission volume slider for better usability.

## 📱 How to Run Offline on Android

You can run DroidCo completely offline on your Android device without a web server.

1.  **Download:** Download the `index.html` file from this repository to your phone.
2.  **Install Editor:** Install **Xed Editor** from the Google Play Store.
3.  **Open & Run:** * Open Xed Editor.
    * Navigate to and open the downloaded `index.html`.
    * Tap the "Run/Preview" button (usually a browser icon or play button).
4.  **Enjoy:** The app will launch locally. Ensure you grant Microphone permissions when asked.

### 🇧🇬 Инструкции за офлайн ползване (Android)

Ако искате да стартирате приложението напълно офлайн на вашия Android телефон:

1.  Изтеглете файла `index.html` от това хранилище на телефона си.
2.  Инсталирайте приложението **Xed Editor** от Google Play Store.
3.  Отворете файла `index.html` чрез Xed Editor.
4.  Стартирайте го директно през едетора (бутона за преглед).
5.  Разрешете достъп до микрофона, когато браузърът попита.

## 🛠️ Protocols

Use the dropdown menu to select the transmission mode:
* **Audible:** Standard "R2-D2" style sounds. Most reliable.
* **Ultrasound:** Near-silent transmission (high frequency). Requires speakers/mics capable of handling ~18kHz+.

## 📜 Credits & License

**DroidCo** is heavily based on the work of **Georgi Gerganov**.

* **Original Library:** [ggwave](https://github.com/ggerganov/ggwave)
* **Author:** Georgi Gerganov
* **License:** MIT License

This project adheres to the original MIT License permissions.
