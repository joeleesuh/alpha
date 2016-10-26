---
permalink: /
title: About Federalist
---

Federalist is an [open source](https://github.com/18F/federalist) web publishing platform for the United States federal government. It provides templates for websites, an online editor for maintaining content, and cloud-based infrastructure for high-scale, low-cost website hosting.

The team at [18F](https://18f.gsa.gov/) builds and maintains it as a hosted service available to federal government agencies.

## Why build static websites

Federalist generates static websites as opposed to using a content management system (CMS) like Drupal or Wordpress. Static websites are collections of text files as opposed to applications that dynamically generate website content. They have several advantages:

- **Easy to host and maintain** It’s very easy to host static website files, and services like Amazon S3 offer very high scalability where you pay only for what you use.

- **Less complexity and vulnerability** Avoiding CMSs means avoiding problems like maintaining dynamic server applications (no PHP or Apache / IIS) and database scaling and redundancy. Production-level static sites generally require one simple static file server or service as opposed to dozens.

- **Fully customizable** Static websites take any form developers and designers intend without the need to strip away CMS-provided features and defaults. Possible applications of static sites vary widely, from organization homepage or intranet to pre-generated web application program interfaces (API).

Static websites store content in text files. The Federalist editor provides a way for editing these files without needing to write code.


## What sites are possible with Federalist

Federalist provides ready-to-use templates for common websites, as well as support for custom website templates based on Jekyll.

See [examples of the templates]({{site.baseurl}}/pages/using-federalist/#federalist-templates) currently available.

Here are a few examples of Federalist websites in production:

![College Scorecard]({{site.baseurl}}/uploads/college-scorecard.png)
**[The College Scorecard](https://collegescorecard.ed.gov/)**


![SBST.gov]({{site.baseurl}}/uploads/sbst.png)
**[The Social and Behavioral Sciences Team](https://sbst.gov/)**

## Getting started

Federalist is currently under active development. We are working with a select list of partners to test the platform and launch new websites.

If you have a project that you think would be a good fit for Federalist, [please let us know](https://docs.google.com/forms/d/1iB8aW7c9r1QH3s8XElQCrnXRGjAiPUYpWG1CMeEqGIo/viewform).