---
title: "How to Deploy Your Licensed App to the Cloud"
space: "General How-Tos"
category: "Mendix Cloud"
---

## 1 Introduction

It has never been easier to deploy a Mendix application to the cloud. This how-to will explain the options a developer has to deploy applications to a connected cloud node.

## 2 Prerequisites

Before starting this how-to, make sure you have completed the following prerequisites:

*   Your app is linked to a licensed Cloud Node
*   You have deployment permissions
*   Your Google Authenticator is enabled

## 3 Deploying the App to the Mendix Cloud

There are two methods of deploying your app to the Mendix Cloud. The first option is directly via the **Mendix Modeler**, and the second  is through the **Developer Portal**.

### 3.1 Deploy via the Mendix Modeler

1.  Open the **[Mendix Modeler](http://appstore.home.mendix.com/link/modeler/)**.
2.  Open the licensed app.
3.  Click **Project** in the menu and select **Deploy to licensed cloud node** (Ctrl+F5).

    [](attachments/18448697/18581233.png)

4.  Click **Deploy**.

    ![](attachments/18448697/18581232.png)

5.  The deployment is now in progress. Click **Show online**, to see the uploaded package.

    ![](attachments/18448697/18581231.png)

### 3.2 Create a package from Team Server in the Developer Portal

An app can also be deployed without using the Mendix Modeler. Take the following steps to do this:

1.  Go to the [Developer Portal](http://home.mendix.com).
2.  Click **Apps** in the top navigation panel.
3.  Select your app.
4.  Go to **Environments**.
5.  Click **Create package from teamserver**.
6.  Select the preferred branch and revision and click **Next**.
7.  Give the build a version number and click **Build this revision**.

The package is now being deployed to the cloud.

## 4 Deploy the App to an Environment

Previous steps explained how to deploy a Deployment Package to the Mendix Cloud. The actual app is not running yet. This chapter will explain how to deploy the App to a node environment.

Follow these steps to deploy a Deployment Package to a node environment:

1.  Open the [Developer Portal](http://home.mendix.com).
2.  Open your app.
2.  Go to **Environments**.
3.  In the **Deployment Package Repository**, choose the preferred Deployment Package and click **Deploy**.
4.  Select the preferred environment and click **Continue**.
5.  Click **Transport**. If asked for, clean the environment.
6.  Configure the Constants if needed, by clicking **Constants** and **Edit constants value**. This can also be done in a later stage in the settings. 
7. Click **Continue**.
8. Click **Start application**. If asked for, click **Synchronize database**.

The app is now deployed and the administrative account can be configured.

## 5 Related content
*   [How to Link Your Free App to a Licensed Cloud Node](how-to-link-app-to-node)
*   [How to Set Up Two-Factor Authentication With Google Authenticator](/howtogeneral/support/how-to-set-up-two-factor-authentication-with-google-authenticator)
*   [How to Upgrade Your Free App to a Licensed App](how-to-upgrade-free-app)
