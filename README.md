Trying Hugo out.
Run 'hugo server -D' and local host 1313. -D gives drafts as well.

Literally zoom in if there's a size issue on localhost.

Need to sort the space between text though.


- config.toml : the configuration file, we will need to edit it later.
- content : stores all the content of the website, including all of your blog posts, resumes and so on, can include folders, but usually all .md files.
- static : Stores static files such as your background pictures, logos, css, js, etc. The files in this directory will be directly copied to it /public. This folder has higher priority than the /staticfolder under the theme.
- themes : now it’s empty, but will save the theme of your choice later.

The others, but we will not use them in this tutorial:
- archetypes : stored .mdtemplate files, it has higher priority than /archetypesfolders under the theme.
- data : stores data files for template calls
- layouts : store .htmltemplates, this folder has higher priority than /layoutsfolders under the theme

Also, there will be a “public” folder created when you want to deploy the website:
- public : After executing the hugocommand, store the generated static file