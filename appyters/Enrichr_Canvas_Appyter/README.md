# Enrichr-Canvas-Appyter

This appyter creates a hexagonal canvas to visualize the similarities between 
gene sets in a selected Enrichr library (or 2 libraries) and a gene list the user
submits. Each hexagon on the canvas represents one gene set from the library the
user selected. The hexagons are colored based on the Jaccard similarity index between 
the user-inputted gene list and the gene set the hexagon represents (the brighter,
the more similar). The hexagons are then placed on a continuous canvas on which
simulated annealing was performed previously so the hexagons representing the most
similar gene sets are grouped together. In the final figure, users can hover over
hexagons to see which gene set they represent and the similarity index between 
that gene set and the gene set they inputted.

Optional: If you want to compare multiple libraries and multiple canvases, you can
choose to normalize the color scaling of the plots so that on both canvases, a
certain color-level means the same Jaccard index.