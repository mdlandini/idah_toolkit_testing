---
layout: default
title: Returning Contributor Files
parent: Post-Production
nav_order: 3
---

# Returning Contributor Files
{: .no_toc }

## This is broken down into three sections:
{: .no_toc .text-delta }

1. TOC
{:toc}

### Creating a .csv File
Before you start, it will be easier to create a csv file for the mail merge process. For this example, we will be using Microsoft Excel on a Microsoft365 Account.
> Note: If you are not using a software with mail merge, you can ignore this section.

1. In Excel, create a new workbook with the following columns:
    - first_name
    - last_name
    - object_title
    - folder_name
    - folder_link

2. In each row, enter the information for each object contributed.

3. Save the file as a csv file extension.

### Returning Files with Mail Merge
This section ccovers how to send contributors their contributions using a mail merge feature. 
> Note: For this guide, we will be using Microsoft Outlook and Microsoft Word on a Microsoft365 Account. The process for mail merge is roughly the same across systems, but youu might have to Google *"insert system mail merge"*.

1. To start, the email that you are wanting to send the contributions back from must be ***the default email*** account in Outlook. 
    - To set this, navigate to Settings -> Accounts to view all accounts, select the account you want as the default, and on Mac, use the arrows in the bottom left corner to move the email to the top/on PC, sign-in with the email account you want to use.

2. With Outlook still open, navigate to Word and draft the email to send back to contributors.
    - We have a template available for download <a href="https://github.com/mdlandini/idah_toolkit_testing/blob/main/assets/images/Email%20Template%20for%20Sharing%20Files.docx">here.</a>
        - To download this template, click the link and then click "view raw". This will start the download process.
    - In the draft, label the fields that you want to fill in with the names of the column headers in your csv file.
  
3. Select "Mailings" in the Ribbon in Word to open up the mail merge.

4. Select "Select Recipients" and then "Use an Existing List".

5. Select your .csv file. This will import your list.

6. Select the text in the email draft that you want to replace with a field from the .csv file.
    - Select "Write & Insert Fields".
    - Select "Insert Merge Field".
    - Select the field from your .csv to autofill the text.
> Note: The name of the field will be the name of the column in your .csv, not the text from the rows of contributions. To see that, select  "Preview Results".

 7. Repeat Step 6 for all of your fields to be replaced.

 8. Doubble check that all the fields are populating by selecting "Preview Results" and scrolling through a few of the previewed emails.

 9. Select "Finish & Merge" and follow the prompts 

Once these steps are complete, Outlook will create a draft and queue for each email participant in the .csv file. 
> Note: Depending on the number of contributions, this will take some time (upwards of 5-10 minutes for large mail merges). We recommend not touching Outlook until all the emails are sucessfully sent.

### Returing Files without Mail Merge
