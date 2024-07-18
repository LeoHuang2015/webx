# webx
A powerful heuristic crawler for security engineer

免责声明
本工具仅面向合法授权的企业安全建设行为，请勿对非授权目标进行爬取行为。
禁止对本软件实施逆向工程、反编译、试图破译源代码等行为。
如果发现上述禁止行为，我们将保留追究您法律责任的权利。
如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。
在安装并使用本工具前，请您务必审慎阅读、充分理解各条款内容，限制、免责条款或者其他涉及您重大权益的条款可能会以加粗、加下划线等形式提示您重点注意。 除非您已充分阅读、完全理解并接受本协议所有条款，否则，请您不要安装并使用本工具。您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。


## 功能概述
- 基于chromium的启发式爬虫，使用[go-rod库](https://github.com/go-rod/rod)
- 能力包括路径猜测、动态爬取、页面url提取（href/src/js...）、表单提交、事件触发等
- 为了方便安全工程师分析：支持敏感信息提取、url风险判断、域名/url提取（报告+文件报错）、联动xray等扫描器


## tips

1. 如果经常联动扫描器，直接配置即可
`
to_proxy_addr: "http://127.0.0.1:10099"
`

2. 基于go-rod，在windows下使用会报病毒，参考：https://github.com/go-rod/rod/issues/720 


## 效果（result目录有html报告）
### demo.aisec.cn  测试结果
![image](https://github.com/user-attachments/assets/e2d7d04d-4445-42ce-ad9a-5a9cea21dcc1)

### testphp.vulnweb.com 测试结果
![image](https://github.com/user-attachments/assets/36dfa37e-3385-4a24-ab9a-fd5efc637afe)


## about
- 个人兴趣，开发时间不一定有保障，有问题欢迎提issue
- 精力有限，后续不一定有时间维护，如果喜欢的人比较多考虑开源





