# AI video skill for Claude Code

A free Claude Code skill that makes a whole AI video from a few sentences: an AI influencer, a UGC ad, or a remake of
a trending reel. You say what you want, take your hands off the laptop, and Claude makes the character sheet, plans
5-8 camera angles, makes stills in Google Flow (Nano Banana), throws out every frame that would not happen in real
life, animates the good ones with Veo or BytePlus Seedance, cuts the best seconds on the music and hands you the mp4.

Shown in this video: https://youtu.be/yDSoV5COvv8

## Install
Copy the `ai-video` folder into your skills folder:
- Claude Code: `~/.claude/skills/ai-video/`
- Any agent that reads skills: its skills folder.

Then type `/ai-video` and say what you want. On the first run it asks a few setup questions (work folder, browser,
your photos if you want your own avatar) and saves them.

## What you need
- Claude Code (or another agent that runs skills) with a browser it can drive (the Playwright MCP works).
- A Google account with access to Google Flow, and optionally a BytePlus account for free Seedance video credits.
  You sign in yourself; the skill never types passwords.
- ffmpeg and yt-dlp on your PATH.

## What's inside
- `ai-video/SKILL.md`: the full workflow.
- `ai-video/references/`: camera angles, shot types, camera moves, transitions and the many-angle "commercial cut".

MIT licence. Made by Anshul (YouTube: Anshul AI).
