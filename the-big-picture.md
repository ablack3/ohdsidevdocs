---
description: The highest level view of the officially supported OHDSI software stack
---

# The Big Picture

To support OHDSI's mission&#x20;

_To improve health by empowering a community to collaboratively generate the evidence that promotes better health decisions and better care._

OHDSI officially supported software is a system designed to facilitate

* Research study/analysis design
* Execution of an analysis on one or more databases in the OMOP Common Data Model format
* Dissemination and interpretation of the analysis results
* Transparency and reproducibility of the process of evidence generation.

To accomplish the process of evidence generation OHDSI Software Generation System includes **Applications** and **Artifacts**.

An Application is a software tool that is developed and maintained by the OHDSI Developers while an Artifact is a static set of files that could include code, json, data that are produced and consumed by Applications or humans. The distinction between Applications and Artifacts is important because the primary goal of developers is to improve and maintain the Applications that assist in the creation of Artifacts. Artifacts can be versioned but are created but are considered static objects that do not necessarily need to be maintained or require development efforts.



## Applications

* WhiteRabbit/RabbitInAHat (java)
* Atlas/WebAPI (java, javascript)
* Hades (R, java)
* data.ohdsi.org

## Artifacts

* Cohort specification (json)
* Analysis specification (json)
* Study package (R, SQL)
* Study results (csv)
* R/Shiny results viewer

## Technologies

The technologies used in OHDSI Software include&#x20;

* Java
* Javascript
* R
* SQL
* Maven for building Java apps
* Docker

