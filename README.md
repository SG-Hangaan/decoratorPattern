# Decorator Pattern

Problem
---------------------------------------------------------------------------------------------------------------------------------- 
Cimb is a digital bank that offers GSave and UpSave savings accounts. As with a typical Savings Account, it contains accountNumber, accountName, and a balance for that account.

<li> The typical savings account offers an interest rate of 1%. The benefits of the typical savings account is the same with the "Standard Savings Account" as compared to other banks.

<li> The GSave account offers an interest rate of 2.5%. Benefits include the "Standard Savings Account" plus access to "GCash transfer".

<li> The UpSave account offers the highest interest rate of 4.0%. Benefits include the "Standard Savings Account" plus "with Insurance".


The content of your Cimb.java should ONLY contain the following codes with the exception of inserting your own package name : 
----------------------------------------------------------------------------------------------------------------------------------
<br> 
<p align="center">
  <img src="https://github.com/SG-Hangaan/decoratorPattern/assets/127215110/e7d9ddb8-fd4e-42d7-8a2b-d0e38ce376ff"/>
</p>


<p align="center">
  You should display the following output: <br> <br> 
  <img src="https://github.com/SG-Hangaan/decoratorPattern/assets/127215110/3b5fb13e-6d26-4ccb-a606-631776b6a441"/>
</p>

**Description of the following methods**
---------------------------------------------------------------------------------------------------------------------------------- 
1. **showAccountType()** - Either returns "Savings Account", "GSave" or "UpSave"
2. **getInterestRate()** - Either returns 1% for Savings Account; 2.5% for GSave; 4.0% UpSave
3. **getBalance()** - Returns the balance of the account set.
4. **showBenefits()** - Either returns "Standard Savings Account" for Savings Account;
benefits offered by savings account + "GSave Transfer";
benefits offered by savings account + "With Insurance";
5. **computeBalanceWithInterest()** - returns new balance by computing the balance plus the interest depending on the interest rate.
6. **showInfo()** - Returns details of account number, account name, and balance.

**BankAcountDecorator** must be an interface.
---------------------------------------------------------------------------------------------------------------------------------- 
Follow instructions. You are not allowed to insert other methods except what is stated in the diagram (setters and getters are allowed).

# Implementation of Decorator Pattern

<p align="center">
  <img src="https://github.com/SG-Hangaan/decoratorPattern/assets/127215110/4751c5b3-d964-4e59-b34a-501eaefce665"/>
</p>

# UML Class Diagram

<p align="center">
  <img src="https://github.com/SG-Hangaan/decoratorPattern/assets/127215110/779030cf-3961-4aeb-a269-993c8faed705"/>
</p>
