# Oneliner
---
这是一个 包含了 只需要一行 instruction sequence 即可完成目标的 仓库.

将每一条记录称为 liner

这个仓库 涵盖了很多方面 如下载 安装 POC验证 EXP利用 等.

仓库遵循 content first 原则.

格式要求
````
## category <!-- 分类, 也是liner的 头部 --> <!-- 由管理员 识别并合并 -->
### title
> ***<date YY-mm-dd>: <author|mail>***
[> **<description>**] <!-- 描述信息 -->
```lang <!-- 该部分可有多个 -->
instruction
```
--- <!-- 当前liner的 分割线 也是尾部 -->
````
## 目录
* [Rust](#rust)
  * [Linux安装Rust环境](#linux安装rust环境)
* [渗透测试](#渗透测试)
  * [Linpeas.sh枚举提权信息](#linpeassh枚举提权信息)

<!-- 列表头 -->
## Rust
### Linux安装Rust环境
> ***2024-6-25: fb0sh***
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
> **(中国区环境)**
```bash
export RUSTUP_DIST_SERVER="https://rsproxy.cn";export RUSTUP_UPDATE_ROOT="https://rsproxy.cn/rustup";curl --proto '=https' --tlsv1.2 -sSf https://rsproxy.cn/rustup-init.sh | sh
```
---


## 渗透测试
### Linpeas.sh枚举提权信息
> ***2024-6-25: fb0sh***
```bash
curl -L https://github.com/peass-ng/PEASS-ng/releases/latest/download/linpeas.sh | sh
```
> **python2**
```python2
python -c "import urllib.request; urllib.request.urlretrieve('https://github.com/peass-ng/PEASS-ng/releases/latest/download/linpeas.sh', 'linpeas.sh')"
```
> **python3**
```python3
python3 -c "import urllib.request; urllib.request.urlretrieve('https://github.com/peass-ng/PEASS-ng/releases/latest/download/linpeas.sh', 'linpeas.sh')"
```
--- 

<!-- 列表尾 -->
