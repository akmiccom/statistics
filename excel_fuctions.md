# EXCEL Funcions for Statistics

## 基本統計量 Excel関数

|     関数     |         使い方（A1:A3）         |       説明       |
| :----------: | :-----------------------------: | :--------------: |
|     SUM      |           SUM(A1:A3)            |      合計値      |
|   AVERAGE    |         AVERAGE(A1:A3)          |      平均値      |
|    VAR.P     |          VAR.P(A1:A3)           |     標本分散     |
|    VAR.S     |          VAR.S(A1:A3)           |     不偏分散     |
|   STDEV.P    |         STDEV.P(A1:A3)          | 標本分散の平方根 |
|   STDEV.S    |         STDEV.S(A1:A3)          | 不偏分散の平方根 |
| STANDARDIZE  | STANDARDIZE(値,平均値,標準偏差) |      標準化      |
|     MAX      |           MAX(A1:A3)            |      最大値      |
|     MIN      |           MIN(A1:A3)            |      最小値      |
|    MEDIAN    |          MEDIAN(A1:A3)          |      中央値      |
| QUARTILE.INC |      QUARTILE.INC(A1:A3,1)      |   第1四分位数    |
| QUARTILE.INC |      QUARTILE.INC(A1:A3,1)      |   第3四分位数    |

## 統計解析 Excel関数

|    関数     |              使い方（A1:A3）              |         説明 (TRUE: 累積分布関数 FALSE: 確率密度関数)         |
| :---------: | :---------------------------------------: | :-----------------------------------------------------------: |
|  正規分布   |                     -                     |                               -                               |
|  NORM.DIST  |   NORM.DIST(値,平均,標準偏差,関数形式)    |                         正規分布の値                          |
|  NORM.INV   |       NORM.INV(確率,平均,標準偏差)        |                正規分布の累積分布関数の逆関値                 |
| NORM.S.DIST |          NORM.S.DIST(z,関数形式)          |                       標準正規分布の値                        |
| NORM.S.INV  |           NORM.S.INV(累積確率)            |             標準正規分布の累積分布関数の逆関数値              |
|    t分布    |                     -                     |                               -                               |
|   T.DIST    |        T.DIST(値,自由度,関数形式)         |                           t分布の値                           |
|  T.DIST.RT  |           T.DIST.RT(値,自由度)            |                        t分布の右側確率                        |
|  T.DIST.2T  |           T.DIST.2T(値,自由度)            |                        t分布の両側確率                        |
|    TDIST    |        TDIST(値,自由度,分布の指定)        |                    1：片側分布 2：両側分布                    |
|    T.INV    |            T.INV(確率,自由度)             |                  t分布の左側確率の逆関数の値                  |
|  T.INV.2T   |           T.INV.2T(確率,自由度)           |                  t分布の両側確率の逆関数の値                  |
|   T.TEST    | T.TEST(配列1,配列2,検定の指定,検定の種類) |                          t検定の結果                          |
|             |         1：片側検定, 2：両側検定          | 1：対応2標本t検定, 2：等分散2標本t検定　3：不等分散2標本t検定 |