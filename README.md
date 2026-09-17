# .github

Default community health files for every repository under this account. GitHub serves
`.github/ISSUE_TEMPLATE/` from here to any repository of ours that has no issue templates of its
own, private repositories included ("Creating a default community health file" in the GitHub
docs). This repository has to be public for that to work; it holds the issue forms, their
configuration, this file, and a licence that covers only this repository (GitHub does not serve
a default licence to other repositories).

Two forms. `Task` is for features and chores: a goal, acceptance criteria a stranger could test
unaided, and optionally what is out of scope. `Bug` is for defects: what is wrong, the build it
was seen on, steps to reproduce, expected and actual behaviour, how often it happens, and
acceptance criteria prefilled with the reproduction and regression checks; it applies the `bug`
label. Either way the body is the brief. Do not add a
`.github/ISSUE_TEMPLATE` folder to another repository; a valid one there replaces this default
entirely, without warning.
