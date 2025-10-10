# insar
remote sensing
基于现代C++构建的高性能遥感数据处理系统，通过面向对象设计、矩阵运算和并行计算技术，实现了海量栅格数据的运算。

采用C++面向对象设计，将各个处理过程封装为CImage、CInterferogram、CArea等核心类

用GDAL库读取和写入GeoTIFF格式的栅格数据，处理海量的地理栅格数据。

基于LAPACK的sgelss接口实现大规模SVD分解，求解最小二乘问题，使用OpenMP实现多线程并行计算

采用make编译
make all
msbas config.txt


