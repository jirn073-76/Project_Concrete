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
#### Hypothesis: 
The more people don't have money available to buy real estate, the less the prices for real estate will be.
#### Conclusion: 
We analysed the data and it's not about the unemployment rate but the rising population growth that's responsible for rising real estate prices.

## Sample Graphs:
### Per District Statistics (i.e. 20th district) - Data and Correlations
![image](https://github.com/jirn073-76/Project_Concrete/assets/54983399/10c14541-a31a-4351-b4a8-5800e70f32b6)
![image](https://github.com/jirn073-76/Project_Concrete/assets/54983399/933aaba4-e9e0-4525-b483-e4c5b08c4838)
![image](https://github.com/jirn073-76/Project_Concrete/assets/54983399/4a4c017c-eb01-493b-950c-9dea47d13d1c)
![image](https://github.com/jirn073-76/Project_Concrete/assets/54983399/80ba2409-d344-4d0b-ad40-aeb4dc8b08af)
![image](https://github.com/jirn073-76/Project_Concrete/assets/54983399/f4cfd1af-bcb1-4bef-9a22-4d18212f933d)
![image](https://github.com/jirn073-76/Project_Concrete/assets/54983399/26dd008d-1768-45c3-a54f-672717ee61ce)

### Per District Forecast (i.e. 20th district) - Population Growth 
![image](https://github.com/jirn073-76/Project_Concrete/assets/54983399/eec93724-573c-4f22-904d-6a58b2146e8f)
![image](https://github.com/jirn073-76/Project_Concrete/assets/54983399/abb21e20-d14c-4af2-b820-0b0027e28fd8)
