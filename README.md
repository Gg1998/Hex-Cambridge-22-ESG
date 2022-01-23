# Hex-Cambridge-22-ESG
Algorithm to improve efficient ESG stock Selection for Retail Investors
## Inspiration

ESG - Environmental, Social, and Governance data have become an important factor in investing over the last few years. ESG seeks to invest in companies that maximize shareholder value while not compromising other stakeholders. However, one of the main challenges of ESG funds today is the low correlation among scores from different ESG providers. Ideally, ESG seeks to measure the company's impact, and having multiple scores using different methods creates confusion among investors who might lack the knowledge to go through each in detail. 

## What it Does

So, one way to solve this is to standardize industry metrics according to investor interest. For this submission, I have considered the environmental aspect of company operations. Traditional accounting measures a company's performance through metrics like RoA - Return on Assets / Profit margins. We can use similar metrics for evaluating companies using GHG emissions from CDP data. This data can be further normalized per industry/ sector/ region depending on investors' preferences.  

## How we built it

For data, I used a limited dataset provided by CDP for emissions and SimFin data for financial information. After performing some basic data processing, I used Python for analysis and creating the final list.  

## Challenges we ran into

The main challenge was getting open-source, clean, and usable data for this project. The second potential challenge is the lack of disclosure from companies.   

## Accomplishments that we're proud of

ESG is typically a complex topic, with teams of analysts dedicated to evaluating and analyzing companies. Finding one metric that can then be applied to all was challenging. While metrics like RoA have been around for a long time, no similar GHG emissions metrics are present. Building simple metrics that investors can easily understand was the key focus of this project. E.g., Our metric of Emissions/ Assets means the metric tonnes of GHG emitted per million dollars worth of assets. Intuitively, a good company will try to minimize this as much as possible. 

## What we learned

Data integrity and lack of disclosure remain key challenges today. Many companies beyond the US and Europe don't have a lot of meaningful disclosure, especially ones engaged in the worst ESG offenses.  

## What's next for ESG Emissions - Emitting less for more

We have registered a website build-for-better-tomorrow.tech that aims to provide users similar metrics and insights. The core idea is to make the process of data gathering and analysis simple while reducing jargon.Once sufficient data has been gathered, we could also build forward-looking predictive tools to estimate future performance. 

Last year's Gamestop saga has proved how retail investors are a force to reckon with in financial markets today. This project aims to provide these investors with tools to understand and analyze ESG risks. 

Whether a  hacker, a scientist, or an investor, all of us are part of the same world. While Science and Technology have already mobilized to reduce emissions, finance still has some way to go. It's only when the three combine, will the tide in this war turn.  
