# RunBacteria
PluMA pipeline to generate microbial social networks (Fernandez et al, 2015).

Starts from raw abundances, and computes correlations and first- and second-level clusters.
Then computes various tightness measures, followed by centrality.
Finally, produces a final set of graphs:

1. Spring layout
2. Fruchterman-Reingold
3. Spring layout, with centrality denoted by opacity

Green edges are positive, red edges are negative.
Node size is proportional to abundance
Edge thickness is proportional to magnitude 
