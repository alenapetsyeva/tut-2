---
title: Build an app from an SAP Web IDE template with p tag
description: Build an app using the SAP Web IDE template wizard
tags: [ products>sap-hana-cloud-platform, products>sap-web-ide, topic>cloud, topic>html5, topic>mobile, topic>odata, topic>sapui5, tutorial>beginner, tutorial>t1 ]
---
## Prerequisites
 - **Proficiency:** Beginner
 - **Tutorials:** [Create a Destination on HANA Cloud Platform](http://go.sap.com/developer/tutorials/hcp-create-destination.html)

## Next Steps
 - [Deploy an app to SAP HANA Cloud Platform](http://go.sap.com/developer/tutorials/hcp-deploy-mobile-web-app.html)

## Details

### You will learn
The SAP Web IDE (Integrated Development Environment) has a project template wizard, which makes it easy to create new applications quickly. In this tutorial you will build an app that reads product and supplier information from an OData source and displays it in a responsive mobile web app.

You will be setting a few configurations, then filling out a few forms in this step, but the end result is an application which can be run on a mobile device.  Ready?  Let's get started...

### Time to Complete
**10 min**
 

1. Go to <https://account.hanatrial.ondemand.com> and log in to your HCP cockpit.

    ![HCP login page](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_1.png)

2. To open SAP Web IDE, click on the **Services** tab in the navigation bar, scroll down and then click the **SAP Web IDE** tile to open the SAP Web IDE service page.

    ![HCP Subscriptions page](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_2.png)

3. On the service page, click on the **Open SAP Web IDE** link to open Web IDE in a new browser tab.

    ![SAP Web IDE status page](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_3.png)

4. The first configuration step is to enable the Hybrid App Toolkit plugin (this is required for Web IDE to show the hybrid template you will use later). In the Web IDE tab, click on the **Tools** menu, then **Preferences**.

    ![SAP Web IDE Tools menu](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_4.png)

5. In the Preferences page, click on **Plugins** on the left, scroll down to find the **Hybrid App Toolkit** plugin then enable it by clicking on the slider.

    ![SAP Web IDE plugins options](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_5.png)

6. Click **Save**, and you will see a dialog box explaining that Web IDE will refresh. The purpose of the refresh is that after selecting the Hybrid App Toolkit plugin, Web IDE will download with the hybrid app configured templates you will use in this tutorial.

    ![mSAP Web IDE plugins reload page](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_6.png)

7. Once SAP Web IDE reloads, close the **Tips and Tricks** dialog box, then click on **File > New > Project from Template** to open the new project creation wizard.

    ![SAP Web IDE creating a new project from template](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_7.png)

8. On the **Template Selection** page, click on the **Category** pulldown menu (where you see **Featured**) and select **SAPUI5 Mobile Application**. When the mobile templates are displayed, select the **SAPUI5 Master Detail Kapsel Application** template, then click **Next**.

    ![SAP Web IDE template selection filtering](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_8a.png)

    ![Selecting a template in Web IDE](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-template-mobile-web-app/mob1-2_8b.png)
