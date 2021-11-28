# SDK-Privacy-Report
This repository is a community maintained & sourced documentation of privacy details of popular SDKs. Details include data collected/shared, purposes, tracking details which app developers can use to fill the privacy forms for Apple Privacy Nutrition & Google Safety Section.

## Overview
As a part of iOS 14 update, Apple made it mandatory for app developers to disclose privacy details of their apps, termed as Apple Privacy Nutritional Labels. Google also launched a similar app privacy disclosure requirement termed as Google Safety Section. Both of these initiatives benefit consumers to easily see the privacy overview of an app before using it. While app developers know what data they collect, for third party SDKs it requires them to read multiple documentation, ask questions and spend a lot of time to know what to fill. This project is an attempt to save that time by creating a centralized documentation of privacy detail of all SDKs. We are starting with 24 SDKs with a goal to keep increasing the list and encourage the community to contribute to it. 

## Repository Structure
We have a CSV file and a Readme file for SDK privacy details of Apple & Google. For Apple, there is more documentation and we have relied on official documentation to create this list. For Google, we have used the documentation released for apple privacy labels to create this and will be updating as more google specific documentation is released by companies. We have added a value of 'draft' where we are not sure based on official documentation and would be getting in touch with SDK owners and rely on community support to help us.

**SDK Privacy Report for Apple:**
| SDK  | Data Types Collected | Linked to User Identity  | Used for Tracking | Purposes | Source |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Name of the SDK  | Data types as defined by Apple  | Yes/No based on linking  | Yes/No based on tracking  | Purposes as defined by Apple  | Source of this information  |
| Firebase Analytics  | User ID  | Yes  | No | Analytics |   |
Refer to the 


**SDK Privacy Report for Android**
Google Data Safety Section will become mandatory in Feb'22. SDKs have not released official documentation yet and we have used their documentation for Apple Privacy Nutrition to create this. Few things to note:
1. Required/Optional Data: Depends on Opt-in(Consent) or Opt-Out if implemented. Most of the Ad SDKs have that implemented but for certain regions like EU, California, China. If you are in India and not using this, please fill Required.
2. We will be in touch with the SDK owners to get more details and update source as we get more information.


| SDK  | Data Types Collected | Shared  | Processed ephemerally? | Required or Optional? | Purposes |Source |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Name of the SDK  | Data types as defined by Google  | Yes/No based on sharing  | | | Purposes as defined by Apple | Source of this information|
| Google Admob  | Approximate Location  | Yes  | No | Required |  "Advertising or marketing, Analytics, Fraud prevention, security and compliance | |

## 📄 Resources
1. Apple Privacy Nutrition Label:
2. Steps to fill the Apple Privacy Nutrition Label Form:
3. Google Safety Section Announcement:
4. Steps to fill the Google Safety Section Form:

## How to Contribute
1. If there is a SDK missing and you want us to add information, start an issue. Also, if you have any questions or want to report incorrect information, please create an issue.
2. To add information of SDK or edit it, edit the CSV file and submit a pull request.

## 🚧 SDKs WIP
So far the project has details of 24 SDKs. We are working to add details for the following SDKs:
1. Pubmatic
2. Facebook SDK - Share, Places
3. Google Tag Manager
4. Inmobi
5. Vungle
6. Twilio
7. Zendesk
8. Amplitude
