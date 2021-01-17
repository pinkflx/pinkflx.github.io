Hello Git and GitHub
Felixs-Air:~ felixpinck$ cd projects
Felixs-Air:projects felixpinck$ mkdir pinkflx.github.io
Felixs-Air:projects felixpinck$ git init
Initialized empty Git repository in /Users/felixpinck/projects/.git/
Felixs-Air:projects felixpinck$ echo "Hello Git and GitHub" >> README.txt
Felixs-Air:projects felixpinck$ git add README.txt
Felixs-Air:projects felixpinck$ git commit -m "First commit"
[master (root-commit) 4433e06] First commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt
Felixs-Air:projects felixpinck$ git remote add origin https://github.com/pinkflx/pinkflx.github.io.git
Felixs-Air:projects felixpinck$ git branch -M main
Felixs-Air:projects felixpinck$ git push -u origin main


Deploy
Felixs-Air:projects felixpinck$ git add -all
Felixs-Air:projects felixpinck$ git commit -m "YOURMESSAGE"
Felixs-Air:projects felixpinck$ git push -u origin main
