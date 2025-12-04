# dmp_guidelines_for-_copilot
Follow these guidelines to answer the Data Management Plan questions that the user will ask. This document will contain the question-and-guideline pair to help refine the DMP. The following are the Questions and their corresponding guidelines: 
 
Topic: Project Outputs 

Q. What data will you collect, and what research outputs will you create, derive, link to, acquire and/or record? 
Guideline: Following the definition from DataCite, research outputs cover a wide range of resources produced throughout the research project, including for example: datasets, software, code, samples, theses, images, video, graphs, models, publications, etc. 

 

Q. Do your research outputs contain Essential Ocean Variables (EOVs) or Essential Climate Variable (ECVs)? 
Guideline: For ingestion into CIOOS, it is preferred that your research output contains at least one EOV. A list of the EOVs supported by CIOOS can be found here (https://cioos.ca/essential-ocean-variables/). The Global Ocean Observing System (GOOS) Expert Panels have identified the EOVs based on their impact and feasibility, and a list of EOVs can be found here (https://www.goosocean.org/index.php?option=com_content&view=article&id=283&Itemid=441), and a list of ECVs here (https://gcos.wmo.int/en/essential-climate-variables/table). Please note that there is overlap between the EOVs and the ECVs, and both contain sub-variables and derived products as well in their specification sheets. 

 

Q. What file formats will your research outputs be in? Will these formats allow for data re-use, sharing and long-term access to the data? 
Guideline: File formats preferred for CIOOS are non-proprietary (open file) formats, e.g. .csv, .netCDF, tab-delimited, GeoTiff, .kmz, etc. Additional information on proprietary vs open file formats can be found from the UBC Library (https://ubc-library-rc.github.io/rdm/content/02_file_formats.html). Proprietary file formats requiring specialized software or hardware to use are not recommended, but may be necessary for certain data collection or analysis methods. 

 

Topic: Documentation and Metadata 

Q. What documentation will be needed for the research outputs to be read and interpreted correctly in the future? Describe how the documentation is captured or updated consistently throughout the active phase of the project. 
Guideline: Good documentation includes referenced supplemental material and information about the study and other contextual information required to make the research outputs (re)usable by others. Development of a README/ (https://ubc-library-rc.github.io/rdm/content/03_create_readme.html ) Codebook throughout the project lifecycle can include elements such as: description of data capture and collection methods (e.g. SOPs, lab procedures, instruments), processing steps, description of data granularity (e.g. taxa were identified to the lowest taxonomic rank practical, spatial resolution), variable definitions (e.g. through a data dictionary), units of measurement, assumptions and limitations to the study, and types of analyses performed (for each sample type).  

For documenting model data, please provide a description of the model planned and (references to) intended input data sources. If applicable and available, consider providing code, tools and/or links to existing publications describing the intended model. 

 

Q. If you are using a data or metadata standard and/or tools to document and describe your data, please list here. 
Guideline: For CIOOS, the most relevant schemas are ISO-19115 (metadata), Climate and Forecast (CF) Conventions (often used for physical or biogeochemical oceanography data) and the Darwin Core standard (often used for marine biological occurrence data). Dataset documentation provided in one of these standard, machine-readable, openly-accessible formats enables effective exchange of information between users and systems.  

Dataset documentation may also include a controlled vocabulary, which is a standardized list of terminology for describing information. Examples of controlled vocabularies include the NERC vocabulary server or NASA’s Global Change Master Directory (GCMD) Keywords. 

 

Q. What processes currently exist to continuously improve data quality (reviews, quality flags, testing, verification, etc) throughout and beyond the active phase of the project? Who has the executive responsibility for the quality of the data? 
Guideline: Some common issues found with data are e.g. duplicates, missing values, spikes or outliers in the data, incorrect format type (character, numeric). Please describe the processes, feedback mechanisms, tools or software in place to identify these issues and continuously improve data quality throughout and beyond the active phase of your project (e.g. QARTOD, etc.). If applicable, please link to scripts used to clean the data. 

 

Topic: Storage and Backup 

Q. What are the anticipated storage requirements throughout the active phase of the project, in terms of storage space (in megabytes, gigabytes, terabytes, etc.) and the length of time you will be storing it? 
Guideline: Storage-space estimates should take into account requirements for file versioning, backups, and growth over time. If you are collecting data over a long period (e.g. several months or years), your data storage and backup strategy should accommodate data growth throughout the active project. 

 

Q. How and where will your research outputs be stored and backed up during the active phase of the research project? 
Guideline: The risk of losing data due to human error, natural disasters, or other mishaps should be considered, an option for mitigating this can include, but is not limited to, the 3-2-1 backup rule:  

Have at least three copies of your data. 
Store the copies on two different media.  
Keep one backup copy offsite.  
Further information on storage and backup practice is available from the Digital Research Alliance of Canada. 

 

Q. What collaboration environment and procedures will the research team use to access, modify and contribute data or other research outputs throughout the active phase of the project? How will you organize, name and version-control files in a (shared) directory? 
Guideline: An ideal collaborative environment is one that facilitates cooperation and ensures data security, yet is able to be adopted by project participants with minimal training. It is important to keep track of different copies or versions of files, files held in different formats or locations, and information cross-referenced between files. To facilitate tracking of file versions, it is strongly recommended to agree on a collaboration environment (e.g. Google Drive, GitHub, Sharepoint, etc.) to use throughout the active phase of the project, and to describe the hierarchies and naming conventions used when organizing and sharing data files. Logical file structures, informative file and folder naming conventions, clear indications of file versions, etc., all contribute to better use of your data during and after your research project. These practices will help ensure that you and your research team are using the appropriate version of your data, and minimize confusion regarding copies on different computers and/or on different media. For research outputs that are ongoing, please describe how new data is being added (e.g. to minimize duplication, reconciling delayed and real-time data). For examples and to read more about file naming and version control: UBC Library. 

Topic: Preservation 

Q. Where and how long will you deposit or archive your data and supplemental materials (i.e. protocols) for long-term preservation and access at the end of your research project?  
Guideline: Data archiving or preservation is different from data storage. Archiving is the practice of moving data to a long-term data storage system (i.e. repository) where it can be located and retrieved as needed. This decision can be driven by external policies (e.g. funding agencies, journal publishers, etc.). Recommended repositories for CIOOS are the Ocean Biodiversity Information System (OBIS) for biological data, and ERDDAP for physical and geochemical oceanography data. Alternatively, data can be archived in public repositories such as Federated Research Data Repository (FRDR), DRYAD Digital Repository, Zenodo and Open Science FrameworkOpens in a new window. An overview of research data repositories can be found here: https://www.re3data.org/. For protocols, these can be archived on generalist repositories, or more specific repositories such asprotocols.io, the Ocean Best Practice system, or Aquadocs. 

Topic: Sharing and Reuse 

Q. What research outputs will be shared and in what form? (e.g. raw, processed, analyzed, and model). 
Guideline: Raw data are the data directly obtained from the instrument, simulation or survey. Processed data result from some manipulation of the raw data in order to eliminate errors or outliers, to prepare the data for analysis, to derive new variables, or to de-identify the human participants. Analyzed data are the results of qualitative, statistical, or mathematical analysis of the processed data. They can be presented as graphs, charts or statistical tables. Model data are data products used to simulate real-world conditions to predict a future instance. Consider which data or other research outputs may need to be shared in order to meet institutional or funding requirements, and which may be restricted because of confidentiality/privacy/intellectual property considerations. 

 

Q. Can your data and research outputs be shared with an open license? 
Guideline: For data sharing through CIOOS, it is recommended to apply an open license such as the Creative Commons Attribution 4.0 International (CC BY 4.0), open government licenses (e.g. Open Government Licence - Canada) or a public domain license (e.g. CC0).  

Licenses determine what uses can be made of your data. Funding agencies and/or data repositories may have end-user license requirements in place; if not, they may still be able to guide you in what license to attach. Note that only the intellectual property rights holder(s) can issue a license, so it is crucial to clarify who owns those rights (see Ethics and Legal Compliance). 

 

Q. What steps will be taken to help the research community know that your research outputs exist? 
Guideline: Describe how CIOOS helps meet funder requirements for openly accessible data, and is a community resource. Possibilities include: data registries, metadata catalogues, repositories, indexes, word of mouth, publications, social media. CIOOS recommends each data record to have a unique digital object identifier (DOI). CIOOS RAs can assist with minting of new DOIs, or link to existing DOIs. It is recommended that collaborators and affiliated organizations have persistent identifiers (e.g. ORCID and ROR). 

 

Topic: Responsibilities and Resources 

Q. Who will be responsible for managing this project's research outputs during and after the project? Please list the data management-specific tasks for which project contributors will be responsible. 
Guideline: Your data and research output management plan has identified important data activities in your project. Identify who will be responsible (individuals or organizations) for carrying out these activities. This could also include the time frame associated with these staff responsibilities and any training needed to prepare staff for these duties. 

 

Q. How will responsibilities for managing data activities be handled if substantive changes happen in the personnel overseeing the project's data, including a change of Principal Investigator? 
Guideline: Indicate a succession strategy, or contingency plan, for these research outputs in the event that one or more people responsible for the management of the outputs leaves (e.g. a graduate student leaving after graduation, or a Principal Investigator leaving the project). 

 

Q. What resources will you require to implement the management of your research outputs? What do you estimate the overall cost for this to be? 
Guideline: This estimate should incorporate research outputs management costs incurred during the project as well as those required for the longer-term support for the data after the project is finished. Items to consider in the latter category of expenses include the costs of documenting, curating and providing long-term access to the data. Some funding agencies state explicitly the support that they will provide to meet the cost of preparing data for deposit. This might include technical aspects of data management, training requirements, file storage and backup, and contributions of non-project staff. 

 

Topic: Ethics and Legal Compliance 

Q. Who owns the intellectual property of the research outputs, and how will that person or institution manage legal, ethical, and intellectual property issues? 
Guideline: Include here a description concerning ownership, licensing, and intellectual property rights of the research outputs. Terms of reuse must be clearly stated, in line with the relevant legal and ethical requirements where applicable (e.g., subject consent, permissions, restrictions, etc.).  

Compliance with privacy legislation and laws that may impose content restrictions in the data should be discussed with your institution's privacy officer or research services office. Research Ethics Boards are central to the research process. 

 

Q. Does your project include Indigenous partner involvement, and if so, does it follow the CARE and OCAP Principles? 
Guideline: Consider how your research may impact or benefit local communities in the respective area. Any research involving Indigenous Partners necessitates education about Indigenous Data Sovereignty through the CARE and OCAP Principles. These resources will help non-Indigenous researchers begin to understand the requirements inherent in data collection in collaboration with Indigenous Partners, allowing them to proceed appropriately before, during, and after the project completion. In addition to these resources, the Indigenous community(ies) should be engaged in how to properly support their data sovereignty and CARE Principles. 

 

Q. If your research project includes sensitive or restricted data, how will you ensure intellectual property rights are protected and that sensitive or restricted data is securely managed and accessible only to approved members of the project, during the active phase of the research? 
Guideline: Consider where, how, and to whom sensitive data with acknowledged long-term value should be made available, and how long it should be archived. Cases may include, but are not limited to marine protected areas (MPAs), Indigenous Community data, endangered species, etc. Sensitive and restricted data considerations should be discussed with the appropriate parties (i.e., Indigenous community partners) and data managers, as well as align with funding requirements.  

Outline problems anticipated in sharing data, and possible measures to mitigate these. Problems may include confidentiality, lack of consent agreements, or concerns about Intellectual Property Rights, among others. In some instances, an embargo period may be justified; these may be defined by a funding agency's policy on research data.  

Restrictions can be imposed by limiting physical access to storage devices, by placing data on computers that do not have external network access (i.e. access to the Internet), through password protection, and by encrypting files. Sensitive data should never be shared via email or cloud storage services such as Dropbox. 

 

Q. If applicable, what strategies will you undertake to address secondary uses of sensitive data? 
Guideline: Obtaining the appropriate consent from research participants is an important step in assuring that the data may be shared with researchers outside your project. The consent statement (e.g. an MoU or Research Agreement) may identify certain conditions clarifying the uses of the data (both beyond and throughout the active phase of the project) by other researchers, or whether the data is only available upon request, and who will provide that access. 

 

 
