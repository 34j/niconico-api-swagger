# Niconico api swagger

[Link/リンク](https://34j.github.io/niconico-api-swagger/)

APIを試すためには、CORSを無効にする必要があります。[このChrome拡張機能](https://chrome.google.com/webstore/detail/cross-domain-cors/mjhpgnbimicffchbodmgfnemoghjakai)をダウンロードして、

In order to "Try it out" apis, it is required to disable CORS in your browser. Running the following command in PowerShell or Command Prompt will work in windows.

```shell
cmd
"%ProgramFiles(x86)%\Google\Chrome\Application\chrome.exe" --disable-web-security --disable-gpu --user-data-dir="C://Chrome dev session" https://34j.github.io/niconico-api-swagger
```
