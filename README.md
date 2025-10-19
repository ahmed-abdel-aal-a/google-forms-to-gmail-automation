# Google Forms to Gmail Automation (Make.com)

A simple but powerful Make.com automation scenario that instantly notifies you via Gmail whenever a new response is submitted to your Google Form.

This project is a foundational example of lead notification and data entry automation, perfect for small businesses, freelancers, and personal projects.

## 🚀 Features

* **Instant Notification:** Automatically triggers when a new row is added to a specific Google Sheet (which is connected to a Google Form).
* **Dynamic Content:** Pulls data directly from the form submission (like Name, Email, and Message) and inserts it into the body of the notification email.
* **Easy to Deploy:** Ready to use! Just import the `blueprint.json` into your Make.com account, connect your apps, and activate.

## 🛠️ Tools Used

This automation relies on two core Make.com modules:

1.  **Google Sheets** (Trigger: `Watch New Rows`)
2.  **Gmail** (Action: `Send an email`)

## 🔧 How to Use This Blueprint

1.  **Download:** Download the `blueprint.json` file from this repository.
2.  **Go to Make.com:** Log in to your Make.com account and go to the "Scenarios" section.
3.  **Import:** Click on the "More" (...) button and select "Import Blueprint".
4.  **Upload:** Select the `blueprint.json` file you just downloaded.
5.  **Connect:** The scenario will appear. You will need to:
    * Click the `Google Sheets` module and connect it to your own Google Account and select the spreadsheet you want to watch.
    * Click the `Gmail` module and connect it to your own Gmail account.
6.  **Customize:** Update the `Gmail` module to send the email *to* your desired address and customize the `Subject` and `Body` as needed.
7.  **Activate:** Save and turn the scenario **ON**!
