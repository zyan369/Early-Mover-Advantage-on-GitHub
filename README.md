# RL19-Opinion-Leaders
Repository for Research Lab project. Opinion leaders in Github

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zyan369/RL19-Opinion-Leaders/master)

The data collection from the GitHub API included following steps:

  • formulation of the "search query" to be used while sending the API requests.
  • sending the API requests and parsing the JSON data to extract the required information
  • saving the extracted information into and CSV file. This was necessary to reduce the processing time and minimizing hitting the GitHub server too often
  • more API requests as per need in order to extract the further limitation.

To perform the analysis, please make sure to have a GitHub developer account and to generate token from the way defined here:

Login to GitHub account --> Go to Settings --> Go to Developer Settings --> Go to Personal Access Token --> Generate Token

Also, similarly in the Colab notebook, you would need to login with Google account. The alternative way is to put those files users.csv and followers.csv in personal computer and perform the same notebook. Due to high computation needs, we performed this analysis on Google Colat Notebook environment.
