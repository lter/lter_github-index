# Welcome to the LTER GitHub Organization

This meta-repository is meant to help with navigation of the repositories within this organization account. To group similar repositories together we make extensive use of GitHub "[topics](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics)" and try to use shared repository name components. Both of these--where applicable--are described below in the following sections.

While the description below includes the _primary_ groups of repositories, there are some topics that are in use that are not described. These include `documentation`, `climhydro`, `eml-metadata`, and `lter-site-specific`. There is also an `inactive` topic that we recommend adding to repositories without activity in the last 5 years (or so).

### LTER Working Groups

_Repository Name Prefix:_ **`lterwg-` _or_ `lter-sparc-`**

_Topic(s):_ **`lter-science` & `synthesis-working-group` _or_ `sparc-group`**

_Description:_ **Repositories created by/for LTER-funded working groups and SPARC groups (Scientific Peers Advancing Research Collaborations)**

### Synthesis Skills for Early Career Researchers

_Repository Name Prefix:_ **`ssecr`**

_Topic(s):_ **`synthesis-science` & `synthesis-skills-for-early-career-researchers`**

_Description:_ **Repositories related to the [SSECR course](https://lter.github.io/ssecr/). At this time (2024), primarily the course content repo itself and several repositories specific to the Synthesis Fellows' project groups**

### Workshops

_Repository Name Prefix:_ **`workshop-`**

_Topic(s):_ **`education` & `workshop` & `synthesis-science`**

_Description:_ **Repositories containing materials for a workshop. Note that the "[eco-data-synth-primer](https://github.com/lter/eco-data-synth-primer)" repository is also a workshop despite lacking that name prefix**

### R Packages

_Repository Name Prefix:_ N/A

_Topic(s):_ **`data-science` & `r` & `r-package` & `lter-science`**

_Description:_ **R packages developed by/at the LTER Network. No shared name prefix but use of topics should make them searchable**

### Information Managers

_Repository Name Prefix:_ N/A

_Topic(s):_ **`lter-imc`**

_Description:_ **Repositories created or maintained by the Information Managers (IMs) from each of the sites in the network**

### Scientific Computing Team

_Repository Name Prefix:_ N/A

_Topic(s):_ **`scientific-computing`**

_Description:_ **Repositories created by the LTER Scientific Computing team. For more information, see the [SciComp website](https://lter.github.io/scicomp/)**







# Basement

### Template

_Repository Name Prefix:_ **``**

_Topics:_ **``**

_Description:_ ****

`climhydro` | `documentation` | `education` | `eml-metadata` | `lter-imc` | `lter-science` | `lter-site-specific` | `scientific-computing` | `sparc-group` | `synthesis-working-group`

There is also an `inactive` topic that we recommend adding to repositories without activity in the last 5 years (or so).

# Basement

## Information Managers (IMC) Committee Working Group Repositories ([all repos](https://github.com/search?q=topic%3Alter-imc+org%3Alter&type=Repositories))

* [LTER Information Managers Executive Committee](https://github.com/lter/IMC_Exec)
* [LTER Information Managers Virtual Water Cooler meetings](https://github.com/lter/IMC_VWC)

* [LTER Information Managers working group repositories](https://github.com/search?q=topic%3Alter-imc-wg+org%3Alter&type=Repositories)

* [EML metadata related repositories](https://github.com/search?q=topic%3Aeml-metadata+org%3Alter&type=Repositories)

## LTER Science working group repositories ([all repos](https://github.com/search?q=topic%3Alter-science+org%3Alter&type=Repositories))



-------------------------------------------------

## Details

**WIReD Working Group**
IMC Website Redesign and/or migration (WIRED)

- Repository: https://github.com/LTER/IMC_WG_wired
- Content migrating from http://im.lternet.edu to various locations.
- also see **imc-migration** (https://github.com/lter/imc-migration)


**Web Services Working Group (WSWG)**

- Repository: https://github.com/lter/WSWG
- Migrated from LTER svn/WSWG 

**personnelDB**
Working group to design and advise on an upgrade to the Network personnel database.

- Repository: https://github.com/lter/WSWG

**pasta2geonis**
Workflow tools to capture spatial data from the PASTA repository of LTER data and enable them in GeoNIS.

- Forked from rbeloin/pasta2geonis
- Repository: https://github.com/lter/pasta2geonis


**ASM/IMC 2015 meeting notes**

- Forked from dataRonin/LTERIM
- Updated on Sep 8, 2015 
- Repository: https://github.com/lter/LTERIM





## Scientific Working Group Repositories 
[All synthesis working group repositories](https://github.com/search?q=topic%3Alter-science+org%3Alter&type=Repositories))




## Data management tools for LTER sites
**Drupal Ecological Information Managment System (DEIMS)**: 
install profile for DEIMS, development repository

- migrated from LTER svn/diems project to GitHub
- Languages: PHP  
- Repository: https://github.com/lter/deims

**Local PASTA-based catalog** example code to harvest metadata records from PASTA+ 
and style them for the purpose of generating a local data catalog.

- Repository: https://github.com/LTER/local_pasta_catalog

**projectDB**: schema, javascript and XSLT tools to support descriptions of research projects.


**deims-d6** version exported from code.google.com/p/deims

- PHP Updated on May 21, 2015
- Repository: https://github.com/lter/deims-d6

**LTER-core-metabase** 
A PostgreSQL database design for ecological metadata. 

- In active development as of September 2019
- https://github.com/LTER/LTER-core-metabase
- **MetaEgress**: an associated R package to export EML (Ecological Metadata Language) documents from LTER-core-metabase. See https::/github.com/BLE-LTER/MetaEgress

## Network Software
**LTER Network Data Portal**  (website)

- Repository: https://github.com/LTER/____
- deployed at 
    - https://portal.lternet.edu/

**EML data ingest/statistical tools**: Stylesheets and programs to transform Ecological Metadata 
Language metadata into R, SAS, Matlab to ingest tables in analysis environments.
Includes treatment of missing values, labeling and does rudimentary analyses of the
    data, including range checking.
    
- Language  XSLT (to create R (and tidy-r), SAS, Matlab, SPSS)
-  Repository: https://github.com/LTER/eml_statistical_tools
- deployed at 
    - http://www.vcrlter.virginia.edu/data/eml2/
    - and by both the LTER and EDI data portals
 
**Controlled Vocabulary**
Migration of the LTER svn/vocab project to GitHub

- Language  SKOS
-  Repository: https://github.com/LTER/vocab
- Deployed at http://vocab.lternet.edu/
    - and used by both the LTER and EDI data portals.

**personnel-db** LTER Personnel Database used by the LNO (20xx-2016)

- Languages: Perl  
- Repository: https://github.com/LTER/personnel-db
- no longer in production

## Data Products

**ClimHy**
Migration of the LTER svn/ClimHy project to GitHub

- Languages: Perl  
- Deployed at: https://climhy.lternet.edu/
- Reposistory: https://github.com/lter/ClimHy
 - migration: May 21, 2015


## Site repositories
**Template for a repo. put name here**
Add a sentence to describe it. 

- Repository: https://github.com/LTER/[repo_name]

**PASTA-JavaScript-Search-Client**
Example HTML, CSS, and JavaScript for searching for items in a PASTA repository

- https://github.com/BLE-LTER/PASTA-JavaScript-Search-Client

**Lunr-Index-and-Search-for-Static-Sites**
How to build and use a Lunr search index for a static website.

- https://github.com/BLE-LTER/Lunr-Index-and-Search-for-Static-Sites

**Solr-JavaScript-Search-Client**
Example HTML, CSS, and JavaScript for searching for items in a Solr repository

- https://github.com/BLE-LTER/Solr-JavaScript-Search-Client

**BLE-LTER website**
Example of a static HTML website for Long Term Ecological Research site

- https://github.com/BLE-LTER/LTER-website

## Bibliography management

**Zotero-JavaScript-Search-Client**
Example HTML, CSS, and JavaScript for searching for items within a public Zotero user or group library

- https://github.com/BLE-LTER/Zotero-JavaScript-Search-Client

-------

***Text below is simply copied from github view. Site repositories are not yet curated.* **


**FCE**
 Prolog  1 Updated on Aug 22, 2017

**deims-knz-custom**
DEIMS customizations to serve the Konza Prairie LTER needs

**VCR**
Tools for working with EML Metadata on PASTA servers

**deims-pie-custom**
Migration and customization for the Plum Island Ecosystems LTER
 PHP GPL-3.0 Updated on Feb 13, 2017

**mcm-im-tasklist**
Drupal 7 based Task list to manage the workload for the MCMLTER IM
 PHP Unlicense Updated on Aug 24, 2016

**deims-mcm-custom**
Repository of customizations for McMurdo Dry Valleys LTER
 PHP  1 GPL-2.0 Updated on Jul 8, 2016

**deims-ilter-custom**
DEIMS customizations for ILTER
 PHP  1  1 GPL-2.0 Updated on Jul 1, 2016

**deims-sevilleta-custom**
To be used in sites/default/modules with a site built with https://github.com/lter/deims
 PHP  1 Updated on Jan 25, 2016

**McMurdo-Environmental-History**
Drupal customizations to make the Environmental History site for McMurdo Dry Valleys LTER
 PHP GPL-2.0 Updated on Nov 2, 2015

**deims-ntl-custom**
Customizations for the NTL DEIMS migration
 PHP GPL-2.0 Updated on Jun 24, 2015

**deims-luquillo-custom**
DEIMS Customizations for the Luquillo LTER site
 PHP GPL-2.0 Updated on Jun 16, 2015

**BES**
Updated on May 22, 2015

**deims-arctic-custom**
Customizations for the migration and settings of the Arctic LTER DEIMS instance
 PHP GPL-2.0 Updated on Sep 18, 2014

**eml-translations**
Translators to and from the Ecological Metadata Language (EML)
 XSLT  2  2 Apache-2.0 Updated on Jul 10, 2014

## Support and Credits
LTER has been funded by the National Science Foundation since 1980.
Any opinions, findings, and conclusions or recommendations expressed in this material are those 
of the author(s) and do not necessarily reflect the views of NSF.


