# 欢迎来到这里！

这里是我个人训练的自用模型

本人的模型都是基于Stable Diffusion来进行训练 其他的waifu、naifu等我没有安装过，不确定是否能使用

[>>点击前往我的B站首页<<](https://space.bilibili.com/4149006)

`embeddings`文件夹下是最新版本的`pt`模型

`textual_inversion`文件夹下是训练过程中产生的中间版本 大家可以自行根据喜好获取（停止更新）

官方webui项目地址：
>https://github.com/AUTOMATIC1111/stable-diffusion-webui

52g完整sd模型下载地址：

>magnet:?xt=urn:btih:5bde442da86265b670a3e5ea3163afad2c6f8ecc&dn=novelaileak&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2810%2Fannounce&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.openbittorrent.com%3A80%2Fannounce&tr=udp%3A%2F%2Fopentracker.i2p.rocks%3A6969%2Fannounce

下载的ckpt模型放到`stable-diffusion-webui\models\Stable-diffusion`目录下

不用全部下载 下载需要的即可

---

如果生成效果有问题请尝试根据以下链接进行设置之后再尝试：

>[【【NovelAI】让你的本地版与官网输出完全一致！最新Stable Diffusion WebUI设置】](https://www.bilibili.com/video/BV1nP411N7CG?share_source=copy_web&vd_source=e79365640d1097b8c8937eac877c95bd)

# 更新历史：
- 2022.10.17
  - 原神-纳西妲角色模型（nahida）
  - keta画风模型（keta）
- 2022.10.22 碧蓝幻想-玛琪拉（鸡神将）角色模型（makira）
- 2022.10.25 
  - 【碧蓝航线-小天城】角色模型（amagi_chan）
  - 【公主连接-可可萝】角色模型（kkr）
  - 重制了keta画风模型 在nsfw上似乎好了一些（keta-nsfw）

# Q&A

1.怎么使用pt模型？

  - 将下载的pt模型文件放到`stable-diffusion-webui\embeddings`目录下
  - 在描述词区域填写pt文件名作为prompt
    - 例：【nahida.pt】 输入prompt为【nahida】 
    - 可以任意更改pt文件名，例：【nahida.pt】->【genshin_nahida.pt】 输入prompt为【genshin_nahida】

2.我生成的图跟你的怎么不一样？
  - 首先确保使用的sd模型文件为【animefull-latest.ckpt[**e6e8elfc**]】或者【animesfw-latest.ckpt[**202fcec0**]】
    - 不要看文件名 看文件名后面的**哈希码** 文件名可以随意修改 哈希码不能 确保使用的是以上两个sd模型才能保证跟我生成的效果一致
  - 把settings中的【Stop At last layers of CLIP model】改成2才能生效 (*如果没有这个选项请更新webui的代码)

<details>
  <summary>点击查看我的设置</summary>

  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/setting1.png)

  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/setting2.png)
</details>

# 目前包含模型

角色模型：

- nahida：原神草神-纳西妲 2022.10.17
- koharu：碧蓝档案-小春 2022.10.20
- makira：碧蓝幻想-十二神将-鸡-玛琪拉 2022.10.22
- amagi_chan：碧蓝航线-小天城 2022.10.25
- kkr：公主连接-可可萝 2022.10.25

风格模型：

- keta(2022.10.17)：
  - 画风超棒的东方知名画师
  - **nsfw!** 目前选用了18600step版本 20000版本感觉有点用力过猛
  - 结合上边的纳西妲模型进行使用效果拔群，单独使用，使用得当的话也能得到不错的图
- gbf(2022.10.20)：
  - blhx就不用多说了 大家都知道的对吧()
  - ~~暂时训练了1万steps 效果还不够理想~~
  - 训练生成的图看起来全都跟意面画风似的（笑）
  - ~~目前生成的图眼睛都不太对 我试着结合nahida模型使用，眼睛会比较正常 大家可以先试试看~~
  - ~~我尝试配合其他tag使用 生成的图眼睛还好 有空我看看再训练一下模型试试~~
  - **根据大佬的设置修改之后生成的图片效果有所改善 眼睛也正常了 主要是设置【Eta noise seed delta】为31337**
  - ~~最新效果图请往下看~~
  - gbf模型又训练了下 目前到了15000steps版本
  - 效果图我就不往这个文档里放了 请往下查看
- keta-nsfw(2022.10.25)：
  - 对keta画风模型进行了重制

后续有更新也会往这里上传

# 效果图
![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E7%94%9F%E6%88%90%E5%B1%95%E7%A4%BA.png)

<details>
  <summary>原神-纳西妲</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E7%BA%B3%E8%A5%BF%E5%A6%B2.jpg)
</details>

<details>
  <summary>风格-keta（nsfw注意）</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/keta-nsfw.jpg)
</details>

<details>
  <summary>风格-gbf</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/gbf.jpg)
</details>

<details>
  <summary>碧蓝档案-小春</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E7%A2%A7%E8%93%9D%E6%A1%A3%E6%A1%88-%E5%B0%8F%E6%98%A5.jpg)
</details>

<details>
  <summary>碧蓝幻想-玛琪拉</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/gbf-%E7%8E%9B%E7%90%AA%E6%8B%89.jpg)
</details>

<details>
  <summary>公主连接-可可萝</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E5%85%AC%E4%B8%BB%E8%BF%9E%E6%8E%A5-%E5%8F%AF%E5%8F%AF%E8%90%9D.jpg)
</details>

<details>
  <summary>碧蓝航线-小天城</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E7%A2%A7%E8%93%9D%E8%88%AA%E7%BA%BF-%E5%B0%8F%E5%A4%A9%E5%9F%8E.jpg)
</details>

<details>
  <summary>碧蓝档案-美游</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E7%A2%A7%E8%93%9D%E6%A1%A3%E6%A1%88-%E7%BE%8E%E6%B8%B8.jpg)
</details>

<details>
  <summary>碧蓝档案-梓</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E7%A2%A7%E8%93%9D%E6%A1%A3%E6%A1%88-%E6%A2%93.jpg)
</details>

<details>
  <summary>风格-as109</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/as109.jpg)
</details>

<details>
  <summary>风格-毛玉牛乳</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/kedama.jpg)
</details>
