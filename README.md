## Magic Window
- its a one page website that 's use for open multiple window in one time .
- the key and data was stored on ipfs network .
- you can use your key with your ipfs json data. 

#### demo page
- https://bafybeihzegvgrqpo5sahnrijtbx2viwoihwhurysknd5xk3w5urx6ouiea.ipfs.dweb.link/#bafybeifyw7j6ez4ddvy55b3fyy3f552bqzvdb7g6actogbrafhojn2su7m

### json file sample

```json
{
    "newPageFormat": "https://twitter.com/{0}",
    "ids": "microsoft,google"
}
```

its means, the page will be automatic open https://twitter.com/microsoft and https://twitter.com/google .

so, you can easily create your owner json file and upload it to ipfs network .

### Upload to IPFS network and get token

- you can upload it by any way if you can , or use https://bafybeihw4onll5erhywvtd52rkpjmtd7ckymgeuhqvqct2dhfj4xohndti.ipfs.dweb.link/

### Thanks

this page used  vue,element-ui,vue-i18n,axios ; thanks for these magic creators . thanks for cloud service  unpkg , ipfs , ipfs nodes，thanks for  jialezi 's ipfs upload page project 。

## License

please ignore .



----

## 魔法门

这是一个支持加密网络的窗口打开器，使用本站点可以帮助你一次性打开很多类似的页面，而你只需要预先弄明白这些页面的类似之处。

如果你不是程序员，也没有关系，你只需要把你获得的key 填写在页面，并点击打开页面按钮。

当然，你需要先关闭浏览器的弹窗禁止

- 谷歌浏览器设置方法：https://support.google.com/chromebook/answer/95472?hl=zh-Hans&co=GENIE.Platform%3DDesktop

### 测试页面

你可以获取本页的代码来制作属于你自己的魔法门，或者直接访问我们部署在ipfs网络的测试页面：[魔法门,magic window (bafybeihzegvgrqpo5sahnrijtbx2viwoihwhurysknd5xk3w5urx6ouiea.ipfs.dweb.link)](https://bafybeihzegvgrqpo5sahnrijtbx2viwoihwhurysknd5xk3w5urx6ouiea.ipfs.dweb.link/#bafybeifyw7j6ez4ddvy55b3fyy3f552bqzvdb7g6actogbrafhojn2su7m)

### json 样本文件

你可以根据我们提供的样本文件来创建你自己的json。

```json
{
    "newPageFormat": "https://www.douyin.com/video/{0}",
    "ids": "7083805205371899172,7084550280355925259,7084795587840822566,7084950260392496395,7084215028798213415"
}
```

使用这个json （它的key是 bafybeifyw7j6ez4ddvy55b3fyy3f552bqzvdb7g6actogbrafhojn2su7m ）,意味着你会随机打开以上指定的某个抖音视频，如果此方法用于分享，会更有趣味性。

当然，你也可以创造属于你自己的json文件，然后部署到ipfs网络。

### 怎么部署json到ipfs网络

网上已经有足够多的教程来告诉你搭建私有的ipfs节点镜像，当然你也可以无需等待，直接使用这个： https://bafybeihw4onll5erhywvtd52rkpjmtd7ckymgeuhqvqct2dhfj4xohndti.ipfs.dweb.link/ ，请注意，上传完成之后等待30秒，然后一定要访问一次你部署的文件，并获取到域名的前缀部分   axxx.ipfs.bxxx , 这个axxx 就是你所上传的文件的 key 啦。  

### 提醒

记住你的key，这个key往往只有你一个人知道，不过应该你也不会用它来存放什么重要信息；如果遗失了它，也没什么大不了。

### 感谢

本单页站点使用了 vue,element-ui,vue-i18n,axios ；感谢诸位前驱让弄这种小页面变得容易。

感谢 unpkg 的云服务，感谢ipfs和ipfs节点的提供者们，感谢 jialezi 死道友不死贫道 的ipfs 上传页面 。

### 条款

一个单页能有啥好条款的

### 联系

有什么好想法，或者需要修改的地方，欢迎联系我  https://t.me/Odinluo
