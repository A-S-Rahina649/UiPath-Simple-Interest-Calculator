# UiPath Simple Interest Calculator

## Project Overview

This UiPath automation calculates simple interest using multiple workflows and arguments.

The application:

* Accepts the initial deposit amount from the user.
* Accepts a deposit period (1, 3, or 5 years).
* Uses a separate workflow to calculate simple interest.
* Passes values between workflows using In and Out arguments.
* Displays the accumulated interest and final deposit balance.

## Formula Used

Simple Interest = Deposit Amount × Rate × Period / 100

Rate per year = 1.75%

## Technologies Used

* UiPath Studio
* Input Dialog
* Invoke Workflow File
* Arguments (In / Out)
* Assign Activities
* Message Box

## Workflow Structure

Main.xaml

* Collects user input
* Invokes CalculateInterest.xaml
* Displays results

CalculateInterest.xaml

* Receives deposit amount and period
* Calculates interest
* Returns the result to Main.xaml

## Sample Output

Deposit Amount: 10000

Period: 3 Years

Accumulated Interest: 525

Final Deposit Balance: 10525
