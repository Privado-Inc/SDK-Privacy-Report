# Contributing to SDK-Privacy-Report

1. If there is a SDK missing and you want us to add information, start an issue. Also, if you have any questions or want to report incorrect information, please create an issue.
2. To add information of SDK or edit it, edit the CSV file and submit a pull request.

## CSV template for Apple and Android SDK:

**SDK Privacy Report for Apple:**
| SDK  | Data Types Collected | Linked to User Identity  | Used for Tracking | Purposes | Source |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Name of the SDK  | Data types as defined by Apple  | Yes/No based on linking  | Yes/No based on tracking  | Purposes as defined by Apple  | Source of this information  |
| Firebase Analytics  | User ID  | Yes  | No | Analytics |   |

**SDK Privacy Report for Android**

Google Data Safety Section will become mandatory in Feb'22. SDKs have not released official documentation yet and we have used their documentation for Apple Privacy Nutrition to create this. Few things to note:
1. Required/Optional Data: Depends on Opt-in(Consent) or Opt-Out if implemented. Most of the Ad SDKs have that implemented but for certain regions like EU, California, China. If you are in India and not using this, please fill Required.
2. We will be in touch with the SDK owners to get more details and update source as we get more information.


| SDK  | Data Types Collected | Shared  | Processed ephemerally? | Required or Optional? | Purposes |Source |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Name of the SDK  | Data types as defined by Google  | Yes/No based on sharing  | | | Purposes as defined by Apple | Source of this information|
| Google Admob  | Approximate Location  | Yes  | No | Required |  "Advertising or marketing, Analytics, Fraud prevention, security and compliance | |
