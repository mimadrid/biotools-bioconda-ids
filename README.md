# Repository to facilitate the ID mamping among the ELIXIR tools platform resources.
## forked from https://github.com/BioContainers/biotools-bioconda-ids 

## Working files from bio.tools, bioconda/biocontainers & galaxy should follow this format:
`<stable tool ID><tab><URL><tab><Relevant URLs separated by ";"><tab><anything else separated by ";">`

### Example taking bio.tools as data source:
`signalp<tab>https://bio.tools/signalp<tab>http://cbs.dtu.dk/services/SignalP/;http://www.cbs.dtu.dk/cgi-bin/sw_request?signalp<tab>doi:10.1038/nmeth.1701`

## This data should allow to generate something in this direction
*Importantly, canonical IDs should be preferentially the ones provided by bio.tools*

```
Canonical ID <tab>bio.tools namespace: bio.tools ID <tab>bio.tools URL<tab>other bio.tools relevant data`
Canonical ID <tab>galaxy namespace: galaxy ID       <tab>Galaxy URL <tab>other Galaxy relevant data`
Canonical ID <tab>bioconda namespace: bioconda ID    <tab>bioconda URL <tab>other bioconda relevant data`
```
