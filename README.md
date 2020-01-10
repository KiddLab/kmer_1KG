# kmer_1KG
QuicK-mer2.0 K-mer analysis of new 30x coverage 1000 Genomes Data

Load the trackhub in the UCSC browser with this link:

https://raw.githubusercontent.com/KiddLab/kmer_1KG/master/kmer-1KG.hub.txt

Files were generated using QuicK-mer2 available at https://github.com/KiddLab/QuicK-mer2

If you are interested in generating copy-number estimates based on multi-mapping reads,
consider  fastCN, accessible at: https://github.com/KiddLab/fastCN

## Heat map tracks

The most useful tracks are the copy number heat maps for each sample.  These are organized by
population.  You can use the UCSC track control to select  a subset of samples to display.  
The tracks are best viewed in dense mode.  Note, that if you zoom out too far the tracks will
only display as black.

The heat map key is:

![heat map color key](heat-map-key-small.png)


## Access to raw estimates
Due to file size limitations, only the heat map tracks can be loaded here.  The raw
copy number estimates (in bigWig format) can be found here: https://kiddlabshare.med.umich.edu/kmer-1kg_bw/

Let us know if you need guidance in making custom tracks from these files.


## How to load the track hub

Go to http://genome.ucsc.edu/

Click on My Data --> Track Hubs

click the 'My Hubs' tab
 
paste in this address: https://raw.githubusercontent.com/KiddLab/kmer_1KG/master/kmer-1KG.hub.txt

Click 'Add Hub'
