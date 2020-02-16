# Does the Early Mover Advantage exist on GitHub?

This repository contains source code of the paper [Does the Early Mover Advantage exist on GitHub](www.example.com) . The paper investigates the relationship of software contribution activities with influential behaviour of users on [GitHub](www.github.com)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/badge_logo.svg))

## Initialization
To perform the analysis, please make sure to have a GitHub developer account and to generate token from the way defined here:

1.  Login to GitHub account --> Go to Settings --> Go to Developer Settings --> Go to Personal Access Token --> Generate Token

2.  In the code, replace value of parameter, for example, 'b499684ea402d0504e021498de8a7339edf091cf' value in quotes need to be replaced with token generated with your user account.

3. The order to access Python Notebooks is as per the naming convention.

4. Also, similarly in the Colab notebook, you would need to login with Google account. The alternative way is to put those files users.csv and followers.csv in personal computer and perform the same notebook. Due to high computation needs, we performed this analysis on Google Colat Notebook environment.

## Datasets
For this research, we used two collection. 
### GHTorrent
This collection is obtained from publicly available dataset from [GHTorrent8](http://ghtorrent.org/downloads.html) project [1]. We used [historical data as of January 1st, 2019](http://ghtorrent-downloads.ewi.tudelft.nl/mysql/mysql-2019-01-01.tar.gz)

### Dataset with GitHub API
We collected data for analysis of recent user activities. We applied the following steps:

1. formulation of the "search query" to be used while sending the API requests.
2. sending the API requests and parsing the JSON data to extract the required information<br />
3. saving the extracted information into and CSV file. This was necessary to reduce the processing time and minimizing hitting the GitHub server too often
3. more API requests as per need in order to extract the further limitation

# References
[1] Gousios, Georgios. "The GHTorent dataset and tool suite." 10th Working Conference on Mining Software Repositories (MSR). IEEE, 2013.

# Contact
Feel free to drop an e-mail for any queries:
Aditya: adityamehta@uni-koblenz.de 
Atul: atulsharma@uni-koblenz.de 
Arun: apaudyal@uni-koblenz.de 
Zyan: zambros@uni-koblenz.de
