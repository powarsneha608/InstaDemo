# Instagram Graph API User Profile Fetcher

# Description
This script fetches user profile details (ID, name, email) from the Instagram Graph API using an access token.

#eatures
- Fetch user details via Instagram Graph API
- Secure API request handling
- JSON response parsing

##  Prerequisites
- Python 3.x installed
- `requests` library installed (`pip install requests`)
- A valid Instagram Graph API Access Token

# How to Get an Access Token
1. Go to [Meta for Developers](https://developers.facebook.com/) and log in.
2. Create a new App and select "For Everything Else".
3. In the App Dashboard, go to Add a Product → Instagram Graph API → Set Up.
4. Use Graph API Explorer** ([Link](https://developers.facebook.com/tools/explorer/)) to generate a User Access Token with `instagram_basic` permission.
5. Copy the generated token and use it in the script.

# Setup & Usage

1️)Set Up Access Token
// change the access token in the code 
  

2) Run the Script

python fetch_instagram_profile.py


