# Issue2PR

## Welcome to Issue2PR, a powerful tool that allows you to automate the process of creating branches and pull requests based on issues in your GitHub repository.

Inspired by LangChain, Issue2PR uses large language models to understand the structure and content of your issues, and generates modified files based on the current state of your repository. With Issue2PR, you can easily create a new branch on GitHub with the changes suggested in your issue, and run GitHub actions to automatically submit a pull request if the tests pass.

To get started, simply create an issue on your repository and pre-prompt Issue2PR with the following information:

```
The following is the issue I created on my repository. I want you to create a new branch based on the current state of my repository and the changes suggested in this issue.
Please run all the tests and if they pass, submit a pull request.
```
### Issue2PR will then analyze your issue, create a new branch with the suggested changes and run GitHub actions to test the branch and if tests pass submit a pull request.


For more advanced features, checkout [GithubGPT](https://github.com/fire17/GithubGPT) which integrates everything with GitHub, making it seamless for developers to use. Other projects include [Repo2Repo](https://github.com/fire17/Repo2Repo) and [Readme2Repo](https://github.com/fire17/Readme2Repo) which are also integrated
