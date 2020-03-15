### <b><i>Note: this is a public repository for data collected and analysis conducted as part of the JDI.</i></b>

# <a href="https://publicsafetylab.org/jail-data-initiative"><b>Jail Data Initiative</b></a>(JDI)
### NYU <a href="https://publicsafetylab.org/"><b>Public Safety Lab</b></a>

The problem of overincarceration has received considerable attention of late. The focus of this attention, however, has largely been on state and federal prison systems. Often overlooked are local jails. In any given year, approximately 11 million Americans will be detained in a county jail, often because they lack the funds to post bail, or even because they lack the funds to pay their fines. Yet we know little about county jail practices, including which counties are systematically jailing defendants pre-trial and/or post-fine, and about the consequences of these practices. 

It is possible that longer periods of pre-trial detention, or detainees’ delayed access to counsel, actually increase recidivism, and/or escalate petty offending into more serious offending. Through the generous support of Arnold Ventures and NYU's Moore-Sloan Data Science Environment, our data science team is building the architecture to collect and merge daily county jail rosters and criminal case records in more than 1,000 counties. Using these data we will be able both to identify counties that are systematically jailing defendants pre-trial and/or post-fine, and to estimate the impacts of these practices on recidivism. We will make all our code and data publicly available to the policy and research communities.

### Methodological Notes

<ul>
  <li>Roster URLs are manually verified. A number of sites claim to provide current jail roster information for every facility in the United States (e.g., mugshots.com, inmateaid.com, etc.). Any roster that exists for a facility but is not explicitly linked on the corresponding county/municipality sheriff's website is discarded.
  </li>
  <li>As a rule, all available data on a given roster is captured by a scrape. We are conducting a continual manual schematic reconciliation process (e.g., if 'Arrest Date' appears on Roster A and 'Date of Arrest' appears on Roster B, both fields will be captured as 'Arrest_Date' by scrapers); documentation of all roster-level field title changes will be made publicly available in the next phase of this project.
  </li>
</ul>

## Contact Information

Please contact Anna Harvey or Orion Taylor (<a href="https://publicsafetylab.org/who-we-are"><b>WHO WE ARE</b></a>) with questions, comments and feedback.
