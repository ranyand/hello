echo "# hello" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:ranyand/hello.git
git push -u origin master
