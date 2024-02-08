# 计算器
传入计算文本辅助计算

+ 支持运算符号
  +
  -
  *
  /

## 示例
```php
$Interpreter=new Interpreter(new Lexer("1+1"));
$count=$Interpreter->expr();
unset($Interpreter);
echo $count;
```
## 留言
  手机写的很烂是这样的
