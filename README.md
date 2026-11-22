# APY Savings Calculator

Every time I needed to calculate my APY, I found myself Googling it online to the point where my browser started predicting my searches. Eventually, I thought: *why not just code it myself?*

So I built this simple Java Swing desktop app in NetBeans to quickly calculate how my savings grow over time with monthly compounding and regular deposits.

## What It Does
- Takes an **Initial Amount**, **Monthly Contribution**, **Number of Months**, and **APY (%)**
- Converts the annual APY into a monthly compounding rate and calculates the final balance
- Handles invalid or blank text inputs without crashing and includes a one-click **Clear** button

## Files
- `APY_Calc.java` - Java Swing GUI and compound interest calculation logic
- `APY_Calc.form` - NetBeans form layout file
