Mortgage Amortization Calculator
========================================================
author: Leigh Anne Poole
date: 9/11/2016
autosize: true

About the Calculator
========================================================

The main inspiration behind this calculator is that I am plan to begin looking for a house soon.  I wanted a tool that I could use to determine how much I could afford when it comes to purchase a house.

How it Works
========================================================

Select your loan parameters (Loan Amount, Interest Rate, & Fixed Payment Amount) see the calculated Loan Term, Total Finance Charge, and Total of all loan payments. 
Also see a plot of the remaining mortgage balance as the loan is paid off. Lastly, the full amortization table is available to inspect

Example Code
========================================================

I wanted to show what the slider code looked like to emphasize what I was looking to create.

sliderInput("loanAmount",
    "Loan Amount",
    min = 10000,
    max = 500000,
    value = 10000,
    step= 1000)


What we hope to gain
========================================================

Our hope is to help other people be able to easily do deeper research into what they will be able to afford in a house.
