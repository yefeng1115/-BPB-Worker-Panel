## 使用方法：Pages+Fork公开仓库
1. 直接`Fork`本存储库。本存储库`main`主线默认为`自动升级为最新版本`。
2. 到`Cloudflare`利用`Pages+github`搭建。
3. 再增加下面必要的变量。
   
## 环境变量与说明
| 变量  | 用法 |
| :-------------: | :-------------: |
| **UUID**  | 必要；[在线生成](https://1024tools.com/uuid) ，用于生成 VLESS 节点配置 |
| **PROXY_IP**  | 必要；部署完成后进入面板设置更加方便，[查是否有效](https://www.nslookup.io/domains/ts.hpc.tw/dns-records/#cloudflare)  |
| **TR_PASS**  | 必要；密码，用于生成 Trojan 节点配置  |
| **kv**  | 必要；KV命名空间  |
| **/panel**  | 在 url 后面增加/panel访问面板  |
| **SUB_PATH**  | 订阅的 URI  |
| **FALLBACK**  | 后备域 |
| **DOH_URL**  | 核心 DOH |
1. 来自大佬分享的PROXYIP：`bpb.yousef.isegaro.com`、`ts.hpc.tw`、`cdn.xn--b6gac.eu.org`、`cdn-all.xn--b6gac.eu.org`、`bestproxy.onecf.eu.org`、`proxyip.cmliussss.net`。
2. 试问面板：`/panel`，部署成功后，在 url 后面增加/panel来进行访问面板，访问面板修改的密码将会保存在`kv`对里。
4. IP/域名用回车键`ENTER`分隔。
