---
layout: module
title: Module 8&#58; Uploading Receipts using the Chatter Feed
---
The Chatter Feed allows authorized users to communicate about an object. Object Actions provide a way to quickly 
access common tasks related to an object. In this module, you enable the Chatter Feed for the Expense 
object, and you create an Object Action that lets the user attach a receipt to an expense.

## Step 1: Enable Feed Tracking 

1. In Setup, select **Customize** > **Chatter** > **Feed Tracking**

1. Select the **Expense** object, and check **Enable Feed Tracking**

    ![](images/enable_feed_tracking.png) 

1. Click **Save**

## Step 2: Modify the Publisher Actions Layout

1. In Setup, select **Build** > **Create** > **Objects** and click the **Expense** link

1. In the **Page Layouts** section, click the **Edit** link to the left of **Expense Mobile Layout**

1. In the **Publisher Actions** section, click the **override the global publisher layout** link.

    ![](images/override-publisher-layout.png) 

1. Examine the Publisher Actions and note that the File action is present by default 

    ![](images/file-action.png) 

1. Click **Save** (upper left)

## Step 3: Test the Application

1. Tap the menu icon ![](images/hamburger.png) (upper left corner)
 
1. In the menu, tap **Expenses** under **Recent**

1. Tap an expense in the list

1. Tap the publisher button ![](images/publisher_button.png) (lower right corner)

1. Tap **File**

    ![](images/s1-file-action.png) 

1. Attach an image
    - If you are running the application on a device, attach an image using **Use Latest Photo**, **Take Photo** or **Pick from Camera 
    Roll** 
    
        ![](images/s1-take-photo.png) 
    - If you are running the application in the Salesforce1 emulator, attach an image using **Upload a file from device**


1. Add an optional comment and click **Share**
    
    ![](images/share.png)

1. On the Expense Report details screen, swipe right to reveal the Chatter Feed for this expense. You should see the 
image attachment. 

    ![](images/chatter-feed.png) 


    >The Chatter Feed automatically allows you and authorized users to communicate about this expense if needed.


## Step 4: Add a Related List to the Page Layout

Another way to look at the receipts for an expense is to add the **Notes & Attachments** list to the Expense 
Mobile Layout:

1. In Setup, select **Build** > **Create** > **Objects** and click the **Expense** link

1. In the **Page Layouts** section, click the **Edit** link to the left of **Expense Mobile Layout**

1. Click **Related Lists**, drag **Notes & Attachments** to the Related Lists section, and click **Save**

    ![](images/layout_related_lists.png) 

1. In the Salesforce1 app, go back to the Expense details view and swipe left to reveal the related information 
view

    > If the Notes & Attachments option doesn't appear, pull (swipe down and release) the view to refresh it.

    ![](images/notes-attachments.png) 

1. Tap **Notes & Attachments** to reveal the list of attachments

    ![](images/attachment-item.png) 

1. Tap the file you just attached to see it in the image viewer

    ![](images/image-viewer.png) 

1. Tap the **Close** button (upper left)

<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-compact-layout.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="create-global-action.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
