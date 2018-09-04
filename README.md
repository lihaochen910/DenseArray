**DenseArray** is a library that uses only one-dimensional arrays to implement multidimensional arrays.<br>
**DenseArray** 是一个只使用一维数组去实现多维数组功能的库.

### Features
* less memory usage
* DenseArray has better read and write performance than traditional arrays, Such as '[,]' or '[][]'


### Usage
Code:
```csharp
var dense = new DenseArray2D<int>(3, 3);
dense[0, 2] = 42;
```

### How it works
- Example in 2D
![Example in 2D](https://eli.thegreenplace.net/images/2015/column-major-2D.png)
![index](https://eli.thegreenplace.net/images/math/ab533f15375dcdb69e7affdd1a4c835e146b7751.png)

- Example in 3D
![Example in 2D](https://eli.thegreenplace.net/images/2015/row-major-3D.png)
![index](https://eli.thegreenplace.net/images/math/3952a22345f3e71ecbf5b74899d875ca2b9035f2.png)


### Reference
Code from [here](https://www.codeproject.com/Articles/1064915/A-Generic-Fast-implementation-of-a-dimensional-de)
and [here](https://dzone.com/articles/memory-layout-of-multi-dimensional-arrays-1).


### Note
Please note class 'DenseArray3D' has not been tested.
