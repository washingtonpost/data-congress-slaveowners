# Congress slaveowners

## About this story

[More than 1,700 congressmen once enslaved Black people. This is who they were, and how they shaped the nation.](https://www.washingtonpost.com/history/interactive/2022/congress-slaveowners-names-list/)

The Washington Post has compiled the first database of slaveholding members of Congress by examining thousands of pages of census records and historical documents.

## Methodology

To create this database, The Washington Post researched more than 5,500 members of Congress — every single member born before 1840 — meaning he had reached 21 by the time the last census before the Civil War was conducted in 1860. The Post found more than 1,700 people who served in Congress and owned human beings at some point in their lives. In the early decades of America’s history as an independent country, more than half of all congressmen voting on the laws forming the country’s framework were enslavers.

To create the database, The Washington Post reviewed 18th- and 19th-century census records, which have been digitized and made available through the National Archives and Ancestry.com, as well as other documents, including wills, journal articles and plantation records.

Washington Post reporter Julie Zauzmer Weil confirmed that the person listed in the census was in fact the member of Congress using available evidence such as age, place of birth, middle name, family relationships and profession. Men who represented U.S. territories are listed in this database under the state that territory eventually became; for example, delegates from Orleans Territory are listed under Louisiana.

But we couldn’t reach a conclusion on 677 additional members of Congress. That’s where you come in. If you have any evidence about any congressman or found any errors, please visit [this page to help us identify members of Congress who enslaved people](https://www.washingtonpost.com/history/interactive/2022/submit-congress-enslaved-database/).

## About the data

This database of every person elected to Congress who was born before 1840 was created based on Washington Post research and data from these two datasets:

• [Biographical directory of the United States Congress](https://bioguide.congress.gov/)

• [congress-legislators](https://github.com/unitedstates/congress-legislators)

## Folders of note in this repo

• data/congress_slaveowners.csv - Download the data used in this story.

## Data dictionary

Variables that can be found in the data:

- `bioguide`: Member's unique identification number within the Biographical Directory of the United States Congress.
- `name`: Name of the member of Congress.
- `positions`: Member's position/s held in Congress.
- `date_of_birth`: Date of birth of this member.
- `states_served`: States where this member served at any point.
- `congresses_served`: Sessions of Congress that this member was a part of at any point.
- `start_date`: First day in Congress.
- `end_date`: Last day in Congress.
- `is_slaveholder`: Describes if this member of Congress was identified as a slaveowner.
  - `true`: This member was a slaveowner.
  - `false`: This member was not identified as a slaveowner.
  - `unknown`: There is not enough evidence to determine if this member was a slaveowner or not.

## Changelog

##### September 15, 2023

We confirmed and updated 6 entries with contributions from Washington Post readers.

##### November 28, 2022

We confirmed and updated 24 entries with contributions from Washington Post readers.

##### May 15, 2022

We confirmed and updated 4 entries with contributions from Washington Post readers.

##### April 12, 2022

We confirmed and updated 21 entries with contributions from Washington Post readers.

##### March 10, 2022

We confirmed and updated 37 entries with contributions from Washington Post readers.

##### Feb. 14, 2022

We confirmed and updated 38 entries with contributions from Washington Post readers.

##### Jan. 20, 2022

We confirmed and updated 30 entries with contributions from Washington Post readers.

##### Jan. 14, 2022

We confirmed and updated 28 entries with contributions from Washington Post readers.

##### Jan. 10, 2022

Database originally published on Monday, January 10, 2022.

The following Washington Post readers contributed research used to update the database of slaveholders in Congress: Luke Voyles in Tuscaloosa, Ala.; Nick Arjomand, Melinda Buterbaugh and Vincent Johnson in Los Angeles; Carol Bannes in St. Charles, Mo.; Joshua Benton in Arlington, Mass.; Karla Benton in Milwaukee; Ned Benton in Larchmont, N.Y.; John Browne in Warrenton, Va.; Paul Carnahan in Barre, Vt.; Vera Cecelski in Durham, N.C.; Lisa C. Childs in Fayetteville, Ark.; Gloria Clarke in Bridgeton, N.J.; Michelle Dwyer Cohen in Poulsbo, Wash.; Lyndon Comstock in Bolinas, Calif.; Beth Danesco in Mansfield, Mass.; Donna W. Dzierlenga in Houston; Matthew Edwards in Atlanta; P. Ekman in Media, Pa.; Susan Erickson in Signal Hill, Calif.; Viva Fisher in Belmont, Mass.; Candace Jackson Gray in Land O’ Lakes, Fla.; Christopher Handy in Santa Barbara, Calif.; Alexandra Kennedy and David B. Mattern in Charlottesville; Karen Krug in Jonesboro, Ark.; Jennie Leichtling in Cambridge, Md.; Kecia Lifton in Plymouth, Mass.; David McGee in Lynchburg, Va.; Susana Moore in New York; Kathy Nitsch in Sarasota, Fla.; Beth O’Malley and Kelly L. Schmidt in St. Louis; Patricia Paakkonen in Espoo, Finland; Charles Perkins in Enfield, N.H.; Timothy M. Phelps and Dustin Renwick in Washington; Courtney Pinkard in Montgomery, Ala.; Chris Pupke in Centreville, Md.; Abby Raskin in Brooklyn; Gordon Rose in Thousand Oaks, Calif.; Gwen Runion in Leonardtown, Md.; Randall K. Stagner in Raleigh, N.C.; Mary Louisa Bacon Sturges in El Cerrito, Calif.; Darlene Walsh in Columbia, Md.; Ruette M. Watson in Princeton, N.J.; Abby Westgate in Little Silver, N.J.; Kim Curlin Wettroth in Cary, N.C.; Paula L. Wiegand in Indian Head, Md.; Allen J. Wiener in Clearwater Beach, Fla.; Bridgett Williams-Searle in Albany, N.Y.

We are soliciting [help and feedback from readers](https://www.washingtonpost.com/history/interactive/2022/submit-congress-enslaved-database/) and we will update the data in this repository as we verify new evidence that comes to light.

## Licensing

This data is published under an [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license](https://creativecommons.org/licenses/by-nc-sa/4.0/).
