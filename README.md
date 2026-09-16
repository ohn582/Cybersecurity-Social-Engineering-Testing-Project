# Cybersecurity-Social-Engineering-Testing-Project

## 📌 Overview

This cybersecurity project demonstrates how a simulated phishing campaign can be created and tested using GoPhish, an open-source phishing toolkit.

I created a dummy Outlook account, configured a sending profile, created a phishing email template and landing page, added a test user, launched the campaign, and reviewed the campaign results through the GoPhish dashboard.

The project also includes a hypothetical post-phishing scenario showing how social engineering could potentially lead to stolen credentials and unauthorized account access.

---

## 🎯 Project Goal

The goal of this project was to understand how phishing and social engineering attacks work by creating a simulated phishing campaign using GoPhish in a controlled environment. I configured a test email account, created a phishing email template and landing page, launched the campaign against a dummy user, and monitored the results through the GoPhish dashboard. The project helped demonstrate how phishing emails can be used to influence users and potentially lead to credential theft or unauthorized account access.

---

## 🔎 Campaign Setup

I started by creating a dummy Outlook account for the phishing simulation.

I then configured a GoPhish sending profile using the test email account and SMTP settings. The account authentication was configured so GoPhish could send the test email.

After configuring the sending profile, I sent a test email to the dummy Outlook account to make sure the email configuration was working correctly.

---

## 📧 Phishing Email Template

I created a custom email template in GoPhish to simulate a phishing message.

The message used a fake financial reward to demonstrate how phishing emails may use urgency and financial incentives to convince a target to interact with the message.

---

## 🌐 Landing Page

I created a landing page in GoPhish for the simulated campaign.

The landing page represented the webpage that a targeted user could be directed to after interacting with a phishing email.

---

## 👤 Test User & Group

I created a test user group within GoPhish and added my dummy email account as the target.

Using a dummy account allowed me to test the campaign in a controlled environment rather than sending the simulated phishing email to a real target.

---

## 📊 Campaign Monitoring

After launching the campaign, I reviewed the results through the GoPhish dashboard.

The dashboard displayed campaign information such as:

Emails sent
Emails opened
Links clicked
Submitted data
Reported emails
Campaign activity

The screenshot on page 6 of the project shows that the campaign successfully sent one test email to the dummy account.

---

## 🔐 Post-Phishing Scenario

I also created a hypothetical scenario explaining what could happen after a successful phishing attempt.

The scenario demonstrates how an attacker could identify a target, send a fraudulent email, convince the target to interact with it, obtain sensitive information, and potentially use compromised credentials to access an account.

---

## 🛠️ Tools Used

GoPhish — Created, configured, launched, and monitored the simulated phishing campaign.

Microsoft Outlook — Used as the dummy email account for testing.

SMTP — Used to configure email delivery for the GoPhish sending profile.

---

## 📂 Project Documentation

The project documentation includes screenshots and explanations of the complete simulation, including the GoPhish sending profile, test email configuration, phishing email template, landing page, user group, campaign creation, campaign results, and hypothetical post-phishing scenario.

---

## ⚠️ Disclaimer

This project was completed for cybersecurity education and training purposes in a controlled testing environment using a dummy account.

The techniques demonstrated in this project are intended to help understand phishing and social engineering threats and should only be used on systems or accounts you own or have authorization to test.
