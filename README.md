# gulp-project-basis

Gulp-based starter kit for developing projects.

## Getting started

Download this zip archive or clone this repository (Git required) to your computer.

Then:

1. `$ cd gulp-project-basis` - go inside the project directory;
2. `$ npm install` - install dependencies;
3. `$ npm start` - run the default task (gulp task).

## Formatter

Command line:

- `$ npm run format` - format all code in files according to a pattern (`**/*.{json,yml,md}`);
- `$ npm run format:check` - check whether there is unformatted code in files (`**/*.{json,yml,md}`).

In addition, the code formatting check (`$ npm run format:check`) is performed in the pre-commit hook.

## Check commit message

Checking a commit message is done using the commitlint module. Rules for validation correspond to [conventional commit](https://www.conventionalcommits.org) specification.

[Commitlint.io](https://commitlint.io) (online generator) is used to create and pre-check the text of the commit message.

## Recommended workflow

Workflow:

1. make changes;
2. commit those changes;
3. pull all the tags _(optional)_;
4. `$ npm version [patch|minor|major]` - run the command;
5. push commits and tags to remote repository.

## Bugs

If you find a bug or something does not work, please leave your questions or comments on [issues](https://github.com/ecmatonix/gulp-project-basis/issues).

## Attributions

Initialization of this project is based on the "[initial-project-basis](https://github.com/ecmatonix/initial-project-basis)" (release: [v0.1.0](https://github.com/ecmatonix/initial-project-basis/releases/tag/v0.1.0)).

Project "[initial-project-basis](https://github.com/ecmatonix/initial-project-basis)" by [Lykov Anton](https://github.com/ecmatonix) is licensed under [MIT](https://github.com/ecmatonix/initial-project-basis/blob/master/LICENSE).

## License

This software is released under the terms of the [MIT license](https://github.com/ecmatonix/gulp-project-basis/blob/master/LICENSE).
