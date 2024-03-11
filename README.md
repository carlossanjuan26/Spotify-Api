# Spotify-Api
This project leverages the Spotify API to conduct sentiment analysis, uncovering the emotional trends within music selections.

## Collaborators

- [@cfermarvill](https://github.com/cfermarvill) 
- [@carlossanjuan26](https://github.com/carlossanjuan26) 
  
## Getting Started with the Spotify API

To utilize the Spotify API it will be necessary follow these initial setup steps:

### Step 1: Spotify Developer Account Creation

1. **Sign Up or Log In**: To access the Spotify API, you must have a Spotify account. Sign up or log in [here](https://developer.spotify.com/documentation/web-api). Upon visiting, locate and select `Log in` at the top right corner to use your Google account or email address for access.

2. **Developer Account Setup**: After logging in, you're directed back to the Spotify API homepage, filled with essential documentation. It's crucial to familiarize yourself with this documentation for a comprehensive understanding of API functionalities, including endpoints, parameters, and responses.

3. **Create Your App**: Navigate to `Dashboard` from the top right corner where your name appears. In the Dashboard, click on `create app`, enter your desired app name, description, and a `Redirect URI` (e.g., http://localhost:8080) for Spotify to callback your application upon login. Ensure to select the Web API option, agree to the Developer Terms of Service, and click `CREATE`. Your application is now registered, and you'll be redirected to its overview page.

### Step 2: Acquire API Credentials

In your app's Dashboard, go to `Settings` to find your `Client ID` and `Client Secret`. These credentials are unique to you and necessary for authenticating your app with Spotify.

### Step 3: Setting Up Environment

This step is very important, so pay attention. You have to create a text file called `.env`. You can do this from R, by clicking on the top left to generate a new file and more specifically by clicking on `Text files`. Inside that file you should put the following:

- "client_id=YourPasswordHere". With `YourPasswordHere` being your actual `Client ID`.
- "client_secret=YourPasswordHere". With `YourPasswordHere` being your actual `Client Secret`.

You only have to write in the file what contains the inverted commas with `YourPasswordHere` being your real passwords.

It is recommended that you save the file `.env` in the same folder that you have saved this work in order to have it located and easy to access, because we will use it later.

### Congratulations!

You're all set to start using the Spotify API for your sentiment analysis project. This setup is the foundation for exploring the vast musical landscape through data and uncovering insights about emotional trends and preferences in music.

### Additional information

You will find the same information with a bit more detail in the final script. It's necessary to follow these steps accurately in order to execute our code flawlessly. Once you do it correctly, you will be able to enjoy our work :)
