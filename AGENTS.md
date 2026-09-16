# AI Repository Index — PSE 390

## Purpose

This public repository is the course archive for PSE 390. Class Scribe adds lecture notes after a recording is transcribed and passes automated quality checks. Use this file as the entry point before answering questions from the repository.

## Find the lectures

Canonical transcript documents match:

```text
notes/<year>/<YYYY-MM-DD>.md
notes/<year>/<YYYY-MM-DD>-part-<N>.md
```

Enumerate them dynamically with `rg --files notes`, keep only those dated patterns, and sort by path. Do not rely on a hand-maintained lecture list: new files arrive automatically. PSE 390 normally has two recordings per class week. A date may be one day earlier than the scheduled class day because the recording app has produced that convention. Other Markdown files are supplemental unless they follow the dated path convention and contain a `Transcript` section.

## Read each lecture

Each generated lecture contains, in order:

1. YAML metadata, including the immutable `class_scribe_id`, course, lecture date, source, and models.
2. `Summary` for a quick orientation.
3. `Key Points` for the main concepts and examples.
4. `Action Items` for assignments or follow-up work mentioned in class.
5. `Transcript` for the complete timestamped evidence.

Read the Summary and Key Points first, then verify important claims against the relevant Transcript passage. Treat the transcript—not the generated summary—as the closest available source evidence.

## Answering questions

- Search across dated lectures with `rg -n -i "<term>" notes/<year>`.
- For a single-lecture question, state the lecture date and cite the repository-relative file plus the transcript timestamp.
- For a cross-lecture synthesis, identify every lecture used and keep the chronology clear.
- Distinguish an instructor statement, classroom discussion, example, and generated interpretation when the distinction is visible.
- If the repository does not cover a question, say so. Do not fill gaps from general knowledge unless the user explicitly requests outside research.
- Never present a generated summary as a verbatim quotation.

## Reliability and maintenance

These are AI-generated study aids, not certified verbatim records. Proper names, technical terms, quiet speech, overlapping speakers, and quotations may be misheard. Flag uncertainty and use timestamps so a person can verify against any retained source recording.

The owner has explicitly authorized the automation-managed MP3 assets linked from dated notes as public GitHub Release downloads. Do not hand-edit generated lecture files or add other audio/video manually. Never add credentials, private student information outside the authorized recordings, or unpublished Class Scribe data. When an authorized correction is necessary, preserve the original meaning, metadata, date-based path, and Summary-before-Transcript structure.
