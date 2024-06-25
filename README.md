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
> <date YY-mm-dd>: <author|mail>
```lang
instruction
```
--- <!-- 当前liner的 分割线 也是尾部 -->
````

<!-- 列表头 -->
## Rust
### Linux安装Rust环境
> 2024-6-25: fb0sh
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
---

### Linux安装Rust环境 (中国区环境)
> 2024-6-25: fb0sh
```bash
export RUSTUP_DIST_SERVER="https://rsproxy.cn";export RUSTUP_UPDATE_ROOT="https://rsproxy.cn/rustup";curl --proto '=https' --tlsv1.2 -sSf https://rsproxy.cn/rustup-init.sh | sh
```
---
<!-- 列表尾 -->
