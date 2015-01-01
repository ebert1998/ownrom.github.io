# OwnROM-Website

A website for OwnDroid and our ROM, OwnROM.



## Tech

Our website uses a number of projects/software to work:

* [Materializecss] - A modern responsive front-end framework based on Material Design
* [jQuery] - Write less, do more
* HTML, CSS and Javascript

Also to make this website we used many great programs/software:

* [Brackets] - A modern, open source text editor that understands web design.
* [Github] - Build better software, together
* [Git] - Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency
* [FileZilla] - The free FTP solution
* [Geany] - Geany is a text editor using the GTK2 toolkit with basic features of an integrated development environment
* And more...

## Downloading

```sh
$ mkdir ownrom-website
$ cd ownrom-website
$ git clone https://github.com/OwnROM/OwnROM-Website
```

Or download the repo as a zip file to the right --> 

Then extracting it to a new directory called ownrom-website

## Development

Want to contribute? Great!

You may edit any file in this respitory including the readme or add files if needed if you think this will improve the site or projet


##### Editing multiple files:

First download the source code as explained above in the downloading section

Then initialize the local directory as a Git repository
```sh
$ cd ownrom-website
$ git init
```

Add the URL for the remote repository where your local repostory will be pushed.
```sh
$ git remote add origin https://github.com/OwnROM/OwnROM-Website.git
```

Then pull in any new changes
```sh
$ git pull origin master
```

You may now add/edit any files in your local respitory

After editing or adding files add the files to your local repository
```sh
$ git add .
```

Then commit the files that you've staged in your local repository (Where commit text could be anything you want)
```sh
$ git commit -m 'commit text'
```

Finally push the changes in your local repository to GitHub
```sh
$ git push origin master
```

(If you get a error this usally means there has been changes in the respitory. Just use the pull command as shown above then push your changes)

##### Editing single files

There is no need to do the steps as explained above but that would work aswell.

To edit just one file click on the file in the respitory that you want to edit, hit the edit button (the pencil), edit the file as you like and subbmit it via a commit.

##### Resources

Our website uses the materializecss framework. To see what you can add/edit using this see the following link

http://materializecss.com/

If you need a text editor we would recommend ethier Brackets or Geany.

If you need a more heavyweight text editor with many features, extensions or themes use Brackets.

http://brackets.io/

If you however want a more lightweight text editor that still has a good amount of feautres try Geany

http://www.geany.org/

Some extensions that you may want to look at if chossing Brackets would be:

* Brackets git - Github/Git commands in the text editor
* eqFTP - For uploading your files to a FTP server directly from the editor
* Markdown preview - For previewing markdown documents that your working on in the editor
* Beautify - Makes html, javascript or css code more readable
* Brackets icons - Add icons of diffrent file formats to the sidebar
* Code overviwer - adds your code in a overview to quickly switch between diffrent parts of your code
* Documents toolbar - Adds a toolbar to quickly switch between files
* Simple To-Do - Adds a todo list to the editor to make quick notes or to-dos for your project
* Monokai - A nice looking theme if your used to sublime text or want something that looks like it

#####What gets added?

If we think your additions or changes will improve this webiste we will add them right away. If for some reason that we think they dont we will not add them to this project.

##Translating

If you would like to see this website in your language you can help translate it at this site:

https://osyihyj.oneskyapp.com/admin/project/dashboard/project/15672

##Questions or need help?

Chat with The OwnROM team and other users of this project here

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/OwnROM/android?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)







[jQuery]:http://jquery.com
[Materializecss]:http://materializecss.com/
[Geany]:http://www.geany.org/
[FileZilla]:https://filezilla-project.org/
[Github]:https://github.com/
[Git]:http://git-scm.com/
[Brackets]:http://brackets.io/