# reference

# split all strings with original char.
:%s/./\0,/g

# git creation option Initialized empty shared Git repository 
git init --bare --shared PROJECT.git

git remote add origin account@192.168.0.1:git/PROJECT.git

git push origin master

git clone account@192.168.0.1:git/PROJECT.git
