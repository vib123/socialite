# socialite
Using socialite package for login in our app which build in Laravel.


composer install <br />
composer update <br />
rename .env.example to .env file <br />
define your database there <br />
php artisan migrate <br />
npm install <br />
npm run dev <br />


GITHUB_CLIENT_ID = Your_GITHUB_CLIENT_ID <br />
GITHUB_CLIENT_SECRET = Your_GITHUB_CLIENT_SECRET <br />
GITHUB_Redirect_URL = Your_GITHUB_Redirect_URL <br />

FACEBOOK_CLIENT_ID = Your_FACEBOOK_CLIENT_ID <br />
FACEBOOK_CLIENT_SECRET = Your_FACEBOOK_CLIENT_SECRET <br />
FACEBOOK_Redirect_URL = Your_FACEBOOK_Redirect_URL <br />

GOOGLE_CLIENT_ID = Your_GOOGLE_CLIENT_ID <br />
GOOGLE_CLIENT_SECRET = Your_GOOGLE_CLIENT_SECRET <br />
GOOGLE_Redirect_URL = Your_GOOGLE_Redirect_URL <br />


Github Configuration: <br />

Login in your github account. <br />
In the upper-right corner of any page, click your profile photo, then click Settings. <br />
In the left sidebar, click Developer settings. <br />
In the left sidebar, click OAuth Apps. <br />
Click New OAuth App. <br />
In "Application name", type the name of your app. <br />
In "Homepage URL", type the full URL to your app's website. <br />
Optionally, in "Application description", type a description of your app that users will see. <br />
In "Authorization callback URL", type the callback URL of your app. <br />
Click Register application. <br />


Facebook Configuration: <br />

Click on https://developers.facebook.com/ link. <br />
Click on the “My Apps” in the upper-top bar. <br />
Click on the “Create App” button in the upper-top bar. <br />
Click on the “Manage Business Integrations”. <br />
Give your app a proper name. <br />
Click on the radio button of “Yourself or your own business”. <br />
Click on the “Create” button. <br />
Click on Basic under the Settings tab by the left of the page. <br />
You need to fill in the details of App Domains in our case localhost. <br />
 Scroll down and click on the button “Add Platform” it will show a modal and you’re to select “Website”. <br />
 Define Client id and Client secret key in your .env file. <br />


Google Configuration: <br />

Click on https://console.developers.google.com link. <br />
Select “Credentials” tab on left. <br />
Select a Project (Besides of “Google API”). <br />
Create New Project - name your project (as you want). <br />
Now, go back to the “Credentials” tab, select your project. <br />
“Create OAuth Consent” screen (If it shows message that it’s mandatory - sometimes it shows optional also). <br />
Click on the “External” radio button. <br />
Give a proper name in the “Application Name” field and “Save”. <br />
Click on “Create Credentials”. <br />
 Select “OAuth Client Id”. <br />
 Select “Web Application”. <br />
 Click on “Create”. <br />
 Click on edit button of your web application under “OAuth 2.0 Client IDs”. <br />
 Get the client id and client secret and define “Call back url” bottom of page.

