Take the below course and grasp the following points
https://www.linkedin.com/learning/paths/develop-critical-thinking-decision-making-and-problem-solving-skills
–What are the technic to clearly define a problem? How to use them?
–What is the root cause and how to find the root cause?
–What are the critical thinking tools mentioned in the course?
–Common pitfalls when solving problem?
–Extra (not in the course): mind-map, 6 thinking hats, 5W1H
–Additional source of learning: 
Mindware: Critical Thinking for the Information Age | Coursera
Problem Solving Using Computational Thinking | Coursera
Using Critical Observation on the Job | Pluralsight
https://www.nguyenphivan.com/lnd-center
•1 week to apply what you have learned into your project or life:
–What are the problems you solved during the week?
–How did you use the tools learned to define and solve your problem?
•Presentation, Reflection and discussion

[![progress-banner](https://backend.codecrafters.io/progress/git/4b1f9bbf-7e78-471a-a7c2-b418e651b284)](https://app.codecrafters.io/users/codecrafters-bot?r=2qF)

This is a starting point for Go solutions to the
["Build Your Own Git" Challenge](https://codecrafters.io/challenges/git).

In this challenge, you'll build a small Git implementation that's capable of
initializing a repository, creating commits and cloning a public repository.
Along the way we'll learn about the `.git` directory, Git objects (blobs,
commits, trees etc.), Git's transfer protocols and more.

**Note**: If you're viewing this repo on GitHub, head over to
[codecrafters.io](https://codecrafters.io) to try the challenge.

# Passing the first stage

The entry point for your Git implementation is in `cmd/mygit/main.go`. Study and
uncomment the relevant code, and push your changes to pass the first stage:

```sh
git add .
git commit -m "pass 1st stage" # any msg
git push origin master
```

That's all!

# Stage 2 & beyond

Note: This section is for stages 2 and beyond.

1. Ensure you have `go` installed locally
1. Run `./your_git.sh` to run your Git implementation, which is implemented in
   `cmd/mygit/main.go`.
1. Commit your changes and run `git push origin master` to submit your solution
   to CodeCrafters. Test output will be streamed to your terminal.

# Testing locally

The `your_git.sh` script is expected to operate on the `.git` folder inside the
current working directory. If you're running this inside the root of this
repository, you might end up accidentally damaging your repository's `.git`
folder.

We suggest executing `your_git.sh` in a different folder when testing locally.
For example:

```sh
mkdir -p /tmp/testing && cd /tmp/testing
/path/to/your/repo/your_git.sh init
```

To make this easier to type out, you could add a
[shell alias](https://shapeshed.com/unix-alias/):

```sh
alias mygit=/path/to/your/repo/your_git.sh

mkdir -p /tmp/testing && cd /tmp/testing
mygit init
```
