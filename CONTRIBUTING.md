## Contributing

Thank your for contributing to this project! We welcome collaborators and expect users to follow our [code of conduct](CODE_OF_CONDUCT.md) when submitting code or comments.

Note: The base branch requires [all commits to be signed](https://help.github.com/articles/about-commit-signature-verification). 

1. Fork the repo (https://github.com/mana-ethereum/mana/fork).
2. Create your feature branch (`git checkout -b my-new-feature`).
3. Write tests that cover your work.
4. Ensure CI rules are satisfied. 
5. Commit your changes (`git commit -S -a -m 'Add some feature'`).
6. Push to your branch (`git push origin my-new-feature`).
7. Create a new PR (Pull Request).

### General
  
* Commits should be one logical change that still allows all tests to pass.  We prefer smaller commits if there could be two levels of logic grouping.  The goal is to provide future contributors (including your future self) the reasoning behind your changes and allow them to cherry-pick, patch or port those changes in isolation to other branches or forks.
* If during your PR you reveal a pre-existing bug and know how to fix it:
  1. If you can isolate the bug, fix it in a separate PR.
  2. If the fix depends on your other commits, add it in a separate commit to the same PR.  

    In either case, try to write a regression test that fails because of the bug but passes with your fix.


### Issues
Creating and discussing [Issues](https://github.com/mana-ethereum/mana/issues) provides significant value to the project. If you find a bug you can report it in an Issue.     

### Pull Requests (PR)

Before submitting a PR:
1. Add a test for the new or updated functionality. For tests that are simple and would make sense in documentation add a doctest. For more complicated tests add a regular test. If you're not sure which type to add ask in [Gitter](https://gitter.im/mana-ethereum/mana).
2. Run `mix format` to format your code.
3. Run `mix credo` and fix any errors and warnings.

**All pull requests should include:** 
* A clear, readable description of the purpose of the PR
* A clear, readable description of changes
* Any additional concerns or comments (optional)