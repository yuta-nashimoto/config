# Prettier(コードフォーマッター)

## 対象ファイル - .prettierrc

# TypeScript 設定ファイル

## 対象ファイル - tsconfig.json

# Cursor 拡張機能

## 対象ファイル - cursor-extensions.txt

**拡張機能のエクポート方法**

```command
code --list-extensions > cursor-extensions.txt
```

**拡張機能のインポート方法**

```
Get-Content cursor-extensions.txt | ForEach-Object { code --install-extension $_ }
```

# Cursor 設定ファイル

## 対象ファイル - cursor-setting.json
