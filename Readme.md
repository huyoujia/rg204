# 软工204信息管理系统　

```
 kr98k 
 因为我们热爱吃鸡，胜过写代码；

```

1. 我们的项目组成员简介。
　　　1. 李晨　鸡王
     2. 刘博超　







    。。。
    
胡宥嘉
=======
##段金松
热爱编程，无不良嗜好。
=======

＃10人小组　每个人都需要ｃｌｏｎｅ这个项目到本地

然后以ｍａｒｋｄｏｗｎ的方式编辑每个成员的详细信息　并提交到这个项目当中　　


在提交的过程中遇到的问题　记录下来，然后尝试这自己解决　　

如果还是搞不定　google stackoverflow   baidu


# 再做点一点新的小玩意


``` python 
import random   
x = [i for i in random.int(0, 100)]
result = list(map(lambda x: x * 2, x))

```

# 二分查找　

### 思想　

### binary_search

``` python
x  = list(range(999999))

n = 1000
import time
def binary_search(l,n):
    min_value = 0
    max_value = len(l) -1
    tag =0
    while(max_value >= min_value):
        print(tag)
        mid = (max_value + min_value) // 2
        if l[mid] == n:
            return n;
        elif l[mid] < n:
            min_value = mid + 1
        else:
            max_value = mid -1
        tag+=1

if __name__ == "__main__":
    result = binary_search(x,n)
    print(result)

```



# branch 

1. this is new branch



