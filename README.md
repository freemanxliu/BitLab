# BitLab
Bit操作相关

### 1. 等比数列的每个数的平方之合
例如： $`1^2 + 2^2 + 4^2 + 8^2 + 16^2 + 32 ^2`$
方法： $`(1 << 11 - 1) & 0x555555 `$
