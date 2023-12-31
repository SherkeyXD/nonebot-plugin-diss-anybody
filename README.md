<div align="center">
    <!--<img width="200" src="logo.png" alt="logo"></br>-->
<img src="https://socialify.git.ci/SherkeyXD/nonebot-plugin-diss-anybody/image?font=Raleway&forks=1&issues=1&language=1&logo=https%3A%2F%2Fraw.githubusercontent.com%2FA-kirami%2Fnonebot-plugin-template%2Fresources%2Fnbp_logo.png&name=1&owner=1&pattern=Floating%20Cogs&pulls=1&stargazers=1&theme=Auto" alt="nonebot-plugin-diss-anybody" width="640" height="320" />

# nonebot-plugin-diss-anybody

用于 [NoneBot2](https://github.com/nonebot/nonebot2) 与 [OneBot](https://onebot.dev) 的随机怼人插件

</div>

## 这是什么？

当你指定的人在群里发言时，有几率对 TA 的发言作出你指定的回复

## 安装插件

使用 nb-cli 安装（推荐）

```shell
nb plugin install nonebot-plugin-diss-anybody
```

使用 pip/pipenv/poetry/pdm 安装

```shell
# pip
pip install nonebot-plugin-diss-anybody
# pipenv
pipenv install nonebot-plugin-diss-anybody
# poetry
poetry add nonebot-plugin-diss-anybody
# pdm
pdm add nonebot-plugin-diss-anybody
```

## 配置插件

| 配置项                | 类型  | 默认值 | 说明 |
| --------------------- | ----- | ------ | ------ |
| diss_enabled          | bool  | True   | 是否启用插件 |
| diss_global_blacklist | list  | 空     | 不在这些群里做回复（全局） |
| diss_global_chance    | float | 0.1    | 回复几率（全局） |
| diss_global_cd        | float | 5.0    | 两次回复最小间隔（全局） |


## 使用插件

目前该插件的回复配置只能手动书写，将来会加入更完善的对话支持

## TODO List

- [ ] 直接通过对话设置回复内容/几率/CD
- [ ] 优化代码结构
- [ ] 支持回复图片/语音/视频等
- [ ] 迁移到 [nonebot-plugin-saa](https://github.com/MountainDash/nonebot-plugin-send-anything-anywhere) 来实现不同适配器支持

