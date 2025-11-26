# PHASTEST
PHASTEST (PHAge Search Tool with Enhanced Sequence Translation) is a useful web  useful web server created to facilitate the quick identification, annotation, and visualization of prophage sequences in bacterial genomes and plasmids. PHASTEST also enables fast annotation and interactive visualization of all other genes (including protein-coding regions, tRNA, tmRNA, and rRNA sequences) within bacterial genomes.

# PHASTEST
Instalação do Phastest

### Download phastest-docker
```bash
wget -c https://phastest.ca/download_file/phastest-docker -O phastest-docker.zip 
```
* unzip
```bash
unzip phastest-docker.zip 
```

### Download docker-database
```bash
wget -c https://phastest.ca/download_file/docker-database -O docker-database.zip
```

* unzip
```bash
unzip docker-database.zip
```

### mover DB para 
```bash
mv DB phastest/phastest-app-docker/
```

### Run (teste)
```bash
cd phastest/phastest_inputs
docker compose run phastest -i fasta -s seq_test.fna
```

### Citation
David S Wishart, Scott Han, Sukanta Saha, Eponine Oler, Harrison Peters, Jason R Grant, Paul Stothard, Vasuk Gautam, PHASTEST: faster than PHASTER, better than PHAST, Nucleic Acids Research, Volume 51, Issue W1, 5 July 2023, Pages W443–W450, https://doi.org/10.1093/nar/gkad382

