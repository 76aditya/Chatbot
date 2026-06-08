# React Chatbot Project

A sleek, interactive, and responsive Chatbot application built using React (via CDN) and styled with Plus Jakarta Sans typography. This project integrates an asynchronous chatbot utility to handle real-time messaging simulations complete with smooth scroll behaviors and dynamic loading animations.

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
