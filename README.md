This module contains related SOLR server plugins for extracting contents from PDF and DOC files.

## Installation

     $ composer require silverstripe/fulltextsearch-extract
     Please provide a version constraint for the silverstripe/fulltextsearch-extract requirement: 1.0.0
     ./composer.json has been updated

Add this to your custom solrconfig.xml

	<!-- Include solr extraction + dist Required fulltextsearch-extract module to be installed  -->
	<lib dir="../../vendor/silverstripe/fulltextsearch-extract/dist" regex="apache-solr-cell-\d.*\.jar" />
    <lib dir="../../vendor/silverstripe/fulltextsearch-extract/contrib/extraction/lib/" />
