## Handsome-Heo
为Typecho Handsome主题添加Heo表情包
个人博客：https://flytusky.top/
欢迎交换友链
## Sticker-Heo表情包 ##
Sticker-Heo表情包是[张洪Heo][1]创作的通用基础表情
表情预览：

![][2]
![][3]
![][4]

充满了滑稽的形象~
更多可参考此文章：https://blog.zhheo.com/p/2daa6a7b.html

## Handsome主题使用指南 ##
做好相关的备份操作后，
前往[我的项目地址][5]下载所需要的文件（Heo目录和OwO.json文件），

将Heo文件夹放于handsome主题`usr/img/emotion/`目录下

接着，（如果你的Handsome未进行过表情方面的魔改，即你usr/目录下的 `Owo.json` 文件是默认的）

把下载来的 `OwO.json` 文件替换掉原来的，

这时候，访问你的网站，发现评论区多出一个Heo的表情栏，但发送评论后，是按照其原始尺寸的（100*100），这样就显得，
有点大

在Handsome主题后台设置，`开发者设置——自定义css`

输入以下（将表情裁剪直55*55，使之适合，亦可根据需要自行修改代码）
                        
    /*Heo表情自定义大小*/
    .emotion-Heo {
        width: 55px;
    }
    .comment-content-true img.emotion-funny {
        max-width: 100%!important;
    }

## 成果演示 ##
![][6]
喜欢的话可以点个star~：https://github.com/YuanYiT-Hou/Handsome-Heo

  [1]: https://blog.zhheo.com/
  [2]: https://github.com/zhheo/Sticker-Heo/raw/main/img/v1/%E5%B0%81%E9%9D%A2.png
  [3]: https://github.com/zhheo/Sticker-Heo/raw/main/img/v1/%E8%A1%A8%E6%83%85%E9%A2%84%E8%A7%88.png
  [4]: https://github.com/zhheo/Sticker-Heo/raw/main/img/v1/%E6%8E%88%E6%9D%83%E6%96%B9%E5%BC%8F%E4%B8%8E%E5%AE%9A%E4%BB%B7.png
  [5]: https://github.com/YuanYiT-Hou/Handsome-Heo
  [6]: https://cdn.flytusky.top/typecho/uploads/2024/02/673044735.png
