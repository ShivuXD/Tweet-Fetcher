# Tweet-Fetcher

This python project made on Google Colab allows users to fetch several tweets based on the given keyword or, a hastag. 


## Requirements

- Python 3.x
- `tweepy` Library
- `getpass` Library
- Google Colab Platform


## Utilization 

1. **Load the script:**

   Go **[Here](https://github.com/ShivuXD/Tweet-Fetcher)**  and, select the " Tweet Fetcher.ipynb " file and, open it in your Google Colab.

2. **Run the libraries:**

   Execute all the libraries given in the 1st code cell.

3. **Upload your Bearer Token:**

   You would have to upload your 'Bearer Token'. Scroll down to find the steps to obtain it.

4. **Input your preferences:**

   The code will ask you to input your preferences and, no. of tweets you would like to fetch.

5. **Tweets:**

   The script will give output and, fetch the no. of tweets based on the user's query with the twitter/X handles that posted it.


   
## How to get your Bearer Token?

*What is a Bearer Token?*
  
  A Bearer Token is a secret key used to authenticate and, access the Twitter API v2 securely. Required for making authorized API requests like fetching tweets.
  This token verifies your identity and ensures that your app has the necessary permissions to interact with Twitter's services.

  **NOTE: Treat your Token like a password. Keep it private and never share it publicly.**

 ### 🔐 Step 1: Create a Twitter/X Developer Account
   1. Visit **[developer.twitter.com](https://developer.x.com/)**

   2. Log in with your Twitter/X account.

   4. Click on "Apply" to become a Twitter/X developer.

   5. Choose " Exploring the API " or, similar for personal/test usage.

   6. Fill in the details and submit it.


 ### ⚙️ Step 2: Create a Project & App
 
   1. After the approval, go to your Developer Dashboard.

   2. Click "Create Project" and fill in the name and, it's purpose.

   3. Then create an App under that project.


 ### 🔑 Step 3: Get Your Bearer Token

   1. Go to your App → Keys and Tokens.

   2. Scroll to Authentication Tokens.

   3. Click "Generate Bearer Token".

   4. Copy it and, save it somewhere else. The Token would be generated and, shown you once unless re-generated.


## Script Explaination 

### Libraries of Function

This python script uses `tweepy` library to aaccess the Twitter/X API, to fetch posts based on a hashtag or, keyword given by the user using their Bearer Token.
The project also uses `getpass` library to let users enter their sensitive information (e.g Bearer Token) without displaying it on the screen, it is used to keep your API key/Bearer Token secure when you're running this program and, ensuring proper security of it.


  ### Working

   This script allows users to fetch recent posts from X (formerly Twitter) using a keyword or, a hashtag. The user is given secured entry for their Bearer Token and, search input (i.e Keyword, Hashtag). Then the script uses the Tweepy library to connect to X’s API and, fetch posts which is directly related or, is similar to the user's query. It then displays each post's content and their user handles directly as the final output.


