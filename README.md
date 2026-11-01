# Tracker

Change a row in `tasks.json`, commit, and push. The site updates from the main branch.

Every item is a row, in dependency order. A row with `due` inside the window is a bar up to that date. A row with no `due`, or a `due` after the window, is a full-width block.

`status` is one of: Unknown, Question, Not started, In progress, Blocked, Done.

`waitingOn` is a list of task ids.

Do not add files from outside this folder.
