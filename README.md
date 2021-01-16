# school-report
今までに学校で出されたReportの回答を載せておく。
## Report-6
### 1　10から1までの二乗した数を算出
実行結果は、
```
100
81
64
49
36
25
16
9
4
1
```
### 2　20人の点数を入れると偏差値を返す
入力したものは
```
95
45
88
67
40
20
10
23
45
34
32
34
5
67
56
32
34
12
34
67
```
実行結果は
```
71.9957
51.245
69.0906
60.3753
49.17
40.8697
36.7196
42.1148
51.245
46.6799
45.8499
46.6799
34.6445
60.3753
55.8102
45.8499
46.6799
37.5496
46.6799
60.3753
```
### 3　10個の数の最小値を算出
ケース1
```
10 8 4 2 5 9 7 1 3 6
```
実行結果は
```
1
```
ケース2
```
10 8 -4 2 -5 9 -7 1 -3 6
```
実行結果は
```
-7
```
ケース３
```
-10 -8 -4 -2 -5 -9 -7 -1 -3 -6
```
実行結果は
```
-10
```
## Report-7
### 1　多次元配列の基本
出力結果
```
1
2
3
4
```
### 2　3のべき乗
出力結果
```
9
27
81
243
729
2187
6561
19683
```
### 3　codからsinを算出
ケース1
```
0.5
```
実行結果は
```
0.866025
```
ケース2
```
2
0
```
実行結果は
```
1
```
### 4　直角三角形の斜辺の算出
出力結果
```
3
4
5
```
### 5　θを入力するとsin,cos,tanを出力する
ケース1
```
0 
```
実行結果は
```
0 1 0
```
ケース2
```
45
```
実行結果は
```
0.707107 0.707107 1
```
ケース3
```
90
```
実行結果は
```
1 0 0
```
tanの値は本来ないため0と出力させてます。
### 6　定義されたθに対してsinθをCSV形式で出力
出力結果は
```
-3.14159,-1.22461e-16
-3.07876,-0.0627905
-3.01593,-0.125333
-2.9531,-0.187381
-2.89027,-0.24869
-2.82743,-0.309017
-2.7646,-0.368125
-2.70177,-0.425779
-2.63894,-0.481754
-2.57611,-0.535827
-2.51327,-0.587785
-2.45044,-0.637424
-2.38761,-0.684547
-2.32478,-0.728969
-2.26195,-0.770513
-2.19911,-0.809017
-2.13628,-0.844328
-2.07345,-0.876307
-2.01062,-0.904827
-1.94779,-0.929776
-1.88496,-0.951057
-1.82212,-0.968583
-1.75929,-0.982287
-1.69646,-0.992115
-1.63363,-0.998027
-1.5708,-1
-1.50796,-0.998027
-1.44513,-0.992115
-1.3823,-0.982287
-1.31947,-0.968583
-1.25664,-0.951057
-1.19381,-0.929776
-1.13097,-0.904827
-1.06814,-0.876307
-1.00531,-0.844328
-0.942478,-0.809017
-0.879646,-0.770513
-0.816814,-0.728969
-0.753982,-0.684547
-0.69115,-0.637424
-0.628319,-0.587785
-0.565487,-0.535827
-0.502655,-0.481754
-0.439823,-0.425779
-0.376991,-0.368125
-0.314159,-0.309017
-0.251327,-0.24869
-0.188496,-0.187381
-0.125664,-0.125333
-0.0628319,-0.0627905
4.44089e-16,4.44089e-16
0.0628319,0.0627905
0.125664,0.125333
0.188496,0.187381
0.251327,0.24869
0.314159,0.309017
0.376991,0.368125
0.439823,0.425779
0.502655,0.481754
0.565487,0.535827
0.628319,0.587785
0.69115,0.637424
0.753982,0.684547
0.816814,0.728969
0.879646,0.770513
0.942478,0.809017
1.00531,0.844328
1.06814,0.876307
1.13097,0.904827
1.19381,0.929776
1.25664,0.951057
1.31947,0.968583
1.3823,0.982287
1.44513,0.992115
1.50796,0.998027
1.5708,1
1.63363,0.998027
1.69646,0.992115
1.75929,0.982287
1.82212,0.968583
1.88496,0.951057
1.94779,0.929776
2.01062,0.904827
2.07345,0.876307
2.13628,0.844328
2.19911,0.809017
2.26195,0.770513
2.32478,0.728969
2.38761,0.684547
2.45044,0.637424
2.51327,0.587785
2.57611,0.535827
2.63894,0.481754
2.70177,0.425779
2.7646,0.368125
2.82743,0.309017
2.89027,0.24869
2.9531,0.187381
3.01593,0.125333
3.07876,0.0627905
3.14159,-7.65718e-16
```
## report-8
### 1　3つの変数の最大値を返す
出力結果は
```
3
2
1
3
```
### 2　2点の座標から距離を算出
出力結果は
```
0
0
1
1
1.41421
```
### 3　nの階乗
出力結果は
```
0!=1
1!=1
2!=2
3!=6
4!=24
5!=120
6!=720
7!=5040
8!=40320
9!=362880
```
## Report-9
### 1　配列にある数を2倍にして出力
出力結果は
```
4
8
12
16
20
```
### 2　何が違う？
出力結果は
```
3
3
```
`int y=func(y)`と表記してないため。`int y`の値がそのまま出力された。
### 3　入力した数を逆から出力し、最大値を出力する。
```
2
4
6
8
3
3,8,6,4,2
8
```
