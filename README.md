# Language learning

This repository keeps language-learning agents, learning materials, and generated practice resources together. Each language has its own folder so an agent can work in that folder while the whole collection stays backed up in one place.

## Folders

- `Spanish/` — Spanish instructions, existing materials, and new Spanish resources
- `Chinese/` — Chinese instructions, existing materials, and new Chinese resources
- `Danish/` — Danish instructions, existing materials, and new Danish resources

Each language folder also has a `Progress.md` file. It records the current skill estimates, goals, recurring strengths and errors, and dated evidence from assignments. Levels begin as unassessed and should be filled in from diagnostic work, not guessed from the materials already in the folder.

Keep generated work in the relevant language folder:

- `Worksheets/` for exercises and answer keys
- `Texts/` for short reading texts and translations
- `Vocabulary/` for word lists and flashcard exports

Use descriptive filenames with the language level and date when useful, for example `A2_At_the_cafe_2026-10-09.md`. Keep source files editable as Markdown or DOCX where practical; PDFs and other exports can sit beside them.

## Agent instructions

The root `AGENTS.md` contains rules shared by all language agents. Each language folder has its own `AGENTS.md` with language-specific direction and `Progress.md` as its learner record. Configure each local agent to use this repository (or its language folder) as its working directory so it sees the matching instructions and materials.

## Back up with GitHub

Create a **private** GitHub repository named `languages`, connect this folder as its local repository, and push the initial commit. After that, commit and push changes regularly so worksheets and texts are available from another computer.

Before the first push, review the files being uploaded. Only add materials you have the right to store in a private cloud repository; keep personal or licensed source material out if needed.
