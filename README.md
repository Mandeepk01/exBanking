# exBanking

### Test Files ### 

1. Test Cases for ExBanking.xlsx For Functional and Non Functional test Cases.
 • Added Test Cases for All APIs > Create User, Deposit, Withdrawal and Get Balance APIs
 • Added Test Scenarios for Non Functional for Performance and Security Testing.
 
2. ExBankingDemo.jmx 

  • Jmeter Script for APIs  > Create User, Deposit, Withdrawal and Get Balance APIs
    Added Sample load testing script where I tested 20 virtual users and mentioned the same in Thread Group, attaching Summary report and Listener > View       Results Tree
  <img width="1508" alt="Screenshot 2022-10-04 at 6 09 47 PM" src="https://user-images.githubusercontent.com/54873896/193821581-1c14f1d2-d3bb-4637-bc48-   8572b05d8218.png">
<img width="1472" alt="Screenshot 2022-10-04 at 6 09 33 PM" src="https://user-images.githubusercontent.com/54873896/193821652-a106efb7-2127-4618-83a0-e7392f9ea6ff.png">

3. TestData.csv 

   • To handle parameterization : Csv file is used to parameterize the firstName, lastName, currency and Mobile number (user id as should be unique             everytime is handled with user parameters in the script).
 
   
  ### How to Run the script ### 
 
 1. Import the  .jmx file in Jmter and changed the path for CSV Data Set Config path needs to be changed as TestData.csv file should be present in bin         directory of Jmeter package.
 2. Check the results in Summary report. 
 
   

