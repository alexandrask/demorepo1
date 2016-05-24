---
title: Configure Android Studio for mobile development
description: Configure an Android Studio project for mobile development with SAP HANA Cloud Platform Development and Operations
tags: [ topic>demo, topic>test, tutorial>intermediate, topic>cloud, topic>java, topic>mobile, products>sap-hana-cloud-platform ]

---

## Prerequisites  
 - **Proficiency:** Intermediate
 - **Tutorials:** [Create a basic native Android master-detail app](http://go.sap.com/developer/tutorials/hcpdo-basic-android-app.html)
 - Download and install the [SAP Mobile SDK](https://store.sap.com/sap/cpa/ui/resources/store/html/SolutionDetails.html?pid=0000013098)

## Next Steps
 - [Compile and run a native Android app on SAP HANA Cloud Platform](http://go.sap.com/developer/tutorials/hcpdo-run-native-android-app.html)

## Details
### You will learn  
You will modify an Android Studio project to include a number of resources from the SAP Mobile Platform SDK to provide secure login functionality (along with the accompanying UI components) as well as support for OData services. You must have already downloaded and installed the SAP Mobile Platform SDK and the latest patch release (if applicable) to continue.

After running the SDK installer you will find the native SDK files in the installation folder: `<install_path>/MobileSDK3/NativeSDK/`

To use the MAF Login Component you must import a number of Libraries and Resources. MAF Libraries were installed with the SMP SDK installer into the folder specified by you when you executed the installer. MAF is shipped with various resources including Android, iOS and Windows specific files like: images, layouts, localization, XML documents etc. 

The procedure shown in this tutorial can be used for any of the Android activity types – including a “no activity” empty project. In this tutorial, we will use an application name, and UI activity titles that match the Android native app tutorial for the Northwind OData service.

### Time to Complete
**15 Min**.
