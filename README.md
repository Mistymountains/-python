-python
=======

为学习python而建立
# -*- coding:UTF-8 -*- #
# 有中文，所以要定义编码为UTF-8#
def is_divisible_by_2or5(n):
	"""
	# >>> 之后要加一个空格，不然会报错。#
	>>> is_divisible_by_2or5(8)
	True
	>>> is_divisible_by_2or5(7)
	False
	>>> is_divisible_by_2or5(5)
	True
	>>> is_divisible_by_2or5(9)
	False
	"""
	return n % 2 == 0 or n % 5 == 0
if __name__ == '__main__':
	import doctest
	doctest.testmod()
#使用-v进行测试 如 python 2ex2.py -v。
#在ST2中，多个同名参数替换用CTRL+H。
