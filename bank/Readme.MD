<h1>Banking App</h1>
Here is the implementation Approach of Banking Application

step first taking input from cli and according to input do some operation 
Step no/Command :CREATE 
<h1>The Command Line for the Account Create is like that   node index.js CREATE ACC01 KPEL</h1>
First input is create the first check the name and account that enter by user already present in database if yes the show msg account no already exist enter different account no if account no is not present then open account and save in it database


Second type is :Deposit
<h1>The Command Line for the Account Create is like that   node index.js DEPOSIT ACC01 10000</h1>
First the account that is enter is present in database or not if yes then destrucuture  and update balance also take care of input that user should not enter the negative no


Third type is :Withdrawl 
<h1>The Command Line for the Account Create is like that   node index.js WITHDRAWL ACC01 10000</h1>
First the account that is enter is present in database or not if yes then check the input is not string and check also the amount present in account is greater than the amount the user want to withdrawl 


Fourth type is :BALANCE
<h1>The Command Line for the Account Create is like that   node index.js SHOW ACC01</h1>
So first check the account no is present in databased is exist or not if yes then show the respective balances 

