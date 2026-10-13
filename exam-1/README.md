# PSE 390 · Exam 1 study kit

Everything built for the PSE 390 (Ethics for Management) midterm: a study guide, two 33-question practice exams with explanations, short-answer practice, and condensed lecture notes. All of it is plain Markdown and JSON, so you can read it here, load it into your own tools, or fork the website.

**Live site:** https://pse390-midterm-guide.vercel.app (a single static page, no backend)

## What's here

| File | What it is |
|---|---|
| [`study-guide.md`](study-guide.md) | Six Steps, the 13 ethical issue types, the Ethics Toolkit, the 11 rationalizations, in-class cases, and the course map with reading links |
| [`practice-exam-1.md`](practice-exam-1.md) | The 33 questions from the Canvas Mid-Term Study Guide, answered and explained |
| [`practice-exam-2.md`](practice-exam-2.md) | 33 new questions plus 2 short-answer prompts, answered and explained |
| [`lecture-notes.md`](lecture-notes.md) | What the professor said in each of the eight recorded lectures |
| [`exam-format.md`](exam-format.md) | Every statement the professor made about the exam, by date |
| [`data/`](data) | The same content as JSON: `practice-exam-1.json`, `practice-exam-2.json`, `short-answer.json`, `lectures.json` |
| [`site/`](site) | Source of the website (`index.html` plus `vercel.json`). Deploy it anywhere that serves static files |

## Using the data

Each question in the exam JSON files looks like this:

```json
{
  "number": 1,
  "part": 1,
  "partName": "Six Steps to Sound Ethical Decision Making",
  "question": "…",
  "options": { "A": "…", "B": "…", "C": "…", "D": "…" },
  "answer": ["B"],
  "multiSelect": false,
  "explanation": "…",
  "inClass": "What the professor said about this in lecture (Exam 1 only, where available)",
  "judgment": true
}
```

`answer` is always an array. `multiSelect` is true for "select all that apply". `judgment` appears only where the answer is a call rather than a certainty.

To run the website locally, open `site/index.html` in a browser. To host it, copy the `site` folder to any static host (it was deployed to Vercel as-is).

## Read this before trusting it

- **The answers are student-derived.** The professor did not post an answer key. Four answers on Practice Exam 1 are tagged as judgment calls.
- **The lecture notes come from AI transcripts**, which garble names and some passages. Unclear parts were left out. Check the full transcripts in [`notes/2026`](../notes/2026).
- **Coverage.** The recordings cover Sep 2 through Oct 5. The Oct 7 class was cancelled and Oct 12 (Conflicts of Interest) had not been recorded when this was written.
- Practice Exam 1 reproduces the professor's study guide questions. Canvas links in the study guide only work with a BYU Canvas login.
- This is an unofficial student-made study aid and is not affiliated with BYU or Prof. Kaylor. Provided as-is, with no warranty.
