---
layout: project
type: project
title: Currency Converter
permalink: projects/currency-converter
image: images/currency_converter_txt_file.png
# All dates must be YYYY-MM-DD format!
date: 2017-11-01
labels:
  - Java
  - Currency
summary: A Java program that mimics a currency converter designed in ICS 355
---

Introduction

This program is a command line program written in Java. It mimics the functionality of a bank with currency exchange. It handles 3 currencies, US Dollar, Australian Dollar, and Japanese Yen, which are represented as their currency codes in the program (USD, AUD, JPY). The main goal of this program was to implement input validation, which was accomplished by implementing try-catch and utilizing exceptions.

 How to Run the Application
 
The display utilizes a switch, and correlates options to numbers. For example, option 1 is to create a new account, 2 for deposits, and so forth. Each prompt will only ask for 1 piece of information at a time, thus minimizing confusion on entry formats. For example, when depositing, the amount is asked first, once entered, the program will prompt the user for the currency that is being deposited. There are secret commands that allow for changes to the currencies and their rates. The display only gives the user options 1-6, in which 6 quits the program. However, 7 is an accepted input, and leads to the maintenance method. There is no prompt for input, the user must enter the command “maint”, then the rest of the method will continue. Any other input is considered invalid, and the program will exit.

How to Install Dependencies

Due to this being a Java program, dependencies must be implemented as JAR files. Add the dependency file to the build path, then add the file as a JAR file. Ensure the file is copied into the appropriate directory.

Code Sample From Runtime

Welcome to your bank.

To create a new account, enter 1

To make a deposit, enter 2

To withdraw, enter 3

To display currency info, enter 4.

To get your current balance, enter 5

To quit, enter 6

1

Please enter the currency code for your account (EX: JPY, USD or AUD)

USD

Your new account number is 124.

Welcome to your bank.

To create a new account, enter 1

To make a deposit, enter 2

To withdraw, enter 3

To display currency info, enter 4.

To get your current balance, enter 5

To quit, enter 6

2

Please enter account number:

124

Please enter the amount being deposited:

345.34

Please enter the currency code (USD, AUD, JPY):

USD


<img class="ui medium rounded image" src="/images/currency_converter_txt_file.png">
Currency Converter text file used for persistance
