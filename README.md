Gabrielle, Genevieve, Kemal, Ravi, Andy

# Process for opening and closing issues (testers)

Use the [Markdown](https://guides.github.com/features/mastering-markdown/) syntax to create a new issue.

Inspect any changes in the code pushed by the developers, and merged by the admin of the repository.

Whenever the changes you requested are fixed, add a comment pointing to the place (`commit`) where the issues were resolved, and close the issue.

> You can paste the url of a specific commit into your issue's textbox and GitHub will automatically turn it into a nice link.

# Process for merging a pull request (developers)

The `main` branch of the repository is blocked. Changes need to come through a **pull request**.

If working with the repository for the first time:

- Fork the repository
- `clone` it to your local computer
```
git clone <url_of_your_fork>
```

- Make changes in your **working directory (playground)**

- Before you send your changes, create a new branch
```
git branch <name_of_the_branch>
git checkout <name_of_the_branch>
```
- **Stage** the files you wish to `commit`
```
git add <files_to_stage>
```

- `commit` the changes, providing a useful (and short) message.
```
git commit -m "<a_useful_message_describing_the_committed_changes>"
```

- Send your changes to the `remote` repository on GitHub
```
git push origin/<name_of_the_branch>
```

> Remember that `origin` is the default name given to the `remote` where you cloned from.

Then, within the web interface of GitHub, the new branch should show up. There's also a button that says `Compare and pull request`.

Make the pull request to the `main` branch.
