# Terminal-T2
Each developer should [fork](https://help.github.com/articles/fork-a-repo) the primary Git repository for their work. All developers should then checkout a local copy of the master branch to begin work -
	
	git clone git@github.com:username/Terminal-T2.git
	git remote add upstream git@github.com:RTRShaders/Terminal-T2.git

For any work [pull requests](https://help.github.com/articles/about-pull-requests/) must be created for individual tasks and submitted for review -
	
	git checkout master
	git pull upstream master
	git checkout -b <new-issue-branch> master
	git push origin <new-issue-branch>
