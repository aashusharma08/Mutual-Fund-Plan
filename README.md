# Mutual-Fund-Plan
Overview
This project demonstrates how a systematic investment plan (SIP) in mutual funds can grow over time using the power of compounding. It calculates and visualizes the future value of a ₹5000 monthly investment over different time periods.

Features
Calculates future value of investments using compound interest formula.
Uses Plotly to generate an interactive visualization.
Highlights the impact of consistent investing and compounding.
Formula Used
The future value of SIP investments is calculated using:

[ FV = P \times \left(\frac{(1 + r/n)^{n \times t} - 1}{r/n}\right) \times (1 + r/n) ]

where:

FV = Future Value
P = Monthly investment amount
r = Annual rate of return (as decimal)
n = Compounding frequency (monthly = 12)
t = Investment period in years
Technologies Used
Python (for calculations)
NumPy (for numerical computations)
Plotly (for interactive charts)
Installation
Clone the repository:
git clone https://github.com/aashusharma08/mutual-fund-plan.git
cd mutual-fund-plan
Install dependencies:
pip install numpy plotly
Run the script:
python mutual_fund.py
Example Output
After 1 year: ₹62,000 approx.
After 5 years: ₹3,00,000+ approx.
After 10 years: ₹8,60,000 approx.
Graph Output:
An interactive line graph showing the future value over time.

Why This Project?
This project highlights the importance of long-term investing and how mutual funds create wealth over time. It serves as a basic investment calculator and can be extended to include real mutual fund data.

Contribution
Feel free to fork the repository, raise issues, and submit pull requests to improve the project.
