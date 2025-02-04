## 基本资料

项目名称：赛凡链 Scifanchain

项目立项日期：2021年5月

相关网站：

- 项目官网：https://scifanchain.com
- 文档：https://docs.scifanchain.com
- 博客：https://blog.scifanchain.com
- api接口文档: https://api.scifanchain.com


## 项目简介

赛凡链以Substrate为基础框架，提供一个去中心化、开放包容、安全智能的科幻创作应用链，为创作者和产业从业者提供存证、共识、驱动引擎和交易、激励、治理模式，创生并推动独具创意、面向未来的科幻创意产业繁荣发展。

### 背景 

随着中国工业和科技升极，一个科幻产业链正在形成。该产业链横跨尖端科技行业、现代制造行业、文创动漫产业、娱乐业，对这些产业产生深远影响。

数字艺术正在成为重要资产。在方兴未艾的科幻产业链条中，居于上游的优秀原创文本作品数量很少，是稀有资源。

### 创意原由

科幻产业理应位于技术变革的前沿。随着科学技术在各领域的迅猛发展，人们对科学的认知与几十年前大不相同。之前人们认为属于科幻的事物如今已经成为现实，人们越来越意识到，现在我们已迈入一个奇特的科幻时代。

在这个时代中，有大量的创造，科学与幻想结合，会给时代注入很多发展元素，产生深远影像。

一个基于区块链的科幻产业链，是这个产业的催化剂、润滑剂，也是这个产业资产数字化、新价值体系构建的必由之路。

### 要解决的问题

项目在发展初始阶段将解决以下问题：

- 协同创作，工作量证明
- 上链存证，创造性解决版权保护与内容分享的矛盾

### logo和文化

<img src="https://github.com/scifanchain/hackathon-2021-summer/blob/main/teams/03-Scifanchain/docs/logo_two.png" alt="logo"/>

- 多元融合。科学与艺术、创意与实践、线上与线下、中心化平台与分布式应用、Rust与Python、人文与AI……海纳百川，取长补短，兼容并收，美美与共。
- 全球视野。我们认为创造无国界，人类是一个命运共同体，这颗星球应当像一个大家庭一样团结起来，共同创造前所未有的灿烂文明。
- 创造未来。立足现实，仰望星空，大胆创新，拥抱理想。

## 黑客松期间计划完成的事项

**整体架构图和黑客松期间功能的流程图**

<img src="https://github.com/scifanchain/hackathon-2021-summer/blob/main/teams/03-Scifanchain/docs/sfc_struct.png" alt="struct"/>
<img src="https://github.com/scifanchain/hackathon-2021-summer/blob/main/teams/03-Scifanchain/docs/sfc_flow.png" alt="flow"/>

**区块链端**

- `pallet-nft`

  - [ ] NFT 创建及数据结构定义
  - [ ] NFT 转帐函数
  - [ ] NFT 销毁函数

- `pallet-poe`

  - [ ] POE 创建存证函数
  - [ ] POE 修改存证
  - [ ] POE 撤消/销毁存证

**服务端**

- api

| 完成进度 | 模块 | 功能说明 | 测试覆盖 
| --- | --- | --- | ---
| 30% | Story | 人物、地点和事件等各类故事元素的CRUD | 0%
| 20% | Era | 星旋宇宙纪元系统 | 0%
| 10% | Auth | 用户鉴权系统 | 0%
| 15% | History | 数据演进过程记录及版本控制 | 0%
| 10% | CORS | 跨源资源共享 | 0%

**客户端**

- web端
  - [ ] 赛凡链官网
  - [ ] 团队博客
  - [ ] 用户文档中心 

- Dapp (react)
  - [ ] 用户注册/登录相关功能
  - [ ] 文本创作流程
  - [ ] 文本借用/引用流程
  - [ ] 用户钱包
  - [ ] 交易查询


## 黑客松期间所完成的事项 (7月5日初审前提交)

- 7月5日前，在本栏列出黑客松期间最终完成的功能点。
- 把相关代码放在 `src` 目录里，并在本栏列出在黑客松期间打完成的开发工作/功能点。
- 放一段不长于 **5 分钟** 的产品 DEMO 展示视频, 命名为 `团队目录/docs/demo.mp4`。

## 团队信息

Github Organization [Scifanchain](https://github.com/scifanchain) 

- unity（欧雪冰），队长，产品策划与设计，《银河书-意谛》<sup id="a1">[[1]](#f1)</sup>作者，官网、应用层、前端开发。著有《诗意的边缘——PHP顶级框架Zend Framework开发实战》（电子工业出版社，2012年）。github账号: [unityoxb](https://githubs.com/unityoxb)
- 柴杰，中国科学技术大学微电子学院研究生，rust中文开源期刊编辑部成员，一年Rust语言经验，非常认同Web3.0的愿景。Substrate层开发。github账号:[
chaijie2018](https://githubs.com/
chaijie2018)
- Stvenyin，拥有丰富的开发经验，深耕区块链技术多年，Substrate层开发。github账号:[stvenyin](https://githubs.com/stvenyin)
- April（李星），白皮书撰写，创意文案，组织推广。github账号:[April593](https://githubs.com/April593)
- 杜禹彤，来自未来的贡献者。github账号:[TinyDuyt](https://githubs.com/TinyDuyt)
- 翟劲儒，平行宇宙实习生。

## 开发路线图

| 时间 | 实现 | 备注
| ---| --- | --- |
| 2001年6月中旬 | 完成应用层基本功能 | 以文本形态为主 |
| 2001年7月5日 | 完成Substrate功能，上传代码 | 实现存证、版本管理和基础治理 |
| 2001年7月12日 | 数据加载 | 注重户体验 |
| 2001年7月15日 | 制作演示视频 | 简要、明晰 |

<span id="f1">1. [^](#a1)</span> 专门为赛凡链创作的银河纪元蓝本，约50万字，全方位构建出了赛凡链的初始宇宙模型和创作框架，为协同创作奠定了基础。
