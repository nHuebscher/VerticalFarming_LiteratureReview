# Resources for Systematic Literature Review on the Sustainability of Vertical Farming 

In this repository, you will find 
- which [tools and sources](#tools-and-sources-used-for-the-literature-review) were used for the Literature Review
- the [research question, design and search strings](#research-question-design-and-search-strings) used
- the [search engine results](#search-engine-results), also uploaded as .csv file per search engine
- in detail [how the tool Cadima was used](#cadima-work-flow)
- the [inclusion and exclusion criteria](#inclusion-and-exlusion-criteria) for the title screening, the abstract screening and the fulltext screening and their results as .xlsx or .csv file


## Tools and Sources used for the Literature review

The literature review (LR) was performed following the steps in the guideline of Silva and Neiva [1]. Inspired by [2], a few research tools were used for organizing and searching.

### Tools
- [Cadima](https://www.cadima.info/index.php), a tool for conducting a systematic literature review [3], [4]
    - Note: if you would like to get more insight in the project I did set up and how I classified which paper, it is possible to create your own account (for free) on Cadima and then I can add you as a member of my project
- [Publish or Perish](https://harzing.com/resources/publish-or-perish), a tool simplifying searching for literature [5] which I used for Scopus and Google Scholar
- [ResearchRabbit](https://www.researchrabbit.ai/), a tool showing connections between a set of papers and helping to find fitting others
    - Note: There is a Zotero Integration which can be very helpful if you use the Zotero online library
- [Zotero](https://www.zotero.org/) for organizing literature
 
### Literature
[1]	R. Silva and F. Neiva, Systematic Literature Review in Computer Science - A Practical Guide. 2016. doi: 10.13140/RG.2.2.35453.87524.

[2]	J. Pearce, ‘How to Perform a Literature Review with Free and Open Source Software’, Practical Assessment, Research and Evaluation, vol. 23, pp. 1–13, May 2018.

[3] C. Kohl et al., ‘Correction to: Online tools supporting the conduct and reporting of systematic reviews and systematic maps: a case study on CADIMA and review of existing tools’, Environmental Evidence, vol. 7, no. 1, p. 12, Mar. 2018, doi: 10.1186/s13750-018-0124-4.

[4] C. Kohl et al., ‘Online tools supporting the conduct and reporting of systematic reviews and systematic maps: a case study on CADIMA and review of existing tools’, Environmental Evidence, vol. 7, no. 1, p. 8, Feb. 2018, doi: 10.1186/s13750-018-0115-5.

[5] A.W. Harzing, ‘Publish or Perish’. 2007.  Available: [Online](https://harzing.com/resources/publish-or-perish)


## Research Question, Design and Search Strings

### Research Question of the LR
How sustainable is producing different goods in vertical farming in comparison to open-field farming in the same climate zone as Germany (assessed in life cycle assessments to measure the environmental impact)?

### Research Design for LR search
- Life cycle assessments (LCAs) are preferred to answer the question of environmental sustainability in the research design, however, social and economic sustainability will be considered as well. Therefore a broad definition of sustainability in the search strings is needed
- Since there is not enough data for Germany, data from the same climate zone as Germany is considered (for more detail, see [Köppen-Geiger Climate classification](https://www.gloh2o.org/koppen/))
- The term "open-field farming" is sometimes also specified as "conventional farming" or other versions. However, in English, for only the term "farming" there are to many results that do not fit the research design. In German, the term "Landwirtschaft" is fitting.
- The search was limited to papers published in or later than 2017
- Plant Factory is found to be a term mostly used in asian papers and therefore included in the English search string

### Search Strings
- English: ("Life Cycle Assessment" OR Sustainability OR Sustainable) AND ("Conventional farming“ OR "organic farming" OR "open-field farming") AND ("Vertical Farming" OR "Vertical Farm" OR "Plant Factory")
- German: (Nachhaltigkeit OR Nachhaltig) AND Landwirtschaft AND ("Vertical farming" OR "Vertical Farm")

      
## Search Engine Results

### Manually added paper
Paper were added manually in three ways:
1. [OpenAgrar](https://www.openagrar.de/content/index.xml) is a joint repository of different research institutes and others in the scope of the Federal Ministry of Food and Agriculture: 10 papers from OpenAgrar found to match the title screening criteria were added to Cadima
2. [Umweltbundesamt](https://www.umweltbundesamt.de/) was checked, but papers matching the title screening criteria were already found in the Cadima database of matched searches
3. Papers found manually and through ResearchRabbit matching the [inclusion and exclusion criteria](#Inclusion-and-exlusion-criteria) were added in the process

### Results
1. English search string (execution 24.08.2023)
   
| Search Engine  | Number of results | 
|:---------:|:---------:|
| [Google Scholar](https://scholar.google.com/)      | 1000     |
| [Scopus](https://www.scopus.com/home.uri)    | 15    |
| [ScienceDirect](https://www.sciencedirect.com/)      | 118     |
| [IEEE Xplore](https://ieeexplore.ieee.org/Xplore/home.jsp)      | 1     |

Note: Google scholar results were limited to 1000 by the tool Publish or Perish, the results used to be 1760

2. German search string (execution 12.09.2023)
   
| Search Engine  | Number of results | 
|:---------:|:---------:|
| [Google Scholar](https://scholar.google.com/)      | 191     |
| [Scopus](https://www.scopus.com/home.uri)    | 0    |
| [ScienceDirect](https://www.sciencedirect.com/)      | 0     |
| [IEEE Xplore](https://ieeexplore.ieee.org/Xplore/home.jsp)      | 0     |

3. In Total
   
| Search Engine  | Number of results | 
|:---------:|:---------:|
| [Google Scholar](https://scholar.google.com/)      | 1191     |
| [Scopus](https://www.scopus.com/home.uri)    | 15    |
| [ScienceDirect](https://www.sciencedirect.com/)      | 118     |
| [IEEE Xplore](https://ieeexplore.ieee.org/Xplore/home.jsp)      | 1     |
| [OpenAgrar](https://www.openagrar.de/content/index.xml)     | 10     |
| Manually added    | 7     |

Note: The manually added papers were already checked to match the [fulltext inclusion or exclusion criteria](#Inclusion-and-exlusion-criteria) and added in Cadima

## Cadima work flow
Cadima is helpful to sort papers for a systematic literature review. If you want to have a closer look how Cadima is structured, you can find a trial version [here](https://test.cadima.info/index.php/area/evidenceSynthesisDatabase).

After creating a project matching your research design, in this case a systematic literature review, the next steps are:

1. Upload results from search engine search
2. Match searches and delete Duplicates. Cadima offers a duplicate deletion function where you can double-check what will be deleted
3. Define [Inclusion and exclusion criteria](#Inclusion-and-exlusion-criteria). You can first do a consistency check if wanted to check whether your defined criteria should be final. In this case, criteria for title screening and abstract and criteria for fulltext screening were defined.
4. Apply the criteria
- first title screening
- then with papers left (132, see title_screening_outcome.xlsx) the abstract screening
- then with papers left (57, see Cadima_abstract_screening.csv) the fulltext screening


### Inclusion and exlusion criteria
For some criteria, only the title or even the abstract can not show whether the paper actually fulfills the criteria, therefore the criteria in the fulltext screening are the same as in title and abstract screening with the mentioned criteria added.

1. Title and Abstract screening
- The language should be either German or English
- The paper should deal with vertical farming matching a pre-set definition
- Year of study >= 2017
- The paper should deal with LCA or sustainability assessment matching a pre-set definition
- The paper should deal with open-field farming matching a pre-set definition
- The data needs to be conducted in a climate zone similar to the German climate zone 

2. Fulltext screening
- Paper available open-access or through Uni Göttingen

