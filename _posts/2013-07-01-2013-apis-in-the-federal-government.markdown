---
title: "APIs in the Federal Government"
lead: Open Data, Transparency, Public Trust, and Efficiency
layout: post
tags: [apis, government]
time: 09:59:32
---
Just after the 2009 Presidential Inauguration, President Obama said,

> My Administration is committed to creating an unprecedented level of openness in Government.  We will work together to ensure the public trust and establish a system of transparency, public participation, and collaboration. Openness will strengthen our democracy and promote efficiency and effectiveness in Government.
-- <cite>[Barack Obama][1]</cite>

<!-- more --> 

Since then a lot has happened in the Federal Government pertaining to open data specifically with Application Programming Interfaces or APIs. It all really started with [data.gov](http://www.data.gov). A site that was created by the executive branch to give access to high value datasets in a machine readable format. Most of these datasets were published large XML, CSV, and ZIP files. In fact this is still the case and you can find over 75,000 datasets available to you today. *Note: Some XML file formats on data.gov are in fact a web service. These links will redirect to the agencies web service page. Example: [http://catalog.data.gov/dataset/airport-status-web-service][4].* But since the creation of [data.gov](http://www.data.gov) in May 2009 a lot has happened. In fact most of this has happened in last year or so. More and more agencies are moving away from a bulk data publishing method and moving to a more advanced real time format method of using APIs. This really has been shaped by [President Obama's Open Data Policy Directive][3] issued on May 9, 2013. This directive says, 

> "going forward, newly generated government data shall be made freely available in open, machine-readable formats, while  appropriately safeguarding privacy, confidentiality, and security."
-- <cite>[forbes.com][2]</cite>

This is really good news for everyone.  Researchers, developers, and the public will be able to use this data for whatever they wish. With this executive order many more datasets will be coming online in the years to come.

So with this said lets checkout some of the APIs that the government has available for use, and how to find new ones. 

## Let's first start with discovering new APIs. 
There are a couple of places to look when looking for Government APIs. Many of these standards are used thoughout the Government websites.

* When you are on a Government website try appending "/developer" or "/developers" to the URL.
* Additionally you can try a subdomain by removing the "www." and trying "developer.", "developers.", "api.", or "services."
* Lastly you can check the [General Services Administration GitHub page][6]. Here they have a bunch of Git repositories that you might be interested in. However, there is one that lists most known Government APIs.  The repository is called [slash-developer-pages][5]. In this repository there are many file formats that list all government "/developer" pages.  If you navigate to any of these pages you will see information on that specific agencies open data initiative. 


## APIs you may be interested in.

* Federal Aviation Administration - [Airport Information](http://services.faa.gov/docs/services/airport/)
* Department of Homeland Security - [TSA Checkpoint Wait Times](http://www.dhs.gov/mytsa-api-documentation)
* Federal Register - [Daily Journal of the Federal Government](https://www.federalregister.gov/learn/developers)
* National Library of Medicine - [Pillbox](http://pillbox.nlm.nih.gov/API-documentation.html)

As you can see there are a vast variety of datasets. These are just a couple of examples that you may find interesting. More are coming online every month and it's exciting to this come together.

## Reference Links
With that said, here are a list of links for your further exploring of APIs in the Government.

* [What is an API?](http://apievangelist.com/, "What is an API")
* [APIs in Government](http://www.howto.gov/mobile/apis-in-government "APIs in Government - HowTo.gov")
* [Data.Gov Catalog](http://catalog.data.gov/ "Data.Gov")
* [GSA GitHub Repositories](https://github.com/GSA/ "GSA Github")
* [White House Open Data Initiative](http://www.whitehouse.gov/open, "White House Open Data Initiative")
* [Project Open Data](http://project-open-data.github.io/, "Project Open Data")
* [US Government APIs Google Group](https://groups.google.com/forum/?fromgroups#!forum/us-government-apis)

----

[1]: http://www.whitehouse.gov/the_press_office/TransparencyandOpenGovernment
[2]: http://www.forbes.com/sites/reuvencohen/2013/05/09/obama-signs-open-data-executive-order-all-u-s-government-data-to-be-made-freely-available/
[3]: http://www.whitehouse.gov/sites/default/files/omb/memoranda/2013/m-13-13.pdf
[4]: http://catalog.data.gov/dataset/airport-status-web-service
[5]: https://github.com/GSA/slash-developer-pages
[6]: https://github.com/GSA/