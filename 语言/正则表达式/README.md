
# 正则表达式

## 常见符号

| 字符     | 含义                      | 举例            |
| -------- | ------------------------- | --------------- |
| +        | `前面的字符出现次数` >= 1 |                 |
| *        | `前面的字符出现次数` >= 0 |                 |
| ?        | `前面的字符出现次数` <= 1 |                 |
| .        | 匹配任何字符              |                 |
| [aeiou]  | 匹配括号里面的字符        |                 |
| [^aeiou] | 不匹配括号里面的字符      |                 |
| [a-z]    | 匹配a-z小写字母           |                 |
| [A-Z]    | 匹配A-Z大写字母           |                 |
| [\s]     | 匹配空白字符              |                 |
| [\S]     | 匹配非空白字符            |                 |
| [\w]     | 等价于[A-Za-z0-9_]        |                 |
| ^        | 以...开头                 | `^a`以a开头的行 |
| $        | 以...结束                 | `z$`以z结束的行 |

## 常见组合

- `.*` 匹配任何

## 保留式追加

括号里面的将保留

```c
([^>}]\n)    ---->   $1<br />
```

## 举例

| 说明                             | 举例            |
| -------------------------------- | --------------- |
| 以 `png` 结束                    | `png$`          |
| 以 `png` 结束行                  | `.*png$`        |
| 有 `换行` `任何` `.` `任何` 的行 | `\n.*\..*$`     |
| 查找中文                         | `[^\x00-\xff]+` |

---
