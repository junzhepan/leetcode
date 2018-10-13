# 48. Rotate Image
## 算法
题目要求把一个矩阵顺时针旋转90度。
主思路是先把矩阵转制，然后再把每行逆序即可。举例：
```
1 2 3       1 4 7       7 4 1
4 5 6  ->  2 5 8  ->  8 5 2
7 8 9       3 6 9       9 6 3
```

## 复杂度
- 时间复杂度：`O(N^2)`
- 空间复杂度：`O(1)`
