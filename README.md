
# 📌 Quick Start

clone the repo
```bash
git clone https://github.com/amitanshusahu/ghb && cd ghb
```
give execute permission
```bash
chmod 700 ghb
```
make the script available locally 
```bash
sudo mv ghb /usr/local/bin/
```


# 📌 What does the Script do?

<div align="center">  
  <h3> A Quick Video (sounds on 🔊) </h3>
  
  https://user-images.githubusercontent.com/83657737/237024144-3183befa-cba8-40eb-81d8-1c607e07ce6c.mp4
  
</div>

- __Saves Password (token)__ : you just need to provide it with your username and password once, it will save it and every time you will write `ghb` it will automatically push without asking for credentials
- __Checks For All The Common Pitfalls__ : 
  - checks if the repo is not initilized, it does it
  - if the remote is not added, asks for it
  - if not staged, it does it
  - if not commited, commits 
  - sometimes in a hurry you push your master branch being in a different branch where you have made the changes, it also checks for this and it will push the current branch you are in to the remote, but there are sometimes you want to push a differnt branch from your master (or any other) whithout doing a `checkout branch`, you can do that too by explicitly typeing the branch name `ghb branch-name`
- __Save Time__ : so you just need to type `ghb` that's it, even if the repo is not initialized. in that way it saves your time by doing the repetative tasks 😅

> ghb ( gitgub ) is your friendly neighbour to push local repo to github. Automating the repetitive tasks " add, commit, push, username, token...". it's simple but useful 👼


<h3 align=center> show some love ⭐ the repo </h2>
