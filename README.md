# 🎬 Claude Editing Kit

One double-click and your Claude video editing setup is ready. No folders to make, no commands to type.

## ⬇️ Download
- **Mac:** [Claude-Editing-Mac.zip](https://github.com/techyakanshu/claude-edit-kit/raw/main/Claude-Editing-Mac.zip)
- **Windows:** [Claude-Editing-Windows.zip](https://github.com/techyakanshu/claude-edit-kit/raw/main/Claude-Editing-Windows.zip)

## How to use
1. Open the zip and double-click **Claude Editing Setup**.
2. First time only:
   - **Mac:** if it says "Apple could not verify", go to System Settings → Privacy & Security → **Open Anyway**.
   - **Windows:** on "Windows protected your PC", click **More info → Run anyway**, and Yes on any popup.
3. Wait 2–5 minutes. A **Claude Editing** folder appears on your Desktop.
4. Put a reference reel in `1-Reference` and your video in `2-Meri-Video`.
5. Open the Claude app → **Code** tab → choose the *Claude Editing* folder.
6. Say: **"edit my video like the reference"**. The edited video lands in `3-Final`.

## What gets installed
ffmpeg, yt-dlp, Node.js and uv (for captions with Whisper). On Mac everything goes into `~/.claude-edit` (no Homebrew, no password). On Windows it uses winget.
