This is a starting point for customizing the look and feel of explorer

To customize the logo, you can simply replace Explorer-Logo.png in explorer.www/assets/images

To customize the css styles, you can override them in explorer.www/assets/css

There are a handful of SWP customizations, as well.  These can be further extended to easily update the contents of the header or homepage.  These reside in explorer-overrides.ui.ttlx.

The most important ones in there:

edgproduct:LandingPageExplorer - simplifies the landing page, removing most of the widgets and the widget layout mechanisms
teamwork:LogoOverride - overrides the logo with the one stored at explorer.www/assets/images/Explorer-Logo.png
teamwork:HeaderExplorer - moves the unified search from the header to the landing page

To install this project in TopBraid Explorer, you can download the repository as a zip file, and use Project Upload in Server Administration to upload the project to Explorer. 
