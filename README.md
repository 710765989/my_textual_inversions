# 欢迎来到这里！

这里是我个人训练的自用模型

`embeddings`文件夹下是最新版本的`pt`模型

`textual_inversion`文件夹下是训练过程中产生的中间版本 大家可以自行根据喜好获取（停止更新）

---

webui项目地址：
https://github.com/AUTOMATIC1111/stable-diffusion-webui

50g完整ckpt模型下载地址：

magnet:?xt=urn:btih:5bde442da86265b670a3e5ea3163afad2c6f8ecc&dn=novelaileak&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2810%2Fannounce&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.openbittorrent.com%3A80%2Fannounce&tr=udp%3A%2F%2Fopentracker.i2p.rocks%3A6969%2Fannounce

放到stable-diffusion-webui\models\Stable-diffusion目录下 只需下载animefull-final-pruned(3.97GB)或者animefull-latest(7.17GB)即可

个人主要使用animefull-latest.ckpt和animesfw-latest.ckpt两个模型

如果pt模型生成效果不正确请切换到对应ckpt模型再试试

如果生成效果有问题请尝试根据以下链接进行设置之后再尝试：

【【NovelAI】让你的本地版与官网输出完全一致！最新Stable Diffusion WebUI设置】 https://www.bilibili.com/video/BV1nP411N7CG?share_source=copy_web&vd_source=e79365640d1097b8c8937eac877c95bd

在使用之前**必须**先修改一下设置：
- **把setting中的【Stop At last layers of CLIP model】改成2才能生效**

可选修改项：
- 【Eta noise seed delta】修改为31337
- 修改后与官方novelai设置相同

# 更新历史：
- 2022.10.17
  - 原神-纳西妲角色模型（nahida）
  - keta画风模型（keta）
- 2022.10.22 碧蓝幻想-玛琪拉（鸡神将）角色模型（makira）
- 2022.10.25 
  - 【碧蓝航线-小天城】角色模型（amagi_chan）
  - 【公主连接-可可萝】角色模型（kkr）
  - 重制了keta画风模型 在nsfw上似乎好了一些（keta-nsfw）

# 目前包含模型

角色模型：

- nahida：原神草神-纳西妲 2022.10.17
- koharu：碧蓝档案-小春 2022.10.20
- makira：碧蓝幻想-十二神将-鸡-马琪拉 2022.10.22
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
  - gbf模型又训练了下 目前到了15000steps版本（新）
  - 效果图我就不往这个文档里放了 请前往【效果图】文件夹下查看
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
  <summary>keta-nsfw</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/keta-nsfw.jpg)
</details>

<details>
  <summary>gbf画风</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/gbf.jpg)
</details>

<details>
  <summary>碧蓝档案-小春</summary>
  
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E7%A2%A7%E8%93%9D%E6%A1%A3%E6%A1%88-%E5%B0%8F%E6%98%A5.jpg)
</details>

<details>
  <summary>gbf-玛琪拉</summary>
  
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
