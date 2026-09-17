# 🚀 paddock - Run Open AI Models on NVIDIA GPUs EASILY

## 🖥️ What is paddock?

paddock is a powerful but **easy-to-use** program that lets you run open-source AI models on your NVIDIA graphics card (GPU). Think of it as a private, local version of ChatGPT or Claude that runs entirely on your own computer. You don't need to be a programmer or know anything about AI. If you have a NVIDIA GPU, you can use paddock.

paddock speaks the same "language" as OpenAI (ChatGPT) and Anthropic (Claude), which means many existing AI tools and apps can connect to it. But unlike those cloud services, your data stays on your computer, and you don't pay per message.

[![Download paddock](https://img.shields.io/badge/Download_paddock-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dhaniselo/paddock)

## ✨ What Makes paddock Special?

- **🧠 Runs Open Models** - It can run popular open-source AI models like Llama, Mistral, and many others. No need for expensive cloud subscriptions.
- **⚡ Blazing Fast on NVIDIA GPUs** - Built specifically for NVIDIA graphics cards, including the latest Blackwell series. It uses advanced optimization to make models run faster and use less memory.
- **🔌 Works With Your Favorite Apps** - Because it's compatible with OpenAI and Anthropic APIs, you can plug it into tools you already use, like chat interfaces, coding assistants, or automation software.
- **📦 Simple Model Management** - Supports easy-to-use model file formats (GGUF and safetensors) and advanced compression types (FP8, NVFP4, MXFP4, Q8, Q4) that make models load faster and use less GPU memory.
- **📊 Built-in Studio** - Comes with a visual interface so you can chat with models, test them, and see them work without needing any technical setup.

## 🚀 Getting Started - Download and Run

Follow these simple steps. You'll be up and running in just a few minutes.

### 📥 Step 1: Download paddock

Visit this link to download the application: **[https://github.com/dhaniselo/paddock](https://github.com/dhaniselo/paddock)**

Look for the download section or the release files on that page to get the Windows version of paddock.

### 💾 Step 2: Run paddock

Once the download is complete, find the downloaded file (usually in your "Downloads" folder). Double-click the file to run it. The program will start, and you'll see the paddock main window appear.

### 🤖 Step 3: Choose a Model

In the paddock Studio, you'll see a list of AI models you can use. Pick one that interests you (like a chat assistant or a writing helper) and click "Load" or "Run" on it. paddock will automatically download and set up the model for you - no manual work needed.

### 🎉 Step 4: Start Using AI

Once a model is loaded, you can start typing messages in the chat box. The model will respond just like ChatGPT. You can ask questions, get help writing, analyze text, and much more.

If you want to connect paddock to an external app, look for the API settings in paddock - it gives you a local address and key that other apps can use to talk to the AI.

## ❓ Frequently Asked Questions

### 🛑 Why isn't paddock working on my computer?

paddock requires a **NVIDIA graphics card (GPU)** to work. If you don't have one, the program won't run properly. Also, make sure your GPU drivers are up to date. You can check by visiting the NVIDIA website for the latest drivers for your specific GPU model.

### 📦 How do I get more models?

In the paddock Studio, there's usually a "Model Store" or "Browse Models" button. Click it, and you'll see a library of models you can download with one click. Models vary in size and quality - bigger models are smarter but need more GPU memory.

### 💡 Can I run paddock alongside other programs?

Yes, but AI models are demanding. If other software is using most of your GPU (like games or video editors), paddock might slow down. It's best to close heavy programs while running large models.

### 🔒 Is my data private?

Yes! Everything runs locally on your computer. Your chat messages are not sent to any server. They stay on your machine. This is one of the big advantages of paddock over cloud services.

### 💻 Does it work on Mac or Linux?

The primary version of paddock is for Windows with NVIDIA GPUs. If you have a Mac with Apple Silicon, or a Linux system, performance and compatibility may vary. Check the project's discussions or issues page for community reports.

## 🛠️ Troubleshooting Common Issues

- **"CUDA error" or "No GPU found"** - This means paddock can't see your NVIDIA GPU. Update your NVIDIA drivers, restart your computer, and try again.
- **Model won't load** - This is often due to insufficient GPU memory. Try a smaller model, or close other applications to free up memory.
- **Slow performance** - Check if Windows is using the integrated graphics instead of the NVIDIA GPU. You can force paddock to use the NVIDIA GPU in Windows Graphics Settings by searching "Graphics settings" in the Start menu.
- **Antivirus false positive** - Some antivirus software flags local AI tools as suspicious. If this happens, add an exception for paddock in your antivirus settings.

## 📚 Advanced Use (For the Curious)

If you want to go deeper, paddock supports connecting to external applications using standard AI API protocols. You'll find connection details (like the local server address and an API key) in the settings or API tab of the Studio. Apps that support custom OpenAI or Anthropic API endpoints can connect to `http://localhost:PORT` with paddock's given key.

For developers, paddock also allows loading custom model files (GGUF or safetensors format). Simply place your downloaded model file in the models folder that paddock creates, then refresh the model list in the Studio.

## 🌟 Why Choose paddock?

- **Own your AI** - No subscriptions, no per-message fees, no usage limits.
- **Privacy-first** - Your conversations never leave your PC.
- **Fast and efficient** - Optimized to get the most out of NVIDIA hardware.
- **Open format support** - Works with many community models and formats.
- **Continuous improvement** - Written in Rust, a language known for speed and safety, ensuring a reliable experience.

## 📢 Get Help & Join the Community

- **GitHub Issues** - Report bugs or request features at the repository: [https://github.com/dhaniselo/paddock/issues](https://github.com/dhaniselo/paddock/issues)
- **Discussions** - Ask questions and share tips in the community discussions section of the GitHub repository.

---

**Ready to get started?** Click the button below to download paddock and unlock the power of local AI.

[![Get paddock Now](https://img.shields.io/badge/🚀_Get_paddock_Now-FF6F00?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dhaniselo/paddock)

Keywords: ai, aimodels, blackwell, cuda, inference, inference-engine, inference-optimization, model-serving, nvidia, rust