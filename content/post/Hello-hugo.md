+++
date = "2016-07-12T22:06:43+05:30"
draft = false
title = "Hello hugo!"
author = "kn330"

+++


I have been wanting to start my blog again for a long time. Github Pages sounded a reliable option and moreover it is free! The only problem being the URL which is [username.github.io](techmaniack.github.io) that looks not so good. I wanted to use [my personal domain](http://www.reversehack.in/).  
Github pages allows you to host a website directly from your github repository. This means that you do not need to get into the hassles of setting up a server or deal with cloud services like heroku. Just push your code to github and the content gets served from Githubs servers.

Although your content gets served over https, bear in mind that Github Pages is not for anything serious. (Don't plan to run a social network out of it. You will not be able to do it anyways). You do not get a database with Github Pages. For more information on the features and limitations of Github Pages head [here](https://help.github.com/articles/what-is-github-pages)

Although Github prefers Jekyll to setup your blog, I am using Hugo. Hugo is a static web site generator written in Go. It is just a matter of choice. Personally for me, Hugo feels more minimal when it comes to development. 

1. __Install Hugo on your local machine.__  
   Download and install the package for your operating system from [here](https://github.com/spf13/hugo/releases).  
   I am using Ubuntu 64 bit and if you are using the same then follow these commands  
   ```shell
   $ wget URL
   $ sudo dpkg -i PKG.deb
   ```
   That's it you are good to go. Check your hugo installation with hugo help  
   `$ hugo help`  
2. __Setting up your hugo project.__  
   Create a hugo project inside your github pages repository. If you haven't created one, go ahead and do it now.  
   `$ cd path/to/username.github.io`  
   `$ hugo new site --force .`  
3. __Writing your first post.__  
   You would now want to write a post. Go ahead and do it as folllows  
   `$ hugo new post/hello-world.md`  
   This will create the file _content/post/hello-world.md_ with the content  
   FILE_CONTENT  
4. __Test your Blog before making it live.__  
   Hugo has an in-built http server that runs on your local machine. This will help you review the content locally before making it live.



Finally getting back to my blog. Feels good.
