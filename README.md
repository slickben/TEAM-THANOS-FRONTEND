# TEAM-THANOS-FRONTEND

This is the repo for frontend developers contributing to the Hotel Madison design

## Steps to follow

- Fork this repo.
- Clone the fucked repo
  `git clone https://github.com/{ your github username}/TEAM-THANOS-FRONTEND`
- Add this repo as an upstream
  `git remote add upstream https://github.com/slickben/TEAM-THANOS-FRONTEND.git`
- Switch to the development branch
  `git checkout development`
- Enter the hotelmadison folder
  `cd hotelmadison`
- Navigate to the designs subfolder
  `cd designs`
- Create your personal folder(eg: mkdir dyc)
  `mkdir {slack username}`
- Navigate to the above folder
  `cd {slack username}`
- Create your files (example: LandingPage.html)
  `touch {filename}.{file extension}`
- When done with your work, add all your files to the staging area
  `git add .`
- You can use git status to view files added to the staging area and unadded/untracked files
  `git status`
- Commit them (eg: git commit -m "initial commit")
  `git commit -m "{commit comment}"`
- Push to your remote repo
  `git push -u origin development`
- Head to your Repo on github and initiate a pull request.
