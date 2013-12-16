This module contains related SOLR server plugins for extracting contents from PDF and DOC files.

## Installation

composer require silverstripe/fulltextsearch-extract


Add this to your custom solrconfig.xml

	<!-- Include solr extraction + dist Required fulltextsearch-extract module to be installed  -->
	<lib dir="../../fulltextsearch-extract/dist" regex="apache-solr-cell-\d.*\.jar" />
	<lib dir="../../fulltextsearch-extract/contrib/extraction/lib/" />
