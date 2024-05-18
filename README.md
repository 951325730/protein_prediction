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

# Running DELPHI
```
./run_DELPHI.sh [input_sequence]
```
