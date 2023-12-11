# fitbit-fetcher

# Prereqs
These steps need to be performed if there are no access and refresh tokens.

## 1. Register APP
- Go to https://dev.fitbit.com/apps and register app. Get Client ID and Client Secret, store those in environment variables

## 2. Get Access Token
- Run get_authorization_code.py script in two steps
1. First run until Authorization url is created then click that link and then you get a redirict url back.
2. Copy redirect url from browser bar and paste to script input(will solve/automate this step later on). Then you get access and refresh tokens.

Note, Same process can be follow here: https://dev.fitbit.com/build/reference/web-api/troubleshooting-guide/oauth2-tutorial/ 

