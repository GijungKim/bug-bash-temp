# HubSpot Getting Started Project Template

This is a project containing a public app, so developers can get up and running on HubSpot Developer Projects.

## Requirements

TBD

## Set up
NOTE: You need to be a super-admin in the developer account, where you will be uploading your app.

1. Run hs project upload --account=<dev-acct-id> to build and deploy the project to your developer account.
2. Retrieve the install URL located in your app's auth tab.
3. Use that install URL to install the app in a developer test account of your choice.
![image](https://github.com/kemmerle/hubspot-public-app-template/assets/44659712/b1d89c75-9055-4828-9e74-73e75cb29056)


4. Once the app is installed in the developer test portal, navigate to the related object's record customization page. For example, if your UIE extension card will appear on Contacts record pages, navigate to the Contacts record customization page.
5. Scroll down to Data Management, expand the Objects navigation item, and select the appropriate object.
6. Select the Record Customization tab, and choose the specified layout.
![image](https://github.com/kemmerle/hubspot-public-app-template/assets/44659712/740b86f6-ee49-4667-98fc-35b2e4ee9005)

7. You can either update the default view or create a team view. Then add the UI Extension card to it.
![image](https://github.com/kemmerle/hubspot-public-app-template/assets/44659712/d8e74c43-f6d5-4f4e-8f52-f5324f55c565)

## Gotchas
Public app UI extensions currently only render for enterprise portals (non enterprise portals are a work in progress)
