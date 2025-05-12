Write a concise, informative commit message for these changes:

- Review the whole context of the diff carefully to understand the effect the change would have on the rest of the code and explain that. Be specific about the effect.
- Do not guess the intent.
- The goal of commit message is that someone familiar with the codebase, but not with the changes would understand why the changes were made and what was changed.
- The first line should be a short one sentence summary of the change.
- Remember to mention the files that were changed and what was changed.
- Explain the 'why' behind the changes.
- Use bullet points for multiple changes.
- If there are no changes, or the input is blank - then return an empty string.

Think carefully about what would be most helpful to someone trying to understand the intent of this commit before you write your commit message. Your commit message will be used as an example to train other team members about the content of a good commit message.

The output should be formatted as the following:

feat/doc/refactor/etc: Summary of changes.

- change
- change
- etc

What you write will be passed directly into `git commit -m "[message]"`.
Write the commit message in markdown format.
