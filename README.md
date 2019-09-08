Carpet Estimation Tool Version 1.0

This application will be able to do quick quotes for customers.

Variables:

//these first 2 variables will be taken by user input

var squareYards 

var totalYards 

//fixed variables
var exchangeRate = parseFloat("1.35");
var duty = parseFloat("1.125");
var brokerage = parseFloat("1.05");
var freight = parseFloat("150.00");
var designerPrice = parseFloat("1.6");
var retail = parseFloat("1.25");

The forumla is as follows: 

squareYards * totalYards = x

x * exchangeRate * duty * brokerage + freight

Print result after freight calculation. Use result to find out Designer Price, and Retail Price.

Result * designerPrice = Net Designers Price

Net Designers Price * 1.25 (25% retail markup) = Retail

