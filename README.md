developer_android
=================

http://developer.android.com/


##一起来参与
如果想做出贡献(翻译或者校对)的话，请加QQ群：137198122，谢谢！

原文文档：
<http://developer.android.com/>


### 参与步骤（页尾有详细的过程演示）
* fork主仓库（https://github.com/1sters/developer_android）
* 按照章节（页面）认领翻译(每次申请一个章节)，在下面这个`README.md`里找还没有被人申请的章节，写上（@你的github号），给主仓库的`master`分支提pull request；
* 提的pull request 被确认，合并到主仓库后，代表你申请的章节*占位*完成，开始翻译；
* 翻译过程请参 *翻译协作规范* ，完成翻译后提交pull request给主仓库的`master`分支；
* 校核完成后，从主仓库的`master`分支合并到主`publish`分支；
* 全部翻译完成后，生成PDF文档和网页发布；

### 翻译协作规范
为了让大家协作顺畅，需要每一个人遵循如下协作规范~

- 使用markdown进行翻译，文件名必须使用英文，因为中文的话gitbook编译的时候会出问题
- 翻译后的文档请放到SOURCE文件夹下的对应章节中，然后pull request即可，我会用gitbook编译成网页
- 工作分支为`master`，用于GitHub的pages服务
- fork过去之后新建一个分支进行翻译，完成后pull request这个分支，没问题的话我会合并到`master`分支中
- 有其他任何问题都欢迎发issue，我们看到了会尽快回复


如果不熟悉的Markdown的，请参考

- <https://help.github.com/articles/markdown-basics>
- <https://help.github.com/articles/github-flavored-markdown>

***

## 认领章节记录

### L Developer Preview 

* [Setting Up the Preview SDK](preview/setup-sdk.md) - [Setting Up the Preview SDK](http://developer.android.com/preview/setup-sdk.html)
* [API Overview](preview/api-overview.md)
* [Material Design](preview/material/index.md)
  * [Get Started](preview/material/get-started.md)
  * [Material Theme](preview/material/theme.md)
  * [UI Widgets](preview/material/ui-widgets.md)
  * [Views and Shadows](preview/material/views-shadows.md)
  * [Animations](preview/material/animations.md)
  * [Compatibility](preview/material/compatibility.md)
* [Design for Notifications](preview/notifications.md)
* [Android TV Apps](preview/tv/index.md)
  * [Get Started with TV Apps](preview/tv/start/index.md)
  * [Design for TV](preview/tv/design/index.md)
    * [Creative Vision for TV](preview/tv/design/principles.md)
    * [Patterns for TV](preview/tv/design/patterns.md)
    * [Style for TV](preview/tv/design/style.md)
  * [User Interfaces for TV](preview/tv/ui/index.md)
    * [Layouts for TV](preview/tv/ui/layouts.md)
    * [Navigation for TV](preview/tv/ui/navigation.md)
    * [BrowseFragment](preview/tv/ui/browse.md)
    * [DetailFragment](preview/tv/ui/details.md)
    * [Adding Search to TV Apps](preview/tv/ui/in-app-search.md)
    * [Making Recommendations](preview/tv/ui/recommendations.md)
  * [Games On TV](preview/tv/games/index.md)
  * [Hardware Features on TV](preview/tv/start/hardware-features.md)
  * [ADT-1 Developer Kit](preview/tv/adt-1/index.md)
* [Samples](preview/samples.md)
* [Reference](preview/reference.md)
* [Support](preview/support.md)
* [License Agreement](preview/license.md)

