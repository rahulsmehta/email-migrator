Princeton Email Converter
========================

## What?
A step-by-step guide (and Python script) to export all emails from your Princeton inbox, and also to find all websites that your Princeton account
was used to sign up for.

## When?
Senior email accounts will deactivate [**Thursday, August 8, 2019**](https://princeton.service-now.com/snap/?id=kb_article&sys_id=c22a27064f9ca20018ddd48e5210c745) 
(65 days after graduation), and will continue forwarding until June 4, 2020. 

## How?
#### Downloading your Gmail inbox
1. Sign in to your Princeton Google Account and navigate to https://takeout.google.com/.
2. In the "Create a New Archive" wizard, deselect all options and only select "Mail."
3. In the "Customize Archive Format" section, keep the selected defaults.
4. Click "Create Archive" and wait for it to finish, and download the compiled .zip file (note: this could take several hours or even days depending on the size
of the inbox)

#### Extracting all accounts associated with the email
1. Extract all archives into one folder (here we'll call it `email_dir/`)
2. Run the associated python script (TODO)

## Who?
This was written by Rahul Mehta (formerly rahulm@princeton.edu, currently mehta.rahul95@gmail.com). PRs/comments are welcome!
