## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到
<img width="187" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/2ea91157-452f-4113-887b-a6de8e14cf08">

作为上马9年没中签的受害者，我决定做一个`自动化脚本`来签到赚积分，虽然积分对于抽签的权重未可知，但是已知的是一定有用，至于作用多大？ 且看后续的上马抽签结果吧··

### Use 使用

1. Fork本项目
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret <img width="1194" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/d54c5260-3471-4b61-8d5f-18fccd53d9b6">
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">

### TODO
- [x] Cookie登录
- [x] github action 支持
- [x] 用户密码登录
### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
