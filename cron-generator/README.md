# Unix Cron 表达式生成器

JavaScript中文网的 Cron 工具用于生成和检查标准五字段 Unix Cron 表达式，适合配置 Linux 定时任务和 CI 任务。

## 在线使用

<https://www.javascriptc.com/tools/cron-generator/>

## 五个字段

```text
分钟 小时 日期 月份 星期
```

示例：

```text
0 9 * * 1-5
```

表示工作日每天 9:00 执行。

## 支持的写法

- `*`：任意值；
- `1,3,5`：列表；
- `1-5`：范围；
- `*/15`：步进；
- 内置每分钟、每小时、每天、工作日和每月示例。

## 注意事项

工具针对标准五字段 Unix Cron。不同系统、云平台和调度器可能有秒字段、特殊宏或不同的时区规则。部署前请确认目标平台的语法和服务器时区。

在线使用：<https://www.javascriptc.com/tools/cron-generator/>
