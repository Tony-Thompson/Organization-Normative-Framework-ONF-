# Organisation Normative Framework (ONF)

Looking Local's ONF is a company-wide repository of Application Security Controls and processes. We will store and update ASCs in a central library called an ASC Library, which is part of the ONF. The ONF also specifies how and when a product should use a particular security activity, such as conducting a penetration test. It groups ASCs by level of trust, which is described in the ASC at <https://github.com/Tony-Thompson/Application-Security-Controls-and-processes>.

This ONF also includes a list of all of the elements in our business, regulatory, and technological contexts. Taking BetterOff as an example, it may have the following:

## Business contexts:

Product is an online application enabling claimants to self serve by applying online for benefit assessments and applications

Product is and external facing application

Application allows money transfer

## Regulatory contexts:

Application is subject to European Privacy Directive

Application is subject to GDPR

Application is subject to Gramm–Leach–Bliley Act (GLBA)

## Technological contexts:

Application is web-based

Application is an embedded system

Application uses RESTful web services

Application uses a SQL database

Application uses Java


The ONF application specifications repository, which is essentially a place to store functional requirements for all applications, can be found in our Application Lifecycle Management tool -  Atlassian JIRA. <https://cognovi.atlassian.net/>

The ONF also includes an Application Life Cycle Security Reference Model. This is basically a complex way of saying a process-agnostic way to define planning, building/buying, testing, using, and decommissioning applications and their associated infrastructure. The purpose of this model is to define at which stages a particular ASC should be used regardless of which kind of process you use (e.g. waterfall vs. agile).

The standard goes into depth about the various elements of the life cycle. The standard uses the term Application Life Cycle rather than software development process or life cycle because its scope is broader: it includes all the steps before and after actually developing an application.

There are other elements in the ONF, such as details around roles & responsibilities which complement this. Refer to the ISO paper for more details on these.
