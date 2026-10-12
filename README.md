# knockoff-quizlet (Cramdeck)

A free, single-file Quizlet-style study app. Open `index.html` in any browser. No install, no account, no build step.

## Features
- **Study sets**: create, edit, delete. Paste in a list (tab, dash, comma, colon or semicolon separated); Quizlet exports paste right in.
- **Flashcards**: flip (Space), know it / still learning (arrow keys), undo (Z), shuffle, definition first, starred only.
- **Quiz**: adaptive drill. Multiple choice first, then typed answers. Missed cards come back until you get each one right twice.
- **Test**: graded exam mixing true/false, multiple choice and written questions. Choose question count and answer side, then retest only what you missed.
- **Match**: timed term/definition matching with a saved best time.
- **Practice** (claude.ai version only): Claude writes new problems from your set each round. Difficulty ramps from easy to hard on a 0 to 1 scale with an adjustable median (default 0.70), with hints, step-by-step solutions and answer checking.
- Per-card progress: new, learning, missed, mastered.

## Storage
- Standalone (`index.html` opened directly): sets save in your browser's local storage, on that device only.
- On claude.ai: sets sync to your account across devices, and Practice mode is available.
