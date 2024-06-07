You have been deployed!


Build Job remotely:

http://jenkins.successtreks.com/job/git%20plugin%20-%20test%201/build?token=secret

As it requires token Authentication and Authorization:
This plugin need to be installed, 

```
Name:
Build Authorization Token Root Plugin

Description:
Lets build and related REST build triggers be accessed even when anonymous users cannot see Jenkins.

```

Now Browse to https://plugins.jenkins.io/build-token-root/ and get the remote building parms
http://jenkins.successtreks.com/buildByToken/build?job=git%20plugin%20-%20test%201&token=secret
