CalculateTradingCommissions application

Brief
===============================================================================
This sample shows how to calculate the estimated commission for trading operations.
The sample performs the following actions:
1. Login. 
2. Print calculated estimated commissions.
3. Logout.

Building the application
===============================================================================
Windows:
    To build this application, you will need MS Visual Studio 2005 or later.

    You can run fxbuild.bat (fxbuild64.bat for 64-bit version) or select
    "build" in MS Visual Studio.

Linux/MacOS:
    To build this application, you will need:
        gcc-4.1 or later
        g++-4.1 or later
        CMake 2.6 or later (use 2.6 for MacOS)
        
Run fxbuild.sh to build application.

Running the application
===============================================================================
You can run this application from the bin directory.
In Windows you can run this application executing fxrun.bat
All arguments must be passed from the command line.
This will run the application and display the output in your console.

You can run the application with no arguments, this will show the
application Help.

Arguments
===============================================================================
/login | --login | /l | -l
Your user name.

/password | --password | /p | -p
Your password.

/url | --url | /u | -u
The server URL. For example, http://www.fxcorporate.com/Hosts.jsp.

/connection | --connection | /c | -c
The connection name. For example, "Demo" or "Real".

/sessionid | --sessionid 
The database name. Required only for users who have accounts in more than one database. Optional parameter.

/pin | --pin 
Your pin code. Required only for users who have a pin. Optional parameter.

/instrument | --instrument | /i | -i
An instrument which you want to use in sample. For example, "EUR/USD".

/account | --account 
An account which you want to use in sample. Optional parameter.

/buysell | --buysell | /d | -d
The order direction. Possible values are: B - buy, S - sell.

/lots | --lots 
Trade amount in lots. Optional parameter.
