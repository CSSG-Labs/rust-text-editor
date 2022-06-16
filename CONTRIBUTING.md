# Contributing

## How to participate

1. Assign yourself to an open git issue
    - To suggest a new feature or bugfix:
      - Check it does not already exist first! If it doesn't then:
      - Open github issue
      - Label it accordingly
      - Discuss with project members on discord or through github
2. Create a branch with `<issue-number>-<branch-descriptor>` naming scheme [*(see article)*](https://deepsource.io/blog/git-branch-naming-conventions/)
3. Work on assigned issue
    - Try not to go outside the scope of the git issue
      - discuss with project members if you end up having to implement new features outside of the original scope
4. Sync branch with dev
5. Create remote branch and push to that branch
6. Start the [pull request process](#pull-request=process)

## Git workflow: Issue branch workflow

- Branches are created from issues/ tasks
- Branches have the same name of its issue id#
- One Branch per issue and one issue per branch
- see [article](https://medium.com/flexisaf/git-workflow-for-your-project-3d9dbdc5f8e2)

## Coding Style

- See the official Rust [Style Guidelines](https://doc.rust-lang.org/1.0.0/style/README.html)

## Development Environment Setup

- Install Rust using the [Rust Language Installation Guide](https://www.rust-lang.org/tools/install) or via [Chapter 1.1](https://doc.rust-lang.org/book/ch01-01-installation.html) of *The Rust Programming Language*.
- Learn more from the Rust team's official [Getting Started Guide](https://www.rust-lang.org/learn/get-started)

### Using Git to make a pull request

- Instructions on [Sachinsf.com](https://www.sachinsf.com/how-to-push-the-code-from-vs-code-to-github/)
  - Make sure you have git installed on your PC, and that all the files you are pushing are in one folder before you push any changes

### Running app

This app can be run by typing `cargo run` in your project directory terminal.  See [Chapter 1.3](https://doc.rust-lang.org/book/ch01-03-hello-cargo.html) of *The Rust Programming Language* for more information on building and running a Rust project.
  
### Resources

- There are a number of resources available online for Rust.  Our recommended choice is [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html) which is the official Rust book released by the Rust Foundation.

## Testing

*todo...*

## Pull Request Process

1. Create branch with correct naming scheme (see [section](#how-to-participate))
2. Ensure code is working properly and passed all tests (see [section](#testing))
3. Open PR (against dev branch)
4. Code review must be completed by running the code and tests, and ensuring code meets our coding standards (see [section](#coding-style))
    - *review is not necessary if PR is related to documentation or project maintenance*
5. Upon approving PR:
    - Close the github issue that the PR for
    - Delete PR branch
    - Merge PR into `dev` branch (*just merge PR to main if its related to documenation or project maintenance*)

## Deployment

*todo...*

## Code of Conduct

*See [Contributors Covenant](https://www.contributor-covenant.org/version/2/0/code_of_conduct/code_of_conduct.txt)*

## Join us

We are discussing this project on [discord](https://discord.com/). Please contact andromedamoon-stack or PatrickBruso by DM on Github or riboney @ ironbe#4809 for details on our server.
