# Big Data Infrastructure - Real estate in Vienna 
Project Concrete aims to correlate, visualize and predict real estate prices based on the relationship between various factors such as unemployment rate and population growth in Vienna, Austria.

## How it works:

### Deployment Instructions

- Deploy a MongoDB instance on Docker\
`docker pull mongo`\
`docker run --name mymongo -d -p 27017:27017 mongo`

- Open the Jupyter Notebook and execute the code blocks step by step. 

## Results: 
We expected that the real estate prices will correlate with the unemployment rate.
Hypothesis: The more people don't have money available to buy real estate, the less the prices for real estate will be.
Conclusion: We analysed the data and it's not about the unemployment rate but the rising population growth that's responsible for rising real estate prices.

