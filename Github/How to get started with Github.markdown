#How to get started with Github

##How to clone Github Repository

1. Install Github
2. Create empty repository from Github GUI and copy it's URL / Copy the URL of the repository you want to work in 
3. Type git clone 'the URL of the repository you want to clone'

`You should see a similar output
Cloning into 'HelpNotes'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (5/5), done.`


##How to commit changes

1. Add/Update/Delete some files in the folder where repository has been cloned
2. Type "git add ." so that it tracks changes in all of the files
3. Type git commit -m "first commit" (with quotes)
4. Type git push origin master(make sure you have rights to push to master branch)
5. Enter your username and password 

You should see a similar output
`Username for 'https://github.com': harnoorsinghdev@gmail.com
Password for 'https://harnoorsinghdev@gmail.com@github.com': 
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 860 bytes | 860.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/harnoorsinghdev/HelpNotes
   8a5d269..d356b3d  master -> master`


