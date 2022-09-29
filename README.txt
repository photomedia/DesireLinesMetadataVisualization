Source Code and Data for Metadata Visualization for the Desire Lines Speaker Series
https://agyu.art/project/desire-lines/

Visualization available at:
http://photomedia.ca/visualizations/artexte/sigma/agyu/

Artexte metadata was converted into a graph using a fork of:
https://github.com/photomedia/EPrintsData2GML

Gephi (https://github.com/gephi/gephi) was used for filtering and layout of the graph.

Interactive export to SigmaJS using Sigma JS Exporter in Gephi
https://gephi.org/plugins/#/plugin/sigmaexporter 

Data was further enriched with WikiData and VIAF using OpenRefine, and minified (for quicker load time):
data-refined-minify.json

data.zip file contains two additional files:
data.json -- this is the original export from Gephi
data-refined.json -- this is the graph file with additional VIAF and WikiData links resolved using OpenRefine