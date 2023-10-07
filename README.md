# DynamicST
自研空转流程

# Manual
## params
  * count
    * --sample：Sample name of each batch,required
    * --id：    Final sample name,required
    * --inputdir：raw data path,required
    * --gtf：genome annotation file
    * --transcriptome：Path of folder containing transcriptome reference
    * --whitelist：Barcode whitelist
    * --barcode：spot list file under tissue
    * --outputdir：output file name
    * --cores: set max cores the pipeline may request at one time
    * --CBposition: position of Cell Barcode(s) on the barcode read(0-base)
    * --UMIposition: position of the UMI on the barcode read, same as CBposition(0-base)
