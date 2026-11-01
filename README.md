# Tracker

Change a row in `tasks.json`, commit, and push. The site updates from the main branch.

`due` is `YYYY-MM-DD` or `null`. A bar is drawn only when `due` is set and `gantt` is not `false`.

`status` is one of: Unknown, Question, Not started, In progress, Blocked, Done.

`waitingOn` is a list of task ids.

Do not add files from outside this folder.
