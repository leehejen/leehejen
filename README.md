Takers-MacBook:~ taker$ cd ~/Documents/代碼
Takers-MacBook:代碼 taker$ mkdir leehejen
Takers-MacBook:代碼 taker$ cd leehejen
Takers-MacBook:代碼 taker$ echo "# leehejen" >> README.md
Takers-MacBook:代碼 taker$ git init
Initialized empty Git repository in /users/taker/Documents/代碼/leehejen/.git/
Takers-MacBook:代碼 taker$ git add README.md
Takers-MacBook:代碼 taker$ git commit -m "first commit"
[master (root-commit）3892533] first commit
	1 file changed, 1 insertion(+)
	create mode 100644 README.md
Takers-MacBook:代碼 taker$ git remote add origin https://github.com/leehejen/leehejen.git
Takers-MacBook:代碼 taker$ git push -u origin master
Counting objects: 3,done.
Writing objects:100% (3/3),223 btyes| 223.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
Tohttps://github.com/leehejen/leehejen.git
	*[new branch]	master-> master
branch 'master' set up to track remote branch 'master' from 'origin'.
Takers-MacBook:leehejen taker$ git add *
Takers-MacBook:leehejen taker$ git commit -m 'add web page'



