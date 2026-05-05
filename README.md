更多合肥工业大学学习资料：https://github.com/Tuning-Luna/HFUT_XC_Study_Things

# 📝 课堂测试系统（C++）

一个基于 C++ 的控制台测试系统，支持试题管理与在线答题。

## 功能

- 试题录入
- 试题修改
- 随机抽题测试
- 自动判题与计分
- 错题查看

## 特点

- 使用静态数组存储（MAX = 100）
- 随机抽题（`rand()`）
- 数据仅保存在内存中（无持久化）

## 使用

```bash
g++ main.cpp -o test_system
./test_system
```
