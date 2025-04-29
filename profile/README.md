# ASAM open source platform
[![tp header](/doc/img/Asam_Background_1.jpg)](http://www.asam.net/)

ASAM e.V. (Association for Standardization of Automation and Measuring Systems) is a not-for-profit organization that promotes standardization of tool chains in automotive development and testing. Our members are international car manufacturers, suppliers, tool vendors, engineering service providers, and research institutes. ASAM standards are developed by experts from our member companies and are based on real use cases. ASAM is the legal owner of these standards and is responsible for their distribution and marketing.

ASAM provides support in connecting members, coordinating work groups, and developing, releasing, and maintaining standards. Our active community includes more than 400 member organizations around the world. These members ensure that ideas with market relevance will progress into standards and that these standards are used worldwide. 

The standards developed at ASAM span a wide range of use cases in automotive development, test, and Validation. They define file formats, data models, protocols, and interfaces. All ASAM standards aim to enable easy exchange of data and tools within and across tool chains. They are applied worldwide.

If you want to contribute in one of our open source projects, please read the [Contributing guidelines](https://github.com/asam-ev/.github/blob/main/profile/CONTRIBUTING.md) 

## ASAM Projects


| ASAM QC FRAMEWORK            | ASAM OSI              | ASAM OpenMATERIAL         | ASAM ODS |
|:----------------------------:|:---------------------:|:------------------------:|:------------------------:|
| [<img src="/doc/img/QC_official.png" width="100" />](https://github.com/asam-ev/qc-framework) | [<img src="/doc/img/OSI.jpg" width="100" />](https://github.com/OpenSimulationInterface/open-simulation-interface) | [<img src="/doc/img/OpenMATERIAL_official.jfif" width="100" />](https://github.com/asam-ev/OpenMATERIAL) | [<img src="/doc/img/ODS_official.jfif" width="100" />](https://github.com/asam-ev/ASAM-ODS-Interfaces) |

Click below in the quick-links to the ASAM projects and their repositories:
- [ASAM Quality Checker Framework](#asam-quality-checker-framework)
- [ASAM OSI® (Open Simulation Interface)](#asam-osi-open-simulation-interface)
- [ASAM OpenMATERIAL® 3D](#asam-openmaterial-3d)
- [ASAM ODS (Open Data Services)](#asam-ods-open-data-services)

Further standardization projects can be found on our webpage [www.asam.net](https://www.asam.net/active-projects/projects/) or directly on:
- [Proposals & enrollments](https://www.asam.net/active-projects/proposals/)
- [Active projects](https://www.asam.net/active-projects/projects/ )

Quick-links to other resources and tools:
- [Tools and helper scripts](#tools-and-helper-scripts)
- [ASAM Project Guide](#asam-project-guide)
- [ASAM GitLab](#asam-gitLab)

### ASAM Quality Checker Framework

A quality checker framework that allows the configuration, execution and reporting of checks. Checks are based on rules defined by ASAM standards that allow users to validate conformity of files and implementations against ASAM standards.

- [qc-framework](https://github.com/asam-ev/qc-framework) - The main repository for the ASAM Quality Checker formed by a collection of C++ and Python components responsible for running the checker bundles.
- [qc-baselib-py](https://github.com/asam-ev/qc-baselib-py) - The Python Base library repository implements a Python interface for interacting with the configuration files and the results files from the ASAM Quality Checker framework.
- [qc-opendrive](https://github.com/asam-ev/qc-opendrive) - The official ASAM checker bundle for ASAM OpenDRIVE.
- [qc-openscenarioxml](https://github.com/asam-ev/qc-openscenarioxml) - The official ASAM checker bundle for ASAM OpenSCENARIO XML.
- [qc-otx](https://github.com/asam-ev/qc-otx) - A checker bundle implementing a sample of rules for the standard ASAM OTX Extensions (Open Test sequence eXchange). Note that this is not to be considered an exhaustive checker bundle.

### ASAM OSI® (Open Simulation Interface)
ASAM OSI® (Open Simulation Interface) is a specification for interfaces between models and components of a distributed simulation. OSI is strongly focused on the environmental perception of automated driving functions.

- [Documentation](https://opensimulationinterface.github.io/osi-antora-generator/asamosi/latest/specification/index.html) - The ASAM OSI specification
- [Class Reference](https://opensimulationinterface.github.io/osi-antora-generator/asamosi/latest/gen/annotated.html)
- [open-simulation-interface](https://github.com/OpenSimulationInterface/open-simulation-interface) - The main repository for the standard.
- [osi-sensor-model-packaging](https://github.com/OpenSimulationInterface/osi-sensor-model-packaging) - OSI Sensor Model Packaging specifies ways in which models (like e.g. environmental effect models, sensor models and logical models) using the Open Simulation Interface (OSI) are to be packaged for their use in simulation environments using [FMI 2.0](https://report.asam.net/fmi-functional-mock-up-interface).
- [osi-validation](https://github.com/OpenSimulationInterface/osi-validation) - The OSI Validator checks the compliance of OSI messages with predefined rules.
- [osi-documentation](https://github.com/OpenSimulationInterface/osi-documentation) - Hosts the AsciiDoc-based part of the documentation. It contains general parts of the content and a CI-pipeline that renders the document with Asciidoctor and deploys it to the [github-pages](https://github.com/OpenSimulationInterface/osi-documentation/deployments/github-pages) of this repo.
- [osi-antora-generator](https://github.com/OpenSimulationInterface/osi-antora-generator) - The pipeline of this repository is responsible for creating the combined and versioned Antora output for ASAM OSI. It also pushes it to the respective GitHub pages for hosting.

### ASAM OpenMATERIAL® 3D

There is a growing need to accurately represent the real world in simulation, a so-called digital twin, particularly as the need for physical sensor simulation grows. However, for this to be feasible, physically correct modelling of material properties is fundamental. To ensure consistent testing across platforms and by different stakeholders, 3D models and corresponding material properties need to be unambiguously exchangeable. It is proposed to develop a standardized format for material properties.   

- [OpenMATERIAL® 3D](https://github.com/asam-ev/OpenMATERIAL)
- [OpenMATERIAL®_old](https://github.com/asam-ev/OpenMATERIAL_old)

### ASAM ODS (Open Data Services)

The [ASAM ODS (Open Data Services)](https://www.asam.net/standards/detail/ods/wiki/) standard defines a set of services and protocols for the management and exchange of measurement data in the automotive industry. ASAM ODS is only available for ASAM members. The files provided here serve as a convenience for developers working with ODS services and are utilized by various pipelines to facilitate communication with ODS services.

- [asam-ods-interfaces](https://github.com/asam-ev/ASAM-ODS-Interfaces) - The .proto files in this repository define the Protocol Buffer schemas used to interface with these ODS services.

## Tools and helper scripts

Often ASAM members or ASAM projects may develop scripts or small tools that support the use of one or more of ASAM's standards. To increase visibility for these, ASAM hosts them on it's repositories.

- [Wireshark plugin for ASAM iLinkRT](https://github.com/asam-ev/Wireshark-iLinkRT) - This enables the popular network protocol analyzer [Wireshark](https://www.wireshark.org/) to dissect ASAM iLinkRT frames. 

## ASAM Project Guide
- [ASAM Project Guide](https://asam-ev.github.io/asam-project-guide/asamprojectguide/latest/index.html)
- [Source](https://github.com/asam-ev/asam-project-guide-content)

## ASAM GitLab
Hosts many other ASAM projects and standards.

https://code.asam.net
