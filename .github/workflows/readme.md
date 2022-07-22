# Contineous Deployment with Github Actions to a Flask Application on a Droplet

Before starting this assignment I already finished the prevoious theory and exercises succesfully.
So I had my Droplet running, understood the basics of GitHub Actions and had managed to succesfully run a flask application on my Droplet. However combining all of these was quite the challenge.
First I created self-hosted runner on GitHub
https://github.com/Target52/my-project/settings/actions/runners

A self-hosted runner is a system that you deploy and manage to execute jobs from GitHub Actions on GitHub.com.

After this I only had to change the workflow so the repository was synchronised.

Problems I encountered where installing pip in root so I used virtual python environments with virtualenv, I had some problems with directory naming and the git pull request. But finally everything worked fine.