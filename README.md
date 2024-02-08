# 计算器
传入计算文本辅助计算

__支持运算符号__
> 加+  
> 减-  
> 乘*  
> 除/
> 支持()混合运算

## 示例
```php
$Interpreter=new Interpreter(new Lexer("1+1"));
$count=$Interpreter->expr();
unset($Interpreter);
echo $count;
```
## 留言
  手机写的很烂是这样的
