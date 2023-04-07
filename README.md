# Scss

## 指令

## @use
1. 不管使用了多少次样式表，@use 都只会引入和执行一次
2. 与全局使用相反，@use 是有命名空间的，而且只在当前样式表中生效
3. 以 -或者 _开头的命名空间被认为是私有的，不会被引入其他样式表

## @import
1. 使用了多次样式表，@import 回被多次执行和引入
2. 即将被废弃

## @forward

## @extend