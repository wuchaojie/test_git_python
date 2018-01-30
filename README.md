# test_git

这是一个测试上传github的程序。

程序功能，输出txt中指定内容。并重定向到文件，

设置思路：选取第一个“：”和 第一个“，”作为字典key值；dict["city"+str(i)] 作为字典dict值。

如：

北京今天的天气怎么样

[{city: 北京, confidence: 99.00990099009901, conversation: isover, domain: weather, date: 2017126, place: 北京, action: query, entry: 1, condition: [c_3]}]

北京今天温度

[{city: 北京, confidence: 99.00990099009901, conversation: isover, domain: weather, date: 2017126, place: 北京, action: query, entry: 0, condition: [c_0, c_1, c_2]}]

新文本格式为：

city1: 北京  
city2: 北京



