# InsideInsights

InsideInsights is a tool for managing insights during data analysis. The system bridges cores aspects from literate computing, provenance tracking, and data-driven storytelling. In short, the system allows users to create interactive hierarchical data-driven reports during analysis, that at any point can be shared, reviewed, and extended. It was published as a research paper at the EuroVis conference in June 2019:

>Andreas Mathisen, Tom Horak, Clemens N. Klokmose, Kaj Grønbæk, and Niklas Elmqvist. 2019. InsideInsights: Integrating Data-Driven Reporting in Collaborative Visual Analytics. Computer Graphics Forum (Proc. IEEE EuroVis 2019), 2019. DOI: https://diglib.eg.org/handle/10.1111/cgf13717.


For an overview, read [our Medium blog post](https://medium.com/hcil-at-umd/on-the-inside-of-insight-fbb850532fd3).


## Installation

InsideInsights is build upon [Vistrates](http://vistrates.org) (a visualization component model), [Codestrates](http://codestrates.org) (a JavaScript-based computational notebook), and [Webstrates](https://webstrates.net). In essence, users alternate between the notebook interface and the InsideInsights interface as needed. 

In order to use InsideInsights, you need to setup a server with Webstrates and Codestrates first. See the also [Codestrates GitHub repo](https://github.com/Webstrates/Codestrates) as well as the [Webstrates documentation](https://webstrates.github.io/#doc-2019-05-16-gigwrdtxkn) for more details.

InsideInsights itself is implemented as Vistrates meta-package. As we have slightly adapted Vistrates itself (e.g. to support composite components), please use the version provided in the repo here.
The Codestrates package management offers a *Import Packages* option, where you can upload the zip-file or directly link to this repo.

Please note that you still need to manually install and configure visualizations [from the Vistrates framework](https://github.com/karthikbadam/Vistrates).
