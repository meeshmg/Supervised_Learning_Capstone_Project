# Supervised_Learning_Capstone_Project

Abstract:
STUDYING SCOTUS: Using Supervised Learning Models to Predict How the Supreme Court Justices of the United States will Vote

This supervised learning capstone through Thinkful tasked me to find a dataset of interest, explore the data, and model the outcome of interest.

This notebook will use data from the Supreme Court Database (found [here](http://supremecourtdatabase.org/about.php)), pared down to include data from only our current supreme court justices (including the late Ruth Bader Ginsburg, in her honor), and not including the newest Associate Justice Amy Coney Barrett, considering there is not yet any data on her votes included in the data base.

The main model will be used to determine how each justice's vote might lean (conservative or liberal, codes for these meanings based on different issues can be found [here](http://supremecourtdatabase.org/documentation.php?var=decisionDirection)), given certain issues, issue areas, the term, the leaning of the entire court on the issue, whether or not there is a possible declaration of Unconstitutionality, and the legal provisions considered in the case. 

The second 'just for fun' model, takes data about certain cases and will predict how the late Ruth Bader Ginsburg would have voted in the case. I call it WWRBGD, short for "What Would Ruth Bader Ginsburg Do?"
