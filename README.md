# Teracloud Streams VS Code Extension – Issues & Documentation

This repository is dedicated to **issue tracking and documentation** for the official [Teracloud Streams VS Code extension](https://marketplace.visualstudio.com/items?itemName=teracloud-aps.teracloud-streams).

📌 **Note:** This repo does not contain the extension source code.  
It is only for reporting issues, tracking feature requests, and hosting documentation (in progress).

## 📥 Installing the Extension
You can install the extension directly from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=teracloud-aps.teracloud-streams).

## 📚 Documentation
The full documentation is a **work in progress** and will be added here soon.  

👉 Until then, please use the **extension walkthrough inside VS Code**:  
- Open the **Teracloud Streams** walkthrough from the VS Code **Welcome** page.  
- Follow the guided steps to configure your environment, connect to your Streams domain, and build/submit jobs.

## 🐛 Reporting Issues
If you encounter problems, have questions, or want to suggest new features:  
1. Check the [Issues](../../issues) tab to see if it’s already reported.  
2. If not, open a **new issue** with as much detail as possible:
   - VS Code version  
   - Extension version  
   - Operating system  
   - Steps to reproduce (if applicable)  

## 🚀 Using Quick Start Edition (QSE) as a Dev Container (Experimental)

For local development, you can use the [Teracloud Streams Quick Start Edition (QSE)](https://hub.docker.com/r/teracloudaps/streams-qse) — a free, containerized, single-node Streams environment licensed for **development only**.

With QSE you get:
- A preconfigured Streams installation  
- A running domain and instance on startup  
- Access to the Streams console, REST API, and `streamtool` CLI

### Using QSE with the VS Code Extension

It is possible to use QSE as a [VSCode Dev Container](https://code.visualstudio.com/docs/devcontainers/containers) .

Once inside the container:
1. In the extension settings, set the Streams installation path to the container’s installation path (mounted into your dev environment).
2. Point your domain connection to https://localhost:8443.
3. Use the default QSE credentials (streamsadmin / streams1).

## 🔗 Resources
- [Teracloud Streams Official Website](https://streams.teracloud.com)  
- [Teracloud Streams Documentation Website]((https://doc.streams.teracloud.com)

✍️ Thanks for helping us improve the Teracloud Streams developer experience!
