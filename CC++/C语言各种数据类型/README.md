# C语言的各种数据类型

## 32位机

|             类型 | 字节数 |    最小值     |    最大值    |
| ---------------: | :----: | :-----------: | :----------: |
|           `char` |  `1`   |  `-128 或 0`  | `127 或 255` |
|  `unsigned char` |  `1`   |      `0`      |    `255`     |
|    `signed char` |  `1`   |    `-128`     |    `127`     |
|                  |        |               |              |
|          `short` |  `2`   |   `-32768`    |   `32767`    |
| `unsigned short` |  `2`   |      `0`      |   `65535`    |
|                  |        |               |              |
|            `int` |  `4`   | `-2147483648` | `2147483647` |
|   `unsigned int` |  `4`   |      `0`      | `4294967295` |
|                  |        |               |              |
|           `long` |  `4`   | `-2147483648` | `2147483647` |
|  `unsigned long` |  `4`   |      `0`      | `4294967295` |
|                  |        |               |              |
|          `float` |  `4`   |               |              |
|         `double` |  `8`   |               |              |
|    `long double` |  `8`   |               |              |
|                  |        |               |              |

| 类型        | 32位 | 64位 |
| ----------- | ---- | ---- |
| `char`      | `1`  | `1`  |
| `short`     | `2`  | `2`  |
| `int`       | `4`  | `4`  |
| `long`      | `4`  | `8`  |
| `long long` | `8`  | `8`  |
| `指针`      | `4`  | `8`  |
