# Source chat context

This is the working memory of the Grok thread that produced the feedback pack. It is not a verbatim transcript. It is enough for Grok Build to know what was said, when, and in what tone.

## Thread purpose

stp used one long Grok chat as a feedback workshop. He asked Grok to keep a running batch, refine wording, stay humble, and later check whether anything shipped.

He also asked Grok to “keep me posted in this chat” if the team replied. Grok does not have an internal ticket back-channel. Status checks in this file are public-observation only.

## Timeline

### 19 Jul 2026 — first batch

stp started with “Feedback on the feedback chat” and then iterated line by line.

Items locked that day:

1. Pinned chats pushed down by new chats; manual re-pin; want a dedicated top section; Expand vs History inconsistency on grok.com desktop. Originally sent with 3 screenshots + video (files not in this repo).
2. History navigation: jump-to-top and jump-to-bottom. After clarification: always show both arrows by default. Opening a chat already goes to the bottom (good). Clicking an arrow when already there can no-op.
3. Add labeled “Search in this chat” for the current conversation only. Note: Ctrl+F / “control at pattern 34” on Windows exists; not everyone knows it.
4. Cross-platform sync not fully real-time. App → grok.com live. grok.com → iOS needs close + reopen. Originally supported with a screen recording (file not in this repo).
5. Sidebar icons only (hover for text). Show labels by default or toggle. If implemented, icon AND text must both be links (whole row clickable). Later: also offer delete-the-icons / text-only. Icons look clean; not always user-friendly.

Humble note added on request:

> These are just things I personally observe while using Grok. I don’t think I’m a pioneer, a genius, or anything like that. These are simply my honest suggestions based on my own experience. They are open to debate and completely up to the team.

### 24 Jul 2026 — naming / App Store

High-priority add: App Store messaging can send people to test the wrong product for coding.

Suggested split:

- Grok → general assistant
- Grok Build → coding agent (powered by the strong model)

Example line he liked:

> Grok 4.5 is our smartest model. For serious coding and agentic work, use Grok Build.

He asked to make the wording clear for the “reasoning team.”

### 25 Jul 2026 — X profiles (positive)

> Feedback on the update of x profiles: Great succes. Love it. Well done to the team. This is how its done.

Follow-up: noticed it earlier, now really appreciates it. Really good.

### 4 Sep 2026 — “any feedback on the feedback?”

Grok checked public sources. Honest answer: no official team reply through the chat. Approximate public status at that time:

- Pinned chats: still a live complaint; third-party sidebars exist to keep pins on top.
- In-chat / history search: still weak; other users report title search misses chats.
- Sync web → iOS: no public confirmation of a fix.
- Sidebar labels: no public change.
- Naming: Grok Build did become a separate product. Confusion then included Grok Bot as a third name. Core point still valid: say which tool is for coding.
- X profiles: the positive item that looked shipped.

### 5 Sep 2026 — Shake to Report

stp recorded an iPhone clip (~20.5s). A bump / putting the phone down / throwing it on the bed opens **Report a Problem** over the live chat.

He called the gesture useless for normal use. Grok pointed at the text already on the sheet: turn it off in Advanced Settings.

stp: never looked into that, still does not see the value, then turned it off (“what a blessing its gone”).

Final wording he approved:

- Suggestion is up for debate.
- He would not put shake-to-open as a default.
- He hit the popup many times, saw the sheet, did not read it, did not ask for help. That part is on him.
- Off switch was already there.
- Still: movement should not open a report sheet.

Evidence in `media/` (committed 14 Sep 2026 from the public share). Original filename in chat: `ScreenRecording_09-05-2026 17-16-05_1.mp4`. Same bytes as `media/shake-to-report-2026-09-05.mp4`.

Share used to recover the file: https://grok.com/share/bGVnYWN5_03c6ea3d-739c-4065-933d-43c140e37e38

That share contains **one** user upload. July pinned-chat / sync files were described, not re-attached.

### 14 Sep 2026 — this pack

stp asked to:

- summarize the feedback
- make a GitHub of it
- insert all vids / screens that exist
- name it **feedback stp delusional**
- write a prompt for Grok Build and give Build access to this chat

That is why this file exists.

## Voice rules for any rewrite

- Short.
- No “visionary user” language.
- Credit the team when he did (X profiles).
- Admit missing files instead of faking screenshots.
- Admit user-side miss on Shake to Report.
- Do not promise the team received or will ship anything.
