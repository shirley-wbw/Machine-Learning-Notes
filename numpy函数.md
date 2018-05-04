# numpy函数用法 #

## shape用法 ##

- shape函数是numpy.core.fromnumeric中的函数。功能是读取矩阵长度，如shape[0]即读取矩阵第一维度的长度。


## tile用法 ##

- 先from numpy import *
-  tile函数是numpy.lib.shape_base中的函数。功能是重复某个数组，如tile(A,n)即将数组A重复n次，构成一个新数组。


## 数组对象 ##

- 先import numpy as np
- 使用array()方法来创建对象，它的参数是一个list对象。

## reshape函数 ##

- 先import numpy as np
- 重定义数据的形状，形状变化的原则是数组元素不能发生改变。

## dtype属性 ##

- 先import numpy as np
- 数组名.dtype。类型可以有整型int32，float64，complex。
- 可以使用typeDict字典来查询某种字符串所代表的数据类型，如np.typeDict['double']:<tuype 'numpy.float64'>

## arange() ##

- 先import numpy as np
- arange常用来创建等差数组，略微类似range。arange返回的是一个数组，range返回的是list。arrge里也有步长。
- 如range(3)>[0,1,2]，arange(3)>([0,1,2])。

## linspace()创建等差数列 ##

- 先import numpy as np
- np.linspace(起始点，终止点，元素个数)，还可以使用参数endpoint来决定是否包含终止值，默认是True，即包含终止点。

## logspace()创建等比数列数组 ##
- 先import numpy as np
- np.logspace(起始点，终止点，元素个数，base=数字)，起始点，终止点指的是基数的多少次幂。默认基数为10，可以通过改base值来更改基数。
- 还可以使用参数endpoint来决定是否包含终止值，默认是True，即包含终止点。

## zeros创建0矩阵 ##
- 先from numpy import *
- zeros(数字，元素类型)，默认是浮点型，创建一维0矩阵。
- zeros(list，元素类型)，创建二维0矩阵。以此类推。

## ones和empty创建数组 ##
- 先from numpy import *
- 用法同zeros，ones可以创建任意维度和元素个数的数组，其元素均为1。
- 用法同zeros，empty函数创建的数组所有元素均为随机无意义的值。

## fromfunction以函数式创建数组 ##
- 先from numpy import *
- 用法同zeros，empty函数创建的数组所有元素均为随机无意义的值