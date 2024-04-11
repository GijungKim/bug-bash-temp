# HubSpot Getting Started Project Template

This is a project containing a public app, so developers can get up and running on HubSpot Developer Projects.

## Requirements

TBD

## Set up
Once you run `hs project upload` and the projects gets fully built and deployed onto your developer portal. You want to then install the app to a portal of your choice via the install URL located in your App's auth tab.
![image](https://github.com/kemmerle/hubspot-public-app-template/assets/44659712/b1d89c75-9055-4828-9e74-73e75cb29056)


Once the app is installed onto that portal, you want to be a super-admin and navigate to the related object's record customization page. i.e. Go to your portal settings, scroll down to Data Management then expand the Objects nav item to the appropriate object and click `Record Customization` and click the specified layout.
![image](https://github.com/kemmerle/hubspot-public-app-template/assets/44659712/740b86f6-ee49-4667-98fc-35b2e4ee9005)

Either update the default view or create a team view and add the UI extension card to the view. 
![image](https://github.com/kemmerle/hubspot-public-app-template/assets/44659712/d8e74c43-f6d5-4f4e-8f52-f5324f55c565)

## Gotchas
Public app UI extensions currently only render for enterprise portals (non enterprise portals are a work in progress)
