# Pre-Event Setup Guide

Complete all steps in this guide **before** the AI Hackathon event. This will ensure you're ready to focus on learning and building during the session.

**Estimated time:** 45-60 minutes

---

## Table of Contents
1. [Choose and Install Your IDE](#1-choose-and-install-your-ide)
2. [Install Cline Extension](#2-install-cline-extension)
3. [Get Your LiteLLM Key](#3-get-your-litellm-key)
4. [Configure Cline with LiteLLM](#4-configure-cline-with-litellm)
5. [Create GitHub Account](#5-create-github-account)
6. [Set Up Git in Your IDE](#6-set-up-git-in-your-ide)
7. [Learn Basic Git Commands](#7-learn-basic-git-commands)
8. [First Exercise: Clone This Repository](#8-first-exercise-clone-this-repository)
9. [Make Your Repository Private](#9-make-your-repository-private)
10. [Verify Your Setup](#10-verify-your-setup)

---

## 1. Choose and Install Your IDE

Cline works with three popular IDEs. Choose the one that best fits your needs:

### Option A: Visual Studio Code (VS Code)
**Best for:** Beginners, most popular choice
- **Download:** https://code.visualstudio.com/
- **Size:** ~100MB
- **Pros:** Lightweight, huge extension library, great documentation
- **Cons:** Fewer AI features built-in

### Option B: Windsurf
**Best for:** Those who want AI-first experience
- **Download:** https://codeium.com/windsurf
- **Size:** ~150MB
- **Pros:** Built-in AI features, modern interface
- **Cons:** Newer, smaller community

### Option C: Cursor
**Best for:** Advanced users who want AI pair programming
- **Download:** https://cursor.sh/
- **Size:** ~120MB
- **Pros:** Advanced AI integration, collaborative features
- **Cons:** Learning curve for advanced features

**Installation Steps:**
1. Download your chosen IDE from the link above
2. Run the installer
3. Follow the on-screen instructions
4. Launch the IDE once installation is complete

> 📸 **Screenshot needed:** `../images/ide-selection.png` showing the three IDE options

---

## 2. Install Cline Extension

Cline is an AI coding assistant that works inside your IDE.

### Installation Steps:

1. **Open your IDE** (VS Code, Windsurf, or Cursor)

2. **Open the Extensions panel:**
   - VS Code/Windsurf: Click the Extensions icon in the left sidebar (or press `Ctrl+Shift+X` / `Cmd+Shift+X`)
   - Cursor: Click Extensions in the sidebar

3. **Search for "Cline"** in the extensions search bar

4. **Click "Install"** on the Cline extension

5. **Wait for installation to complete** (usually takes 10-30 seconds)

6. **Verify installation:**
   - You should see a Cline icon appear in your sidebar
   - Click it to open the Cline panel

![Search for Cline in Extensions](../images/extensions-search.png)

![Cline installed](../images/cline-installed.png)

![Cline panel in the IDE sidebar](../images/cline-panel.png)

---

## 3. Get Your LiteLLM Key

LiteLLM provides access to AI models (like GPT-4) through Lingaro's infrastructure. You'll need a key to use Cline during the hackathon.

### Step-by-Step Instructions:

#### Step 1: Open Microsoft Teams
- Launch Microsoft Teams on your computer

#### Step 2: Search for "Lingaro Dev Env Agent"
1. Click the **Search bar** at the top of Teams
2. Type: `Lingaro Dev Env Agent`
3. Click on the result to access the agent

![Searching for the Lingaro Dev Env Agent in Teams](../images/team-search-agent.png)

#### Step 3: Install the Agent (if not already installed)
1. If you see an "Install" or "Add" button, click it
2. Follow any prompts to complete installation
3. The agent will appear in your Teams chat list

#### Step 4: Start a Conversation with the Agent
1. Click on **"Lingaro Dev Env Agent"** in your chat list
2. The chat window will open

#### Step 5: Generate Your LiteLLM Key
1. In the chat, type exactly: `Generate LiteLLM Key`
2. Press Enter
3. Wait for the agent to respond (usually 5-10 seconds)
4. The agent will generate and display your unique key

![Generate LiteLLM Key command and response](../images/agent-chat-generate-key.png)

#### Step 6: Copy and Save Your Key
1. **Copy the entire key** (it will be a long string of characters)
2. **Save it temporarily** in a secure note or text file
3. **Do NOT close this window yet** - you'll need the key in the next step

### Understanding Your Budget

**Initial Budget:** $20 USD
- This is sufficient for the hackathon and initial learning
- Typical usage: ~$0.10-0.50 per conversation with GPT-4
- You can complete the entire hackathon within this budget

**Requesting Additional Budget:**
1. Return to the "Lingaro Dev Env Agent" chat
2. Type: `increase my budget`
3. The agent will ask: "How much?"
4. Enter your desired amount (e.g., `50`)
5. Your request will be sent for approval
6. **Only request what you need** - be mindful of costs

**Important Notes:**
- If you use **Solution Cockpit**, it shares the same LiteLLM key and budget
- All usage across tools is counted against your total budget
- Monitor your usage to avoid running out during important work

> ⚠️ **SECURITY WARNING**
> - **NEVER share your LiteLLM key** with anyone
> - **DO NOT** post it in chat, email, or documents
> - If you accidentally expose it, generate a new one immediately
> - Treat it like a password

---

## 4. Configure Cline with LiteLLM

Now let's connect Cline to LiteLLM so you can use AI models.

### Configuration Steps:

1. **Open Cline panel** in your IDE (click the Cline icon in sidebar)

2. **Open Settings:**
   - Click the gear/settings icon in the Cline panel
   - Or click "Configure API" if this is your first time

3. **Select API Provider:**
   - Choose **"LiteLLM"** from the provider list

4. **Enter the Base URL:**
   - Use: `https://llm.lingarogroup.com`

5. **Enter your LiteLLM key:**
   - Paste the key you copied from the Lingaro agent in Teams
   - Click "Save" or "Confirm"

6. **Select a Model:**
   - For now, use **Claude Haiku 4.5** for basic tasks

7. **Test the connection:**
   - Cline should show "Connected" or a green indicator
   - Try asking Cline a simple question: "What is 2+2?"

![Cline setup](../images/cline%20setup.png)

**Troubleshooting:**
- **"Invalid API Key" error:** Double-check you copied the entire key
- **"Connection Failed":** Check your internet connection
- **No response:** Try selecting a different model or regenerating your key

---

## 5. Create GitHub Account

GitHub is where we'll store and share code. You'll use your Lingaro email to create an account.

### Why GitHub?
- Version control for your projects
- Collaborate with team members
- Share and showcase your work
- Access to millions of open-source projects

### Step-by-Step Account Creation:

1. **Go to GitHub:**
   - Open your browser
   - Navigate to: https://github.com/signup

2. **Enter your Lingaro email:**
   - Use your `@lingaro.com` email address
   - This links your account to your work identity

![GitHub signup email step](../images/github-signup-email.png)

3. **Create a password:**
   - Use a strong, unique password
   - Consider using a password manager

4. **Choose a username:**
   - This will be public and part of your profile
   - Suggestions: `firstname-lastname` or `finitiallastname`
   - Example: `john-smith` or `jsmith-lingaro`

> 📸 **Screenshot needed:** `../images/github-username.png`

5. **Verify your account:**
   - Complete the verification puzzle
   - Check your Lingaro email for verification code
   - Enter the code on GitHub

6. **Complete your profile (optional but recommended):**
   - Add a profile picture
   - Add your name and location
   - Keep it professional - this is a work account

> 📸 **Screenshot needed:** `../images/github-profile-complete.png`

### Account Settings to Review:

- **Email notifications:** Set preferences for repository updates
- **Two-factor authentication:** Highly recommended for security
- **Profile visibility:** Set to public or private as preferred

---

## 6. Set Up Git in Your IDE

Git is the tool that tracks changes to your code. Let's configure it in your IDE.

### First, Check if Git Is Installed

1. **Open your IDE terminal**
2. **Run:**
   ```bash
   git --version
   ```
3. **If Git is already installed**, you will see a version number and can continue.
4. **If Git is not installed**, download it from: https://git-scm.com/downloads
5. **Restart your IDE** after installing Git, then come back and continue with the steps below.

### Initial Git Configuration:

1. **Open your IDE terminal:**
   - VS Code/Windsurf: `Terminal > New Terminal` or `Ctrl+` (backtick)
   - Cursor: Similar menu option

2. **Set your name:**
   ```bash
   git config --global user.name "Your Full Name"
   ```
   Example: `git config --global user.name "John Smith"`

3. **Set your email:**
   ```bash
   git config --global user.email "your.email@lingaro.com"
   ```
   Use the same email as your GitHub account

4. **Verify configuration:**
   ```bash
   git config --list
   ```
   You should see your name and email in the output

### Authenticate with GitHub:

#### Using GitHub CLI (Recommended)
1. Install GitHub CLI: https://cli.github.com/
2. In terminal, run:
   ```bash
   gh auth login
   ```
3. Follow the prompts:
   - Choose "GitHub.com"
   - Choose "HTTPS"
   - Authenticate via browser

### Verify Authentication:
```bash
git ls-remote https://github.com/mv-alvarado/MNL-AI-Hackathon-2026
```
If you see a list of references, authentication works!

---

## 7. Learn Basic Git Commands

Here are the essential Git commands you'll use during the hackathon:

### Core Git Commands:

#### `git clone` - Copy a repository to your computer
```bash
git clone https://github.com/username/repository-name
```
**When to use:** Getting a project for the first time

**Example:**
```bash
git clone https://github.com/mv-alvarado/MNL-AI-Hackathon-2026
```

---

#### `git pull` - Get latest changes from GitHub
```bash
git pull
```
**When to use:** Before starting work, to sync with team changes

**What it does:**
- Downloads new changes from GitHub
- Merges them with your local files
- Keeps your copy up-to-date

---

#### `git add` - Stage files for commit
```bash
git add filename.txt          # Add specific file
git add .                     # Add all changed files
```
**When to use:** Before committing changes

**What it does:** Prepares files to be saved in the next commit

---

#### `git commit` - Save your changes
```bash
git commit -m "Description of what you changed"
```
**When to use:** After completing a logical chunk of work

**Example:**
```bash
git commit -m "Added team summary automation script"
```

**Best practices for commit messages:**
- Start with a verb: "Add", "Fix", "Update", "Remove"
- Be specific: "Fix login bug" not "Fixed stuff"
- Keep it under 50 characters when possible

---

#### `git push` - Upload your changes to GitHub
```bash
git push
```
**When to use:** After committing, to share your work

**What it does:** Uploads your commits to GitHub so others can see them

---

#### `git status` - See what's changed
```bash
git status
```
**When to use:** Anytime you want to check the state of your files

**Output shows:**
- Modified files (not yet staged)
- Staged files (ready to commit)
- Untracked files (new files Git doesn't know about)

---

#### `git log` - View commit history
```bash
git log                       # Full history
git log --oneline            # Compact view
```
**When to use:** To see what changes have been made

---

### Common Git Workflows:

#### Daily Workflow:
```bash
# 1. Start your day - get latest changes
git pull

# 2. Make your changes to files
# (edit files in your IDE)

# 3. Check what changed
git status

# 4. Stage your changes
git add .

# 5. Commit with a message
git commit -m "Describe what you did"

# 6. Upload to GitHub
git push
```

#### When Working with Team:
```bash
# Before starting new work
git pull                      # Get team's changes

# After completing your work
git add .
git commit -m "Your changes"
git push                      # Share with team
```

### Git Sync in IDE (Alternative to Commands):

Most IDEs have a built-in Git interface:

**VS Code/Windsurf:**
1. Click **Source Control** icon in sidebar
2. Review changed files
3. Enter commit message
4. Click **✓ Commit**
5. Click **⋯ More Actions > Push**

**Or use the sync button (↻)** to pull and push in one action

![IDE Git interface](../images/ide-git-interface.png)

![Committing in the IDE](../images/commit-in-ide.png)

![Sync button location](../images/sync-button.png)

---

## 8. First Exercise: Clone This Repository

Let's practice by cloning the AI Hackathon repository!

### Method 1: Using Terminal (Recommended for Learning)

1. **Open your IDE terminal**

2. **Navigate to where you want the project:**
   ```bash
   cd ~/Documents              # Mac/Linux
   cd C:\Users\YourName\Documents   # Windows
   ```

3. **Clone the repository:**
   ```bash
   git clone https://github.com/mv-alvarado/MNL-AI-Hackathon-2026
   ```

4. **Enter the directory:**
   ```bash
   cd MNL-AI-Hackathon-2026
   ```

5. **Verify the files:**
   ```bash
   ls                          # Mac/Linux
   dir                         # Windows
   ```
   You should see: README.md, SETUP-GUIDE.md, etc.

### Method 2: Using IDE Interface

**VS Code/Windsurf:**
1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
2. Type: `Git: Clone`
3. Enter: `https://github.com/mv-alvarado/MNL-AI-Hackathon-2026`
4. Choose destination folder
5. Click "Open" when prompted

### Verify Your Clone:

1. **Check you have all files:**
   - README.md
   - SETUP-GUIDE.md (this file!)
   - AI-FUNDAMENTALS.md
   - Other project files

2. **Try opening a file in your IDE**

3. **Success!** You've completed your first Git operation! 🎉

---

## 9. Make Your Repository Private

When you create your own repositories during the hackathon, you may want to keep them private.

### Creating a New Repository (Private):

1. **Go to GitHub.com**
2. Click **"+"** in top-right corner
3. Select **"New repository"**
4. Enter repository details:
   - **Name:** Your project name
   - **Description:** Brief summary
   - **Visibility:** Select **"Private"**
5. Click **"Create repository"**

### Making an Existing Repository Private:

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll to **"Danger Zone"**
4. Click **"Change visibility"**
5. Select **"Make private"**
6. Confirm by typing the repository name

### Why Private Repositories?

**Use Private for:**
- Work in progress
- Client projects
- Proprietary code
- Personal experiments

**Use Public for:**
- Open source contributions
- Portfolio projects (after approval)
- Community resources

---

## 10. Verify Your Setup

Let's make sure everything is working correctly!

### Checklist:

- [ ] **IDE installed and opens successfully**
  - Test: Launch your IDE

- [ ] **Cline extension installed**
  - Test: See Cline icon in sidebar

- [ ] **LiteLLM key configured**
  - Test: Ask Cline "What is 2+2?" and get a response

- [ ] **GitHub account created with Lingaro email**
  - Test: Login to github.com

- [ ] **Git configured with your name and email**
  - Test: Run `git config --list` in terminal

- [ ] **Repository successfully cloned**
  - Test: See MNL-AI-Hackathon-2026 folder with all files

### Quick Test Exercise:

1. **Open MNL-AI-Hackathon-2026 folder in your IDE**

2. **Ask Cline a question:**
   - Open Cline panel
   - Type: "Explain what this repository is for"
   - Wait for response

3. **Make a test change:**
   - Create a new file: `test.txt`
   - Add text: "Setup complete! Ready for the hackathon."
   - Save the file

4. **Commit the change:**
   ```bash
   git add test.txt
   git commit -m "Verified setup is working"
   ```

5. **Check status:**
   ```bash
   git status
   ```

If all steps work, **you're ready for the hackathon!** 🚀

---

## Troubleshooting Common Issues

### Cline Not Responding
**Problem:** Cline doesn't respond to questions

**Solutions:**
1. Check your LiteLLM key is entered correctly
2. Verify you have budget remaining (check Teams agent)
3. Try switching models (GPT-4 to GPT-3.5-turbo or vice versa)
4. Restart your IDE

### Git Authentication Fails
**Problem:** "Authentication failed" when pushing/pulling

**Solutions:**
1. Verify you're using the correct GitHub account
2. Re-run `gh auth login` if using GitHub CLI
3. Generate a new Personal Access Token
4. Check your internet connection

### Clone Command Not Found
**Problem:** `git: command not found`

**Solutions:**
1. Install Git: https://git-scm.com/downloads
2. Restart your IDE after installation
3. Check Git is in your PATH: `echo $PATH` (Mac/Linux) or `echo %PATH%` (Windows)

### LiteLLM Budget Exhausted
**Problem:** "Insufficient budget" error

**Solutions:**
1. Check remaining budget with Teams agent
2. Request increase: `increase my budget`
3. Use GPT-3.5-turbo instead of GPT-4 (cheaper)
4. Wait for budget approval if requested

---

## Next Steps

✅ Setup complete? Great! Now:

1. **Read [AI-FUNDAMENTALS.md](AI-FUNDAMENTALS.md)** to prepare for the session
2. **Explore the `/examples/` folder** for sample prompts
3. **Try asking Cline a few questions** to get comfortable
4. **Think about business problems** you'd like to solve during the hackathon

---

## Need Help?

If you encounter issues during setup:
1. Check the Troubleshooting section above
2. Search for your error message online (often someone else had the same issue)
3. Reach out to the facilitation team before the event
4. Bring your questions to the event - we'll help!

---

**You're all set! See you at the hackathon! 🎉**