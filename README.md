# watsonForms
Using Watson to analyze responses from a Google form.

# Setup

### File Structure

This is the basic file structure I use for this project:

```
Project -> Data
        -> Authorization
```

## Cloud Platform Accounts

Proprietry services for this project:

### IBM Cloud

1. You will need to register for a free [IBM cloud account](https://cloud.ibm.com/registration).
2. From the dashboard click the "manage" drop down list, and select account.
3. From the menu on the left click "resource groups" to name and create a new resource.
4. Return to the dashboard and click "create resource" in the top right corner.
5. Click "AI" from the categories menu on the left hand side.
6. Select "Natural Language Understanding" from the option in the center.
7. Name your service, select a region closest to you, and select a resource group to assign it to and click create at the bottom of the page on the right.
8. On the left hand menu select "service credentials" and click "New credentials"
9. Click on "view credentials" and save this .json file as "watson_client_secret.json" in your "Authorization" folder.

### Google Developer Console

1. You will need to register for a free [Google developer account](https://console.developers.google.com/)
2. Click the dropdown menu on the top left, and click "new project".
3. Once created click the "enable APIs" button.
4. You will have to enable the "Google Drive API", "Google Sheets API" and the "Google Cloud Key Management Service (KMS) API"
5. From the API dashboard click "credentials" on the left menu and then "create credentials".  
6. Select "Service Account Key" and select "New Service Account" then, assign it the project owner role, name it and click create.
7. Save the .json file to your "Authorization" folder as "google_client_secret.json"
8. From the API dashboard click the three lines to the left of "Google APIs".
9. Click "IAM & Admin" followed by "service accounts".
10. Under the action header, click the three dots and then edit.
11. Click "Show domain wide delegation" and click the box that says "enable domain wide delegation" and save.
12. From the dashboard click credentials followed by the tab for "OAuth consent screen" 
13. 






