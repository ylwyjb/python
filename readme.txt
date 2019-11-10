高级函数
    1.可以将变量指向一个函数，例如 f = abs
    2.一个函数可以接收另一个函数作为参数，这种函数就称之为高阶函数
    3.map(函数，[Iterable])，map将传入的函数依次作用到序列的每个元素，并把结果作为新的Iterator返回。
    4.reduce(函数,[Iterable])，reduce将一个函数（必须接受两个参数）作用于序列，将函数结果与序列的下一个元素做累计计算
        from functools import reduce
    5。字符床也可看成一个序列：例如map(f,'123456')
    