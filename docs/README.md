

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/thebgacademy/ASCC) 
And then Click Continue

```bash
mkdir run_test
cd run_test
nextflow run /workspace/ascc/main.nf --input /workspace/ASCC/BGA_test.yaml -profile docker,gitpod,test --include kmers,tiara,nt_blast,vecscreen,kraken,organellar_blast,fcs-adaptor,fcs-gx,pacbio_barcodes,coverage -config /workspace/ASCC/extra.config
```

this should take ~8 min to run

```
cd /workspace/run_test/null/FCS-adaptor
ls -ltr
cd /workspace/run_test/null/organelle
ls -ltr
```

```
cd /workspace/run_test/null/create/btk_datasets
ls -ltr
cd /workspace/run_test/null/ASCC-main-output
ls -ltr
```
```
less /workspace/run_test/null/ASCC-main-output/asccTinyTest_V2_contamination_check_m
erged_table.csv
```

```
ls -ltr /workspace/pyoelii_full_yaml/create/btk_datasets
```

```
https://grit-btk.tol.sanger.ac.uk/view/Plasmodium%20yoelii%20yoelii%2017XNL/dataset/20240119_pyoelii_test/blob?fcs_gx_div--Active=true&catField=fcs_gx_div&yField=embedding_y_PCA&embedding_x_PCA--Active=true&xField=embedding_x_PCA&embedding_y_PCA--Active=true#Filters
```
