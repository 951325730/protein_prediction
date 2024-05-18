# system requirement
python 3.5.

# installation
1. clone the source code
```
mkdir -p Src && cd Src
git clone 
```
2. install python packages.
``` 
pip3 install -r requirement_gpu.txt
```
3. install dependencies
```
create a program directory
mkdir -p ../programs && cd ../program
```
 - install [SPRINT](https://github.com/lucian-ilie/SPRINT)
 ```
 git clone https://github.com/lucian-ilie/SPRINT.git
 git checkout DELPHI_Server
 make compute_HSPs_parallel
 ```
 
 - install psiblast: 2.6.0+ and download the corresponding nr database. The database is large. You computing cluster should probaly already have a local copy of it.
 ```
 For Ubuntu:
 sudo apt-get install ncbi-blast+
```
 
 - intall [hh-suite](https://github.com/soedinglab/hh-suite). The [database](http://wwwuser.gwdg.de/~compbiol/data/hhsuite/databases/hhsuite_dbs/old-releases/) used in DELPHI is uniprot20_2015_06.
 
 - intall [GENN+ASAquick](http://mamiris.com/software.html)
 
 - install [ANCHOR](http://anchor.elte.hu/Downloads.php)
 
# Running DELPHI
```
./run_DELPHI.sh [input_sequence]
```
