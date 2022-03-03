---
title: Anonymizing Quantitative Data
teaching: null
exercises: 30
duration: null
summary: In this lesson we will collaboratively build a checklist to help us in
  anonymising quantitative data so that it can be shared. We will consider how
  these steps can be done automatically.
questions:
  - Why do we need to anonymize data?
  - How do we anonymize data?
objectives:
  - Gain an understanding of how to anonymise data
  - Create a checklist of anonymisation steps for quantitative data
keypoints:
  - Anonymised data are easier to share legally.
  - Remove direct identifiers
  - Reduce precision to stop outliers leading to identification
  - Consider the potential for reidentification by cross-tabulating fields
is-break: null
ukrn_wb_rules: []
day: 1
order: 200000
missingDependencies: []
dependencies: []
originalRepository: UKRN-Open-Research/ukrn-wb-lesson-templates

---
## What is anonymisation?

Anonymisation is the process of turning data from which individual people can be identified into data from which individual people cannot be identified.

Pseudonymisation is the process of turning data from which individual people can be identified into data from which individual people can only be identified using other, non-shared information.

## How might we identify people in a dataset?

> ## Discussion `10 min`
> How easy might it be to identify individual people in the datasets below?  
> What data might need to be included to allow us to identify individual people?
> 
> * Chimpanzee community members and their relationships
> * National Census Data
> * 1-week of smartphone location tracking data
> * Advertising preference information for students in a university yeargroup
> * Adveritsing preference information for all students nation-wide
> * Behavioural data for a task conducted on Amazon Mechanical Turk
> * Genome-wide association study data
> * Longitudinal study of mental health of adopted children
> * Structural MRI and depression screening questionnaire
{: .discussion}

## Building a checklist

> ## Activity `20 min`
> Divide up the resources below between the group, and make a checklist of things to consider when anonymising or pseudo-anonymising data.
> How would you go about doing it in your projects? 
> When would you go about doing it in your projects?
>
> As you go along, collaborate in the collaborative editing document to create a checklist.
> If you find your needs are incompatible with someone else's, add some conditional items to the checklist or create a new copy for each approach.
>
> > ## Resources
> > * [UK Data Service](https://www.ukdataservice.ac.uk/manage-data/legal-ethical/anonymisation/quantitative.aspx)
> > * [Finnish Social Science Data Archive](https://www.fsd.tuni.fi/en/services/data-management-guidelines/anonymisation-and-identifiers/#anonymisation-of-quantitative-data)
> > * [UK Information Commissioner's Office Guidance, Appendix 2](https://ico.org.uk/media/1061/anonymisation-code.pdf)
> > * [Consortium of European Social Science Data Archives](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/5.-Protect/Anonymisation)
> > * **what else can you find?** 
> >   * Guidance from your institution
> >   * Guidance from your government
> >   * Papers from others in your field
> >   * Good old web search
> {: .solution}
{: .discussion}

### Location data

Location data renders people especially identifiable. 
You can use the tool at [https://cpg.doc.ic.ac.uk/individual-risk/](https://cpg.doc.ic.ac.uk/individual-risk/) to explore this - enter some details and scroll down on the second page to where you can add extra attributes. 
What happens to the identifiability when you check or uncheck the postcode field?
