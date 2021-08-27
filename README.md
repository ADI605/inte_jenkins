integrate jenkins with webserver and deploy applications. 

Developer--> SCM --> jenkins --> webserver
    |
html files


steps:

1. we will create one Git Repo
2. Developer will store the coded files in the Git Repo
3. creation of webserver.
        (a). we need to create a linux machine and on top of it we will install and configure webserver in it.
4. we will create one user account in webserver.
5. /var/www/html --> chown user:user
6. Establishing the connectivity between jenkins machine and webserver machine --> ssh passwordless authentication.
7. jenkins Dashboard :
        (a). install the publish over ssh plugins from manage jenkins
        (b). in the configure system f jenkins we will store the webserver details (hostname , username and password)
        (c). creating a freestyle project from new item section.
        (d). scm --> build
 
8. accessing the website from the internet.
 
~                                               
