Tricks
========================================
- is_numeric 前后有空格时，不会判断为true
- 松散比较时，两个0e开头的不同哈希会判断为相等
- 松散比较时，非数字的字符串序列和数字比较会自动转换
- strcmp/ereg 等函数在传入参数类型为数组时会有非预期行为
