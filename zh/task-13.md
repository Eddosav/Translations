这个编程联系类似用于计算CRC和其他校验和以及字符串上的哈希函数的更复杂的算法。此外，它还会给你提供一个将值拆分成十进制数字的练习。在此之前你可能通过计算 [Sum of Digits][1] 来练练手。

然我们开始计算数字之和的练习吧，就像之前所说的，但是这里是将每位数字乘以数字所在的位置（从左到右，从1开始）。例如，给定了一个数字 `1776`，我们计算出这个 **加权数字之和** （我们就称之为"wsd"吧）为：

    wsd(1776) = 1 * 1 + 7 * 2 + 7 * 3 + 6 * 4 = 60

**输入数据** 会在第一行给出测试案例的个数。

数据在第二行给出，你需要计算给出的每个数据的加权数字之和。

**答案：** 跟往常一样，把结果放到同一行，用空格隔开。

举个栗子：

    input data:
    3
    9 15 1776

    answer:
    9 11 60

[1]: https://www.codeabbey.com/index/task_view/sum-of-digits