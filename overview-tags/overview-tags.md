# Overview and Tags Dashboards

## Introduction

In this lab we will learn the different capabilities that **Oracle Database Service for Azure** portal has under **Overview** and **Tags** sections.


**Estimated Lab Time: 15 minutes.**

### Objectives

In this lab, you will:

* Use every capability that Overview Dashboard has:

    - Database Actions
    - Metrics
    - Scale
    - Start
    - Stop
    - Restart
    - Download wallet
    - Rotate wallet
    - Refresh
    - Change password
    - Delete

![Overview Dashboard](./images/task1/overview-dashboard.png)

* Use Tags capability from Tags Dashboard

![Tags Dashboard](./images/task1/tags-dashboard.png)

### Prerequisites

* Have previous labs completed.


## Task 1: Overview - Database Actions

**Oracle Database Actions** is a web-based interface that uses Oracle REST Data Services to provide development, data tools, administration and monitoring features for Oracle Autonomous Database.

The main features include executing your SQL statements and scripts, creating Data Modeler diagrams, developing RESTful web services, managing JSON collections, and using the Data Load, Catalog, Data Insights, Business Models, and Data Transforms tools to load data from local and remote sources, view data in your tables and views, view objects in your data dictionary, and organize, analyze, and transform your data.

If you want to lear more about Oracle Database Action click [here](https://docs.oracle.com/en/database/oracle/sql-developer-web/sdwad/about-sdw.html#GUID-AF7601F9-7713-4ECC-8EC9-FB0296002C69).

![DB Action Development Dashboard](./images/task1/db-actions-development.png)
![DB Action Administration Dashboard](./images/task1/db-actions-administration.png)

1. Login to **Azure ODSA Portal**: [signup.multicloud.oracle.com/azure](https://signup.multicloud.oracle.com/azure)

    ![ODSA Portal Dashboard](./images/task1/odsa-portal-dashboard.png)

2. We can see on the ODSA Dashboard the three database versions that we can provision. Click on **Autonomous Database**.

    ![ODSA Portal Dashboard - ADB](./images/task1/odsa-portal-dashboard-adb.png)

3. **Select** the database that we created on the previous lab. Be sure you have selected the location where you created the database. In out case **Germany West Central**.

    ![ADB Created](./images/task1/adb-created.png)

4. **Click** on the **Database Actions** button to access to this dashboard.

    ![Database Actions Dashboard](./images/task1/database-actions.png)

5. **Sign in** using the user **ADMIN** and the **password** that we created on the previous lab.

    ![Database Actions Dashboard](./images/task1/sign-in.png)

6. You can access to the **Database Actions dashboard** where you can use **Development, Data Tools, Administration, Monitoring, Downloads and Related Services** capabilities. Spend a bit of time using and learning them.

    ![Database Actions Dashboard - Development & Data Tools](./images/task1/development-data-tools.png)
    ![Database Actions Dashboard - Administration, Monitoring, Downloads & Related Services & Data Tools](./images/task1/administration-monitoring-downloads-related-services.png)

## Task 2: Overview - Metrics

1. **Click** on **Metrics** button to access to this dashboard.

    ![Metrics Dashboard](./images/task2/metrics.png)

2. You can access to the **Application Insights dashboard** where you can use **Application Dashboard, Getting started, Search, Logs, Monitor resource group, Feedback, Favorites, Rename and Delete** under the Overview seection. Spend a bit of time using and learning them.

    ![Application Insights Dashboard](./images/task2/application-insights.png)

## Task 3: Overview - Scale

1. **Click** on **Scale** button to access to this dashboard.

    ![Scale Dashboard](./images/task3/scale.png)

2. You can access to the **Scale dashboard** where you can use scale the **OCPU count** and **Storage (TB)** based on your business needs. Spend a bit of time using and learning them.

    ![Scale OCPU & Storage Dashboard](./images/task3/scale-ocpu-storage.png)

## Task 4: Overview - Start

1. **Click** on **Start** button to access to this dashboard.

    ![Start Dashboard](./images/task4/start.png)

2. You can't access to the **Start dashboard** as the database is **Active** at the moment. As soon as you stop it, this button will be accesible to Start the database.

## Task 5: Overview - Stop

1. **Click** on **Stop** button to access to this dashboard.

    ![Stop Dashboard](./images/task5/stop.png)

2. You can access to the **Stop dashboard** where you can **stop** the **Database** confirming that you want to stop the Autonomous Database.

    ![Stop Database Dashboard](./images/task5/stop-database.png)

## Task 6: Overview - Restart

1. **Click** on **Restart** button to access to this dashboard.

    ![Restart Dashboard](./images/task6/restart.png)

2. You can access to the **Restart dashboard** where you can **restart** the **Database** confirming that you want to restart the Autonomous Database.

    ![Restart Database Dashboard](./images/task6/restart-database.png)

## Task 7: Overview - Download wallet

1. **Click** on **Download wallet** button to access to this dashboard.

    ![Download Wallet Dashboard](./images/task7/download-wallet.png)

2. **Write the Password** that we created on previous lab to download the wallet and click **OK**.

    ![Wallet Password Dashboard](./images/task7/password-wallet.png)

3. After a few seconds, your **wallet will be downloaded**.

    ![Wallet Downloades Dashboard](./images/task7/wallet-downloaded.png)

## Task 8: Overview - Rotate wallet

1. **Click** on **Rotate Wallet** button to access to this dashboard.

    ![Rotate Wallet Dashboard](./images/task8/rotate-wallet.png)

2. You can access to the **Rotate wallet dashboard** where you can **confirm** that the wallet will be rotate and the implications.

    ![Rotate Wallet Confirmation Dashboard](./images/task8/rotate-wallet-confirm.png)

3. After a few seconds, your **wallet will be rotated**.

    ![Wallet Downloades Dashboard](./images/task8/rotating-wallet.png)

## Task 9: Overview - Refresh

1. **Click** on **Refresh** button to access to this dashboard.

    ![Refresh Dashboard](./images/task9/refresh.png)

2. Your **database will be refreshed** all changes that you have done recently. 

## Task 10: Overview - Change password

1. **Click** on **Change password** button to access to this dashboard.

    ![Change Password Dashboard](./images/task10/change-password.png)

2. **Write the New admin password** and click **OK**.

    ![Change Password Confirm Dashboard](./images/task10/change-password-confirm.png)

3. After a few seconds, your **password will be changed**.

    ![Password Changed Dashboard](./images/task10/changed-password.png)

## Task 11: Overview - Delete

1. **Click** on **Delete** button to access to this dashboard.

    ![Delete Dashboard](./images/task11/delete.png)

2. You can access to the **Delete dashboard** where you can **delete** the **Database** confirming that you want to delete the Autonomous Database.

    ![Delete Confirm Database Dashboard](./images/task11/confirm-delete.png)

## Task 12: Tags

We will explore now the **Tags dashboard**, where we can create tags to getr notifications related to every resource that we want to tag. [If you want to learn more about tags](https://docs.oracle.com/en-us/iaas/Content/Tagging/Concepts/taggingoverview.htm).


1. **Click** on the **Tags menu** in the left side of the window and you will access to Tags dashboard.
    
    ![Tags Dashboard](./images/task12/tags.png)

2. **Write** any tag that you want to include and the value. In my case, I will create a tag for **3 databases** as an example. After **Apply** the changes.

    ![Tags Creation Dashboard](./images/task12/tags-creation.png)

3. After a few seconds, your **tag will be created**.

    ![Tags Created Dashboard](./images/task12/creating-tags.png)

4. You can **removed** any tags at any time, just clicking the **Delete** button next to each tag.

    ![Tags Removed Dashboard](./images/task12/remove-tags.png)


*You can proceed to the next lab…*

## Acknowledgements
* **Author** - Priscila Iruela, Technology Product Strategy Director
* **Contributors** - Victor Martin Alvarez, Technology Product Strategy Director
* **Last Updated By/Date** - Priscila Iruela, September 2022

## Need Help?
Please submit feedback or ask for help using our [LiveLabs Support Forum](https://community.oracle.com/tech/developers/categories/livelabsdiscussions). Please click the **Log In** button and login using your Oracle Account. Click the **Ask A Question** button to the left to start a *New Discussion* or *Ask a Question*.  Please include your workshop name and lab name.  You can also include screenshots and attach files.  Engage directly with the author of the workshop.

If you do not have an Oracle Account, click [here](https://profile.oracle.com/myprofile/account/create-account.jspx) to create one.