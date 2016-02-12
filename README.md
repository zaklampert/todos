[![Circle CI](https://circleci.com/gh/meteor/todos.svg?style=svg)](https://circleci.com/gh/meteor/todos)

This is a Todos example app built on the principles described in the Meteor Guide. This app uses the module functionality from the upcoming Meteor 1.3, but everything else should be applicable to Meteor 1.2 as well.

### Installing the beta

In order to run properly, please make sure you've installed the 1.3 beta.

```bash
meteor update --release 1.3-modules-beta.8
```

### Running the app

```bash
npm install
meteor
```

### Scripts

To lint:

```bash
npm install -g eslint babel-eslint
eslint .
```

Pass the `--quiet` flag to ignore warnings.
