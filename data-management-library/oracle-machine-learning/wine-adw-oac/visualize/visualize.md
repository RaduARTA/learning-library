# Visualize Your Data[Workshop Under Construction]

## Introduction

*Describe the lab in one or two sentences, for example:* This lab walks you through the steps to ...

This lab walks you through the steps to ...

Estimated Lab Time: n minutes

### About Product/Technology
Enter background information here..

### Objectives

*List objectives for the lab - if this is the intro lab, list objectives for the workshop*

In this lab, you will:
* Objective 1
* Objective 2
* Objective 3

### Prerequisites

*Use this section to describe any prerequisites, including Oracle Cloud accounts, set up requirements, etc.*

* An Oracle Free Tier, Always Free, Paid or LiveLabs Cloud Account
* Item no 2 with url - [URL Text](https://www.oracle.com).

*This is the "fold" - below items are collapsed by default*


## **STEP 1**: Login to Oracle Analytics Cloud


## **STEP 2**: 



## **STEP 1**: Create Visualizations using your data sets

1. Create a new project by clicking **Create Project**.

    ![Data Set - Create project](./images/lab300_21.png)

    A new screen with a **white canvas** is opened using the **SH&#95;SALES Data Set** you created.

    ![OAC - White canvas](./images/lab300_22.png)

    Before drowning into details, let us give you a quick **explanation** of the different parts of this screen. This will help you to easily follow the next steps.

    An **Oracle Analytics Project** consist of **three main parts** (you can see them at the top right part of the screen):

    ![OAC Navigation](./images/lab300_23.png)

    - **Prepare**: Here is where you configure your data. You get a preview of each dataset on the project. You enrich it by adding columns, hiding or renaming the available ones. You can also define joins between datasets here

    - **Visualize**: Here is where you explore and Analyze the data. You can create several canvases to hold the different visualizations you define

    - **Narrate**: Here is where you create a more presentation-oriented view of the analysis you created. This tab allows you to choose which insights to show and add comments and descriptions. It helps to understand your analysis journey and focus on showing the results

    During this workshop, you will use the **Prepare** and **Visualize** tabs mainly.

    You have already seen the **Prepare** screen on previous steps. The **Visualize** screen is this one:

    ![OAC - Canvas explanation](./images/lab300_24.png)

    Main areas to note here are:

    - **Explorer**: Contains all fields from your datasets to be used in the project

    - **Properties box**: Allows you to define the properties and parameters of the selected object. If it is a column it will be highlighted in blue (in the screen PROD_ID in the Explorer menu is selected), if it is a graphic from the canvas it will have a thin blue borderline around it

    - **Graph Definition**: Contains definition of the selected Visualization, which fields to use and where (Axis, Filters, Trellis Groups...)

    - **Canvas**: Your play area. You can place your visuals here. You can also create more Canvases and copy/move visuals around

2. Now that you know a bit your way around in the **Project**, you can continue with the workshop.

    **Remember** that you just added the new dataset from the **SH&#95;SALES** table.

    All the number-type columns from this table are treated as **NUMBER** by default. You can check the information on the **Properties** section of each table column under the Data Type section.

    ![SH-SALES Properties](./images/lab300_25.png)

## **STEP 1**: title

Step 1 opening paragraph.

1. Sub step 1

  To create a link to local file you want the reader to download, use this format:

  Download the [starter file](files/starter-file.sql) SQL code.

  *Note: do not include zip files, CSV, PDF, PSD, JAR, WAR, EAR, bin or exe files - you must have those objects stored somewhere else. We highly recommend using Oracle Cloud Object Store and creating a PAR URL instead. See [Using Pre-Authenticated Requests](https://docs.cloud.oracle.com/en-us/iaas/Content/Object/Tasks/usingpreauthenticatedrequests.htm)*

2. Sub step 2 with image and link to the text description below. The `sample1.txt` file must be added to the `files` folder.

    ![Image alt text](images/sample1.png "Image title")

3. Ordered list item 3 with the same image but no link to the text description below.

    ![Image alt text](images/sample1.png)

4. Example with inline navigation icon ![Image alt text](images/sample2.png) click **Navigation**.

5. One example with bold **text**.

   If you add another paragraph, add 3 spaces before the line.

## **STEP 2:** title

1. Sub step 1

  Use tables sparingly:

  | Column 1 | Column 2 | Column 3 |
  | --- | --- | --- |
  | 1 | Some text or a link | More text  |
  | 2 |Some text or a link | More text |
  | 3 | Some text or a link | More text |

2. You can also include bulleted lists - make sure to indent 4 spaces:

    - List item 1
    - List item 2

3. Code examples

    ```
    Adding code examples
  	Indentation is important for the code example to appear inside the step
    Multiple lines of code
  	<copy>Enclose the text you want to copy in <copy></copy>.</copy>
    ```

4. Code examples that include variables

	```
  <copy>ssh -i <ssh-key-file></copy>
  ```

*At the conclusion of the lab add this statement: note this is the last lab in the workshop*
Congratulations! You have completed this workshop!

## Learn More

*(optional - include links to docs, white papers, blogs, etc)*

* [URL text 1](http://docs.oracle.com)
* [URL text 2](http://docs.oracle.com)

## Acknowledgements
* **Author** - Charlie Berger & Siddesh Prabhu, Data Mining and Advanced Analytics
* **Contributors** -  Anoosha Pilli & Didi Han, Database Product Management
* **Last Updated By/Date** - Didi Han, Database Product Management,  March 2021
* **Workshop Expiry Date** - March 2022