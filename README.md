# sing-box-geosite

在links.txt添加规则集，自动生成 sing-box Source Format 和 Surge .list 规则集。fork后自己添加想要转换的规则集。

仓库 Settings ----> Actions ----> General ----> Workflow permissions ----> Read and write permissions 勾选上

规则集源文件写法eg:

```json
{
  "tag": "geosite-wechat",
  "type": "remote",
  "format": "source",
  "url": "https://raw.githubusercontent.com/Toperlock/sing-box-geosite/main/wechat.json",
  "download_detour": "auto"
}
