# Step 1

Create 2Gezer Inspector User or use already existing account and assign it the "API Only Permission" permission set.

## Step 2

-Create New Connected App
-Enable Oaauth Settings
-Set Callback URL https://login.salesforce.com ( not really important, just be sure that the URL begins by https://)
-Select OAuth Scopes : Full Access, Perform Requests at any time, Manage User data via API
-Enable Client Credentials FLow
-Edit Custom Label "Client ID" with the Consumer Key of the connected app.
-Edit Custom Label "Client Secret" with the Consumer Secret.

## Step 4

-Manage the connected App > Edit policies
-Select the User setted up in Step 1 Client Credentials Flow > Run As.

## Step 5

-Find ToolingConnectedApp in AppManager > Manage > Edit policies
-Select the User setted up in Step 1 Client Credentials Flow > Run As.

## Step 6

-Open an account detail page, click on the gear > Edit Page
-Select twogz in custom components and put it where you want on the page
-Activate> select default org and both desktop and phone
