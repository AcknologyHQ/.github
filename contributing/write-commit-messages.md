# How to Write Commit Messages

A commit message is a short description of the changes that are included in a commit. It is an important part of the version control process, as it helps to document the changes that are made to the codebase and provides context for why the changes were made.

Follow [Conventional Commits](https://conventionalcommits.org/) or [Gitmoji](https://gitmoji.dev/) to format your commit messages in a uniform way, which can help to keep commits organized and easy to understand. 

By following a consistent pattern for commit messages, you can make it easier for others to review and understand the changes that you have made, and to see how they fit into the overall project.


* Follow either [Conventional Commits](https://conventionalcommits.org/) or [Gitmoji](https://gitmoji.dev/) to format your commit messages 
    
    > **gitmoji** is preferred for formatting commit messages because it is easier to read and write and provides a visually appealing way to convey the purpose of the commit.

* Keep it short: A commit message should be concise, typically no more than 50-70 characters in the subject line.

* Use the imperative mood: The subject line should be written in the imperative mood, as if you are issuing a command. 

* Provide context: The body of the commit message should provide more context for the changes, including a detailed description of what was changed and why the changes were made.

* Use bullet points: If the commit includes multiple changes, you can use bullet points to list them out. This helps to make the commit message easier to read and understand.

<br>
<br>

## Mapping Conventional Commits to Gitmoji

A basic table to show the equivalent Conventional Commits and Gitmoji for formatting commit messages.

type | conventional | gitmoji | description
--- | --- | --- | ---
begin |  | :tada: | Start of a new project `Initial commit`
fix | bug: | :bug: | bug fix
feature | feat: | :art: | introuce new feature
docs | docs: | :memo: | documentation only
style | style: | :pencil: | formatting, white-space, missing semi-colons, etc
refactor | refactor: | :pencil: | A change that neither fixes a bug nor adds a feature
perf | perf: | :zap: | A change that improves performance
chore | chore: | :wrench: | A change that doesn't modify src or test files
revert | revert: | :rewind: | Revert to a commit
WIP | WIP: | :hammer_and_wrench: | Work in progress
release | release: | :rocket: | A release commit
breaking | breaking: | :boom: | A breaking change
remove | remove: | :fire: | A removal of code, or files

For more information, visit [gitmoji.dev](https://gitmoji.dev/)