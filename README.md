# CoExpression_Networks


## Hey look, I found a link to some pre-created co-expression networks for the human post-mortem DLPFC:
https://www.synapse.org/#!Synapse:syn7187666
... but double check their publication, because I believe they removed "surrogate variables" before creating this, which makes me pretty nervous.
Since this data is from post-mortem samples, the main sources of variation the data are likely to relate to dissection and how people died. Therefore, co-expression networks are likely to reflect cell type and perhaps age/health/metabolism/hypoxia.

## Even better: co-expression networks generated from a large sample of freshly-resected human hippocampus (n>100), which were also compared to the post-mortem human hippocampus and mouse.
Here's the paper:
http://www.nature.com/neuro/journal/v19/n2/full/nn.4205.html
The coexpression modules (all nodes - no edges) are in the supplementary tables (S2).
Since this data is from freshly-resected human samples, the main source of variation will probably be related to dissection and pathology (intractable epilepsy - but they tried to remove the variation related to pathology using linear regression modeling). Therefore, these co-expression networks probably strongly reflect cell type and anatomy.  Maybe age/development too - I need to double check their methods, but a lot of times hippocampal resection surgery occurs during childhood.

## Oh awesome: I just found co-expression networks created from a large sample of fresh mouse tissue for the hippocampus and striatum (n=100) too... which are then related back to strain-related differences in conditioned fear responses (yesss....):
https://www.researchgate.net/publication/50408521_Gene_networks_associated_with_conditional_fear_in_mice_identified_using_a_systems_genetics_approach
... and apparently one of the co-authors is my old housemate's brother (Eleazar Eskin). How funny.
The coexpression modules (all nodes - no edges) are in supplementary file 2. 
Since this data is from the whole hippocampi of mice from 100 different strains of selective breeding that were subject to a conditioned fear task, the primary source of variation in the data will probably be genetic or related to different responses to the fear conditioning task. Therefore these co-expression networks may more closely reflect genes that are correlated structurally (cytobands maybe?) or networks of genes responsive to stress or learning/memory processes.
... or anything else that might differ structurally or functionally across strains.

## General network creation (includes data from co-expression and protein-protein interaction experiments):

### FunCoup includes a wide variety of evidence-types:
http://funcoup.sbc.su.se/help/

### Coexpressdb focuses just on standard co-expression and protein-protein interaction data:
http://coxpresdb.jp
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3531062/
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4383961/

### Mouse hippocampal and amygdala co-expression networks... but they only provide the nodal genes for 3 modules in the supplementary section. Jerks.
https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-11-20#MOESM2


