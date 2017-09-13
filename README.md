# README
Hello it's Lynn. Thanks for Lucas, I've been practicing how to start a rails app and update this to git.

Here's what I did today in detail. To start up a rails app named me_hero913:

1.Make a directory, enter it.
> $ mdkir diary913
> $ cd diary913

2.Use `rails new` to open a new repository.
> $ rails new me_hero913 -d postgresql

3.Srart rails server in the new repo
> $ cd me_hero913
> $ bin/rails server

Go to 0.0.0.3000 to see if the rails server is setup. For me, I see:
Yay! You are on Rails

Rails version: 5.1.4
Ruby version: 2.4.1 (x86_64-darwin15)

It means the rail server is started. So finally, can start to update this to git.

> $ git init
> $ git add.

By doing `git add .` This should add everything in the directory to the repository

> $ git status

Lucas told me to check git status often lol. This should shows files that were added to git or not.

> $ git commit -m"Initial commit"

By adding `-m"Initial commit"` after commit command, you can look back this note knowing what this commit means.

Here, I went to github and add a new repository named: me_hero913. After creating this repository, I came back to:

> $ git remote add origin git@github.com:lynn022307/me_hero913.git
> $ git push -u origin master

Voila! Here we are.
