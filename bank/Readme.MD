<h1>Banking App</h1>
Here is the implementation Approach of Banking Application

step first taking input from cli and according to input do some operation 
Step no/Command :CREATE 
<h4>The Command Line for the Account Create is like that</h4>
<h1> node index.js CREATE ACC01 KPEL</h1>
First input is create the first check the name and account that enter by user already present in database if yes the show msg account no already exist enter different account no if account no is not present then open account and save in it database


Second type is :Deposit


<h4>The Command Line for the Account Deposit is like that</h4>
<h1> node index.js DEPOSIT ACC01 10000</h1>
First the account that is enter is present in database or not if yes then destrucuture  and update balance also take care of input that user should not enter the negative no


Third type is :Withdrawl 
<h4>The Command Line for the Withdraw  is like that</h4>
<h1> node index.js WITHDRAW ACC01 10000</h1>

First the account that is enter is present in database or not if yes then check the input is not string and check also the amount present in account is greater than the amount the user want to withdrawl 


Fourth type is :BALANCE
<h4>The Command Line for the Show  is like that</h4>
<h1> node index.js SHOW Acc01</h1>

So first check the account no is present in databased is exist or not if yes then show the respective balances 

