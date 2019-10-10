# Research Questions for the Project


## Short-term research questions (To be presented at 16 October meeting)

- What new information can still be drawn out of the T3010 data? [Q: how to tell what has been done already]
   - predict receipt of and/or size of a grant / government money? (Financial Data -> 4510 onwards for government)
   - unsupervised clustering of the whole data? compare with organisation classification/age/size/geography-
   - Can we predict whether an organisation is affiliated to another organisation?
   - Can we predict whether a charity changed its name? (Would need a field "aka")
   - For foundations [there is a flag: public/private/other charity], what is the relation between other characteristics and percentage of operating costs and  relation to number of gifts ["how much does it costs you to give out $1?"] -- distinction between private and public foundations to control for fundraising costs. 
   

## Data sets to answer the short-term research questions

https://open.canada.ca/data/en/dataset/7ef067c4-07a8-4882-ade3-643d00fd6c49

The following .csv files might be useful (Attention: the headers are numbers, referring to fields in a form. Elizabeth to send document to Michael explaining these.)
- Identification: web site, business number. But does have categorisation according to CRA.
- Financial Data: this is the "meat". 
- Compensation: data about compensation.
- Non-cash gifts received (header "Gifts in Kind" in the PDF description)
- Qualified donees: list of gifts charities have made to qualified donees (organisations eligible to receive moneys from foundations, i.e. roughly other charities)






## Long-term research questions (To be presented later)

- How does the SDG taxonomy compare with one machine learned by unsupervised clustering?
  - In particular, how are the "a priori" / "social science" classifiers of charities represented / distributed in the machine-created clusters?
- how do changes in board composition affect giving patterns?
