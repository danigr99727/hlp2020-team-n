# hlp2020-team-n

Sample repo for HLP2020.

FOLLOW THESE INSTRUCTIONS

They let you use gitub with a private repo and more than 3 contributors

(1) Create a github id from github.com using your **imperial.ac.uk** e-mail address

(2) Join ImperialCollegeLondon organisation as detailed [here](https://www.imperial.ac.uk/admin-services/ict/self-service/research-support/research-support-systems/github/working-with-githubcom/).

(3) Fork this repo once only (one student) to imperialcollegelondon github. 

(4) Rename the forked repo (settings)replacing `team-n` by your piazza team name.

(5) Set is as **private** (settings).

(6) Add all team members as contributors with write permission.

(7) Each team member clone the repo to their own computers.

## Working with the team repo

The directory `tomcl` shows sample individual code submission files and project.

* Add one directory for each team member named by his/her IC login
* Create branches for each team member (see below). After initial setup no-one should directly commit to master except for repo maintenance purposes.
* Make sure the project and file structure for each individual submission follows that in `tomcl` directory (module files can have different names, there can be more than one module)
* Each team member must KEEP ALL THEIR INDIVIDUAL CODE UNDER THEIR DIRECTORY EXCEPT FOR FUNCTIONS WRITTEN FOR OTHER PEOPLE
* Each team member should do work under OWN BRANCH(s). OWN branches named `login-XXX` where `login` is team member login and `XXX` is name of branch. (Could be just one branch named `login-dev`).
* Each team member should merge their work to master/ update from master from time to time. Needed before end (for assessment) and if their work has functions contributed from/to others.
* Directory `team` will be used for final team deliverable. In that case merging individual branch work is not trivial since all code will run under the same directory.

## Guidelines

* Always do development on own branch, never directly on master
* Commit to own branch regularly - at least once per hour of work
* Fetch/Push local clone to github cloud regularly (gives you backup in case of computer breakdown/loss/left it in wrong place)
* **Create pull request to master** and then **Merge pull request** when own branch code reaches consistent state of when needed to share code with other team members (e.g. if they are writing functions in your module)
* **Update own branch from master** regularly. Normally in individual phase this will have no great effect (because it will only change code in other team member's directories).
* NEVER COMMIT CODE EXCEPT TO OWN BRANCH (even when writing functions from someone else, good practice is go through merge onto master, then they update from master)
