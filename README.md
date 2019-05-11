# CD2H Next Generation Data Sharing and Analytics Core

# Leadership
*Director: Christpher G Chute (Johns Hopkins University)

*Co-Director: Peter Robinson (The Jackson Laboratory)
 
# Other Core Members
Don't edit this - the RPPR generator populates this section

# Year 3 Budget
Don't edit this - the RPPR generator populates this section

# Specific Aim

Harmonize the data ecosystem. An improved data ecosystem will enhance and extend existing work being performed on the NCATS Data Translator system, which integrates clinical and translational data at scale for mechanistic discovery, as well as other emergent systems such as the NIH Commons. We will apply our strengths and existing activities to make data FAIR-TLC: Findable, Accessible, Interoperable, and Reusable, as well as Traceable, Licensable, and Connected. We will assist contributors and users to develop and apply data standards, Common Data Elements (CDEs), and other commonly utilized data models such as FHIR and OHDSI. We will extend and supplement infrastructure, training, and collaborative environments to enable data to be shared openly, so that groups can collaborate on its harmonization based on specific needs or standards. The data ecosystem will provision CTSA-wide quality assurance reports and data quality assessment, as well as gold-standard datasets and synthetic clinical data sets. Fundamentally, we aim to develop an open-science ethos and unite CTSA community data sharing with broader global efforts.

# Research Strategy
This core has three projects (see current projects below):
1. Data harmonization and federated query.   This project focuses on common data models, shared syntax, and federated query.
2. Healthcare Open Terminology FHIR (hot-fhir).  This project focuses upon shared semantics, mappings, and bindings to data models.
3. EHRs to HPO.  This project focuses on methods and technologies that enable CTSA hubs to map content from EHRs onto Human Phenotype Ontology (HPO) concepts.
## Significance
A core aspiration of the CTSA program is to enable all hub to operate as a synergistic network, pooling data and knowledge, expanding the scope of observational and interventional trials, and dramatically reducing the time and cost for biomedical discovery and evaluation.  These goals have as prerequisites the projects comprising the Next-generation data sharing core.  In particular, common syntax (models), semantics (terminology servers), and resources enabling interoperability are critical path requirements for this vision.
## Innovation
Historically, common data models for research have invoked large-scale relational data models which prematurely bind data onto a rigid and brittle data structure.  These rigid models do not always accommodate "orthogonal" queries, which often arise in translational research.  The core innovation is to leverage existing and emerging clinical data standards (HL7 FHIR) which align closely with data at its source in EHRS, thus minimizing the cost and effort of data transformation.  Furthermore, we can instantiate a next-generation data model that harmonizes data at the level of a data element, rather than a rigid large-scale relational model. 
### Justification and Feasibility
The work is justified, as CTSA hubs confront too many incompatible traditional “common data models (CDMs).”  It is becoming tedious and resource consuming for CTSA hubs to maintain such redundancies.  The vision is that a canonical FHIR-based repository can computationally generate CDM content with minimal overhead.  As second major justification is the size and demonstrated productivity of the clinical FHIR resource authoring community.  The research community cannot marshal the scale and depth of resources being focused on creating FHIR resources for new and novel datatypes, such as wearables or OMICs, clearly relevant to the translational research agenda. 

The feasibility is evident in the recent proliferation of high-performance FHIR servers, from Microsoft, Google, and the Cerner Bunsen project.  These complement the traditional development servers such as HAPI FHIR.  All of these servers are available as open-source code repositories, and in some cases as well-supported and optimized cloud services.
### Summary of existing system and findings
See CD2H Labs for our latest demonstration platforms.
## Approach
CD2H does not intend to create yet another FHIR data or terminology server.  We will evaluate existing server offerings and establish their suitability as canonical hubs for federated query across CTSA.

We also recognize that FHIR resources are deliberately underspecified.  We propose to leverage the ontology and binding work among the traditional data models, in concert with the US Core FHIR Implementation Guide.
### Progress Report
Progress on each project is represented in milestones and their completion.
### Current Projects
* [Data Harmonization](https://github.com/data2health/data-harmonization) ([RPPR](https://github.com/data2health/data-harmonization/blob/master/RPPR.md))
* [EHR2HPO](https://github.com/data2health/ehr2HPO.prj) ([RPPR](https://github.com/data2health/ehr2HPO.prj/blob/master/RPPR.md))
* [Healthcare Open Terminology FHIR (hot-fhir) server](https://github.com/data2health/hot-fhir-projects) ([RPPR](https://github.com/data2health/hot-fhir-projects/blob/master/RPPR.md))




