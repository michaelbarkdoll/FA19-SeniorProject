# How to build docker containers with GitHub and DockerHub

The following document requires an account at DockerHub and GitHub.  This document explains the following:

    1. How to fork the Apache Guacamole client and server repositories on GitHub.
    2. How to link your Github Account to your DockerHub account.
    3. How to automate the build of docker containers from your Github Apache Guacamole server and client repositories.

1. Create an account on DockerHub
http://hub.docker.com

2. Go to you Repositories
![](2019-11-04-09-09-07.png)

3. Click Account Settings

![](2019-11-04-09-37-43.png)

4. Under Account Settings, Go to Linked Accounts


Click the Connection Plug to link DockerHub to your currently logged in GitHub Account.

![](2019-11-04-09-13-26.png)


5. Click Authorize docker

![](2019-11-04-09-32-20.png)

6. On GitHub Fork the apache guacamole repositories.

https://github.com/apache/guacamole-server


![](2019-11-04-09-34-48.png)

https://github.com/apache/guacamole-client

![](2019-11-04-09-36-15.png)

7. On DockerHub, Create the repository

Click Create a Repository
![](2019-11-04-09-09-56.png)

![](2019-11-04-09-43-57.png)

Select Github under Build Settings
![](2019-11-04-09-44-41.png)

Select your organization and forked github repository
![](2019-11-04-09-45-07.png)

Select Click here to customize the build settings
![](2019-11-04-09-45-51.png)

Confirm similar settings.
![](2019-11-04-09-46-17.png)

You'll need to perform this step for both guacamole-client and guacamole-server.

8. Select Create & Build

![](2019-11-04-09-47-22.png)

Complete information of docker-hub build process:
https://docs.docker.com/docker-hub/builds/