# 涩涩密文转换器

本项目是一个基于 gsuid-core 的涩涩密文编码/解码插件。

## 功能简介
- **h编码**：将原文内容编码为涩涩密文。
- **h解码**：将涩涩密文解码为原文内容。
- **h帮助**：查看插件使用说明。

## 安装方法

### 方法一：使用 git 安装（推荐）
1. 进入 gscore 插件目录（如 `gscore/plugins`）。
2. 执行：
   ```shell
   git clone https://github.com/jiang068/gscore-plugin-hcode.git
   ```
3. 重启 gscore 。

### 方法二：手动下载文件
1. 访问本插件仓库：[gscore-plugin-hcode](https://github.com/jiang068/gscore-plugin-hcode)。
2. 点击 "Code" → "Download ZIP" 下载并解压。
3. 将解压后的文件夹放入 gscore 插件目录（如 `gscore/plugins`）。
4. 重启 gscore 。

## 使用方法
- 编码：`h编码 你要转换的内容`
- 解码：`h解码 你的涩涩密文`

## 示例
- 编码：
  - 输入：`h编码 我喜欢你`
  - 输出：涩涩密文
- 解码：
  - 输入：`h解码 ❤呼咕咿❤呼唔齁哈唔哈咕噢呼齁啊～`
  - 输出：原文内容

## 原理说明
本插件使用自定义字符表，将 UTF-8 每个字节编码为两位密文字符，实现文本的加密与还原。

## 依赖
- [gsuid-core](https://github.com/Genshin-bots/gsuid_core)

## 版权声明
源码参考于  
[呃嗯！呼～❤呃啊～哼！！呃嗯哈嗯～啊](https://msbt.seku.su/)
