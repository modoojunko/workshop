# thoughtworks devops持续集成峰会 2015年7月18日

## 上午分享
### 什么是集成
### 什么是持续集成
1. 7步提交法。
2. 静态检查
2. 持续集成的弱点——部署不是自动化
3. 为什么需要tdd，从一开始就为项目保驾护航，后续需求变动，能快速检测出是否老的功能运行是否正常。


### 持续交付
* 持续价值流动
* 随时可发布
* 快速实验反馈
* 更频繁部署


## 下午
### 7步提交法
* 更新代码
* 运行测试
* 编写代码
* 本地编译
* 本地测试
* 合并重新编译及测试
* 提交代码

### 项目代码提交公约
* 无法本地编译，不能提交
* 本地测试代码（单元测试），不通过不许提交
* 每次合并代码后，重新编译及测试
* 先写测试
* 编码风格和测试覆盖率

### 持续集成与静态分析
* 代码不是机器能跑，人也能懂才是好代码。

#### 持续集成流水线
* 代码变更
* 单元测试
* 静态检查
* 编译出包
* 依赖检查（用的什么库，dependency check，tw自己写的）

### 持续交付
* CI自动化部署
  * 基础设施即代码 低频率
  * 服务器集群初始化即代码 中频率
  * 软件部署即代码 高频率
  * 从高频率到低频率实现自动化




