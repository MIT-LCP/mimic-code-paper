<!--

How will your work make others in the field think differently and move the field forward?
How does your work relate to the current literature on the topic?
Who do you consider to be the most relevant audience for this work?
Have you made clear in the letter what the work has and has not achieved?

-->

Dear Editors,

We would like to submit our paper, entitled "The MIMIC Code Repository: enabling reproducibility in critical care", for publication in the Special Focus Issue on Biomedical Data Science: Sharing Digital Objects to Accelerate Discoveries and Ensure Reproducibility of Results. The paper describes a collection of software that we believe is both an important research contribution to accelerate progress in the field of secondary analysis of electronic health records, as well as a strategy to improve research reproducibility.

Over the past decade our team, the MIT Laboratory for Computational Physiology, has gained expertise in integrating and analyzing high-resolution electronic health records from critical care patients admitted to the Beth Israel Deaconess Medical Center in Boston, USA. A de-identified version of this data is shared with thousands of researchers around the world as a database known as the Medical Information Mart for Intensive Care (MIMIC). Using MIMIC, researchers have discovered novel relationships between patient physiology and treatments, built decision support tools, and improved techniques for handling heterogenous medical data.

There are challenges in secondary analysis of routinely collected health data, in particular because the data is collected for routine care and not specifically for research. Learning from the data is complex, requiring close collaboration with hospital staff including nurses, doctors, respiratory therapists and so on. Concepts which are readily apparent at the bed side, such as the use of mechanical ventilation to support breathing, must be carefully inferred from concurrently documented surrogate settings. The same holds for dialysis, severity of illness, intravenous medication usage, and many more concepts key to clinical research. As a consequence of these challenges, many researchers must spend a large amount of effort searching for data prior to attempting any methodological research. At best this is wasted effort, but at worst the definition of these concepts can differ from researcher to researcher making studies incomparable.

To address this gap in the field, we have created open source software that defines a large number of core concepts. Developing these concepts required extensive technical and clinical expertise, but future use is designed to be as simple as possible. We have also created a number of tools which facilitate research on MIMIC such as build scripts for initially installing the database, tutorials to introduce new users, and executable documents to facilitate interpretation of code. One executable document in the repository entirely reproduces a previously published clinical study and could be used as a framework for creating future reproducible studies.

We believe this work will serve as a foundation for a large body of future work in secondary analysis of electronic health records, and we look forward to the opportunity to publish in JAMIA.

Kind Regards,

Alistair Johnson, on behalf of the authors
