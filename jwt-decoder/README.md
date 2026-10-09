# JWT Decoder：在线查看 JWT 内容

JWT 通常由 Header、Payload 和 Signature 三段组成。JavaScript中文网的 JWT Decoder 可以在浏览器中查看前两段内容，帮助排查 Claims、过期时间和令牌格式问题。

## 在线使用

<https://www.javascriptc.com/tools/jwt-decoder/>

## 功能

- 支持粘贴完整的三段式 JWT；
- 自动显示 Header 和 Payload；
- 展示 `exp`、`iat`、`nbf` 等时间字段；
- 显示 Signature 编码文本；
- 支持加载示例和复制结果。

## 安全边界

这个工具只做 Base64URL 解码，不验证签名，也不支持五段式加密 JWE。JWT Payload 通常是编码而不是加密，因此不要把“能解码”理解成“安全可公开”。请勿粘贴生产令牌。

在线工具由 JavaScript中文网提供：<https://www.javascriptc.com/tools/jwt-decoder/>
