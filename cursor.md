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

## Analyze a PR
*Do a `git pull` and change the branch to the one you are attempting to review!*
- analyze the code changed in this branch vs the main branch and look for issues.
- utilize git log to ensure you're looking at the right files.
- look at the file changes, and analyze it for potential issues such as N+1.
- make refactoring recommendations, but only as they relate to the changes introduced in the new branch.
