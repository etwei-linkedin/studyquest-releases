# StudyQuest

A Mac study app for kids, roughly ages 8–12:

- **Math:** daily practice, a step-by-step Learning Path that starts with a short placement test, and Contest Training with AMC 8–style puzzles.
- **Flashcards** with spaced review, so tricky cards come back sooner.
- **AI tutor** that gives hints first instead of handing out answers.
- **Writing** with prompts and AI feedback.
- **Speaking** practice with feedback.
- **Reading log** with book suggestions.
- **Planner** with progress charts.
- **Rewards:** XP, levels, streaks and badges.
- **Parents area,** protected by a PIN, with reports, daily goals and settings.

> **This is an early test version.** Thanks for trying it! Your feedback shapes what comes next.

## Download

**[Get the latest version →](https://github.com/etwei-linkedin/studyquest-releases/releases/latest)**

Download the **.dmg** file. It needs **macOS 14 Sonoma or newer** and works on both Apple Silicon and Intel Macs.

🎬 New here? Watch the **4-minute tutorial video** (`StudyQuest-Tutorial.mp4` on the same page).

## Install (about 2 minutes)

1. Open the .dmg and drag **StudyQuest** into **Applications**.
2. Open StudyQuest. The first time, macOS says **"StudyQuest" Not Opened**. Click **Done**. *Don't* click Move to Trash, which is the highlighted button.
3. Open **System Settings → Privacy & Security**, scroll down to **Security**, and click **Open Anyway** next to "StudyQuest was blocked to protect your Mac".
4. Click **Open Anyway** again, then enter an administrator's name and password.

You only do this once; after that it opens normally. macOS asks because this test version isn't registered with Apple yet (notarized). That will change in a future version.

## First steps

1. Type the child's first name and pick a buddy.
2. Follow the short guided tour, which takes about 2 minutes. You can replay it anytime from **Go → Take the Tour…**.
3. **Grown-ups:** open **Parents** and create a 4–6 digit PIN that only you know. Then set daily goals in **Settings**.

## AI features (optional)

The **tutor**, **writing and speaking feedback**, and **AI plans** use Claude by Anthropic. To turn them on:

1. Create an API key at [console.anthropic.com](https://console.anthropic.com/) → **API Keys**. Usage is billed to your Anthropic account and is typically a few cents a day for one child.
2. In StudyQuest, open **Parents → Settings → AI helper**, paste the key, and click **Test connection**.

The key is stored in your Mac's Keychain. Everything else (math, the Learning Path, contests, flashcards, reading, the planner and rewards) works without a key.

## Privacy

- **No accounts, ads, analytics or tracking.**
- **Progress stays on your Mac,** in `~/Library/Application Support/StudyQuest`.
- **Speech recognition runs on the Mac.** Audio is never uploaded.
- **AI features** send only the text they need, such as the question or the writing, to Anthropic using your own key. The AI is told to stay kid-friendly and on learning topics, and never to ask for personal information.

## Feedback and bugs

**[Open a feedback issue →](https://github.com/etwei-linkedin/studyquest-releases/issues/new/choose)** (needs a free GitHub account)

Helpful details: what you did, what happened, your macOS version (Apple menu → About This Mac), and a screenshot if you can. Please don't include your child's full name, or your API key, in screenshots.

## Uninstall

1. Drag **StudyQuest** from Applications to the Trash.
2. To also delete progress, remove `~/Library/Application Support/StudyQuest`.
3. To remove a saved API key, open **Keychain Access**, search for `studyquest`, and delete the item.
