---
order: 1
title: "Supplier Data Catalog"
client: "Whole Foods Market + Amazon"
year: "2024"
role: "Product Design"
thumb: "/images/frame-28378.png"
---

## Problem

When it comes to setting up a new item in Whole Foods Market catalogs, data quality and disparate manual processes have been underlying issues in the day-to-day work for Category Merchants. The current item setup is cumbersome and time consuming, consisting of approximately 12 steps, 9 manual interventions, and about 5 different software tools.

## Solution

To establish a source-of-truth item catalog wherein team members can set up, manage, and add new items within a unified platform. Given the team structure, it is essential for them to have the capability to review and approve items within the tool.

![](/images/frame-28378.png)

### Project Background

### Team

1x Lead UX Designer

1x User Researcher

1x Product Manager

7-10x Engineers

2-4x Users

### The Timeline

4 Months

### Our Users

![](/images/personas.png)

### Current New Item Process + CX Audit

To gain deeper insights into the current item setup process at Whole Foods Market, my UX research partner and I orchestrated a comprehensive workshop involving various merchant teams. Our objective was to meticulously outline their existing processes and pinpoint key pain points. This hands-on approach allowed us to collaboratively delve into the intricacies of the workflow, fostering a comprehensive understanding of the challenges faced by different teams involved in the item setup process.

![](/images/screenshot-2024-02-04-at-4-44-27-pm.png)

My research partner and I broke up the teams by category and asked them to map out their current new item set up & supplier data gathering process, focusing on their pain points.

![](/images/screenshot-2024-02-04-at-4-44-43-pm.png)

A close up of the **Center Store** team's flow.

![](/images/screenshot-2024-02-04-at-4-54-53-pm.png)

User flow demonstrating how the new tool could work, taking into account the pain points and project requirements.

### **The Pain Points of the Current New Item Setup Process**

After gathering and synthesizing data from merchants on how the current item lifecycle at WFM operates, I identified five key issues that informed my design work:

**Tools are fragmented, users are reformatting, uploading, and downloading same dataset 8+ times.**

New item setup today is structured sequentially, and mandates users to upload, download, copy, paste, and cleanse 70+ critical data points across a set of spreadsheets and different online tools. ****

**Teams are unnecessarily managing the transfer of data from its original source.**

****Merchants are playing telephone between the supplier and internal WFM teams - product data is rarely coming directly from its original source.

**There is a lack of data standardization.**

****Category Merchants process 90% of attributes for 3,500 requests per year; each request taking 3-5 hours to process. They’re reviewing supplier data that has no boundaries or guidance, and suppliers can submit anything they want.

**New items are managed at the *request* level rather than at the *item* level.**

One of the merchants’ largest pain points include the inability to submit a single item once it's ready to be added to the catalog. A single faulty item in a request can hold the entire item set back from being available for review downstream, which greatly slows down the process.

### Usability Testing: Item Edits

After multiple rounds of iterative conceptual designs, I progressed to the testing phase with our users. Given that adding new items was identified as a priority 2 feature, we initiated the development of the item edit experience. We wanted to gauge the usability and efficiency of proposed new item setup process.

#### Focus #1: Catch bad data!

Category Merchants’ goal is to catch any item attribute errors before submitting new items to other teams for review. However, sometimes errors can slip through the cracks and are identified downstream. Errors can range from entries made by a new global buyer, wrong item IDs, incorrect ounces, items not scanned in the store, or misspellings in product descriptions.

##### Immediate Product Code Validation

Previously, when incorporating new items into Whole Foods catalogs, merchants had to rely on the trustworthiness of the item codes provided by suppliers. The legitimacy of these product codes remained uncertain until much later in the process. Implementing an upfront check not only reduces rework but also guarantees the addition of valid products to the catalog.

![](/images/screenshot-2024-02-11-at-5-10-24-pm.png)

#### Focus #2: Make it easy to find product categories

Another identified challenge was the difficulty category merchants faced in accurately classifying new items. To address this, I developed a product category finder that allows users to input keywords, facilitating the identification of the correct match without requiring knowledge of the taxonomy.

![](/images/screenshot-2024-02-11-at-5-16-48-pm.png)

![](/images/screenshot-2024-02-11-at-5-16-59-pm.png)

![](/images/screenshot-2024-02-11-at-5-16-59-pm.png)

![](/images/screenshot-2024-02-11-at-5-17-10-pm.png)

![](/images/screenshot-2024-02-11-at-5-17-26-pm.png)

#### Focus #3: Enable in-tool communication and provide item status visibility

Recognizing a pain point where merchants lacked visibility into the approval status of their added items, we introduced a communication feature within the tool. This enhancement aims to streamline communication, providing merchants with real-time updates on the status of their requests and facilitating a more efficient and unified process.

![](/images/gdo-pending-items-send-back-item.png)

### Additional Images

![](/images/home-nav-expanded.png)

![](/images/child-item-unlinked.png)

![](/images/gdo-pending-items-send-back-item.png)

![](/images/notifications.png)
