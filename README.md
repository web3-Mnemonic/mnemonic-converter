# Mnemonic Converter

BIP39 Mnemonic Code Converter (Generate & Convert).

> ⚠️ **SECURITY WARNING / 安全警告**
> This tool runs entirely locally in your browser. No data is uploaded to any server. 
> **NEVER** use real, funded mnemonic phrases on public online websites. It is recommended to download the code and run it offline for maximum security.
> 
> 本工具完全在您的浏览器本地运行，不会上传任何数据。
> **绝对不要**在公开的在线网站上使用存有真实资产的助记词！强烈建议将代码下载到本地并断网离线使用，以确保绝对安全。

---

## 🇬🇧 English

### Features
- **Generate**: Create secure 12 or 24-word BIP39 mnemonic phrases.
- **Validate**: Check if a given mnemonic phrase is valid according to the BIP39 standard.
- **Convert**: Convert the mnemonic phrase into an Ethereum Address and Private Key (using the standard `m/44'/60'/0'/0/0` derivation path).
- **Offline Support**: All cryptographic operations are performed client-side using `@scure/bip39` and `ethers.js`. 

### How to Use
1. **Generate**: Choose 12 or 24 words and click "Generate".
2. **Convert**: Paste your mnemonic phrase into the text area, click "Validate" to check validity, then click "Convert to ETH Address & Private Key".
3. **Copy**: Use the copy buttons to safely copy the results.

### Deployment
This is a static web application. You can host it anywhere that supports static files (like GitHub Pages).
To run locally, just open `index.html` in your browser, or use a local server (e.g., `python -m http.server`).

---

## 🇨🇳 中文说明

### 功能特性
- **生成助记词**：安全生成 12 位或 24 位 BIP39 助记词。
- **验证有效性**：检查输入的助记词是否符合 BIP39 规范。
- **地址推导**：将助记词转换为以太坊地址及私钥（使用标准推导路径 `m/44'/60'/0'/0/0`）。
- **纯本地运行**：所有加密运算均通过前端库（`@scure/bip39` 和 `ethers.js`）在您的浏览器本地完成，无任何网络请求。

### 使用方法
1. **生成**：在页面顶部选择 12 或 24 个单词，点击“随机生成”。
2. **转换**：将您的助记词粘贴到输入框中，可先点击“验证有效性”检查拼写，然后点击“转换为 ETH 地址及私钥”。
3. **复制**：点击“复制”按钮即可安全复制结果。

### 本地运行
这是一个纯静态网页项目。您可以将其部署在任何支持静态托管的平台（例如 GitHub Pages）。
如需在本地运行，直接双击打开 `index.html`，或使用本地服务器（例如 `python -m http.server`）运行。

---
*Disclaimer: This tool is for educational and development purposes. You are solely responsible for the security of your own crypto assets.*
*免责声明：本工具仅供技术学习与开发测试使用，请自行承担资产安全责任。*
