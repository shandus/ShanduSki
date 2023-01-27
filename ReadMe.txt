
//Application Details
*Database: SQLite and Redis
*Database: Identitydb (stores users) and Skinet.db (stores products and orders)
*Design Pattern: Repository N-tier architecture
*Language: C#
*Framework: .NET CORE 
*Backend: .NET CORE Web API
*Frontend: Angular
*Visual Studio Code
*Payment: Stripe


//Instructions
*Please download the files to the following link i.e. link https://github.com/shandus/ShanduSki.git
*Extract Redis Installation folder
	-click Redis-x64-3.0.504.msi installation file
	-click "next"
	-check "accept terms and conditions in the license agreement"
	-check "add the redis installation folder to the Path environment variable
	-click "next"
	-click "next"
	-click "next"
	-click "install"
	-click "finish"
	*Redis is installed succesfuly*
	-open command line (cmd) 
	-type the following i.e. redis-cli
	-at 127.0.0.1:6379> type ping
	-you should get a response of pong
	-redis server has been started locally 
*go to visual studio code under file click open folder select ShanduSki folder
*project should then load.
*open terminal under ShanduSki type dotnet restore
*after that type dotnet build to build all the dotnet project, there should be no errors!!!!
*click F5 or start debugging the api
*project should open at http://localhost:5001
*open terminal and type cd client
*type ng build, you might be promted to type npm install, if this comes up please type the command
*if your project builds type ng serve 
*open http://localhost:4200/

*sign up as new user or login as the below test user
Username:bob@test.com
Password:Pa$$w0rd

*Home menu takes you to the dashboard and Shop menu takes you to the products page.
*You can filter by brands and types of products by clicking on each brand/type or combination of both, also use search bar
*Hover on each product to view or add to basket.

*Test Card Details
	-Card Number: 4242 4242 4242 4242
	-Date: 12/34
	-CVV: any 3 digit number e.g. 123 etc
 
