# JavaScript中文网在线开发者工具

JavaScript中文网面向前端和全栈开发者，提供 JavaScript、TypeScript、前端工程化、Web API 教程，以及一组可以直接在浏览器中使用的开发者工具。

本项目整理了这些工具的使用入口和说明。工具无需安装，输入内容默认在浏览器本地处理，适合日常开发、接口调试、文档编写和学习练习。

> 平台主页：<https://www.javascriptc.com/>  
> 在线工具目录：<https://www.javascriptc.com/tools/>

## 工具一览

| 工具 | 适合解决的问题 | 主要功能 | 在线使用 |
| --- | --- | --- | --- |
| [JSON 格式化与校验](./json-formatter/README.md) | 接口响应、配置文件或日志中的 JSON 难以阅读或存在语法错误 | 格式化、压缩、校验、复制、下载 | [打开 JSON 工具](https://www.javascriptc.com/tools/json-formatter/) |
| [JWT 解码](./jwt-decoder/README.md) | 排查 JWT 的 Header、Payload、Claims 和过期时间 | 本地解码三段式 JWT，查看常见时间字段 | [打开 JWT 工具](https://www.javascriptc.com/tools/jwt-decoder/) |
| [正则表达式测试](./regex-tester/README.md) | 不确定 JavaScript 正则是否匹配预期文本 | 匹配结果、位置、捕获组、替换预览 | [打开正则工具](https://www.javascriptc.com/tools/regex-tester/) |
| [Cron 表达式生成器](./cron-generator/README.md) | 配置 Linux 定时任务时不确定五字段表达式写法 | 生成、检查和解释标准 Unix Cron 表达式 | [打开 Cron 工具](https://www.javascriptc.com/tools/cron-generator/) |
| [Markdown 转 HTML](./markdown-to-html/README.md) | README、文档或博客草稿需要转换成 HTML | 转换、预览、复制和下载 HTML | [打开 Markdown 工具](https://www.javascriptc.com/tools/markdown-to-html/) |

## 为什么提供这些工具

开发者经常需要处理一些短而明确的任务：检查一段 JSON、查看 JWT 内容、验证一个正则、生成定时表达式，或者把 Markdown 草稿转换成 HTML。为这些任务安装大型软件或上传到陌生服务并不方便，因此 JavaScript中文网将它们做成了可以直接访问的浏览器工具。

这些工具也对应 JavaScript中文网的内容方向：

- 工具解决即时问题；
- 教程解释背后的原理和常见错误；
- 示例帮助用户把结果放进真实项目；
- GitHub 页面提供公开说明和反馈入口。

平台上的教程和专题可以从这里开始浏览：

- [JavaScript 教程与前端基础](https://www.javascriptc.com/special/efficiently/)
- [TypeScript 专题](https://www.javascriptc.com/special/typescript/)
- [前端工程化专题](https://www.javascriptc.com/special/frontend-engineering/)
- [Web API 与调试专题](https://www.javascriptc.com/special/web-api/)
- [全部开发者工具](https://www.javascriptc.com/tools/)

## 隐私与安全边界

- 工具输入默认在浏览器中处理，不发送到 JavaScript中文网或第三方 API；
- 不需要注册账号，也不会要求上传文件到服务器；
- JWT 解码只读取 Header 和 Payload，不验证签名；
- JWT Payload 通常是编码而不是加密，不能把解码结果当作安全凭证；
- 请勿在任何在线工具中粘贴生产环境密钥、密码、Cookie、访问令牌或个人数据；
- 使用 Cron 工具部署任务前，应确认目标系统的语法和服务器时区。

## 适合收藏和分享的入口

- [JavaScript中文网首页](https://www.javascriptc.com/)
- [在线开发者工具目录](https://www.javascriptc.com/tools/)
- [JSON 格式化与校验](https://www.javascriptc.com/tools/json-formatter/)
- [JWT 解码](https://www.javascriptc.com/tools/jwt-decoder/)
- [正则表达式测试](https://www.javascriptc.com/tools/regex-tester/)
- [Cron 表达式生成器](https://www.javascriptc.com/tools/cron-generator/)
- [Markdown 转 HTML](https://www.javascriptc.com/tools/markdown-to-html/)

## 反馈与贡献

如果发现工具错误、浏览器兼容问题或有新的工具建议，可以通过 [JavaScript中文网联系页面](https://www.javascriptc.com/contact-us/) 反馈。

如果你在自己的项目中引用这些工具，欢迎在 Issue 中说明使用场景。提交反馈时，最好附上：

1. 使用的浏览器和版本；
2. 输入内容的最小可复现示例（请先删除敏感信息）；
3. 预期结果和实际结果；
4. 对应的在线工具地址。

## 相关说明

本仓库主要提供工具入口、使用场景和安全说明；在线工具的实际运行版本由 JavaScript中文网维护。发布到 GitHub 后，请保留本 README 的工具说明和在线地址，避免只留下没有上下文的裸链接。
