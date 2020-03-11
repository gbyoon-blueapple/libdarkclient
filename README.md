# libdarkclient

1. First of all, You can run the following command to install 3rd party packages for libdarkclient.

1)	swig package

    $>sudo rpm -ihv swig-4.0.1-mr13.d14.el7.x86_64.rpm

2)	mimetic package

    $>sudo rpm -ihv mimetic-0.9.8-mr13.d14.el7.x86_64.rpm

3)	libevent package

    $>sudo rpm -ihv libevent-2.1.8-mr13.d14.el7.x86_64.rpm

4)	protobuf package

    $>sudo rpm -ihv protobuf-3.7.0-mr13.d14.el7.x86_64.rpm

5)	openssl package

    $>sudo rpm -ihv openssl-1.1.1c-mr13.d14.el7.x86_64.rpm
    $>sudo rpm -ihv openssl-devel-1.1.1c-mr13.d14.el7.x86_64.rpm

6)	curl package

    $>sudo rpm -ihv curl-7.64.1-mr13.d14.el7.x86_64.rpm
    $>sudo rpm -ihv curl-devel-7.64.1-mr13.d14.el7.x86_64.rpm

7)	libwebsockets package

    $>sudo rpm -ihv libwebsockets-3.1.99-mr13.d14.el7.x86_64.rpm

2. In order to test tools of libdarkclient, the configure path is needed.
   this path is set by dc-env tools. 
   
   (ex) ./dc-env mr13
