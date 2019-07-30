# Exam CKAD: Kubernetes Certified Application Developer

## Tooling Know-how
You won't be able to take the test and pass if you don't know how to use a *nix terminal and Vim. Learn to use them if you don't know already. If you think you're solid in this area, at least skim and "check off" what I suggest you know and are able to execute.

* bash
* vim

## 1. Bash terminal
You should be proficient enough to know these basic commands cold.

* quickly navigate file system
* copy and paste
* ability to pipe
* able to direct input / output 
* launch vim to edit a file

## 2. Vim - know your editor
I picked and stuck with vim. You can choose nano if you want. The same guidance applies.

### Tabs and spaces
YAML is important for editing and quickly creating "template" pod or deployment manifests.

* memorize how to set the number of spaces that a tab is set to for vim. 

* set tab with and stop for vim

    > WARNING: You __do not__ want to be stuck pressing the tab key and getting an actual tab or having to hit the space bar and hope to god that pressed it the right number of times to get the right YAML formatting. Speaking during the exam is not allowed, so muttering shit under your breath isn't recommended :)

```bash
:set tabstop=2
:set shiftwidth=2
:set expandtab
```

### Essential commands
Use the [vim cheatsheet](https://gist.github.com/awidegreen/3854277) to learn all the commands you should be proficient in.

Memorize how to do the follow:

* edit (obviously)
* move to start and end of line
* insert a new line below or above
* select whole lines or words
* copy (lines and words)
* paste (*tip: use this in combination with insert new line*)
* quickly exit and save changes, e.g. `ZZ`



