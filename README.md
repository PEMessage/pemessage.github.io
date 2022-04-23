# ReadMe

1. 本博客使用 Notion + Github Page + Github Action 自动部署
2. 感谢 [artxia/Action-NotionSite](https://github.com/artxia/Action-NotionSite)  与 [leoncvlt/loconotion ](https://github.com/leoncvlt/loconotion/) 提供的方案
3. 本博客的过去使用 [dragonman225/notablog](https://github.com/dragonman225/notablog) 历史文件位于 `master` 分支

# Some Modification
1. 原版 Loconotion 中会自动更改html的名称 (slug) 以获得更加可读的 URL , 但是这样会导致所有的 Page 名称都不能重名
   这本来对于一般的博客应用来说没什么, 但是我希望能直接笔记快速迁移, 所以小小的添加了一个参数. 使得可以关闭这项功能
   详见对应的仓库.
2. 不再使用 reposity serect 功能, 直接依赖配置文件. 因为对应的 Notion Page 已经是公开页面了



# License

[MIT](https://github.com/artxia/Action-NotionSite/blob/main/LICENSE) © XIA
