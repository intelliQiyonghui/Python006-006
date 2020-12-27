###学习笔记

# def fib(N):
#     # print(N)
#     if N <= 1:
#         return N
#     return fib(N-1) + fib(N-2)


# print(fib(3))

# import time
# print(time.localtime())
# print(time.strftime("%Y-%m-%d %X",time.localtime()))
# print(time.strptime('2020-12-27 14:19:21',"%Y-%m-%d %X"))

# from datetime import *
# print(datetime.now())
# print(datetime.today())
# print(datetime.today() - timedelta(days=1))

#IndentationError：unexpected indent，什么意思呢？
#indentation是缩进，缩排的意思。unexpected indent 就是说“n”是一个“意外的”缩进。也就是说，这里的问题就是指“n”是一个意外的缩进。
# 通过查看源代码可知这里的确是缩进了一个字符位。据此推断，我们把这句话的缩进取消，也就是顶格写

# from random import * 
# print(random())
# #0到100之间的偶数
# print(randrange(0,100,2))
# print(choice(["red","blue","green"]))
# print(sample([1,2,3,4,5],k=4))

import json
print(json.loads('["foo",{"bar":[null,"baz",1,0,2]}]'))
print(json.dumps("['foo', {'bar': [None, 'baz', 1, 0, 2]}]"))

from pathlib import Path
p = Path()
print(p.resolve())