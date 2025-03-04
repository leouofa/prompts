## Refactoring

### Create a refactoring plan prompt
#### Prompt Step 1
- create a file called `notes.md`
- go through the files in the `directory` and update the `notes.md` with:
``` 
* with refactoring opportunities
* note filenames and line numbers
* describe the refactoring pattern that would be beneficial
* specifically look for things that can be turned into reusable service jobs and objects
```
- update the notes.md after each file
- look at related files if necessary for better understanding
- when you finish going through all the files iterate through notes.md and verify that the refactoring opportunities are there.

#### Prompt Step 2
Can you iterate through the notes.md and ensure that all refactoring opportunities are there?

## Analysis

## Review a PR
- *Enable `yolo` mode with the follwoing commands `git diff`, `git show`, `grep`, `rspec`, `cat`, `git brach`, `git log`.*
- *Do a `git pull` and change the branch to the one you are attempting to review.*

#### Prompt Step 1
- Analyze the code change in the branch we are on vs. the main branch and look for issues.
- utilize git log to ensure you're looking at the right files.
- look at the file changes, and analyze it for potential issues such as N+1 introduced by the new branch
- make refactoring recommendations, but only as it relate to the changes that were introduced in the new branch.

#### Prompt Step 2
Can you ensure that issues listed were introduced by the files changed in this branch?
