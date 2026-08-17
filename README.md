# mall‑performance‑test
基于JMeter的mall电商全链路性能压测项目

## 项目简介
对mall电商后端业务链路做梯度性能压测，覆盖登录鉴权、商品查询、购物车、下单核心接口。
通过梯度加压寻找系统性能拐点，统计TPS、90%/95%响应时间、错误率，使用htop监控服务器CPU负载。

## 环境
- 压测工具：JMeter 5.6.3
- 服务端：Ubuntu + Docker部署mall项目
- 压测执行端：Windows
- 监控工具：htop

## 运行方式
1. 克隆仓库
```bash
git clone https://github.com/Jacker‑OSS/mall‑performance‑test.git
