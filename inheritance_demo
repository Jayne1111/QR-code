

#!/usr/bin/env python3

-- coding:utf-8 --

class Person(object):

	cnt = 0

    def __init__(self, name, sex, age):
    	self.__name = name
    	self.__sex = sex
    	self.__age = age
    
    	Person.cnt += 1
    
    def set_name(self, name):
    	self.__name = name
    
    def set_age(self, age):
    	self.__age = age
    
    def show(self):
    	print("{}, {}, {}".format(self.__name, self.__sex, self.__age))

class Chinese(Person):

	def init(self, name, sex, age, gongfu):

		# super().init(name, sex, age)	

		Person.init(self, name, sex, age)	

		self.__gongfu = gongfu

	

    def show(self):
    	super().show()
    	# print("{}, {}, {}, {}".format(super().__name, super().__sex, super().__age, self.__gongfu))
    	print(self.__gongfu)
    
    def set_gongfu(self, gongfu):
    	self.__gongfu = gongfu
    
    '''
    def show(self, n):
    	print(n)
    '''

class Hubei(Chinese):

	def init(self, name, sex, age, gongfu, rgm):

		super().init(name, sex, age, gongfu)

		self.__rgm = rgm

	

	

def f():

	print("f()")

def f(a):

	print("f(a)")

def f(a, b):

	print("f(a, b)")	

a = f

f(3, 2)

a(2, 3)

f = 3

f(2, 3)

if name == 'main':

	p1 = Person("tom", "male", 23)

	p1.show()

	p1.set_name("jim")

	p1.show()

	print(Person.cnt)

    c1 = Chinese("张三", "男", 25, "太极八卦掌")
    c1.show()
    c1.set_gongfu("九阴白骨爪")
    c1.set_name("张三丰")
    c1.show()
    print(Chinese.cnt)
    # c1.show(100)
    
    Person.dj = 5  # 给Person类动态绑定属性dj
    
    h1 = Hubei("李四", "女", 24, "狮子吼", True)
    h1.show()

	

	





