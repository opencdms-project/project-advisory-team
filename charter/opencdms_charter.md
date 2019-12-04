# Project Charter for the OpenCDMS project

OpenCDMS is a free Reference Open Source Climate Data Management System for atmospheric, hydrological, marine, phenological, air composition and other environmental data with a time-series component. It stores observational data concerning water, weather, hydrology and climate in a secure and flexible manner and enables extracting useful information from the data.

## Climate Data Management System (CDMS) Strategy

A survey from the Commission for climatology (CCl) of the World Meteorological Organization (WMO) revealed that WMO Members operate almost 100 different Climate Data Management Systems (CDMSs), developed in the absence of consistent WMO CDMS specifications. The survey estimated that almost 50% of WMO Members face operational issues with their CDMS and almost 25% of Members do not use an electronic database to manage climate data.

WMO aims to achieve a step-change in addressing capability required to respond to many questions of societal needs for climate information and services; and acting nationally to implement and evolve interoperable and sustainable CDMSs that will address national requirements for climate data, and in addition help in addressing regional and global needs.

WMO Commission for Climatology in April 2018 (Resolution 4) decided:

* To establish a framework that comprises a base collection of technologies, policies and institutional arrangements that facilitate the management of, and access to, consistent climate data, thereby establishing clear governance arrangements around CDMS activities; and also
* To revise the current ways to develop and maintain CDMSs by establishing a coordinated close collaboration of partners involved including pooling resources to develop and maintain a single Reference open-source CDMS based on tested software practices.

See: Commission for Climatology, April 2018, [WMO-No.1216](https://library.wmo.int/doc_num.php?explnum_id=4611), page 12

WMO Congress in June 2019 (Resolution 22) requested:

* To support development of a reference open-source Climate Data Management System (CDMS) for climate and hydrological data management based on tested software practices, which implements the Climate Data Management System Specifications (WMO-No 1131) and the HQ-GDMFC, that can be used as a base for implementation in the National Meteorological and Hydrological Services (NMHSs) of Members and other entities.

See: World Meteorological Congress, June 2019, [WMO-No.1236](https://library.wmo.int/doc_num.php?explnum_id=9827), page 88

## Scope

OpenCDMS is a phased project. OpenCDMS will liaise with current projects within the climate and environmental community such as the Climate Services Toolkit of the Global Framework for Climate Services (GFCS), the WMO Information System and especially its version 2 built on industry-standard cloud computing techniques, the European Copernicus programme and its Climate Change Service.

For OpenCDMS to thrive, it needs to be seen to be agile and managed by consensus among those contributing to its development. The project will follow best-practice for open-source projects.

The OpenCDMS project will include modules providing specific data products to the WMO Information System, but assumes that WIS provides the interface to receive and transmit these products.

The OpenCDMS project will include porting of end-user hydrology and climate applications which are currently operational in precursor systems (Climsoft, MCH, ClidDE, etc) but will not include development of new end-user applications. It is assumed that these will be provided by the (separate) WMO Climate Services Toolbox project, or others.

## Project Approach

OpenCDMS has two strands. One is a top-down approach which sets what is acceptable for the reference functions of OpenCDMS, where it will either replace existing CDMS or act as the reference for the processes in those CDMSs. The other is a bottom-up approach which builds on existing precursor CDMSs, including building rapid prototypes and adding recommended features of OpenCDMS into existing systems.

### Phase 1: Incubation Phase

The “incubation” phase is to build a community of contributors and developers with experience and interest in developing and using a CDMS, with an emphasis on including those based in developing countries while bringing innovative solutions to developed countries.

This phase includes a communication plan for OpenCDMS promoted through WMO to provide information and awareness about the project to WMO Members, the Association of Hydro-Meteorological Equipment Industry (HMEI), current CDMS developers and distributors, scientist and academic organizations.

During this phase, a strategy for implementation will be developed, and the coding and implementation tools and standards will be investigated and agreed. An Application Programming Interface will be developed which will wrap the database system for two (or more) of the candidate precursor CDMS (initially Climsoft and MCH). 

### Phase 2: Core Implementation

In the second phase, a common data model for OpenCDMS will be developed and tested, using the API. User interface modules will be ported and tested with the OpenCDMS data model. These user interfaces will include data ingestion, storage, exchange and quality control and production of the minimum set of climate-relevant products that are required by WMO standards and recommended practices. This includes storage of data obtained through data rescue activities. 

Also with the core implementation, processes and tools for migration from predecessor CDMSs (MCH, CliDE, Climsoft etc) will be developed and tested.

Implementation in a number of NMHSs will be undertaken, initially with those who already use a precursor CDMS.

### Phase 3: Consolidation and Improvement

The principal objective of OpenCDMS at Stage 3 is to expand the variety of observations that can be managed within OpenCDMS, and to improve the quality of the coding and processes within OpenCDMS. This will include widening the peer-review of methodologies, especially for quality control of observation data and management of observation systems. Capabilities will expand to include the functionality and data types which are recommended in WMO No-1131, and to interface with the Climate Services Toolkit components as these develop.

At this stage, OpenCDMS will link to Oscar/surface to exchange information on the metadata associated with the observations.

Implementation and training will continue to expand the number of user sites.

Then phase 4, the “mature phase” for the long term will focus on consolidation, maintenance, training and support. There will be an emphasis on implementation in NMHSs which do not currently use a CDMS. Also use of OpenCDMS to test compliance of other CDMSs with WMO Recommendations on best-practice.

## Milestones & Schedule

| Period      | Phase                                  | On-going process                               |
|-------------|----------------------------------------|------------------------------------------------|
| End of 2020 | Phase 1: Incubation                    | Communication                                  |
| End of 2021 | Phase 2: Core Implementation           | Building the community                         |
| End of 2023 | Phase 3: Consolidation and Improvement | Maintaining capability, support implementation |
| On-going    | Mature phase                           | Developing and debugging, technology watch     |

## Deliverables

* Governance, infrastructure and policies defined
* Community of open-source contributors initiated and sustainable (on-going process);
* Roadmap for OpenCDMS development, implementation and interfaces for environmental observation time-series data;
* Precursor CDMSs improved and rationalized towards OpenCDMS;
* OpenCDMS data model designed, tested and implemented;
* User interfaces for data and metadata management designed, tested and implemented;
* End-user applications tested and implemented.

## Configuration management

Development and documentation will be managed through the Gihub project https://github.com/opencdms as a free open-source project using best-practice and following the rules of the OpenWIS Association.

## Sponsor and funding source

WMO is one of the sponsors of the OpenCDMS. WMO has an established mechanism for receiving, managing and spending voluntary financial contributions through trust funds or special accounts. The sustainability of the interest of WMO for a Reference open-source CDMS, is clearly indicated in its Resolutions (CCl and Congress see above).

As an open source project, OpenCDMS will be delivered by a range of contributors. Some of those individuals will be volunteers contributing in their personal time, and others will be assigned by their employers to contribute to the project. OpenCDMS will need to solicit those contributions.

OpenCDMS will encourage contributions from Members of WMO and of the Association of Hydro-Meteorological Equipment Industry (HMEI) as well as non-profit organizations, universities, the Food and Agricultural Organization, and other interested bodies and individuals. 

Users in the NMHSs will be encouraged to participate as Contributors, especially from their experience, and in the design, testing and usage discussions. There will be an emphasis on inclusion and mentoring for contributors based in developing and least-developed countries while being vigilant on the use of the best adapted and most appropriate technologies.

At this stage, it is not envisaged to solicit any funding from or through the OpenWIS AISBL.

## OpenCDMS Project Structure and Initial Governance

As required by OpenWIS AISBL Internal Rules, the initial development (phase 1 to 3) of OpenCDMS will be managed by a **Project Management Committee**. This committee will be the interface between the Association and the Project, and will determine the overall strategic direction of the project. It will also maintain strong coordination with the WMO Secretariat and the WMO Expert Team on Data Rescue and Management (ET-DRM) or its successor.

The overall strategic direction of the project will be determined by the Project Management Committee (PMC) whilst the day to day operations will be overseen by the **Project Technical Team (PTT)** and a **Project Advisor Team (PAT)**.

The Project Advisor Team will follow a bottom-up approach creating rapid prototypes with the aim of graduating these to production. The Project Management Committee will mediate between the two teams

### Project Management Committee (PMC)

The initial membership of the PMC is proposed as follows:

#### Members of PMC:
* WMO Secretariat;
* OpenWIS Association AISBL representative;
* Representative (usually a co-Chair) of WMO ET-DRM or successor;
* Representatives of projects for precursor CDMSs (MCH, Climsoft, CliDE etc)
* Representatives of bodies providing developers and other support, including WMO Members, HMEI, non-profit organisations, universities and others.

The Chair of Project Management Team is to be proposed by the Members of the Project Management Committee and endorsed by the OpenWIS Association AISBL Steering Committee.

#### Functions:
* Coordinating the work of the project
* When appropriate, make formal decisions
* Managing financial support to the project
* Ensure that the project is managed in accordance with OpenWIS practices
* Report, at least on an annual basis, to the OpenWIS Streering Committee
* Provide information to the WMO ET-DRM (or successor) 

### Project Technical Team (PTT)
The PTT will manage the implementation of the long-term strategic direction and be responsible for determining top-down what is accepted into the OpenCDMS software as a high-quality reference and practical system. The PTT has the responsibility to “plan for success”.

The PTT has a predominantly technical role and leads day-to-day software delivery and management of the production software (github.com/opencdms ) They have responsibility for coordinating technical effort and ensuring software quality across the entire project (both the production code on the left and prototypes on the right).

The PTT will be responsible for software development and delivery from day one; particular responsibilities are:
a)	Supervise, support and train developers in the right hand prototyping groups to ensure that the solutions being developed become high quality.
b)	Ensure that software moves from right to left when it is ready.
c)	Ensure that solutions do not transfer if they are not yet fit for purpose.

### Project Advisor Team (PAT)

The Project Advisor Team on the right hand side has a predominantly non-technical role. The team’s objective is to bring new parties into the safe-sandbox environment and facilitate collaborations/experimentation (github.com/opencdms-dev ). 

The PAT has the responsibility to “plan for failure”. This means:
* Work undertaken should be useful within existing CDMS projects even if it is not used in OpenCDMS.
* If the OpenCDMS high-level approach does not succeed then the bottom up approach would still rationalise and improve the existing CDMS.

New developers (people), and the software that they create (code), will generally both start on the right. The responsibility of the PTT is to up skill developers so they know how to operate as open source software engineers (so they can move to the left hand team) and also to improve the quality of the software solutions that are created so that they meet the required standards (so that code can also move to the left).
