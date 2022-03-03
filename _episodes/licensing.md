---
title: Licenses for Data
teaching: 5
exercises: 25
duration: null
summary: A discussion about data licensing - what kind of options are there, and
  what are the pros and cons?
questions:
  - What is a license?
  - What licenses are there?
  - How do I choose a license?
objectives:
  - Understand the main issues in licensing.
  - Know what license suits your data.
keypoints:
  - Licenses let you control who can do what with your work.
  - Licenses are not a substitute for strong community norms.
  - Using a well-known license makes it easier for users and automated systems
    to understand and respect.
is-break: null
ukrn_wb_rules: []
day: 1
order: 400000
missingDependencies: []
dependencies: []
originalRepository: UKRN-Open-Research/ukrn-wb-lesson-templates

---
## What is a license?

Roughly, in lay terms, when you put in work to create or curate something, you acquire _rights_ over that thing. 
Your rights include things like the right to be identified as the author.
When other people use your work, they may do things that infringe upon your rights. 
To help them understand what they can and can't do, and to give them a legal basis on which to interact with your work, you can apply a _waiver_ or a _license_ to your work.

* A _waiver_ gives up rights, meaning that those rights cannot be infringed. 
* A _license_ specifies how someone can use your work. 
	* Generally, this adds to what people can do
	* But it can also require them to do some things, such as credit you as the author

If you don't include a waiver or a license people will not know how they can legally and appropriately use your work.
**Include a license**.

## How do I choose a license?

* Licenses used by others in your field
* Funder/Institution/Government requirements/guidance
* [License picker tool](http://ufal.github.io/public-license-selector/)

## What common data licenses are there to choose?

There are several _families of licenses_ which offer suites of similar licenses that place different restrictions on the users.
The families covered here are _Creative Commons_ (**CC-x**), _Open Data Commons_ (**ODC-x**), and _(UK) Government License_ (**xGL**).
Each subheading below addresses a different use case.

### No restrictions

To make your data maximally reusable, at the cost of losing the (legal) right to attribution and any control over how it is used, apply a public domain license. 
Public domain licenses can consist of a waiver, giving up all your rights, and a permissive license in case the waiver is not acceptable.
These licenses avoid the _attribution stacking_ problem of attribution licenses, but can only be used where 

* CC-0 4.0
* **PDDL**: Open Data Commons Public Domain Dedication and License
	* The PDDL includes attribution-sharealike requests as community norms, but not as legal requirements

> ## Community norms
> Just because you're legally _allowed_ to do something, doesn't mean you should.
> It's within the license terms of a public domain release to include a work verbatim without attribution, but many communities have strong norms against plagarism.
> 
> If the norms of your community cover your concerns, and you're not especially worries about how your work is used outside your community, you can use a public domain license even if you would _like_ attribution (you just don't _require_ it).
{: .notification}

### Attribution

You can require that people attribute your work to you when they use it.
This is a common requirement, and modern licenses usually make it clear what constitutes attribution (e.g. a URL for a page with attribution information).
A disadvantage to requiring attribution is that it can lead to _attribution stacking_, where attribution lists become unweildy because each derivative of a work must attribute the creators of each previous incarnation.

* **CC-BY 4.0**
* **ODC-By**
* **OGL** is designed to minimise attribution stacking by requiring a very basic attribution statement

### Share-alike (copyleft)

You can require that people share derivative works as openly as the original.
This can be awkward in practice because many copyleft licenses are incompatible with one another, meaning that it can be very difficult to find a way to release resources that include multiple components with sharealike licenses.

* **CC-BY-SA 4.0**
* **ODC-ODbL** allows products derived from a database to be released on an attribution basis, but requires new _databases_ derived from a database to be released on a sharealike basis

### No commercial use

You can require that people release derivatives of your work free of charge.
It is quite common for work with a non-commercial license to include an alternative license for use by those who wish to use work commercially (acquisition of the work under the more permissive license usually costs money). 
The definition of commercial can vary - in some cases textbooks or academic articles may count as commercial (even if the person producing the derivative work doesn't get the money). 

* **CC-BY-NC 4.0**
* **CC-BY-NC-SA 4.0** includes a sharealike clause alongside the non-commerical requirement
* **NCGL** is designed to minimise attribution stacking with a minimal acknowledgement notice, and has no sharealike requirement

> ## Discussion `15 min`
> Which licensing approach seems most relevant for your data?
> 
> Does that approach suit all your data from all your projects? 
{: .discussion}

## Further reading
* [Digital Curation Centre Data License Guide](https://www.dcc.ac.uk/guidance/how-guides/license-research-data)
* [CESSDA License Training](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/6.-Archive-Publish/Publishing-with-CESSDA-archives/Licensing-your-data)
* [Data Carpentry Licensing Blogpost](https://datacarpentry.org/blog/2016/06/data-licensing)
