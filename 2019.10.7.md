# 學習重點
```
1.使用range 函式 的功能建立整數循序數列
2.使用for 廻圈 執行固定次數的廻圈運算(通常)
3.使用while 廻圈執行沒有固定次數的廻圈運算
4.使用continue 指令--- 通常也是用於廻圈中，是在廻圈執行中途暫時停住不往下執行，而跳到廻圈的起始處執行
5.使用break 指令 通常用於廻圈中，可以在廻圈執行中途強迫跳離廻圈，跳到廻圈後面的程式繼續執行。
6.廻圈中又包含廻圈的 巢狀廻圈(nested loop)設計===九九乘法表
```
# range的技術
### range的技術(1)
```
range(7)
```
```
答案是range(0, 7)
```
```
list1=range(7)
list1
```
```
答案是:range(0, 7)
```
```
list(range(7))
```
```
答案是:[0, 1, 2, 3, 4, 5, 6]
```
### range的技術(2)
```
list(range(1,6))
#list2=range(1,6)
#list2
```
```
答案是:[1, 2, 3, 4, 5]
```




# range的技術(3)
```
list3=range(1,6,2)
list3
```
```
答案是:range(1, 6, 2)
```
# range的技術(4)
```
for dd in range(6):
   print(dd)
```
```
答案是:0
1
2
3
4
5
```

# 程式閱讀題:下列程式執行後會印出什麼？
```
list1=range(10)
list2=range(1,10)
list3=range(1,10,2)
list4=range(10,1,-2)

print(list(list1))
print(list(list2))
print(list(list3)) 
print(list(list4))  

```
```
答案是:[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
      
```
### 程式設計題
```
1.產生1,3,6,7的list
2.產生1,3,5,7的list
3.產生1,11,21,31,41,51的list
4.產生51,41,31,21,11,1的list
```
```
答案是:
答案是:list(range(1,8,2))
答案是:list(range(1,60,10))
答案是:list(range(51,1,-10))
```
