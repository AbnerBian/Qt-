## widget与view



widget申请空间，对大内存不合适

view 把可视的内存创建

QTableWidget是QTableView的子类，主要的区别是QTableView可以使用自定义的数据模型来显示内容(也就是先要通过setModel来绑定数据源)，而QTableWidget则只能使用标准的数据模型，并且其单元格数据是QTableWidgetItem的对象来实现的(也就是不需要数据源，将逐个单元格内的信息填好即可)

## 虚函数

被调用者覆盖

隐藏与覆盖

~~~~c
for(int i=0)
{
    
}
//i存在于for循环内
//局部变量
静态全局变量

静态成员函数/变量属于类
声明static，不能使用this指针。通过类名：静态方法调用

~~~~





## 标准模板库

list链表

vector数组

















