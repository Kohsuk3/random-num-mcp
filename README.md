# Random Number MCP Server

![Header Image](assets/header.svg)

## 🎲 概要
このプロジェクトは、ランダムな数字を生成するMCPサーバーです。TypeScriptで実装されており、簡単にランダムな数字を取得することができます。

## 🚀 使用方法
1. プロジェクトをクローンします。
   ```bash
   git clone git@github.com:Kohsuk3/random-num-mcp.git
   cd random-num-mcp
   ```

2. 依存関係をインストールします。
   ```bash
   npm install
   ```

3. MCPサーバーを起動します。
   ```bash
   npm run build
   node build/index.js
   ```

## 🖥️ Claude Desktopでの利用方法
1. MCPサーバーを起動した状態で、Claude Desktopを開きます。
2. 設定ファイルに以下の内容を追加します。
   ```json
   {
     "mcpServers": {
       "random-number": {
         "command": "node",
         "args": ["path/to/random-number-server/build/index.js"]
       }
     }
   }
   ```
3. Claude Desktopを再起動し、MCPサーバーが利用可能になっていることを確認します。

## 📄 ライセンス
このプロジェクトはMITライセンスの下で公開されています。