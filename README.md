# 计算器
传入计算文本辅助计算

## 示例
```php
$Interpreter=new Interpreter(new Lexer("1+1"));
$count=$Interpreter->expr();
unset($Interpreter);
echo $count;
```
