#Augur
###What is Augur

#####Example Website (running on a development grade web server, *be gentle*): http://augur.sociallycompute.io

Our project is focused on building human centered open source software health metrics defined by collaborations with the Linux Foundation's [CHAOSS Project](https://chaoss.community) and other open source stakeholders. Augur is software focused on making sense of data using four key human centered data science strategies:



1. Enable comparisons. People navigate complex unknowns analogically. Let folks see how their project compares with others they are familiar with.
*This is not ranking*
**If you start thinking about "metrics" like "rankings", you are probably going to create suboptimal metrics.**

2. Make time a fundamental dimension in all metrics from the start. "Point in time scores" are useful. They are more useful if we can see how they compare historically and can be used to anticipate a trajectory.

3. All data driving visualizations should be downloadable as a .csv or other data exchange format. This is because
people trust metrics when they can __*see*__ the underlying data.
Proving traceability back to the [CHAOSS Project](https://chaoss.community)'s metrics standards requires easy transparency.

4. Make all the visualizations downloadable as .svg's. People want to put your visualizations in reports to explain things they care about. Give them the tools. That's what makes folks care about metrics.

Our core team has a long standing interest in social computing, software engineering measurement and the ethical instrumentation of online human behavior.

#####Source Code Repository: http://github.com/OSSHealth/augur
#####List of Metrics: https://github.com/chaoss/metrics/blob/master/activity-metrics-list.md

Several "data providers" are available for the project. A good one to start with is GHTORRENT, because it has a number of readily populated tables in a relational structure. You can learn more about GHTorrent here: GHTorrent is explained here: https://github.com/gousiosg/github-mirror

*Notice there is SQL in those python files*.

The Schema is GHTorrent: http://ghtorrent.org/relational.html http://ghtorrent.org/files/schema.pdf
There are limits to ghtorrent as a data source and we are exploring strategies for incorporating higher trust data in our prototyping activities. Some of these concerns are introduced and discussed in this thread on the CHAOSS mailing list. https://lists.linuxfoundation.org/pipermail/oss-health-metrics/2017-September/000112.html

####Augur Use Cases
Augur has four main use cases:
1. Organizations seek metrics for open source communities before becoming engaged or using the software [1-org-outside]
2. Organizations seek metrics for open source communities that they actively engage or use the software [2-org-engaged]
3. Open source foundations seek metrics for helping open source communities [3-foundation]
4. Open source community leaders seek metrics for managing their communities [4-oss]

---

###Development
*This project reqiures an understanding of the Python programming langugage for development. To learn more about Python [Click Here](https://docs.python.org/3/tutorial/).*

#####To Contribute to Augur's Development: 
Check out our [development guide](https://github.com/OSSHealth/augur/blob/master/DEV-GUIDE.md) and our notes on making contributions. Also, please note our [code of conduct](https://github.com/OSSHealth/augur/blob/master/CODE_OF_CONDUCT.md). We want Augur to be open for everyone and to be a welcoming development community.

#####For Local Development [click here](https://github.com/OSSHealth/augur/blob/master/dev-install.md)
The GHTorrent database.
You can use the *much smaller MSR14 dataset for a quick look or to perform development.
To get Augur up and running quickly, install our docker image. [Installation Instructions for Docker Image](https://github.com/OSSHealth/augur/blob/master/docker-install.md) of Augur

To contribute to our code base routinely, we recommended that developers configure Augur on their local workstations. Get started with our [Installation Instructions for Developers](https://github.com/OSSHealth/augur/blob/master/docs/development/devloperstartup.md), and then check out our development guide

Both configurations require a MariaDB database with a subset of the GHTorrent dataset
#####Hosted Deploymnet [click here](https://github.com/OSSHealth/augur/blob/dev/docs/deployment.md) 

---
###Roadmap

Our technical, outreach, and academic goals [roadmap](https://github.com/OSSHealth/augur/wiki/Release-Schedule).

---

###License and Copyright
Copyright © 2018 University of Nebraska at Omaha, University of Missouri and CHAOSS Project at the Linux Foundation

Augur is free software: you can redistribute it and/or modify it under the terms of the MIT License as published by the Open Source Initiative. See the file [LICENSE](https://github.com/OSSHealth/augur/blob/master/LICENSE) for more details.

(This work has been funded through the [Alfred P. Sloan Foundation](https://sloan.org/about))