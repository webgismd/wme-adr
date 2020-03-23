|   |   | Internet
  Mapping Framework 2 |   | BC Map Hub |   | Simple Map Kit |   | Common Web
  Mapping |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |   | IMF2 |   | AGOL |   | SMK |   | CWM |
|   |   |   |   |   |   |   |   |   |
| Overview[1] |   | A
  web mapping platform that's versatile through configuration and open for
  custom tool development.  Ideal for fit
  for purpose applications, both desktop and mobile.  Can be light weight or heavy weight
  depending on clients needs. |   | ESRI's
  extension of ArcGIS into the cloud, ArcGIS Online provides a space to develop
  applications and share apps and contents for purposes of collaboration.  A potential alternative to the DMF with its
  application templates, but some still have that GIS feel. |   | Leaflet
  based toolkit allowing for contanerized deployments that are light
  weight.  Targeted to non-GIS
  developers. |   | The
  perfect platform for map within an app transactional builds that need to be
  integrated into a larger click-through system.  Architecture is complex |
| Overview Alternative |   | A
  web mapping platform which is the built upon the ESRI GeoCortex
  platform.  This is a DataBC product
  which provides maps and reports from the BC Geographic Warehouse. Ideal for
  either mobile or desktop as is or with additional development.   |   | The
  official BC Government location for ESRI's ArcGIS Online (AGOL) tool. It is a
  cloud-based tool which allows a user to develop applications and share
  geospatial information. Useful to link GIS Analyst work with Business users
  to share maps and reports.  |   | Leaflet
  based toolkit allowing for deployments that are light weight.  Useful for non-GIS developers who are
  building in the Agile environment. |   | This
  NRM service is part of Common Services tools which provides an Open Source
  framework for building a map within an application.  The CWM Client can be added to host
  application web pages to display and interact with maps and spatial
  data.  |
| Primary Strengths |   | All
  purpose Web Mapping Framework focusing on fit for purpose application
  configuration

    Custom tools, workflows and reports can be developed to extend an
  application

    Mobile support through phone and tabloid

    Light or heavy weight implementations |   | Simple
  applications that can be built and shared with groups, a ministry, government
  or public

    Hundreds of default templates to choose from including story books

    ArcGIS Online collector for quick, simple field data collection

    Elastic server architecture for high, short term use applications

    Integration with Location Service APIs |   | Container
  based deployment

    Apache 2.0 license

    Lightweight, API based

    Non-GIS Developers

    Direct system integration

    3D option |   | The
  NRM Common Web Mapping (CWM) framework provides a simple, powerful and
  lightweight mapping capability for web-browser based client applications. CWM
  is integrated with the NRS ISSS service-based architecture.  The client component provides a simple API
  to let host pages interact with the map to display and manipulate spatial
  data.  |
| Future Direction |   | Platform
  Maturity

    Minor UI Updates

    JS 4x viewer upgrade (future) |   | Continued
  vigilance on data governance and content publication

    Essentials workflows |   | Positioned
  as light weight points on a map replacement for DMF.

    Community involvement, source code on GitHub

    Optional support and hosting model from DataBC |   | Platform
  Maturity

    Minor UI Updates |
| Contact / Initiation Process |   | Client
  Engagement - Terry Lanktree |   | Client
  Engagement - Terry Lanktree |   | Client
  Engagement - Terry Lanktree or GitHub |   | Common
  Services Manager IITD |
| Architecture |   | Custom
  BC Gov't Web services and tools on top of Essentials/ArcGIS
  Server/Geoserver/BCGW |   | Licensed
  cloud based service running on elastic Amazon cloud/BCGW/ArcGIS Server/Portal |   | Containerized,
  deploy anywhere |   | Custom
  BC Gov't Framework on top of Geoserver/OSDB/BCGW and Open Layers 2 |
| Examples |   | iMapBC
    Consultative Area Database
    Major Projects
    ACDF
    Traditional Use Studies |   | EMBC
  COP                                                                                                         
  PICES
    Mount Polly
    Wildfire apps
    Drought portal app |   | Assisted
  living and residential care |   | MTO,
  ILRR, EYOR, NRS Explore |
| Build Requirements |   | IMF2 |   | AGOL |   | SMK |   | CWM |
| Self-serve/wizard option to build web mapping applications
  quickly with no coding/scripting experience |   | O |   | P |   | ? |   | O |
| Self-serve/wizard option to build web mapping applications
  quickly with coding/scripting experience |   | O |   | P |   | P |   | O |
| Full development of coding/scripting web mapping applications |   | P |   | P |   | P |   | P |
| A web mapping application that can be configured and deployed
  with internal resources |   | P |   | P |   | P |   | P |
| A web mapping application that can be configured and deployed
  with Consulting/contractor services |   | P |   | P |   | P |   | P |
| Simple customizations without the effort of a full development |   | P |   | P |   | P
  partial |   | No
  - Depends how you define simple. Lots of customization can be done by changes
  to a JSON configuration file, without writing any code. |
| Complex custom tools, workflows and applications to provide
  powerful and feature-rich end-user experiences |   | P |   | P |   | O
  needs developer |   | P  Workflows are the
  responsibility of the developer.  |
| Customization of web mapping applications that can be embedded
  in other applications or web pages |   | P |   | P |   | P |   | P |
| Is hosted in the 'cloud' |   | O |   | P |   | P |   | O |
| Is hosted in Canada |   | P |   | no
  - but we are scoping ArcGIS Portal - an "on premises" instance of
  AGO |   | exported
  sites can be hosted on any web server (in Canada or elsewhere) |   | P |
| Is hosted with write access to a web server (Self serve) |   | P |   | Can
  be if author chooses to download and customize an AGO web app |   |   |   | P |
| Is hosted with deployment via a web server (DataBC/IIT managed
  deployment) |   | P |   | yes
  - it is possible to customize AGO web apps, which must be hosted on a web
  server i.e. Web AppBuilder Developer Edition |   | exported
  sites can be hosted on any web server |   | P |
| Has zero or minimal licensing fees |   | ELA |   | ELA |   | P |   | P |
| Supports the ability to secure the application or data within
  the application based on IDIR/BCeID user layer level security |   | P
  layer level |   | P internal seat license
  requirements |   | P through SGW |   | P both site and layer level |
| Provides high performance, fast and efficient response times |   | P |   | P |   | P |   | P |
| Can handle a lot of users and high data volume |   | P |   | P |   | P |   | P  Yes - The CWM library is running completely
  in the user’s browser, so it scales to any number of users. The map data it
  is showing is being generated on other machines, and those resources are
  being shared by all users.  |
| Time to Market |   | Varies
  - Standard SDLC |   | Fast
  - Self publication potential |   | Fast
  - build and deploy anywhere |   | Varies
  - Standard SDLC |
| Build Cost/Development |   |   |   | low
  build cost - no coding required, configuration via GUI |   |   |   | Application
  Owner |
| License/Platform Cost |   |   |   | ELA |   |   |   | No
  licensing costs associated with CWM client. The data that is being shown on
  the map may require licensing depending on who is hosting it.  |
| Data Modelling Costs |   |   |   | ? |   |   |   | O |
| Hosting Costs |   | Annual
  hosting costs vary based on app complexity or MOU |   | No
  - but data hosting costs may apply |   | Optional |   | Not
  hosted as it is offered by DataBC |
| End User Requirements |   | IMF2 |   | AGOL |   | SMK |   | CWM |
| Easily FIND the web mapping application and data within the map[2] |   |   |   | P |   |   |   | P |
| Easily FIND metadata/information about the data in the web
  mapping application |   | P |   | P |   |   |   | P |
| ACCESS the web mapping application via their mobile device |   | P |   | P |   | P |   | O |
| Easily USE the web mapping application without training
  (Training to use, and/or build) |   |   |   | P |   |   |   | P |
| Easily USE the web mapping application if they have a visual
  impairment (Maybe better as a application requirement but can aplications
  allow for this?) |   | P |   | some
  AGO App templates do provide options to assist visually impaired users.  Not sure how robust (story maps are an
  example) |   |   |   | O |
| SHARE the mapping application session and its data internally
  within government |   | P |   | P |   | O |   | P |
| SHARE the mapping application session and its data externally
  with non-government  |   | P |   | P |   | O |   | P |
| Consume and integrate local data into the web mapping
  application |   | Shape
  and CSV |   | P |   | SHAPE,
  GeoJSON, CSV, KML |   | P  Seven popular geometry
  types for import  |
| Consume and integrate Provincial data into the web mapping
  application |   | P |   | P |   | P |   | P |
| Consume and integrate External data into the web mapping
  application (WMS, REST) |   | Rest |   | P |   | WMS |   | P |
| Transfer data collected within the web mapping application to
  operational systems |   | P |   | P |   | O |   | P not part of CWM client.
  Application which hosts CWM needs to be able to handle this. |
| Collect data |   | Custom
  only |   | Yes
  - through Collector for AGO and Survey123 for AGO mobile apps |   | No |   | P 
  correct that CWM client provides the tools, but the application needs
  to implement workflows |
| Edit data |   | P |   | P |   | O |   | P 
  correct that CWM client provides the tools, but the application needs
  to implement workflows |
| Filter or query data |   | P |   | P |   | P |   | P |
| Download the data being viewed |   | P |   | Yes
  - but there may be some limitations |   | O |   | P |
| Prepare specific datasets for off-line use |   | O |   | P |   | O |   | P |
| Add mark-ups to the map in the web mapping application |   | P |   | P |   | P |   | P |
| Re-symbolize, modify or customize map data or labels |   | P |   | P |   | O |   | No
  - The application can draw custom features or labels on the map if
  desired.  |
| Customize printing by modifying the legend |   | O |   | not
  sure what this means (turn layers on or off? If so, yes) |   | O |   | P |
| Save work and return to it at a later date |   | P |   | does
  this mean the end user of an app? If so, no. |   | O |   | P |
| Access visualization tools in the web mapping application |   | Basic/Advanced/3D? |   | P |   | 3D |   | P |
| Identify & discover relationships among features (e.g.
  proximity, intersection) |   | P |   | P |   | O |   | P CWM client can make use of SOS
  to find features that overlap a polygon. |
| Detect statistically significant patterns (e.g. hotspots,
  outliers) |   | O |   | P |   | O |   | O |
| Use analytical models to make predictions based on data |   | O |   | (AGO
  does have some capabilities - but we encourage folks to use ArcMap or Pro
  instead.  Complexity of desired
  analytical model may be a factor too) |   | O |   | O |
| Types of training available |   | manual,
  webinar, video |   | P |   | documentation |   | Floating
  Help, contextual help,  |
| Mobile Friendly |   | Yes |   | Yes |   | Yes |   | O |
|  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |
