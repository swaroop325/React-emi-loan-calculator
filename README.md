#React app to calculate the EMI based on amount in $USD

I have done a lone amount calculator which allows a user to enter loan amount and loan duration in months with slider which then displays
the interest rate and the monthly payment.

API used in this react app:
https://ftl-frontend-test.herokuapp.com/interest?amount=<amount>&numMonths=<months>

Response obtained in form: (JSON)
{
  "interestRate":0.33,
  "monthlyPayment": {
    "amount":208.0,
    "currency":"USD"
  },
  "numPayments":15,
  "principal": {
    "amount":2216.0,
    "currency":"USD"
  }
}

TO RUN THIS CODE:

  1. Clone this repo
  2. Run npm install
  3. Run npm start
