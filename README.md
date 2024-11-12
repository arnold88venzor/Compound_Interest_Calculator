# Compound_Interest_Calculator
      Required libraries: Python 3.x
                          Matplotlib (Visualization)


Presenting a Python powered Compound Interest Calculator , exploring impact of monthly compounding on investment over time.
Allows users to see how their money grows with compound interest by entering -  an inital  investment amount, annual interest rate, and investment duration (years). 

Script will provide an accurate calculation of the final amount and total interest earned.
Included will be pseudo code to provide steps and insight into what is going on underneath the hood of the script.

# INTRODUCTION and OBJECTIVES
Comound_Interest_Calculator serves as a tool for personal finance or investment planning.

Aim is to answer the following questions: 
"How much will my investment grow in a set period with monthly compounding?"
"How does the choice of comounding frequency impact the overall growth of my investment?"

# GOALS
Educational purpose: Demonstrate the concept of compound interest and the role of monthly compounding.
User-Centric Design: Clear, accessible way for users to calculate compound interest. 

# HOW IT WORKS 
      Given Formula for monthly compound interest, Script calculates the final amount.
#         final_amount = principle x (1+(rate/12))^12 x years


# Result Display
Upon running the script , expect the following outputs:
Initial Investment: Amount initially invested.
Final Amount:       Investment value after specified period.
Interest Earned:    Difference between initial investment and the final amount.
          EXAMPLE:
                  INPUT:
                  Enter initial investment amount: $1000
                  Enter annual interest rate (e.g., 0.05 for 5%): 0.05
                  Enter number of years: 10
                  
                  Results:
                  Initial Investment: $1,000.00
                  Final Amount: $1,647.01
                  Interest Earned: $647.01

# VISUALIZATION 
     install library: pip install matplotlib 
     
Enhance the Compound_Interest_Calculator by adding Visualization.
This feature will graph how the investment grows overtime with monthly compounding.
We will use Matplotlib to plot the growth curve, displaying the investment and effect of compound 
interest year by year. 
Result, a visual representation of how the initial investment grows over the selected time frame, demonstrating the long-term impact of monthly compounding. 






















