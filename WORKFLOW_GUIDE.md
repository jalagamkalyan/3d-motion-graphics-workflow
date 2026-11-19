# The $0 3D Motion Graphics Workflow: From Prompt to 60 FPS Video

**Channel:** Kalyan's Lab (@TheKalyanChakri)  
**Cost:** $0  
**Tools Required:** Claude (or ChatGPT) + Google Chrome (or any browser) + OBS / Screen Recorder  
**Time to Execute:** ~3 Minutes  

---

## Why Stop Using Expensive 3D Software?
* **After Effects:** $35/month + steep learning curve.
* **Blender:** Hours of keyframing, lighting nodes, and 30-minute render times per clip.
* **Stock Footage:** $30/month + everyone uses the exact same overused clips.

This workflow uses **Three.js** (the WebGL engine that powers modern websites like Apple and Vercel) and **AI** to generate custom, 60 FPS 3D animations that run entirely in your web browser for free.

---

## The 3-Minute Step-by-Step Workflow

### Step 1: Generate the Code with Claude
1. Open [Claude.ai](https://claude.ai) (or ChatGPT).
2. Copy and paste the prompt from [`CLAUDE_MASTER_PROMPT.txt`](./CLAUDE_MASTER_PROMPT.txt).
3. Customize the text or colors if you want (e.g., change `"KALYAN'S LAB"` to your channel name, or change the color from `#00F5D4` cyan to gold or violet).
4. Hit Enter. Claude will output a single block of HTML/JavaScript code.

### Step 2: Run It in Chrome (Zero Install)
1. Open Notepad (or VS Code).
2. Paste the code into the file.
3. Save the file as `card.html` (make sure it ends with `.html`, not `.txt`).
4. **Double-click `card.html`** to open it in Google Chrome.
5. You now have a live, interactive 3D WebGL card running at a butter-smooth 60 frames per second! Move your mouse or drag your finger to see the 3D perspective shift.

### Step 3: Capture the 60 FPS Footage
1. Press `F11` in Chrome to go full-screen.
2. Use **OBS Studio**, **Windows Game Bar** (`Win + G`), or **QuickTime** on Mac to record 5 to 10 seconds of the smooth floating card.
3. Drop the recorded MP4 file straight into **CapCut**, **Premiere Pro**, or **DaVinci Resolve** as an overlay or background for your YouTube video or Short!

---

## How Kalyan Used This to Break Through 22 Views

> *"My channel was stuck at 22 views. Viewers were dropping off in the first 3 seconds because static stock footage looked lazy. When I replaced stock clips with custom Three.js WebGL visuals, audience retention jumped from 20% to 84%, and views exploded to 1,203 in 24 hours. Audiences don't care about your subscriber count—they care about visual effort."*

---

## ⚡ Want the Next 3D Template?
Subscribe to **Kalyan's Lab** on YouTube [@TheKalyanChakri](https://youtube.com/@TheKalyanChakri).  
Every Friday, we open-source a new custom AI + code motion graphics asset!
