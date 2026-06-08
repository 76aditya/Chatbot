# React Chatbot Project

An interactive Chatbot application built using React (via CDN) and styled with Plus Jakarta Sans typography.

This project integrates an asynchronous chatbot utility to handle real-time messaging simulations complete with smooth scroll behaviors and dynamic loading animations.

---

## Features

*   **React Component Architecture:** Utilizes modular components (`App`, `ChatMessages`, `ChatMessage`, and `ChatInput`) to cleanly manage state and UI updates.
*   **Asynchronous Simulation:** Simulates realistic network delay using automated response promises.
*   **Dynamic Loading Indicators:** Shows a typing/loading state while waiting for the bot's response.
*   **Auto-Scroll Messaging:** Automatically scrolls the message pane to the latest text whenever a new message is sent or received.
*   **Dual-Input Actions:** Supports both clicking the "Send" button and pressing the `Enter` key to transmit messages easily.

---

## Project Structure

Your local `chatbot` directory inside the `React` folder contains the following core files:

```text
chatbot/
├── Chatbot.html          # Main HTML entry point containing the React/Babel code
├── chatbot.js            # Underlying JavaScript logic & string similarity algorithm
├── User.jpg              # Profile avatar picture representing the user
├── Bot.jpg               # Profile avatar picture representing the chatbot
└── loading-spinner.gif   # Animated loading icon used during message delays
```
## Steps to Setup:
1- Clone this repository from GitHub using your terminal:
   ```
      git clone [https://github.com/your-repo-name/Chatbot.git]
   ```
2- Navigate to the Project Folder
   Change your working directory to the folder containing the chatbot files:
   ```
      cd your-repo-name/chatbot
   ```
3- Ensure all file names are correctly cased in your local directory (e.g., User.jpg, Bot.jpg, loading-spinner.gif, Chatbot.html, and chatbot.js).

## Chatbot Capabilities:

Chatbot Capabilities
The local chatbot.js background processor is pre-programmed to cleverly detect variations of commands using string similarity matching.
Try asking it to:

Flip a coin, 
Roll a dice, 
What is the date today, 
Say Hello or Thank you!
