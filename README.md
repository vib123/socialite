# socialite
Using socialite package for login in our app which build in Laravel.


composer install
composer update
php artisan migrate
npm install
npm run dev
rename .env.example to .env file
define your database there

GITHUB_CLIENT_ID = Your_GITHUB_CLIENT_ID
GITHUB_CLIENT_SECRET = Your_GITHUB_CLIENT_SECRET
GITHUB_Redirect_URL = Your_GITHUB_Redirect_URL

FACEBOOK_CLIENT_ID = Your_FACEBOOK_CLIENT_ID
FACEBOOK_CLIENT_SECRET = Your_FACEBOOK_CLIENT_SECRET
FACEBOOK_Redirect_URL = Your_FACEBOOK_Redirect_URL

GOOGLE_CLIENT_ID = Your_GOOGLE_CLIENT_ID
GOOGLE_CLIENT_SECRET = Your_GOOGLE_CLIENT_SECRET
GOOGLE_Redirect_URL = Your_GOOGLE_Redirect_URL


Github Configuration:

Login in your github account.
In the upper-right corner of any page, click your profile photo, then click Settings.
In the left sidebar, click Developer settings.
In the left sidebar, click OAuth Apps.
Click New OAuth App.
In "Application name", type the name of your app.
In "Homepage URL", type the full URL to your app's website.
Optionally, in "Application description", type a description of your app that users will see.
In "Authorization callback URL", type the callback URL of your app.
Click Register application.


Facebook Configuration:

Click on https://developers.facebook.com/ link.
Click on the “My Apps” in the upper-top bar.
Click on the “Create App” button in the upper-top bar.
Click on the “Manage Business Integrations”.
Give your app a proper name.
Click on the radio button of “Yourself or your own business”.
Click on the “Create” button.
Click on Basic under the Settings tab by the left of the page.
You need to fill in the details of App Domains in our case localhost.
 Scroll down and click on the button “Add Platform” it will show a modal and you’re to select “Website”.
 Define Client id and Client secret key in your .env file.


Google Configuration:

Click on https://console.developers.google.com link.
Select “Credentials” tab on left
Select a Project (Besides of “Google API”)
Create New Project - name your project (as you want)
Now, go back to the “Credentials” tab, select your project.
“Create OAuth Consent” screen (If it shows message that it’s mandatory - sometimes it shows optional also)
Click on the “External” radio button.
Give a proper name in the “Application Name” field and “Save”.
Click on “Create Credentials”
 Select “OAuth Client Id”
 Select “Web Application”
 Click on “Create”
 Click on edit button of your web application under “OAuth 2.0 Client IDs”
 Get the client id and client secret and define “Call back url” bottom of page.

