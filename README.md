# 欢迎来到这里！

这里是我个人训练的自用模型

`embeddings`文件夹下是最新版本的`pt`模型

`textual_inversion`文件夹下是训练过程中产生的中间版本 大家可以自行根据喜好获取

webui项目地址：
https://github.com/AUTOMATIC1111/stable-diffusion-webui

50g完整ckpt模型下载地址：

放到stable-diffusion-webui\models\Stable-diffusion目录下 只需下载animefull-final-pruned(3.97GB)或者animefull-latest(7.17GB)即可

magnet:?xt=urn:btih:5bde442da86265b670a3e5ea3163afad2c6f8ecc&dn=novelaileak&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2810%2Fannounce&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.openbittorrent.com%3A80%2Fannounce&tr=udp%3A%2F%2Fopentracker.i2p.rocks%3A6969%2Fannounce

在使用之前**必须**先修改一下设置：
- **把setting中的【Stop At last layers of CLIP model】改成2才能生效**

可选修改项：
- 【Eta noise seed delta】修改为31337
- 修改后与官方novelai设置相同 本人训练的gbf模型在修改后生成的眼睛会变得正常


目前包含模型有：

角色模型：

- nahida：原神草神-纳西妲

风格模型：

- keta：画风超棒的东方知名画师
  - **nsfw!** 目前选用了18600step版本 20000版本感觉有点用力过猛
  - 结合上边的纳西妲模型进行使用效果拔群，单独使用，使用得当的话也能得到不错的图
- gbf：blhx就不用多说了 大家都知道的对吧()
  - 暂时训练了1万steps ~~效果还不够理想~~
  - 训练生成的图看起来全都跟意面画风似的（笑）
  - ~~目前生成的图眼睛都不太对 我试着结合nahida模型使用，眼睛会比较正常 大家可以先试试看~~
  - ~~我尝试配合其他tag使用 生成的图眼睛还好 有空我看看再训练一下模型试试~~
  - **根据大佬的设置修改之后生成的图片效果有所改善 眼睛也正常了 主要是设置【Eta noise seed delta】为31337**
  - **最新效果图请往下看**
  
  【【NovelAI】让你的本地版与官网输出完全一致！最新Stable Diffusion WebUI设置】 https://www.bilibili.com/video/BV1nP411N7CG?share_source=copy_web&vd_source=e79365640d1097b8c8937eac877c95bd

后续有更新也会往这里上传

效果图
![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E7%94%9F%E6%88%90%E5%B1%95%E7%A4%BA.png)

![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E6%88%90%E5%93%81%E5%9B%BE/02681-2425705406-%2C%20white%20hair%20%2C(nahida)%2C%20(keta-5300).png)

![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E6%88%90%E5%93%81%E5%9B%BE/02730-3867066413-%2C%20white%20hair%20%2Cnahida%2C%20(keta).png)

![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E6%88%90%E5%93%81%E5%9B%BE/02928-2393729360-white%20hair%2C%20nahida%2C%20%20keta.png)

![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E6%88%90%E5%93%81%E5%9B%BE/02955-3962985033-white%20hair%2C%20nahida%2C%20keta%2C%20side%20ponytail%2C%20elf.png)

- gbf(*new*)

  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E6%88%90%E5%93%81%E5%9B%BE/gbf/%E4%BF%AE%E6%94%B9%E8%AE%BE%E7%BD%AE%E4%B9%8B%E5%90%8E%E7%9A%84%E6%95%88%E6%9E%9C%E5%9B%BE/03556-1573251876-gbf.png)
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E6%88%90%E5%93%81%E5%9B%BE/gbf/%E4%BF%AE%E6%94%B9%E8%AE%BE%E7%BD%AE%E4%B9%8B%E5%90%8E%E7%9A%84%E6%95%88%E6%9E%9C%E5%9B%BE/03557-350437287-gbf.png)
  ![](https://github.com/710765989/my_textual_inversions/blob/main/%E6%95%88%E6%9E%9C%E5%9B%BE/%E6%88%90%E5%93%81%E5%9B%BE/gbf/%E4%BF%AE%E6%94%B9%E8%AE%BE%E7%BD%AE%E4%B9%8B%E5%90%8E%E7%9A%84%E6%95%88%E6%9E%9C%E5%9B%BE/03558-342862894-gbf.png)
