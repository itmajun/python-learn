# 我的python学习记录

## 基本结构

1. 编码指定:
`# -*- coding: UTF-8 -*-`
2. 流程控制:

    1.  **条件语句-if**
    ```
    if x < 0:
        pass
    elif x == 0:
        pass
    else:
        pass
    ```
    2. **循环语句-for**
    
    ```
    for i in range(5):
        pass
    ```
3. 数据结构:

    ```
        a = [22,33,44] //list
        a.insert(2,-1)
        a.append(55)
        a.index(22)
        a.remove(22)
        a.reverse()
        a.sort()
        a.pop()
        del a  //删除列表
        
        t = 1,2,3,'hello' //元组
        u = t,(1,2,3) //元组
        h = 'tt', //元组
        
        m = set('aaaabbbccc') //set
        
        d = {'t1':222, 't2': 333} //dict
        
        //循环dict
        for k, v in d.items():
            print(k,v)
            
        //循环列表
        for i, v in enumerate(['a','v','c']):
            print(i, v)
            
        //zip 循环两个序列 按照顺序取值
        q = ['name','age']
        an = ['mn','22']
        for q, a in zip(q, an):
            print(q, a)
    ```
    
4. main方法模板:

    ```
    if __name__ == "__main__":
        pass
    ```

5. 异常处理:

    ```
    try:
        
    except:
    
    else:
    
    finally:
    ```
    
6. 类模板:

    ```
    class Sample:
        """类文档说明"""
        i = 123 //类属性
        __private_name = 222 //私有变量    
        def __init__(self,name):
            self.name = name
        
        def f(self)://类方法
            return 'hello'
    
    
    ```



