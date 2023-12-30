# Learning Git Branches and GitHub

## Git Branches:

### 1. Install Git:

If you haven't installed Git on your machine, you can download and install it from [git-scm.com](https://git-scm.com/).

### 2. Initialize a Git Repository:

Open a terminal and navigate to the directory where you want to create your project. Run the following commands:

```bash
git init
```

### 3. Create a Branch:

To create a new branch, use the following command:

```bash
git branch branch_name
```

### 4. Switch to a Branch:

To switch to the newly created branch, use:

```bash
git checkout branch_name
```

Alternatively, you can use a single command to create and switch to a new branch:

```bash
git checkout -b branch_name
```

### 5. Make Changes:

Make changes to your project files while on the branch.

### 6. Commit Changes:

After making changes, commit them to the branch:

```bash
git add .
```

```bash
git commit -m "Your commit message here"
```

### 7. Merge Branches:

Once you're done with changes on a branch, you can merge it back into the main branch (usually `main` or `master`):

```bash
git checkout main git merge branch_name
```

### 8. View Branches:

To see all branches and the current branch, use:

```bash
git branch
```

GitHub:
-----------------------------

### 1. Create a GitHub Account:

If you don't have one, create a GitHub account at [GitHub](https://github.com/).

### 2. Create a New Repository:

On GitHub, click the "+" in the top right corner and select "New Repository." Follow the instructions to create a new repository.

### 3. Push Code to GitHub:

After creating a repository, connect your local repository to the GitHub repository:

```bash
git remote add origin https://github.com/your-username/your-repository.
```

```bash
git git branch -M main git push -u origin main
```

Make sure to add your username and your repository name.

### 4. Push Branches:

If you want to push branches other than `main`, use:

```bash
git push origin branch_name
```

## Additional Commands

1. To view all Git branches:

    ```bash
    git branch
    ```

2. To delete a Git branch:

    ```bash
    git branch --delete 'branch_name'
    ```

## Contributing

Welcome to contribute to Branch Test! Feel free to fork the repository and suggest any improvements. To contribute, follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them.
4.  Push the changes to your fork.
5.  Submit a pull request.

Thank you for your contributions!

## License

This project is licensed under the [MIT License](LICENSE).

## Author

[Vikranth Udandarao](https://github.com/Vikranth3140)