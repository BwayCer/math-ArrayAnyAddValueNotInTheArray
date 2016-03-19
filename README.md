數列中的數值任意相加仍不與數列中的值重複
==========


## 故事情節

小花想重數列中取出任意個數的值相加，其總和的值不與數列中的值重複，請問其數列為何？

_# 小花純粹無聊_<br />
_# 原本在想 linux chmod 權限設定的方式，然後寫了此算式_<br />
_# 上述的東東最後想通原來是二進位 -.-_



## 使用說明

### 使用方式：

```js
//設定起頭的兩個數值 NumA, NumB。
//>> 數值 NumA 小於 NumB。
//>> 可選執行次數 NumLimit。
jNoDoubleNum( [ NumA, NumB ], NumLimit )

//停止執行。
jTimer.stop()

//繼續執行。
jTimer.continue( NumContinueLimit )

//設定執行間隔毫秒數。
jTimer.ms = NumMS
```


### 顯示訊息：

```js
//顯示說明。
jGetInfo("booklet")

//顯示整理訊息。
jGetInfo()

//顯示已排除的數值（含有效個數）。
jGetInfo("rmNum")
```


## 免責說明

經過誠意修補，致力讓本文件有更好的體驗，且通過數毫秒的查核，其公信力不言可喻。

