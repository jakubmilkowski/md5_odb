## README

Program searches for files in specific path and calculates MD5 sum,  
after that it compare that files by MD5 and write out each pair which is the same.  
To speed up whole process program uses [**OpenMP**](http://openmp.org/wp/openmp-specifications/) library. 

### Compilation command:
` g++ md5_omp.cpp -o md5_omp -std=c++11 -fopenmp`

### Run example:
`./md5_omp /home/pywapi-0.3.8/examples/ 4`

### Output example:
![](/http://milkowsky.pl/scr.png)

