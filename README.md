# IP-Address-Viewer
find our IP address by CMD command in other words ipconfig.

So, to handle this thing we have a few classes in the System.Net namespace. In this article, we deal with a few.

Start a new Console project in your Visual Studio. and Add a namespace in your project as in the following: - Using System.Net;

Before fetching the IP Address we need to know whose IP Address we really want. It's quite understood that we want our own PC. But, that must be specified in my code because computers are dumb. So, we can fetch the machine Name (or Host Name) by the GetHostName() Method. And this is inside the Dns class.

We are now ready to get the IP address of the Host.

For this we need to use the GetHostByName() method followed by AddressList array (first Index).

And, in GetHostByName's argument we "host name".
