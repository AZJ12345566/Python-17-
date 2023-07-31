# Python-17-
Python学习笔记(17)
# p56 列表元素的排序操作
lst=[20,40,10,98,54]
print('排序前的列表',lst,id(lst))
#开始排序，调用列表对象的sort方法，升序排序
lst.sort()
print('排序之后的列表',lst,id(lst))  #输出为:[10，20，40，54，98]id

#通过指定关键字参数，将列表中的元素进行降序排序
lst,sort(reverse=True)  #reverse=True 表示降序排序，reverse=False就是升序排序
print(lst)
lst.sort(reverse=False)
print(lst)

#使用内置函数sorted()对列表进行排序，并产生一个新的列表对象
lst=[20,40,10,98,54]
print('原列表',lst)
new_list=sorted(lst)
print(lst)
print(new_list)
#指定关键字参数，实现列表元素的降序排序
sorted(lst,reverse=True)
print(desc_list)



# p57 列表生成式
lst=[i*i for i in range(1,10)]
print(lst)  #输出为1-9
#i*i输出的值为表示列表元素的表达式

lst2=[i*2for i in range()1,11)]
print(lst2)  #输出为2，4，6，8，10...



# p58 什么是字典
#使用{}定义字典，和列表一样是可以增删改，是一个可变序列
#字典是一对一对存储的,冒号之前叫做键，冒号后面叫做值，字典是一个无序序列，列表是一个有序序列
