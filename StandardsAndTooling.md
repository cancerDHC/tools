# Standards and Tooling

The CCDH aims to provide relevant standards and tooling for the CRDC community. Below are curated lists of relevant standards and tools for use in data harmonization, aggregation, modeling and other use cases. Please [contact us](centerforcancerdh@gmail.com) or join our [office hours](https://ccdhportaldev.pedscommons.org/support) for any questions related to ontologies, standards or tooling.

## Standards
Ontology/Terminology |	Abbreviation	| Description
-- | -- | --
[AJCC staging system](https://www.cancerstaging.org/)	| AJCC | A classification system developed by the American Joint Committee on Cancer for describing the extent of disease progression in cancer patients
[Clinical Data Interchange Standards Consortium](https://www.cdisc.org/)	| CDISC	| CDISC develops and advances data standards to transform incompatible formats, inconsistent methodologies, and diverse perspectives into a powerful framework for generating clinical research data that is as accessible as it is illuminating.
[Cancer Data Standards Registry and Repository](https://datascience.cancer.gov/resources/metadata)	|CaDSR | The caDSR and its associated applications help the research community manage and use data standards by providing the shared standards in a variety of human and machine readable contexts.
[Common Terminology Criteria for Adverse Events](http://bioportal.bioontology.org/ontologies/CTCAE) | CTCAE	| CTCAE is widely accepted throughout the oncology community as the standard classification and severity grading scale for adverse events in cancer therapy clinical trials and other oncology settings.
[Digital Imaging and Communications in Medicine](https://www.dicomstandard.org/) | DICOM	| DICOM® is the international standard for medical images and related information. It defines the formats for medical images that can be exchanged with the data and quality necessary for clinical use.
[eagle-i Resource Ontology](http://bioportal.bioontology.org/ontologies/ERO) | ERO | ERO models research resources such instruments. protocols, reagents, animal models and biospecimens. It was developed in the context of the eagle-i project.
[Environmental and Exposures Ontology](https://github.com/EnvironmentOntology/environmental-exposure-ontology) |ECTO |The purpose of ECTO is to create compositional classes that assemble existing OBO ontologies such as ExO, CHEBI and ENVO to make ready-made precomposed classes for use in describing:
[Genotype Ontology](http://bioportal.bioontology.org/ontologies/GENO) | GENO | An integrated ontology for representing the genetic variations described in genotypes, and their causal relationships to phenotype and diseases.
[Human Phenotype Ontology](https://hpo.jax.org/) | HPO | HPO provides a standardized vocabulary of phenotypic abnormalities encountered in human disease. Each term in the HPO describes a phenotypic abnormality
[Image biomarker standardisation initiative](https://arxiv.org/abs/1612.07003) | IBSI | IBSI is an independent international collaboration which works towards standardizing the extraction of image biomarkers from acquired imaging for the purpose of high-throughput quantitative image analysis (radiomics). 
[International Statistical Classification of Diseases and Related Health Problems](https://www.who.int/classifications/icd/en/) | ICD-9, ICD-10, ICD-11 | A medical classification list by the World Health Organization (WHO) that contains codes for diseases, signs and symptoms, abnormal findings, complaints, social circumstances, and external causes of injury or diseases.
[International Classification of Diseases for Oncology](https://www.who.int/classifications/icd/adaptations/oncology/en/) |ICD-O | A domain-specific extension of the International Statistical Classification of Diseases and Related Health Problems for tumor diseases.
[Integrated Semantic Framework](http://bioportal.bioontology.org/ontologies/VIVO-ISF)	| ISF	| The VIVO-ISF ontology provide a set of types (classes) and relationships (properties) to represent researchers and the full context in which they work.
[LOINC](http://bioportal.bioontology.org/ontologies/LOINC) | LOINC	| The international standard for identifying health measurements, observations, and documents.
[Medical Dictionary for Regulatory Activities](http://bioportal.bioontology.org/ontologies/MEDDRA) | MEDDRA	| MedDRA is an international medical terminology with an emphasis on use for data entry, retrieval, analysis, and display.
[Mondo Disease Ontology](https://mondo.monarchinitiative.org/)	| Mondo	| Mondo is a disease ontology that represents disease terminology across species. It is a semi-automatically constructed ontology that merges in multiple disease resources to yield a coherent merged ontology.
[NCBI Taxonomy](http://bioportal.bioontology.org/ontologies/NCBITAXON)	| NCBI Taxon	| The NCBI Taxonomy Database is a curated classification and nomenclature for all of the organisms in the public sequence databases.
[National Cancer Institute Thesaurus](http://bioportal.bioontology.org/ontologies/NCIT)	| NCIT	| A vocabulary for clinical care, translational and basic research, and public information and administrative activities.
[Ontology of Biomedical Investigations](http://bioportal.bioontology.org/ontologies/OBI)	| OBI	| OBI is an ontology of investigations, the protocols and instrumentation used, the material used, the data generated and the types of analysis performed on it.
[Protein Ontology](http://bioportal.bioontology.org/ontologies/PR)	| PRO	| PRO provides an ontological representation of protein-related entities by explicitly defining them and showing the relationships between them.
[Uber Anatomy Ontology](http://bioportal.bioontology.org/ontologies/UBERON)	| Uberon	| Uberon is an integrated cross-species anatomy ontology representing a variety of entities classified according to traditional anatomical criteria such as structure, function and developmental lineage. 
[UniProt](https://www.uniprot.org/)	| | The mission of UniProt is to provide the scientific community with a comprehensive, high-quality and freely accessible resource of protein sequence and functional information.

## Tooling
Type | Resource Name	| Description
-- | -- | --
API | [Simple Terminology  Server]() | A simple RESTful API for validating data values against enumerated value domains.
Data cleaning tool | [OpenRefine]()	| An open-source tool for cleaning up tabular data.
Data harmonization tool | [Ptolemy.V]()	| A tool for harmonizing datasets to valuesets, designed for use with the caDSR. Currently in a closed pilot.
Modeling language | [BiolinkML]()	| BiolinkML is a general purpose modeling language following object-oriented and ontological principles.
Modeling language | [Bento Graph Model Description Framework (BentoMDF)]() | A YAML-based model description format for describing a property graph model.
Modeling language | [BRIDG]() | The goal of the Biomedical Research Integrated Domain Group (BRIDG) Model is to produce a shared view of the dynamic and static semantics for the domain of basic, pre-clinical, clinical, and translational research and its associated regulatory artifacts.
Repository | [Cancer Data Standards Registry and Repository (caDSR)]()	| A repository of Common Data Elements (CDEs), which are descriptions of fields used in cancer-related datasets.
Repository | [NCI Thesaurus]()	| A repository of concepts relating to cancer managed by the National Cancer Institute.
Repository | [NCI Metathesaurus]()	| A repository of concepts relating to cancer from over a hundred sources, including the NCI Thesaurus and SNOMED, managed by the National Cancer Institute.
Repository | [BioPortal]()	| A Web-based application for searching, sharing, visualizing and analyzing a large repository of biomedical ontologies, terminologies, and ontology-based annotations.
Repository | [Ontology Lookup Service (OLS)]() | The Ontology Lookup Service (OLS) is a repository for biomedical ontologies that aims to provide a single point of access to the latest ontology versions. You can browse the ontologies through the website as well as programmatically via the OLS API.
Repository | [Ontobee]() | A linked data server designed for ontologies. Ontobee is aimed to facilitate ontology data sharing, visualization, query, integration, and analysis.
Repository | [Unified Medical Language System (UMLS)]() | The UMLS integrates and distributes key terminology, classification and coding standards, and associated resources to promote creation of more effective and interoperable biomedical information systems and services, including electronic health records.
Standard | [CTS2/LexEVS]()	| The Common Terminology Services 2 (CTS2) Standard is an API specification jointly developed by HL7 and the Object Management Group (OMG) for the distribution and federation of terminological resources, including code sets, classification systems, ontologies, value sets and mappings.
Standard | [Fast Healthcare Interoperability Resources (FHIR)]()	| The FHIR Specification is a standard for exchanging healthcare information.
Standard | [FHIR Terminology]()	| The FHIR Terminology module provides an overview and guide to the FHIR resources, operations, coded data types and externally-defined standard and FHIR-defined terminologies.
Standard | [Shape Expressions (ShEx)]()	| A standard for describing and validating RDF shapes.
Standard | [Shapes Constraint Language (SHACL)]()	| A standard for describing, documenting and validating RDF shapes.
Standard | [Portable Format for Biomedical Data (PFB)]()	| An Apache Avro-based format for storing biomedical data side-by-side with schema and semantic metadata. Other documentation resources: [CBIIT Bento Meta DB Readme](https://github.com/CBIIT/bento-meta/tree/feat-pfb/python/bento_meta/pfb#portable-format-for-bioinformatics).
Metadata Annotator | [CEDAR Template Builder]()	| A JSON-based format for describing metadata forms as well as a website for creating and filling in such forms.
Metadata Annotator | [SciGraph Annotator]()	| A software tool for identifying terms from one or more ontologies in an input document.

