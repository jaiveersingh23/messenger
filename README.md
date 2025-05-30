# OnlyChat – Java-Based Android Messenger

OnlyChat is a versatile Java-based chat application built using **Android Studio**. It supports multiple modes of communication, including:

- 🌐 **Internet Chat**: Real-time messaging using Firebase over the Internet.
- 🤖 **AI Chatbot**: Chat with an intelligent assistant powered by OpenAI's GPT (API key required).
- 📶 **Mesh Network Messaging**: Offline communication via **Bluetooth**, ideal for close-proximity, internet-free messaging.

> ⚠️ Note: Bluetooth Chat currently works up to **Android 12**. Android 13+ introduces new permission models and Bluetooth constraints that need to be implemented separately.

---

## 🚀 Features

### ✅ Chat Using the Internet
- Real-time one-on-one messaging
- Firebase backend integration
- Simple and secure user interface

### ✅ Chat with AI Chatbot
- Ask questions and get intelligent responses
- Uses OpenAI GPT API
- API key must be manually inserted into the project (excluded for security reasons)

### ✅ Mesh Network Messaging (Bluetooth)
- Chat offline using Bluetooth
- Auto device discovery and peer-to-peer communication
- Works up to Android 12

---

## 🛠 Tech Stack

- **Language**: Java
- **IDE**: Android Studio
- **Cloud Backend**: Firebase Realtime Database
- **AI Integration**: OpenAI GPT (via REST API)
- **Bluetooth Communication**: Android Bluetooth APIs

---

## 🔒 API Key Information

The OpenAI API key is **not included** in the repository to prevent misuse. To enable chatbot functionality:

1. Obtain your own OpenAI API key from [OpenAI](https://platform.openai.com/).
2. Insert it into the designated section in the codebase (e.g., `ChatbotActivity.java`).

---

## 📲 Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/jaiveersingh23/messenger.git
