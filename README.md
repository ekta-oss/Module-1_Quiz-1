# Quick Check (Quiz 1)

Everyday Workplace Communication · Module 1 · Segment 1: Meeting Someone New · **Stage 1.8**, in the Swift AI Academy frame.

A static website: plain HTML, JavaScript, CSS, fonts, images and audio. No server and no build step are needed to host it.
Built from `module1-segment1/` with `node scripts/build-site.mjs 1.8`. Do not edit these files by hand; change the source and rebuild.

## Publish on GitHub + Vercel

1. Put this folder in a GitHub repository (it can be the whole repository, or one folder in it) and push.
2. In Vercel choose **Add New → Project** and import the repository.
3. If this folder is not the repository root, set **Root Directory** to this folder.
4. Set **Framework Preset** to **Other**. Leave the build command and output directory empty.
5. Choose **Deploy**. Vercel gives you an `https://….vercel.app` link.

GitHub Pages also works: Settings → Pages → deploy from the branch and folder that hold `index.html`.

## Try it on your own computer

```bash
npx serve .
```

Then open the address it prints. Double-clicking `index.html` does not work, because browsers block these scripts on `file://` pages.

## Content status

How it works: one question per screen with four progress dots; immediate feedback (right: tick and chime; wrong: gentle shake and an amber card, try again); no negative marking; ungraded self-check, not the Module Assessment. The whole quiz has a 10-minute limit; when it lapses, or when the learner resumes after a pause, the quiz starts again from the first question. Each attempt is recorded in the browser as `1.8.quiz-log` (answers, tries, right first time).

Only the listening item has audio (`media/audio/M1_S01_08_LIS_01.mp3`, "Good afternoon.", interim computer voice: replace it with a recording of the same name and push again).

Open point: the brief says "drag 'am' into both blanks" for Q3, which would make "This am my first day." The quiz uses two chips, **am** and **is** (I am Ananya. This is my first day.), pending confirmation.
