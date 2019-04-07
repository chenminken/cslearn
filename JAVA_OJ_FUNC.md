# JAVA OJ(online judge)常用函数

## String 

###  String.substring(int beginIndex,[int endIndex])

//[endIndex]代表可选的意思

返回从beginIndex开始到<u>endIndex-1</u>结束的子字符串。

endIndex可选，当endIndex为空的时候函数返回从beginIndex到字符串尾部的子字符串。

需要注意的情况：

1. 字符串索引从0开始。
2. 当beginIndex为0，endIndex为正整数时返回整个字符串。
3. 若字符串长度为len, beginIndex 的合法取值范围是[0,len]，包括len。当beginIndex 为len时，返回空字符串。

