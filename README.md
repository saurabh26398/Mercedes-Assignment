# Mercedes-Assignment
# Mercedes
For Assignment

These are the Microservices that will get the Customer the Price of Petrol Based on the Location and the Amout of time required to refill the Tank of the Car and the Total Bill Amout if the Customer refills the Tank.
---------------------


HOW to RUN
--------------------
There are 2 MicroServices
-PetrolPriceAPIService
-SendingService
and One Eureka Server

--First Run Eureka Server
--Then Run PetrolPriceAPIService ( Using dummy Data to Get the Price of fuel corresponding to the City  )
--Then Run SendingService     ( Contains the Business Logic )


EXECUTION
--------------------

  http://localhost:8020/getPetrolDetailsForCity type This URL in Your Browser
  this Will Wait for the User Response for Fuel fill Status  in your Sending Service in console.
  Enter Desire Value True/False
  then will Automatically redirected in Browser ,the result will be shown in 3 ways
  
 3 Cases
  ---------------------
1-> Mercedes Data will be shown if the input fuel status set to be trueand then if the city was found in the dummy Data Set (City Choosen Randomly).
2-> If City not Found then result will be displayed as message  (City not found,Petrol Price Not Available) on the screen.
3-> If the Fuel lid Status was set to be false by user then result will be displayed as message (Keep Driving) on the screen.
    
