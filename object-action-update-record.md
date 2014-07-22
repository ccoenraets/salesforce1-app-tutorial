---
layout: module
title: Module 11&#58; Updating a Record with an Object Action
---

## Step 1: Create the Object Action

1. In Setup, select **Build** > **Create** > **Objects** and click the **Expense Report** link

1. In the **Buttons, Links, and Actions** section, click **New Action**, and define the Action as follows:
  - Action Type: **Update a Record**
  - Standard Label Type: **--None--**
  - Label: **Submit Report**
  - Name: **Submit_Report**

    ![](images/object_action_update.png) 

1. Click **Save**

1. Drag the **Status** field to the Layout (after Expense Report Name)
 
    ![](images/object_action_update_layout.png) 

1. Click **Save** (upper left) 

## Step 2: Create a Predefined Field Value

1. In the **Predefined Field Values** section, click **New**

1. Set the **Status** field value to **Submitted** 

    ![](images/predefined_value.png) 

1. Click Save

## Step 3: Modify the Publisher Actions Layout

1. In Setup, select **Build** > **Create** > **Objects** and click the **Expense Report** link

1. In the **Page Layouts** section, click the **Edit** link to the left of **Expense Report Layout**

1. Click **Actions**

1. Drag the **Submit** action to the **Publisher Actions** section (after Add Expense)

    ![](images/object_action_update_publisher.png) 

1. Click **Save** (upper left)

## Step 3: Test the Application

1. Tap the menu icon ![](images/hamburger.png) (upper left corner)
 
1. In the menu, tap **Expense Reports** under **Recent**

1. Tap an expense report in the list

1. Tap the publisher button ![](images/publisher_button.png) (lower right corner)

1. Tap **Submit Report**

    ![](images/s1_object_publisher.png) 

1. Tap the **Submit** button (upper right)

 

<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="object-action-create-record.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="mobile-card.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
