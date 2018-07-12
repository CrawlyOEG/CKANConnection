(Under construction) CKANConnection
===================================================

`CKANConnection` is a library to upload metadata on a CKAN.

© 2018 Jorge Galán - OEG-UPM. Available under Apache License 2.0. See [`LICENSE`](LICENSE).

## Description

The main idea of the following code is to make an automatic process or batch in which every day at a certain time a series of metadata contributing to the open portal are downloaded from the sources provided by the [WebCrawler](https://github.com/CrawlyOEG/WebCrawler) library and manage them with the [PDFExtractor](https://github.com/CrawlyOEG/PDFExtractor) library. To do this, you will need to have a record of those already managed and only download the new ones. The following code contains a basic structure to continue it.

## Building from Source

Clone this repo and run:

```
mvn clean compile assembly:single
```

Then, get your own version of the jar in the project's `target` folder.

<a title="OEG Laboratory" href="http://www.oeg-upm.net/" target="_blank"><img alt="OEG Laboratory" src="http://stars4all.eu/wp-content/uploads/2016/10/OEG.png" width="220" height="220"></a>
<a title="STARS4ALL" href="http://stars4all.eu" target="_blank"><img alt="STARS4ALL" src="http://linkeddata4.dia.fi.upm.es/wordpress-new/wp-content/uploads/2016/12/logo_dark.png" width="220" height="220"></a>