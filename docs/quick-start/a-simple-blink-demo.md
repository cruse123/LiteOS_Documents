# 点灯演示工程（简）

知识点：任务，队列，定时器
业务流程：
1. 创建一个队列（队列大小为1）和两个任务TX/RX
2. TX表示发送队列，RX表示接收队列，RX优先级高于TX
3. TX精确没200ms想队列发送命令，比如100
4. RX接收从队列中读取数据，如果等于100，控制灯LED开关

## 项目背景

## 环境准备

## 源码解读

## 功能验证