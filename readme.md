# Hack the Trico 2019: git/GitHub Workshop

:squirrel: September 27-28, Haverford College :squirrel:

Nabil Kashyap (@bulbil)

### Goals

1. What is git and GitHub 
2. Familiarity with basic concepts
3. Familiarity with basic commands
4. Familiarity with workflows
5. Resources

### 1. What is git and GitHub

- git as software, GitHub as a service
- anatomy of git
	- repository
	- commit
	- branch
	- remote
	- `.gitignore`
- `.git` folder
- how to install
- how to authenticate
- setup a github account

### 2. Familiarity with basic concepts

http://git-school.github.io/visualizing-git/#free-remote

- concept of "bundling" changes vs saving a file
- branching
	- local/master
	- local/feat/add-menu
	- origin/master
	- origin/feat/add-menu (optional)
- merging
- reseting

### 3. Familiarity with basic commands

- `init`
- `checkout -b`
- `add`
- `commit`
- `remote`
	- setting up a new repo on git
	- adding a license
- `push`
- `pull`
- `reset`

### 4. Familiarity with workflows

1. define what you are working on at this moment
2. `pull` make sure you have the newest code
4. `checkout -b` checkout a new branch
5. code --> test --> code --> test (repeat)
6. `status`
7. `add` as needed + `commit -am`
8. `checkout master`
9. `pull`
10. `merge [branch]`
11. after things look good `push origin master`


naming branches
- `feat`: Feature I'm adding or expanding
- `bug`: Bug fix or experiment
- `junk`: Throwaway branch created to experiment
- or issue number on github

commit messages
- present tense verb
- `closes #[issue number]`

### 5. Resources

- [git project page](https://git-scm.com/)
- [Git Guides: Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [git project tutorial](https://git-scm.com/docs/gittutorial)
- [Programming Historian: An Introduction to Version Control](https://programminghistorian.org/en/lessons/getting-started-with-github-desktop)
- [GitHub Learning Labs](https://lab.github.com/)
- [Git Style Guide](https://github.com/agis/git-style-guide)