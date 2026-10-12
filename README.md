# DDLForge

Excel テーブル定義書から CREATE / ALTER を生成する Windows 向けツールです。ALTER と同時に複数項目の UPDATE を生成できます。

## 客户下载

[下载最新便携版](https://github.com/smallannsen-droid/DDLForge/releases/latest)

请选择 `DDLForge-1.2.0-Windows-x64-Portable.zip` 附件，使用提供给您的解压密码完整解压，双击 `DDLForge.exe`。请勿使用 GitHub 自动生成的 Source code 压缩包作为客户安装包。

运行环境：Windows 10 / Windows 11 64 位。已附带运行时，无需另行安装 Python、Node.js 或 Microsoft Excel。操作界面为日文。

## 功能

- 读取 xlsx / xlsm 定义书、文件夹和多个工作簿。
- 输出 Oracle、PostgreSQL、MySQL、SQL Server 的 CREATE / ALTER。
- 支持与旧定义书或保存的定义基准比较。
- 勾选同时生成 UPDATE，指定多个更新字段和值。
- 工具生成 SQL 文件，不连接数据库执行。

UPDATE 没有 WHERE，作用于整张表。具体操作见压缩包内的使用说明。
