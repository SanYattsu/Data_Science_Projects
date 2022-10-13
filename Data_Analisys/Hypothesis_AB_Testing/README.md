# Hypothesis Prioritization and A/B Testing

## Task

Prioritize hypotheses, run an A/B test, and analyze the results for an online store.

## Data

Table orders Hypotheses & RICE

- Hypothesis - a brief description of the hypothesis;
- Reach - coverage of users on a 10-point scale;
- Impact - impact on users on a 10-point scale;
- Confidence - confidence in the hypothesis on a 10-point scale;
- Efforts - the cost of resources to test the hypothesis on a 10-point scale.

Table orders

- transactionId - order identifier;
- visitorId - ID of the user who made the order;
- date - the date when the order was made;
- revenue — order revenue;
- group — the A/B test group the order belongs to.

Table visitors

- date — date;
- group — A/B test group;
- visitors - the number of users on the specified date in the specified A/B test group

## Libraries used

- pandas
- scipy
- numpy
- seaborn
- matplotlib
- dotenv
- re
