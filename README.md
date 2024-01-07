# Git and GitHub Commands and Practice

# What is Git?

Git is an open-source distributed version control system designed for tracking changes in source code during software development. It enables multiple developers to work on projects simultaneously, managing revisions, merging code changes, and maintaining a complete history of modifications.

# What is GitHub?

GitHub is a web-based platform used for version control and collaboration on software development projects. It allows users to host and manage code repositories, track changes, coordinate work among teams, and facilitate seamless collaboration through features like pull requests and issue tracking.

# Some Basic Git Command

```jsx
git init
```

This command is used to initialise a git repository in the current local directory.

```jsx
git add <file-name>
```

Add a file to the staging area. (Replace <file-name with the actual file name)

```jsx
git add <file-name-1> <file-name-2> <file-name-3>
```

Add multiple files to the staging area

```jsx
git add .
```

Add all files in the directory to the staging area

```jsx
git status
```

Track the changes in files (Not the code inside the files, but if the files if created / deleted / modified)

```jsx
git commit -m "message here"
```

This is used to change the current status of files as a checkpoint or a version, so that we can have a history of versions of our application.

```jsx

git log
```

Check detailed history of all commits.
