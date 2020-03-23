| ﻿|   | Internet Mapping Framework 2   |   | BC Map Hub   |   | Simple Map Kit |   | Common Web Mapping|
| |   | IMF2 |   | AGOL  |   | SMK|   | CWM   |
| |   ||   |  |   |   |   |   |
| Overview   |   | A web mapping platform that's versatile through configuration and open for custom tool development.  Ideal for fit for purpose applications, both desktop and mobile.  Can be light weight or heavy weight depending on clients needs.  |   | ESRI's extension of ArcGIS into the cloud, ArcGIS Online provides a space to develop applications and share apps and contents for purposes of collaboration.  A potential alternative to the DMF with its application templates, but some still have that GIS feel.|   | Leaflet based toolkit allowing for contanerized deployments that are light weight.  Targeted to non-GIS developers.   |   | The perfect platform for map within an app transactional builds that need to be integrated into a larger click-through system.  Architecture is complex   |
| Overview Alternative   |   | A web mapping platform which is the built upon the ESRI GeoCortex platform.  This is a DataBC product which provides maps and reports from the BC Geographic Warehouse. Ideal for either mobile or desktop as is or with additional development.  |   | The official BC Government location for ESRI's ArcGIS Online (AGOL) tool. It is a cloud-based tool which allows a user to develop applications and share geospatial information. Useful to link GIS Analyst work with Business users to share maps and reports. |   | Leaflet based toolkit allowing for deployments that are light weight.  Useful for non-GIS developers who are building in the Agile environment. |   | This NRM service is part of Common Services tools which provides an Open Source framework for building a map within an application.  The CWM Client can be added to host application web pages to display and interact with maps and spatial data.   |
| Primary Strengths |   | All purpose Web Mapping Framework focusing on fit for purpose application configurationCustom tools, workflows and reports can be developed to extend an applicationMobile support through phone and tabloidLight or heavy weight implementations |   | Simple applications that can be built and shared with groups, a ministry, government or publicHundreds of default templates to choose from including story booksArcGIS Online collector for quick, simple field data collectionElastic server architecture for high, short term use applicationsIntegration with Location Service APIs |   | Container based deploymentApache 2.0 licenseLightweight, API basedNon-GIS DevelopersDirect system integration3D option|   | The NRM Common Web Mapping (CWM) framework provides a simple, powerful and lightweight mapping capability for web-browser based client applications. CWM is integrated with the NRS ISSS service-based architecture.  The client component provides a simple API to let host pages interact with the map to display and manipulate spatial data. |
| Future Direction  |   | Platform MaturityMinor UI UpdatesJS 4x viewer upgrade (future) |   | Continued vigilance on data governance and content publicationEssentials workflows |   | Positioned as light weight points on a map replacement for DMF.Community involvement, source code on GitHubOptional support and hosting model from DataBC |   | Platform MaturityMinor UI Updates|
| Contact |   | Client Engagement - Terry Lanktree  |   | Client Engagement - Terry Lanktree|   | Client Engagement - Terry Lanktree or GitHub |   | Common Services Manager IITD|
| Architecture |   | Custom BC Gov't Web services and tools on top of Essentials/ArcGIS Server/Geoserver/BCGW  |   | Licensed cloud based service running on elastic Amazon cloud/BCGW/ArcGIS Server/Portal  |   | Containerized, deploy anywhere |   | Custom BC Gov't Framework on top of Geoserver/OSDB/BCGW and Open Layers 2   |
| Examples   |   | iMapBCConsultative Area DatabaseMajor ProjectsACDFTraditional Use Studies|   | EMBC COP  PICESMount PollyWildfire appsDrought portal app|   | Assisted living and residential care|   | MTO, ILRR, EYOR, NRS Explore|
| Build Requirements|   | IMF2 |   | AGOL  |   | SMK|   | CWM   |
| Self-serve/wizard option to build web mapping applications quickly with no coding/scripting experience   |   | no  |   | yes |   | ? |   | no |
| Self-serve/wizard option to build web mapping applications quickly with coding/scripting experience |   | no  |   | yes |   | yes |   | no |
| Full development of coding/scripting web mapping applications|   | yes |   | yes |   | yes |   | yes |
| A web mapping application that can be configured and deployed with internal resources   |   | yes |   | yes |   | yes |   | yes |
| A web mapping application that can be configured and deployed with Consulting/contractor services |   | yes |   | yes |   | yes |   | yes |
| Simple customizations without the effort of a full development   |   | yes |   | yes |   | P partial|   | No - Depends how you define simple. Lots of customization can be done by changes to a JSON configuration file, without writing any code.  |
| Complex custom tools, workflows and applications to provide powerful and feature-rich end-user experiences|   | yes |   | yes |   | no needs developer   |   | P  Workflows are the responsibility of the developer.   |
| Customization of web mapping applications that can be embedded in other applications or web pages |   | yes |   | yes |   | yes |   | yes |
| Is hosted in the 'cloud'|   | no  |   | yes |   | yes |   | no |
| Is hosted in Canada|   | yes |   | no - but we are scoping ArcGIS Portal - an "on premises" instance of AGO |   | exported sites can be hosted on any web server (in Canada or elsewhere)  |   | yes |
| Is hosted with write access to a web server (Self serve)|   | yes |   | Can be if author chooses to download and customize an AGO web app |   |   |   | yes |
| Is hosted with deployment via a web server (DataBC/IIT managed deployment)  |   | yes |   | yes - it is possible to customize AGO web apps, which must be hosted on a web server i.e. Web AppBuilder Developer Edition |   | exported sites can be hosted on any web server|   | yes |
| Has zero or minimal licensing fees|   | ELA|   | ELA   |   | yes |   | yes |
| Supports the ability to secure the application or data within the application based on IDIR/BCeID user layer level security  |   | P layer level |   | P internal seat license requirements|   | P through SGW|   | P both site and layer level |
| Provides high performance, fast and efficient response times|   | yes |   | yes |   | yes |   | yes |
| Can handle a lot of users and high data volume  |   | yes |   | yes |   | yes |   | P  Yes - The CWM library is running completely in the user’s browser, so it scales to any number of users. The map data it is showing is being generated on other machines, and those resources are being shared by all users. |
| Time to Market|   | Varies - Standard SDLC|   | Fast - Self publication potential |   | Fast - build and deploy anywhere|   | Varies - Standard SDLC |
| Build Cost/Development |   ||   | low build cost - no coding required, configuration via GUI   |   |   |   | Application Owner |
| License/Platform Cost  |   ||   | ELA   |   |   |   | No licensing costs associated with CWM client. The data that is being shown on the map may require licensing depending on who is hosting it.   |
| Data Modelling Costs   |   ||   | ?|   |   |   | no |
| Hosting Costs|   | Annual hosting costs vary based on app complexity or MOU   |   | No - but data hosting costs may apply|   | Optional|   | Not hosted as it is offered by DataBC  |
| End User Requirements  |   | IMF2 |   | AGOL  |   | SMK|   | CWM   |
| Easily FIND the web mapping application and data within the map  |   ||   | yes |   |   |   | yes |
| Easily FIND metadata/information about the data in the web mapping application   |   | yes |   | yes |   |   |   | yes |
| ACCESS the web mapping application via their mobile device  |   | yes |   | yes |   | yes |   | no |
| Easily USE the web mapping application without training (Training to use, and/or build) |   ||   | yes |   |   |   | yes |
| Easily USE the web mapping application if they have a visual impairment (Maybe better as a application requirement but can aplications allow for this?) |   | yes |   | some AGO App templates do provide options to assist visually impaired users.  Not sure how robust (story maps are an example)   |   |   |   | no |
| SHARE the mapping application session and its data internally within government  |   | yes |   | yes |   | no |   | yes |
| SHARE the mapping application session and its data externally with non-government|   | yes |   | yes |   | no |   | yes |
| Consume and integrate local data into the web mapping application|   | Shape and CSV |   | yes |   | SHAPE, GeoJSON, CSV, KML |   | P  Seven popular geometry types for import  |
| Consume and integrate Provincial data into the web mapping application |   | yes |   | yes |   | yes |   | yes |
| Consume and integrate External data into the web mapping application (WMS, REST) |   | Rest |   | yes |   | WMS|   | yes |
| Transfer data collected within the web mapping application to operational systems|   | yes |   | yes |   | no |   | P not part of CWM client. Application which hosts CWM needs to be able to handle this.  |
| Collect data |   | Custom only   |   | Yes - through Collector for AGO and Survey123 for AGO mobile apps |   | No|   | P  correct that CWM client provides the tools, but the application needs to implement workflows   |
| Edit data  |   | yes |   | yes |   | no |   | P  correct that CWM client provides the tools, but the application needs to implement workflows   |
| Filter or query data   |   | yes |   | yes |   | yes |   | yes |
| Download the data being viewed|   | yes |   | Yes - but there may be some limitations  |   | no |   | yes |
| Prepare specific datasets for off-line use |   | no  |   | yes |   | no |   | yes |
| Add mark-ups to the map in the web mapping application |   | yes |   | yes |   | yes |   | yes |
| Re-symbolize, modify or customize map data or labels   |   | yes |   | yes |   | no |   | No - The application can draw custom features or labels on the map if desired.   |
| Customize printing by modifying the legend |   | no  |   | not sure what this means (turn layers on or off? If so, yes) |   | no |   | yes |
| Save work and return to it at a later date |   | yes |   | does this mean the end user of an app? If so, no.   |   | no |   | yes |
| Access visualization tools in the web mapping application   |   | Basic/Advanced/3D? |   | yes |   | 3D|   | yes |
| Identify & discover relationships among features (e.g. proximity, intersection)  |   | yes |   | yes |   | no |   | P CWM client can make use of SOS to find features that overlap a polygon.   |
| Detect statistically significant patterns (e.g. hotspots, outliers)|   | no  |   | yes |   | no |   | no |
| Use analytical models to make predictions based on data|   | no  |   | (AGO does have some capabilities - but we encourage folks to use ArcMap or Pro instead.  Complexity of desired analytical model may be a factor too)|   | no |   | no |
| Types of training available  |   | manual, webinar, video|   | yes |   | documentation|   | Floating Help, contextual help,  |
| Mobile Friendly   |   | Yes|   | Yes   |   | Yes|   | no |

