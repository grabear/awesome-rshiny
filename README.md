# Awesome R Shiny [![Join the chat at https://gitter.im/awesome-rshiny/Lobby](https://badges.gitter.im/awesome-rshiny/Lobby.svg)](https://gitter.im/awesome-rshiny/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[<img src="https://www.rstudio.com/wp-content/uploads/2014/04/shiny.png" align="right" width="100">](https://www.rstudio.com)
A curated list of resources for R Shiny.  This awesome list was inspired by https://github.com/dpastoor/awesome-shiny.
Also see [Awesome-shiny-apps-for-statistics](https://github.com/huyingjie/Awesome-shiny-apps-for-statistics)

### This list is currently featured on [Awesome-R!](https://awesome-r.com/)

- [Resources](#resources)
    - [General](#general)
    - [Community](#community)
    - [Deployment](#deployment)
    - [Tutorials](#tutorials)
- [Tools](#tools)
    - [Packages](#packages)
    - [Integrations](#integrations)
- [People](#people)
- [Books](#books)
- [Galleries](#galleries)
- [App Examples](#app-examples)
- [Contributors](#contributors)

# Resources

## General

* [Official Website](http://shiny.rstudio.com/)
	* [Blog](https://blog.rstudio.org/category/shiny/)
	* [Articles](http://shiny.rstudio.com/articles/)
	* [Old Webinars Page](https://www.rstudio.com/resources/webinars/)
        * [Shiny Essentials](https://www.rstudio.com/resources/webinars/#shinyessentials)
        * [Advanced Shiny](https://www.rstudio.com/resources/webinars/#advancedshiny)
    * [New Webinars Page](https://resources.rstudio.com/webinars)
	* [2019/2020 Conference](https://www.rstudio.com/conference/)
	* [Training](https://www.rstudio.com/certified-partners/)
	* [Consultants](https://community.rstudio.com/groups/consultants/)
	* [Function References](http://shiny.rstudio.com/reference/shiny/latest/)
* [GitHub](https://github.com/rstudio/shiny)

## Community

* [Shiny Server Forum](https://support.rstudio.com/hc/en-us/sections/204025308-Shiny-Server)
* [StackOverflow Questions](http://stackoverflow.com/questions/tagged/shiny)
* [R-bloggers](http://www.r-bloggers.com/search/shiny)
* [Google Group](https://groups.google.com/forum/#!forum/shiny-discuss)
* [RStudio Community](https://community.rstudio.com/c/shiny) 
* [rOpenSci](https://ropensci.org/)
* [R-Shiny on Reddit](https://www.reddit.com/r/rshiny/)
* [RGov - Government network for R/Shiny](https://rdotgov.wordpress.com/deploy-shiny/)

## Deployment

### Self Hosting

* [Shiny Server](https://github.com/rstudio/shiny-server) - Back end software that builds a web server for shiny apps.
* [RStudio Connect](https://www.rstudio.com/products/connect/) - Back end software for hosing shiny applications, Rmarkdown... plus other features for enterprise contexts.
* [Shinyproxy](https://www.shinyproxy.io/) - Uses containers for hosting shiny apps and a Java server control and proxy traffic to the app containers. [How-to Blog](http://lukesingham.com/shiny-containers-with-shinyproxy/).
* [ShinyStudio](https://github.com/dm3ll3n/ShinyStudio) - Builds on the [Rocker project](https://www.rocker-project.org/) by including ShinyProxy to provide secured access to RStudio, VS Code, and Shiny.

### Platform As A Service (PAAS)

* [ShinyApps.io](http://www.shinyapps.io/) - Rstudio's PAAS specifically for hosting shiny apps.
* [Heroku](https://www.heroku.com) - General cloud application platform that can be utilised by shiny apps with these [buildpack scripts](https://github.com/virtualstaticvoid/heroku-buildpack-r/tree/heroku-16).

## Tutorials

* [The R-Podcast](https://r-podcast.org/)
    * [Episode 15: Introduction to Shiny](https://r-podcast.org/episode/015-introduction-to-shiny/)
    * [Episode 16: Interview with Dean Attali](https://r-podcast.org/episode/016-interview-with-dean-attali/)
    * [Episode 17: A simply Radiant Chat with Vincent Nijs](https://r-podcast.org/episode/017-a-simply-radiant-chat-with-vincent-nijs/)
    * [Episode 18: Interviews with the R-Studio Team](https://r-podcast.org/episode/018-interviews-with-the-rstudio-team/)
    * [Episode 19: Talking Shiny at R-Studio Conf wiht Barabara Borges and Dean Attali](https://r-podcast.org/episode/019-talking-shiny-at-rstudio-conf-with-barbara-borges-and-dean-attali/)
    * [Episode 21: Talking Rcpp and More with Dirk Eddelbuettel](https://r-podcast.org/episode/021-talking-rcpp-and-more-with-dirk-eddelbuettel/)
    * [Episode 25: Interview with Ian Lyttle (Rstudio::Conf 2018](https://r-podcast.org/episode/025-rstudioconf-ian-lyttle/)
    * [Episode 27: Get The {Gt} Tables (Rstudio::Conf 2019)](https://r-podcast.org/episode/027-rstudioconf-tables/)
* [R-Studio (video)](https://shiny.rstudio.com/tutorial/)
    * [RStartHere](https://github.com/rstudio/RStartHere)
	* [Effective Reactive Programming – Part 1 & Part 2](https://www.rstudio.com/resources/videos/effective-reactive-programming/)
	* [Coordinated multiple views (linked brushing)](https://www.rstudio.com/resources/videos/coordinated-multiple-views-linked-brushing/)
	* [Building interactive tools for exploratory data analysis (gadgets)](https://www.rstudio.com/resources/videos/building-interactive-tools-for-exploratory-data-analysis/)
	* [Improvements in deploying apps](https://www.rstudio.com/resources/videos/deploying-apps/)
	* [Modularizing Shiny app code](https://www.rstudio.com/resources/videos/modularizing-shiny-app-code/)
	* [Shiny UI](https://www.rstudio.com/resources/videos/shiny-ui/)
	* [Debugging Techniques](https://www.rstudio.com/resources/videos/debugging-techniques/)
	* [Profiling and Performance](https://www.rstudio.com/resources/videos/profiling-and-performance/)
	* [Interfacing DataTables](https://www.rstudio.com/resources/videos/interfacing-datatables/)
	* [Complex application layouts with Grid Style Sheets](https://www.rstudio.com/resources/videos/grid-style-sheets/)
	* [Building Dashboards](https://www.rstudio.com/resources/videos/building-dashboards/)
* [R-Studio (YouTube)](https://www.youtube.com/playlist?list=PL9HYL-VRX0oTAHdR62i2YaLNmJhFiiwaO)
* [R-Studio (Vimeo)](https://vimeo.com/rstudioinc)
* [DataCamp](https://www.datacamp.com/)
	* [Building Web Applications in R with Shiny](https://www.datacamp.com/courses/building-web-applications-in-r-with-shiny)
	* [Dean Attali: Shiny Case Studies: My new online interactive video course (DataCamp)](https://deanattali.com/blog/shiny-use-cases-datacamp-course/)
* [Dean Attali](https://deanattali.com/shiny/)
    * [CRANalerts: Get email alerts when a CRAN package gets updated](https://cranalerts.com/)
	* [2018 Blog Post: shinyalert: Easily create pretty popup messages (modals) in Shiny](https://deanattali.com/blog/shinyalert-package/)
	* [Blog Post:  Building Shiny apps - an interactive tutorial](http://deanattali.com/blog/building-shiny-apps-tutorial/)
	* [Blog Post:  Shiny tips & tricks for improving your apps and solving common problems](http://deanattali.com/blog/advanced-shiny-tips/)
	* [Blog Post:  How to get your very own RStudio Server and Shiny Server with DigitalOcean](http://deanattali.com/2015/05/09/setup-rstudio-shiny-server-digital-ocean/)
	* [Blog Post: Mimicking a Google Form with a shiny app](http://deanattali.com/2015/06/14/mimicking-google-form-shiny/)
	* [Blog post: Persistent data storage (and retrieval) in Shiny apps](http://deanattali.com/blog/shiny-persistent-data-storage/)
	* [Blog post: How to set-up shiny server on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-shiny-server-on-ubuntu-14-04)
	* [Course: Stat545](http://stat545.com/)
	* [Advanced-Shiny](https://github.com/daattali/advanced-shiny)
* [Joe Cheng](https://medium.com/@joe.cheng)
	* [Async programming in R and Shiny](https://medium.com/@joe.cheng/async-programming-in-r-and-shiny-ebe8c5010790)
	* [An informal intro to async Shiny](https://medium.com/@joe.cheng/an-informal-intro-to-async-shiny-cbf01c85c4c5)
* [Alyssa Columbus](https://alyssacolumbus.com)
	* [Blog Post: Introduction to R Shiny](https://opendatascience.com/introduction-to-r-shiny/)
* [Abhinav Agrawal (YouTube)](https://www.youtube.com/playlist?list=PL6wLL_RojB5xNOhe2OTSd-DPkMLVY9DfB)
* [AHmed HAsan (YouTube)](https://www.youtube.com/playlist?list=PLXiYeGj1hvHN5Nnu2VwRg_E-YMoc1vtan)
* [Zev-Ross](http://zevross.com/blog/2016/04/19/r-powered-web-applications-with-shiny-a-tutorial-and-cheat-sheet-with-40-example-apps/)
* [Cheat Sheet](https://www.rstudio.com/resources/cheatsheets/#shiny)
* [Delivering Data Science for the Enterprise with Shiny in Kubernetes](https://blog.kublr.com/delivering-data-science-for-the-enterprise-with-shiny-r-in-kubernetes-8430c88d1b52)
* [Shiny Server on Docker: CentOS 7 Edition](http://www.datascienceriot.com/r/shiny-docker/)
* [Use Docker to distribute and run Shiny apps](https://wabi-wiki.scilifelab.se/display/KB/Use+Docker+to+distribute+and+run+Shiny+apps)
* [Dockerizing a Shiny App](http://www.rmining.com.br/2015/04/30/dockerizing-a-shiny-app/index.html)
* [Cookie based authentication with Shiny](https://calligross.de/post/using-cookie-based-authentication-with-shiny/)
* [Speed Up Shiny Coding with Data](https://roh.engineering/post/speeding-up-shiny-coding-with-data/)

# Tools

## Packages

* R-Studio
	* [shinydashboard](https://github.com/rstudio/shinydashboard) - Shiny Dashboarding framework.
	* [fontawesome](https://github.com/rstudio/fontawesome) - Easily insert FontAwesome icons into R Markdown docs and Shiny apps.
	* [shinythemes](https://github.com/rstudio/shinythemes) - Bootstrap themes for use with Shiny.
        * [miniUI](https://github.com/rstudio/miniUI) - Provides UI widget and layout functions for writing Shiny apps that work well on small screens.
* [dashboardthemes](https://github.com/nik01010/dashboardthemes) - An experimental R package to provide custom theme options for Shinydashboard applications
* [shinyAce](https://github.com/trestletech/shinyAce) - Integrate ace editor with shiny.
* [shinyjs](https://github.com/daattali/shinyjs) - Common javascript operations in shiny via R code.
* [colourpicker](https://github.com/daattali/colourpicker) - Colour picker widget that can be used in different contexts in R.
* [ShinySky](https://github.com/AnalytixWare/ShinySky) - Various UI widgets/components not part of Shiny e.g. alerts, styled buttons.
* [radiant](https://github.com/radiant-rstats/radiant) - Business analytics using R and Shiny.
* [shinyTree](https://github.com/shinyTree/shinyTree) - Enables Shiny application developers to use the jsTree library in their applications.
* [shinystan](http://mc-stan.org/interfaces/shinystan) - Provides visual and numerical summaries of model parameters and convergence diagnostics for MCMC simulations.
* [shinyjqui](https://github.com/Yang-Tang/shinyjqui) - jQuery UI interactions and effects for shiny.
* [bsplus](https://github.com/ijlyttle/bsplus) - Shiny and R Markdown addons to Bootstrap 3.
* [shinyFiles](https://github.com/thomasp85/shinyFiles) - Extends the functionality of shiny by providing an API for client side access to the server file system.
* [shinyDND](https://github.com/ayayron/shinydnd) - Create Shiny drag and drop elements in R.
* [shinyforms](https://github.com/daattali/shinyforms) - Easily create questionnaire-type forms with Shiny.
* [ECharts2Shiny](https://github.com/XD-DENG/ECharts2Shiny) - Insert interactive charts from ECharts into Shiny.
* [shinyFeedback](https://github.com/merlinoa/shinyFeedback) - Display user feedback along side Shiny inputs.
* [shinycssloader](https://github.com/andrewsali/shinycssloaders) - Add CSS loader animations to Shiny outputs.
* [directoryInput](https://github.com/wleepang/shiny-directory-input) - Widget for interactive selection of directories.
* [shinymaterial](https://github.com/ericrayanderson/shinymaterial) - Implements Google Material Design in Shiny Applications.
* [shinysense](https://github.com/nstrayer/shinysense) - Series of Shiny modules to help Shiny sense the world around it.
* [shinyWidgets](https://github.com/dreamRs/shinyWidgets) - Extend input widgets available in Shiny.
* [ggedit](https://github.com/metrumresearchgroup/ggedit) - A Shiny gadget for exploring ggplot objects.
* [shinytest](https://github.com/rstudio/shinytest) - Automated testing for shiny apps.
* [timevis](https://github.com/daattali/timevis/) - Create interactive timeline visualizations in R.
* [shinytoastr](https://github.com/MangoTheCat/shinytoastr) - Notifications in Shiny, via [toastr](https://github.com/CodeSeven/toastr). 
* [shiny.collections](https://github.com/Appsilon/shiny.collections) - Google Docs-like live collaboration in Shiny.
* [RinteRface](https://rinterface.com) - A collection of HTML templates for Shiny.
* [shiny.semantic](https://github.com/Appsilon/shiny.semantic) - Semantic UI wrapper for Shiny.
* [yonder](https://github.com/nteetor/yonder) - A reactive web framework built on shiny.
* [shinycustomloader](https://github.com/emitanaka/shinycustomloader) - Add a custom loader for R Shiny.
* [shinybusy](https://github.com/dreamRs/shinybusy) - Minimal busy indicator for Shiny apps.
* [waiter](https://github.com/JohnCoene/waiter) - Loading screens for Shiny.
* [shinyhelper](https://github.com/cwthom/shinyhelper) - Add markdown help files to Shiny apps.
* [shinyauthr](https://github.com/PaulC91/shinyauthr) - Server-side authentication using shiny modules.
* [auth0](https://github.com/curso-r/auth0) - Authentication in Shiny apps using Auth0 service.
* [reactlog](https://github.com/rstudio/reactlog) - Visual insight into a Shiny apps reactive graph.
* [supreme](https://github.com/strboul/supreme) - Structure Shiny applications developed with modules.

## Integrations

* [HTML Widgets/Javascript](http://www.htmlwidgets.org/)
	* [Crosstalk](https://rstudio.github.io/crosstalk/shiny.html) - Extends htmlwidgets with functionality for implementing cross-widget interactions.
	* [DT](https://github.com/rstudio/DT) - Provides a function `datatable()` to display R data via the DataTables javascript library.
	* [leaflet](http://rstudio.github.io/leaflet/shiny.html) - JavaScript library for creating dynamic maps that support panning and zooming along with various annotations like markers, polygons, and popups.
	* [leaflet.minicharts](https://github.com/rte-antares-rpackage/leaflet.minicharts) - Add and update small charts on an interactive leaflet maps.
	* [d3heatmap](https://github.com/rstudio/d3heatmap) - Implements a D3 heatmap htmlwidget.
	* [dygraphs](https://github.com/rstudio/dygraphs) - R interface to the dygraphs JavaScript charting library. It provides rich facilites for charting time-series data in R.
	* [DiagrammeR](https://github.com/rich-iannone/DiagrammeR) - Tool for creating diagrams and flowcharts using Graphviz and Mermaid.
	* [MetricsGraphics](https://github.com/hrbrmstr/metricsgraphics) - Enables easy creation of D3 scatterplots, line charts, and histograms.
	* [networkD3](https://github.com/christophergandrud/networkD3) - Graph data visualization with D3.
	* [rthreejs](https://github.com/bwlewis/rthreejs) - 3D scatterplots and globes.
	* [rbokeh](http://hafen.github.io/rbokeh/) - Interface to Bokeh that provides a flexible, powerful, declarative framework for creating interactive plots.
	* [plotly](https://github.com/ropensci/plotly) - Easily translate your ggplot2 graphics to an interactive web-based version, and also provides bindings to the plotly.js graphing library.
	* [formattable](https://renkun.me/formattable/) - This package is designed for applying formatting on vectors and data frames to make data presentation easier, richer, more flexible and hopefully convey more information.
	* [manipulateWidget](https://github.com/rte-antares-rpackage/manipulateWidget) - Add More Interactivity to htmlWidgets.
	* [gglabeller](https://github.com/AliciaSchep/gglabeller) - Gadget that enables selecting points on a ggplot to label.
	* [billboarder](https://github.com/dreamRs/billboarder) - Htmlwidget for billboard.js.
	* [highcharter](http://jkunst.com/highcharter/index.html) - Flexible JavaScript charting libraries in shiny.
	* [rhandsontable](https://github.com/jrowen/rhandsontable) - An htmlwidgets implementation of Handsontable.js.
    * [echarts4r](https://github.com/JohnCoene/echarts4r) - Create interactive charts by leveraging Echarts.js library.
    * [rintrojs](https://github.com/carlganz/rintrojs) - Wrapper for the Intro.js library.
    * [slickR](https://github.com/metrumresearchgroup/slickR) - Slick carousel htmlwidget for R.
    * [rclipboard](https://github.com/sbihorel/rclipboard) - clipboard.js for R/Shiny Applications.
    * [scatterD3](https://github.com/juba/scatterD3) - Scatter plot htmlwidget based on D3.js.
    * [trelliscopejs](https://github.com/hafen/trelliscopejs/) - TrelliscopeJS R package.
    * [visNetwork](https://github.com/datastorm-open/visNetwork) - Network visualization for R using vis.js library.
    * [sigmajs](https://github.com/JohnCoene/sigmajs) - Fully-fledged wrapper for the sigma.js JavaScript library.
    * [excelR](https://github.com/Swechhya/excelR) - An interface to jExcel.js library.
* [flexdashboard](http://rmarkdown.rstudio.com/flexdashboard/index.html) - Easy interactive dashboards for R.
* [Shiny in Rmarkdown](http://rmarkdown.rstudio.com/authoring_shiny.html) - Run shiny apps in rmarkdown documents.
* [ggvis](https://github.com/rstudio/ggvis) - Make it easy to describe interactive web graphics in R.
* [RInno](https://github.com/ficonsulting/RInno) - Install local shiny apps by providing an interface between R and Inno Setup, (Windows Only).
* [googleVis](https://github.com/mages/googleVis) - An interface between R and the [Google's charts tools](https://developers.google.com/chart/).
* [pool](https://github.com/rstudio/pool) - Abstract away the logic of connection management and the performance cost of fetching a new connection from a remote database.

# People

* [Dean Attali](https://github.com/daattali)
* [Joe Cheng](https://github.com/jcheng5)
* [Winston Chang](https://github.com/wch)
* [Barbara Borges Ribeiro](https://github.com/bborgesr)
* [Ramnath Vaidyanathan](https://github.com/ramnathv)
* [Jeff Allen](https://github.com/trestletech)
* [Vincent Nijs](https://github.com/vnijs)
* [Sebastian Kranz](https://github.com/skranz)
* [David Granjon](https://divadnojnarg.github.io)

# Books

* [Web Application and Development Using Shiny (2nd edition) - by Chris Beely](https://www.amazon.com/Web-Application-Development-using-Shiny/dp/1782174346)
* [Learing Shiny - by Hernán G. Resnizky](https://www.amazon.com/Learning-Shiny-Hernan-G-Resnizky/dp/1785280902)
* [(WIP) Mastering Shiny - by Hadley Wickham](https://mastering-shiny.org/)

# Galleries

* R-Studio
	* [Shiny User Showcase](https://www.rstudio.com/products/shiny/shiny-user-showcase/) - Featured user Shiny apps.
	* [Shiny Gallery](https://shiny.rstudio.com/gallery/) - Shiny apps and much more.
* [Showmeshiny](http://www.showmeshiny.com/) - Huge gallery of Shiny apps.
* [Shiny Widgets](http://shinyapps.org/) - Experience statistics with apps designed for teaching and analysis.
* Html Widgets
	* [Html Widgets Showcase](http://www.htmlwidgets.org/showcase_leaflet.html) - Featured Html widgets.
	* [Html Widgets Gallery](http://gallery.htmlwidgets.org/) - User submitted Html widgets.
* [R Graph Catalog](http://shinyapps.stat.ubc.ca/r-graph-catalog/) - Complement to the book  “Creating More Effective Graphs” by Naomi Robbins.
* [Awesome Shiny Apps for Statistics](https://github.com/huyingjie/Awesome-shiny-apps-for-statistics) - A curated list of awesome Shiny Apps for statistics.

# App Examples

* [R-Studio Examples](https://github.com/rstudio/shiny-examples)
* [Waze](https://www.rstudio.com/resources/customer-spotlight/waze_story/) - Community based real-time traffic and navigation info.
* [Astra Zeneca](https://www.rstudio.com/resources/customer-spotlight/astra_zeneca/) - Data science tools used to create medicines more efficiently.
* [shiny-salesman](https://github.com/toddwschneider/shiny-salesman) - Traveling salesman app.
* [Shiny GEM](https://github.com/dm3ll3n/Shiny-GEM) - ‘GEM’ stands for ‘general exploratory methods’, as this app aims to simplify a variety of basic EDA tasks.
* [shinyEd](https://github.com/ShinyEd/ShinyEd) - Statistics education apps.
* [STARTapp](https://github.com/jminnier/STARTapp) - Transcriptome Analysis Resource Tool.
* [shiny-phyloseq](https://github.com/joey711/shiny-phyloseq) - Provides a graphical user interface to the microbiome analysis package for R, called phyloseq.
* [shiny-ampvis2](https://kasperskytte.shinyapps.io/shinyampvis) - Provides some basic functionality for using ampvis2 to visualize microbiome data.
* [Google Analytics Dashboard](https://github.com/MarkEdmondson1234/ga-dashboard-demo) - Demo on how to build your own Google Analytics dashboard with R, Shiny and MySQL.
* [BallR](https://github.com/toddwschneider/ballr) - Uses the NBA Stats API to visualize every shot taken by a player during an NBA season dating back to 1996.
* [GenMap-Comparator](https://github.com/holtzy/GenMap-Comparator) - Compare genetic maps with D3 & Shiny.
* [MAVIS](https://github.com/kylehamilton/MAVIS) - MAVIS: Meta Analysis via Shiny.
* [iTunes Reviews Analysis](https://github.com/amrrs/itunesr_webapp) - iTunes App Store Reviews Text Extractor and Text Analysis Web App.
* [NYT Bar Optimizer](https://github.com/jordanmeyer/nyt-bar-optimizer) - Optimize your liquor cabinet using cocktail recipes from New York Times Cooking.
* [Lights Out game](https://daattali.com/shiny/lightsout/) - Lights Out is a puzzle game consisting of a grid of lights that are either on or off.
* Australian Tax Office:
	* [Workforce Demographics](https://atogov.shinyapps.io/workforcedmgs/) - View a range of workforce related demographics information across an organisation. [Source Code](https://github.com/atogov/workforceDmgs).
	* [Bivariate Demographics](https://atogov.shinyapps.io/bivariatedmgs/) - Examine how an organisation is performing on a range of demographic information. [Source Code](https://github.com/atogov/bivariateDmgs).
* [Shiny Database App (CRUD)](https://ipub.com/dev-corner/apps/shiny_crud01/) - An example of a [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) shiny app with [accompanying how-to post](https://ipub.com/shiny-crud-app/).
* [taskviewr](https://github.com/bearloga/taskviewr) - Browse R packages by CRAN Task Views and license info.
* [homebrewR](https://davesteps.shinyapps.io/homebrewR/) - Explore and compare beer recipes.
* [vinylSpotting](https://github.com/ewenme/vinylspotting) - Visualize and explore Discogs record collections.
* [polMonitor](https://ewenme.shinyapps.io/polMonitor/) - Monitor police violence in the United States.
* [OCRinShiny](https://github.com/longhowlam/OCRinShiny) - OCR an image with the tesseract package.
* [ExpressionDB](https://github.com/5c077/ExpressionDB) - Host gene expression/ontology data with Shiny.
* [Interactive PCA Explorer](https://github.com/benmarwick/Interactive_PCA_Explorer) - Explore a PCA plots and data.
* [contributr](https://github.com/LucyMcGowan/contributr) - Find beginner GitHub issues to contribute to.
* [VisualPruner](https://github.com/LaurenSamuels/VisualPruner) - Cohort selection in observational studies.
* [Opioid Overdose Shiny App](https://github.com/Dmunslow/Opioid-Overdose-Shiny-App) - Visualize opioid overdose data.
* [Shiny App Spotify](https://github.com/joelcponte/shiny-app-spotify) - Connect with spotify's API and generate personalized playlist recommendations through machine learning and data visualization.
* [National Parks Weather](https://github.com/sgaraycoa/National-Parks-Weather) - Visualize National Parks locations and weather using user input.
* [html2r](https://github.com/alandipert/html2r) - Convert HTML to R.
* [Anomaly Detection](https://murat-koptur.shinyapps.io/AnomalyDetectionShiny/) - Detect anomalies on univariate timeseries data using AnomalyDetection package. 

# Contributors

[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/0)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/0)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/1)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/1)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/2)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/2)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/3)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/3)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/4)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/4)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/5)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/5)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/6)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/6)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/7)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/7)

* [Rob Gilmore](https://github.com/grabear)
* [Shaurita Hutchins](https://github.com/sdhutchins)
* [Devin Pastoor](https://github.com/dpastoor)
* [Dean Attali](https://github.com/daattali)
* [Luke Singham](https://github.com/ucg8j)
* [Abdul Majed Raja](https://www.github.com/amrrs)
* [Leonardo Trimarchi](https://domthecodingcaveman.wordpress.com/)
* [Kshitiz Khanal](http://twitter.com/kshitizkhanal7)
* [Alyssa Columbus](https://alyssacolumbus.com)
