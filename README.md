## XML-based Clinical and Experimental Data Exchange 

The XCEDE schema provides an extensive metadata hierarchy for describing and documenting research and clinical studies. The schema organizes information into five general hierarchical levels: a complete project; studies within a project; subjects involved in the studies; visits for each of the subjects; the full description of the subject's participation during each visit

Each of these sub-schemas is composed of information relevant to that aspect of an experiment and can be stored in separate XML files or spliced into one large file allowing for the XML data to be stored in a hierarchical directory structure along with the primary data. Each sub-schema also allows for the storage of data provenance information allowing for a traceable record of processing and/or changes to the underlying data. Additionally, the sub-schemas contain support for derived statistical data in the form of human imaging activation maps and simple statistical value lists.

XCEDE was originally designed in the context of neuroimaging studies and complements the Biomedical Informatics Research Network (BIRN) Human Imaging Database, an extensible database and intuitive web-based user interface for the management, discovery, retrieval, and analysis of clinical and brain imaging data. This close coupling allows for an interchangeable source-sink relationship between the database and the XML files, which can be used for the import/export of data to/from the database, the standardized transport and interchange of experimental data, the local storage of experimental information within data collections, and human and machine readable description of the actual data.

#### Latest release
* XCEDE 2.0: [schema](https://github.com/incf-nidash/XCEDE/blob/master/xcede-2.0-core.xsd) 

#### User Resources
* [XCEDE Manual](https://github.com/incf-nidash/XCEDE/blob/master/manual/manual_full.pdf)

#### Developer Resources (build applications using NIDM)
* [Schema Documentation](https://github.com/incf-nidash/XCEDE/blob/master/documentation/xcede-2.0-core.xsd.html)
* [Examples](https://github.com/incf-nidash/XCEDE/tree/master/examples)
* [Tools](https://github.com/incf-nidash/XCEDE/tree/master/tools)

