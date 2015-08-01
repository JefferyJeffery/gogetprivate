gogetprivate
============
go get like command that works with some private repositories

To use, setup your $GOPATH and then checkout go project like so:

    gogetprivate bitbucket.org/my_org/my_project

If your project contains any private bitbucket repositories, they will be checked out over SSH instead
of HTTPS.
