# MedPlanner

A free study planner for medical and allied health students (MBBS, BDS, DPT, Pharm-D, Nursing, MLT, Radiology and more). It runs in the browser, installs on your phone like an app, and works offline. All your data stays on your own device.

**Live demo:** https://adil.liveblog365.com

## Features

- **Timetable builder** - enter your wake-up time and bedtime and it builds a daily routine with prayers, meals and study blocks, plus a weekly subject plan you can edit.
- **Subjects and topics** - pick your department and semester, or import subjects from a syllabus PDF, pasted text or an AI-made list.
- **Spaced revision** - mark a topic as studied and it is scheduled for revision on days 1, 3, 7, 14, 30 and 60.
- **Flashcards** - spaced-repetition review, with bulk import from Anki or Excel.
- **Quiz tab (AI test builder)** - generate professor-style MCQs by subject, topic, difficulty and question style (clinical vignette, one-line recall, assertion-reason, OSCE/viva). Questions can follow the pattern of past papers for your university and semester. Test history and MCQ bank export included.
- **AI Tutor tab** - explanations, mnemonics, model exam answers, clinical cases and flashcards for any topic. Save answers to your notes.
- **Many AI providers** - Gemini, Groq, OpenRouter, Mistral, Cerebras, Pollinations (no key), Claude, ChatGPT, DeepSeek, or any OpenAI-compatible service. If one fails or runs out of quota, the app tries the next one you have set up.
- **NotebookLM workflow** - export your notes as a sources file, generate MCQs from your own notes and past papers, and paste them back into the app.
- **Alarms** - a loud alarm screen with snooze for study blocks, prayers and revision, plus an export of your whole timetable to your phone calendar (`.ics`) so alarms ring even when the app is closed.
- **Focus timer, task list, exam countdown, progress statistics, themes and cloud backup.**

## Using the AI features

1. Open **More > AI connection** and choose a provider.
2. Paste your API key. Keys are stored only in your browser's local storage and are never included in backups.
3. Open the **Quiz** tab, choose a subject and tap **Generate & start**.

No key? Tap **Copy prompt**, paste it into the free Claude, ChatGPT, Gemini or NotebookLM app, then paste the answer back and tap **Import**.

Notes:
- Free tiers, model names and limits change often. Use **Load all models** to see what your key can use.
- Web search for real past papers works only with Claude, ChatGPT and Gemini, and only where your plan allows it. Otherwise questions are written in past-paper style and labelled that way.
- AI output can be wrong. Check medical facts against your textbooks.

## Install on your phone

Open the live demo in Chrome, then use the browser menu and choose **Install app** or **Add to Home screen**.

## Run or host it yourself

There is no build step. The app is plain static files: `index.html`, `sw.js`, `manifest.webmanifest` and two icons. Upload them to any static host, for example GitHub Pages (Settings > Pages > Deploy from a branch > `main` / root).

When you publish an update, change the cache name in `sw.js` (for example `medplanner-v11`) so users receive the new version.

## Privacy

Everything is stored in your browser on your device. The app talks to the internet only when you use AI features (to the provider you choose), fetch prayer times, or load the PDF reader library.

## Disclaimer

MedPlanner is a study aid and is not medical advice or an official source of exam content.# Akmedplnner-v10.pk
Free offline study planner for MBBS, BDS, DPT, Pharm-D, Nursing and allied health students: timetable, spaced revision, flashcards, focus timer, AI quiz generator and study alarms.
