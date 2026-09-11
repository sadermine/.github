# .github

Default community health files for every repository under this account. GitHub serves
`.github/ISSUE_TEMPLATE/` from here to any repository of ours that has no issue templates of its
own, private repositories included ("Creating a default community health file" in the GitHub
docs). This repository has to be public for that to work; it holds the issue form, its
configuration, and this file.

One form, `Task`, for bugs, features and chores alike. Its body is the brief: a goal, acceptance
criteria a stranger could test unaided, and optionally what is out of scope. Do not add a
`.github/ISSUE_TEMPLATE` folder to another repository; a valid one there replaces this default
entirely, without warning.
