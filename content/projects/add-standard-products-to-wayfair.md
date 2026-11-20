---
order: 2
title: "Add Standard Products to Wayfair"
client: "Wayfair"
year: "2022"
role: "Product Design"
thumb: "https://cdn.prod.website-files.com/61f087014bd85c3adea3643a/61fa9856807534b4a4dca100_Group%2077%20(2).png"
---

### January 2022

## Problem

Today, suppliers are forced to provide their product information in a step by step, linear workflow that does not support the flexibility suppliers need to enter product information when and how they want to. An overwhelming 70% of suppliers have expressed interest in using Excel as the primary way to upload their product data into Wayfair’s system.

## Solution

My team and I responded directly to user feedback by designing and building a product addition tool that works with Excel to upload large amounts of product data. This tool allows the supplier to add their product information in a flexible way, while significantly reducing the number of steps the user needs to complete in order to submit their products to Wayfair.

![](https://cdn.prod.website-files.com/61f087014bd85c3adea3643a/61fa9856807534b4a4dca100_Group%2077%20(2).png)

### Process

Before jumping to solutions, I dissected the [current product addition workflow](https://www.youtube.com/watch?v=Qtco7flRpBI) to understand where suppliers were having the most trouble. I mapped out the experience to identify potential paths the user could take, pain points, and where they could be improved.

![](/images/bsa-workflow.png)

A large part of the problem was not only the time spent in tool, but also in the Wayfair review process. Rather than looking only at the software, I discovered that the problems were arising from other parts of the business.

1. **Wayfair Asks For More**: Unlike other online marketplaces, Wayfair asks for significantly more product information from their suppliers. The reason for this is to improve the quality of storefront product listings. It was proven that providing more product information results in a 40% increase in listing visits, and a 53% revenue increase.
2. **Long Review Time**: Today, it typically takes around 2-3 days after product submission for the Wayfair review team to launch the product live on site. I created a workflow that demonstrated the manual interventions that occur during the Wayfair review process to show that the problem not only lies within the outdated software, but in the review process itself.
3. **Users Submit All or Nothing**: The current product addition tool only allows suppliers to upload their entire catalog at once. This means each individual product must go through the review process and have 0 errors for them to submit. If the supplier wanted to only submit the products that are ready to go, they do not have the ability to do so.

![](https://cdn.prod.website-files.com/61f087014bd85c3adea3643a/61f1c5bd14c40881aa93d088_Manual%20Interventions_%20Rome%20Flow%402x%20(1).png)

This process outlines the manual interventions that occur after a supplier submits their completed product to Wayfair's QA team.

After gaining a better understanding of the underlying reasons the product addition process takes so long, I met with corresponding teams to discuss how we can improve the manual QA processes and potentially decrease the amount of product data that we ask for. While keeping these issues in mind, I started to develop a new workflow that would bypass several linear steps and allow the user to upload their product information in a more flexible and faster way, while considering the business needs. I focused on the KPI of reducing the time in tool from around 1 day to 10 minutes.

![](/images/untitled-2x.png)

****

****  
After solidifying an ideal user flow, I began to wireframe.

![](/images/screen-shot-2022-01-26-at-4-09-51-pm.png)

## Prototype

We tested several iterations of the flows, and gained valuable feedback, primarily around how the user can differentiate where they upload their product information versus their product media like images, videos, and legal documents.

1. The user can search and select for their product class and download a .csv template to fill out all of their product information in the format they prefer (Excel, Google Sheets, etc).

![](/images/screen-recording-2022-01-26-at-4-36-44-pm.gif)

Here, you can see the user search and select the appropriate product class, then download the template to their local desktop.

2. The user then uploads their completed spreadsheet of product information to the system. The system then ingests the spreadsheet, and provides information about any errors or warnings that were found in the file.

![](/images/screen-recording-2022-01-26-at-4-39-35-pm.gif)

The user uploads the completed csv file to the system. The system then shows them if there are any errors, warning, or products immediately ready for launch.

3. Unlike the previous upload tool, the supplier has the ability to choose whether to submit the products that are ready to go without having to wait until they resolve other product errors. They have more control and freedom over which products will be launched when, without having to wait for their entire uploaded catalog to be ready for launch.

![](/images/screen-recording-2022-01-26-at-4-49-11-pm.gif)

The user decides to launch the products that are ready, and resolve the ones with errors later.
