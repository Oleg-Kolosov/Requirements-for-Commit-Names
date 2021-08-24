<h1 align="center">This specification is based and modified on the AngularJS commit message convention.</h1>

#### Commit Message

```
 init   (hw_3):    add solutions for tasks
<type> (<scope>):  <short summary>
  │       │             │
  │       │             └─⫸ Summary in present tense. Not capitalized. No period at the end.
  │       │
  │       └─⫸ Commit Scope: hw_1|hw_2|hw_3|hw_4|hw_5
  │
  └─⫸ Commit Type: build|docs|feat|fix|perf|refactor|test|init
```

### Type

> Must be one of the following:

+ **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
+ **docs**: Documentation only changes
+ **feat**: A new feature
+ **fix**: A bug fix
+ **perf**: A code change that improves performance
+ **refactor**: A code change that neither fixes a bug nor adds a feature
+ **test**: Adding missing tests or correcting existing tests
+ **init**: start project/task

### Examples

```
  init(hw_1): add solutions for tasks

  refactor(hw_5): rename variables 

  feat(hw_7): add solution for advanced level task 1-4

  fix(hw_3): fix bug in task 3

  docs(hw_12): add technology list
```

[watch original](https://github.com/angular/angular/blob/master/CONTRIBUTING.md)
