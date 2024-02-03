git token : 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
gh auth login --with-token <<< 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
gh auth status
create new repo in gui
git init
git remote add origin git@github.com:GritworkTMH/git-tfc-hcp-vault-cluster.git
git remote rm -rf .git (previous git file will not know now )
git remote -rm git-tfc-hcp (want to change from ssh to http)
git remote set-url --add origin https://github.com/GritworkTMH/git-tfc-hcp-vault-cluster.git

git config user.name "GritworkTMH"
git config user.email "gritworktmh@gmail.com"
git remote -v
git config --list
git remote add origin git@github.com:GritworkTMH/git-aws-tf-ws.git
git add .
git commit -m "xxxx"
git log 
git push
git push --set-upstream upstream develop (copy for above command noti)
