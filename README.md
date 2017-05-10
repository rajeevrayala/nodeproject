
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Welcome to your Node.js project on Cloud9 IDE!

This chat example showcases how to use `socket.io` with a static `express` server.

## Running the server

1) Open `server.js` and start the app by clicking on the "Run" button in the top menu.

2) Alternatively you can launch the app from the Terminal:

    $ node server.js

Once the server is running, open the project in the shape of 'https://projectname-username.c9users.io/'. As you enter your name, watch the Users list (on the left) update. Once you press Enter or Send, the message is shared with all connected clients.


rajeevrayala:~/workspace (master) $ git init
Reinitialized existing Git repository in /home/ubuntu/workspace/.git/
rajeevrayala:~/workspace (master) $ git add .
rajeevrayala:~/workspace (master) $ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md
        new file:   client/css/bootstrap-responsive.min.css
        new file:   client/css/bootstrap.min.css
        new file:   client/img/glyphicons-halflings-white.png
        new file:   client/img/glyphicons-halflings.png
        new file:   client/index.html
        new file:   client/js/angular.min.js
        new file:   client/js/bootstrap.min.js
        new file:   client/js/jquery.min.js
        new file:   nodeproject/app.js
        new file:   package.json
        new file:   server.js

rajeevrayala:~/workspace (master) $ git commit
[master (root-commit) 0285097] initial commit
 12 files changed, 413 insertions(+)
 create mode 100644 README.md
 create mode 100644 client/css/bootstrap-responsive.min.css
 create mode 100644 client/css/bootstrap.min.css
 create mode 100644 client/img/glyphicons-halflings-white.png
 create mode 100644 client/img/glyphicons-halflings.png
 create mode 100644 client/index.html
 create mode 100644 client/js/angular.min.js
 create mode 100644 client/js/bootstrap.min.js
 create mode 100644 client/js/jquery.min.js
 create mode 100644 nodeproject/app.js
 create mode 100644 package.json
 create mode 100644 server.js
rajeevrayala:~/workspace (master) $ git push https://github.com/rajeevrayala/nodeproject
Username for 'https://github.com': rajeevrayala
Password for 'https://rajeevrayala@github.com': 
Counting objects: 19, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (18/18), done.
Writing objects: 100% (19/19), 109.66 KiB | 0 bytes/s, done.
Total 19 (delta 0), reused 0 (delta 0)
To https://github.com/rajeevrayala/nodeproject
 * [new branch]      master -> master
