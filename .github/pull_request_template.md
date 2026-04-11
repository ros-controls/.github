Contributions via pull requests are much appreciated. Before sending us a pull request, please ensure that:

1. Limited scope. Your PR should do one thing or one set of things. Avoid adding “random fixes” to PRs. Put those on separate PRs.
2. Give your PR a descriptive title. Add a short summary, if required.
3. Make sure the pipeline is green.
4. New code = new tests. If you are adding new functionality, always make sure to add some tests exercising the code and serving as live documentation of your original intention.
5. If a PR is merged all commits will get squashed, a linear commit history is not required.
6. Once a PR got reviewed, please don't do force pushes as this will break github UI and subsequent reviews will take more time.

To send us a pull request, please:

- [ ] Fork the repository.
- [ ] Modify the source; please focus on the specific change you are contributing. If you also reformat all the code, it will be hard for us to focus on your change.
- [ ] Ensure local tests pass. (`colcon test` and `pre-commit run` (requires you to install pre-commit by `pip3 install pre-commit`)
- [ ] Commit to your fork using clear commit messages.
- [ ] Send a pull request, answering any default questions in the pull request interface.
- [ ] Pay attention to any automated CI failures reported in the pull request, and stay involved in the conversation.
