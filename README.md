# travel-tide-individual-project

## Project Description
Travel Tide is committed to continuously improving its strategies to better:
1. Attract new customers
2. Retain and foster loyalty among existing customers
3. Add value to its current customer base
The primary objective of this data analysis report is to provide comprehensive insights and observations based on the available data, enabling Travel Tide to make informed decisions and enhance its overall performance by offering exclusive offers and deals. 

This report includes the travel perks suggested to users based on the groupings done on the available data. This can lead to enhance the user engagements and get better understanding of the user travel preferences. 

## Table of Contents
- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Visualizations](#visualizations)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Installation

Clone the repository:
   ```bash
   git clone https://github.com/ap186093/travel-tide-individual-project.git
   cd travel-tide-individual-project
 ```
## Usage

To reproduce the analysis, run the csv file in the `google sheets`.
or run the code in `google colab` to see the output.
```bash
https://colab.research.google.com/drive/1UwtEoYK9W46n9e59F3rai0zP8ASPebIi?usp=sharing
```
```bash
https://docs.google.com/spreadsheets/d/1CrILyvuOxU_Dn6pa6nh6ITRKO5f8fGylHm1Q6gLNRBM/edit?usp=sharing
```

## Project Structure

- `data/`: Contains the dataset used for analysis.
- `colab/`: Google colab with the analysis code.
- `results/`: Output files and results.
- `README.md`: Project documentation.

## Data

The dataset used in this project is the [Travel tide individual project final dataset] (https://docs.google.com/spreadsheets/d/1CrILyvuOxU_Dn6pa6nh6ITRKO5f8fGylHm1Q6gLNRBM/edit?usp=sharing). The data includes user information, groups the customer is listed into and all the required aggregations alongside some exploratory information.

**Data Preprocessing**:
- The dataset includes sessions that started on or after January 4, 2023.
- Users with more than 7 sessions.
- Working on only non-cancelled trips.
- The negative nights anomaly was solved by replacing the negative amounts with 0.
- All the null values are also replaced with 0 to make the aggreagations simple.
- Users are segmented into categories based on their past recorded travel data.


## Analysis

The analysis was conducted in the following steps:
1. **Exploratory Data Analysis (EDA)**: Found significant trends and patterns in the data.
2. **Feature Engineering**: Created new aggregations, summarizations and groupings to understand the commonalities in the user behaviour.
3. **Clustering**: Applied sql coding to find out groups of users in Beekeeper studio.
4. **Evaluation**: Evaluated the groupings' functionality using visual assessments and representation outcomes on Tableau.


## Results

The analysis identified few distinct outcomes:
- **Solo Travellers**: Highest user count, emphasising a noteworthy market niche.
- **Age Group Insights**: Age groups 46-60 and 36-45 are the highest recipients of travel perks.
- **Revenue Opportunities**: USA Market witnessed high revenue from married travellers in business and family categories, indicating potential for targeted marketing and exclusive deals.
- **Home Airport Preference**: LGA is a major hub for the majority of users alongside JFK and LAX, indicating a key focus area for service improvement.

The business can better serve each group's needs by customising its promotional approaches with support of these groups.


## Visualizations

Visualizations were created using Tableau public. Interactive visualizations are available on [Tableau Public](https://public.tableau.com/views/TravelTideindividualproject_17206956610980/Dashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

![Groups of customers and the respective perks received]()
<img width="774" alt="Screenshot 2024-07-11 at 12 53 24" src="https://github.com/ap186093/travel-tale-individual-project/assets/167745816/643d8af8-cb16-479e-918a-0a7db6147fa2">

![Groups vs. flight cost vs. count of users]()
<img width="1011" alt="Screenshot 2024-07-11 at 12 55 16" src="https://github.com/ap186093/travel-tale-individual-project/assets/167745816/ac709035-033d-49da-a481-5ae9171de470">

## Conclusions
The analysis of customer segmentation yielded major insights into the travel habits of the target audience. To further hone the segments, future research could explore different methodologies for segmentation or incorporate demographic information.
Possibility of customised offerings of services and promotional efforts based on user categories and solo traveller travel habits.

## Acknowledgements

I would like to thank [Thimo Wellner] and [Juan Bavaresco] for their guidance and support throughout this project. Additionally, I appreciate the use of the [Travel Tide customer](postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766.us-east-2.aws.neon.tech/TravelTide).

## Contact

For any questions or feedback, please contact:
- Name: Apurva Daoo
- Email: apoorva.daoo@gmail.com
- LinkedIn: [Apurva Daoo](<https://www.linkedin.com/in/apurva-daoo>)
