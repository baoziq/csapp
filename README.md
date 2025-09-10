### `bitXor`
根据真值表写出表达式
### `tmin`
32位补码表示的最小值
### `isTmax`
通过异或判断是否等于自身，再取反
### `allOddBits`
先通过与运算将不相关位置0，再判断
### `negate`
各位取反，末位加一
### `isAsciiDigit`
未想到其他做法，只能判断是否相等
### `conditional`
当x为真时，返回y，否则返回z，先将x变为全0或全1，再与y和z进行与运算，根据x的值将其中一个置为0，另一个为本身，再相加
### `isLessOrEqual`
两个数符号相同时，只需要判断x-y的符号就可以
两个数符号不同时，为避免溢出，直接判断符号即可：可通过sign_res & sign_x判断x为正还是负
还需判断两个数是否相等
### `logicalNeg`
一个数（非0）与负数取`|`,结果为负数，所以除0外的数与自己的相反数取`|`，符号位为1
符号位为1，右移，高位补1
符号位为0，右移，高位补0
所以右移31位，结果为全0或全1，再加1，结果为1或0
### howManyBits
todo
### floatScale2
todo
### floatFloat2Int
todo
### floatPower2
todo
