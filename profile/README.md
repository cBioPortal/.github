## cBioPortal
The cBioPortal for Cancer Genomics provides visualization, analysis, and download of large-scale cancer genomics data sets. For a short intro on cBioPortal, see [these introductory slides](https://docs.google.com/presentation/d/1hm0G77UklZnpQfFvywBfW2ZIsy8deKi5r1RfJarOPLg/edit?usp=sharing).

If you would like to know how to setup a private instance of the portal and/or get set up for developing, see the [documentation](https://docs.cbioportal.org). For details on contributing code changes via pull requests, see our [Contributing document](CONTRIBUTING.md).

If you are interested in coordinating the development of new features, please contact cbioportal@cbioportal.org or reach out on https://slack.cbioportal.org.

## 📘 Documentation
See [https://docs.cbioportal.org](https://docs.cbioportal.org)

- The [cBioPortal News page](https://www.cbioportal.org/news) shows user focused release information (e.g. new data and new features)
- The release notes on [GitHub](https://github.com/cBioPortal/cbioportal/releases) provide detailed information for each release for deployers/maintainers of cBioPortal
- Docker Images are available for each tag and branch from [Docker Hub](https://hub.docker.com/repository/docker/cbioportal/cbioportal/tags)

## 🐛 Bug reports and Feature Requests
Please email us at cbioportal@googlegroups.com or file a ticket in the [cbioportal/cbioportal isssue tracker](https://github.com/cBioPortal/cbioportal/issues).

## 📁 Repositories
Read the [Architecture docs](https://docs.cbioportal.org/architecture-overview/) to see how these relate:

- [cbioportal](https://github.com/cBioPortal/cbioportal): Backend
  - Read-only REST API written in Java Spring, which connects to MySQL database 
  - Importer in Java Spring for loading data into MySQL database
  - Validator in Python for checking data file consistency with spec
- [cbioportal-frontend](https://github.com/cBioPortal/cbioportal-frontend): Frontend in TypeScript/React
- [session-service](https://github.com/cbioportal/session-service): User Session Service in Java Spring
- [cbioportal-docker-compose](https://github.com/cBioPortal/cbioportal-docker-compose): Recommended way to install cBioPortal and all its components using Docker
- [codebook](https://github.com/cBioPortal/codebook): Analysis recipes for Python and R that leverage the cBioPortal REST API
- [datahub](https://github.com/cBioPortal/datahub/): Contains all public data files for published studies
- [datahub-study-curation-tools](https://github.com/cBioPortal/datahub-study-curation-tools): Scripts to help curate studies for import into cBioPortal 

## Cite 📚
See [How to Cite](https://docs.cbioportal.org/user-guide/faq/#how-do-i-cite-the-cbioportal) section of docs.
