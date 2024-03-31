# xray for replit

在 Replit 代码平台上部署 xray 节点

## 项目特点

* 本项目用于在 [Replit](https://replit.com/) 免费服务上部署 vmess / vless / trojan / shadowsocks 节点
* 部署完成如发现不能上网，请检查域名是否被墙，可使用 Cloudflare CDN 或者 worker 解决。

## 部署

* 下载压缩包并解压（下图为老项目图，仅供参考）

![image](https://user-images.githubusercontent.com/122191366/218304812-289de515-cd33-4233-b42d-184647715d34.png)

* 注册 [Replit](https://replit.com/)
* 新建一个项目，项目类型选择 Blank Repl，名称随意

![image](https://user-images.githubusercontent.com/122191366/218304834-5bebffb1-882c-43eb-ba80-6af020575df9.png)

* 将项目文件全部上传
* 点击左侧 Secrets，在右侧选项卡设置变量。变量内容如下所示：

  | 变量名 | 是否必须 | 默认值 | 备注 |
  | ------------  | ------ | ------ | ------ |
  | UUID          | 否 | 随机生成 | 可在线生成 https://www.uuidgenerator.net/ |
  | VMESS_WSPATH  | 否 | /vm | 以 / 开头 |
  | VLESS_WSPATH  | 否 | /vl | 以 / 开头 |
  | TROJAN_WSPATH | 否 | /tr | 以 / 开头 |
  | SS_WSPATH     | 否 | /ss | 以 / 开头 |

![image](https://user-images.githubusercontent.com/122191366/218304846-6c6f80f9-b5ce-4eeb-82dd-5f201f1fc2bf.png)

* 点击上面的“Run”按钮，启动程序代码
* 点击 Webview 里面的 `replit.dev` 域名部分，复制域名下来备用

![image](https://github.com/Misaka-blog/replit-sbox/assets/122191366/77591e9c-b30b-4c32-9d18-1f9741b80cb6)

* 修改 `main.sh` 文件的第 8 行，最终结果如下所示

![image](https://github.com/Misaka-blog/replit-sbox/assets/122191366/069f50bc-f325-4a40-95e2-a2c872627121)

* 重新运行，然后点击链接获取节点信息即可使用

## 赞助

爱发电：https://afdian.net/a/Misaka-blog

![afdian-MisakaNo の 小破站](https://user-images.githubusercontent.com/122191366/211533469-351009fb-9ae8-4601-992a-abbf54665b68.jpg)