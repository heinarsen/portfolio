---
order: 3
title: "Add Custom Products to Wayfair"
client: "Wayfair"
year: "2022"
role: "Product Design"
thumb: "/images/group-129.png"
---

## Problem

A custom product is a highly-configurable product. The number of possible permutations given all its options could range in the thousands to millions. These vary significantly from Standard Products, as information is stored both on the Base & Option level. Today, Wayfair and competitive marketplaces like Amazon, Etsy, and Home Depot, do not allow suppliers to add their highly configurable products to be uploaded and sold on the storefront in a self service way.

## Solution

To enable an intuitive product addition and maintenance process for custom products, giving different suppliers a standardized, self service way to to upload their base part and option information.

![](/images/group-129.png)

### Process

Over the last year, my team and I conducted [discovery research](https://docs.google.com/presentation/d/1D3nxfhIgCMe_qf5yIpZaFv7iZl4fBAp7pYFL1GmhXnw/edit#slide=id.g10df0d1fc36_1_935) to better understand a historically untouched territory, both within Wayfair and across other competitive marketplaces. Since no other marketplace currently supports the ability to bulk upload custom products and their options in a self service way, we conducted discovery research to understand how the supplier currently offers their custom products, the anatomy of a custom product, and how they expect to interact with a tool that allows them to upload these types of products to Wayfair.

Our Findings:

1. Suppliers store information across different levels: base product, option, and combinations of the two.
2. Custom product orders should align with suppliers’ internal order processing systems.
3. Complex product data is fairly static.
4. Suppliers separate complex products from standard products.
5. Suppliers want to enable configurability without overwhelming the end consumer.

After gaining a better understanding of how custom suppliers manage their product information and what a custom product actually consists of, we created several diagrams that outline the anatomy of a custom product. Our discovery research provided us with a base level understanding of how custom suppliers currently structure, manage, and configure their option and pricing information for each base part. To gain a better understanding of what a custom product actually is, we conducted several exercises to map out the anatomy of a custom product.

![](/images/screen-shot-2022-02-02-at-9-53-05-am.png)

Object Orientated UX Exercise

![](/images/wmky4gmxisyas2megjdwnutmx00pr2miaj3fuuqly9b-10rkawgb1p4ohewjp-fyjnstocynhip-r2i8w8ksp1rnvzhob04toill-f-kqqs9zajafty0vac5zvimtte6tnyccu38.png)

![](https://cdn.prod.website-files.com/61f087014bd85c3adea3643a/61faa9b1f3fad961bec21a4e_Complex%20Product%20Addition%20-%20Product%20Overview%20-%20Add%20Option%20Categories%402x%20(1).png)

Low-Fidelity wireframe for configuring option categories

![](https://cdn.prod.website-files.com/61f087014bd85c3adea3643a/61faaa2153ed1e57f1e61d16_Complex%20Product%20Addition%20-%20Select%20Options%402x%20(1).png)

Low-Fidelity wireframe for configuring option categories

![](https://cdn.prod.website-files.com/61f087014bd85c3adea3643a/61faacbba529546df128e29a_Complex%20Product%20Addition%20-%20Product%20Overview%20-%20Add%20Rules%20%26%20Part%20Number%20Order%402x%20(1).png)

Low-Fidelity wireframe for configuring allowable option categories, exception rules, and how they want to concatenate their part numbers

After testing these wireframes, different suppliers had a great understanding of how they could upload their products, primarily the ways that they could **upload and configure their options and pricing information.**

*“Just as far as the category relationships, this makes my life a whole lot easier.”*

*“This looks pretty straightforward*" - Klaussner, Custom Upholstery Supplier

These are the potentially riskiest areas of this workflow, so we iterated further on these flows and will focus on these in the next round of research. A typical use case for managing options on a base part is to **reuse common options**, such as body fabric, across multiple base parts like sofas and sectionals. To minimize uploading duplicative information, the user has the ability to link existing options to a new base part, as well as upload and configure new options. This workflow gives them the flexibility to do either of these in the order they prefer:

**Option Configuration**

![](/images/complexoptions.gif)

**Option Upload**

After the user configures their option rules, they can generate a template based on their selection.

![](/images/screen-shot-2022-02-06-at-5-02-34-pm.png)

Each sheet in this template demonstrates an option category.

**Pricing Configuration**

Typically, a base part price begins at the **intersection of the chosen base part (like a sofa), and a starting option (like a body fabric).** The supplier can tell us what their matrix pricing begins with, as well as if there will be any up-charges on the options they have configured to this base part. They can then generate a template based on what they just told us, and provide their pricing information.

![](/images/complexpricing.gif)

**Pricing Template**

After the user configures their pricing rules, they can generate a template based on their selection.

![](/images/screen-shot-2022-02-06-at-5-02-06-pm.png)

Each sheet demonstrates different pricing scenarios.

Beyond focusing on two of the potentially riskiest and unknown areas, I created several options for showing **progress** and **error** indication throughout the upload process.

**Progress Indication Option A [Alternative Option Configuration Flow]**

![](/images/complexvid1.gif)

**Progress Indication Option B**

![](/images/complexvid2.gif)

My team and I unlocked an opportunity that will support a projected multiple billion dollar industry, and allow custom suppliers to now sell their products with Wayfair.

We plan to conduct 8 moderate user sessions to test areas like progress indication, error indication, and overall use of certain steps specific to uploading and configuring their option and pricing information.
