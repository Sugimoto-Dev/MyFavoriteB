## Bug fixed: 2020-11-17

0.0.2版在我的机器上运行正常, 在其他人机器上似乎有无法自动配置IINA的问题, 现提供一个手动修复的方法.

![](./thumbs/bug.jpg)

打开IINA, 找到上图位置, 手动添加两个键值对

key: `http-header-fields`, value: `user-agent:Safari/537.3`
key: `http-header-fields`, value: `referer:https://www.bilibili.com/`

添加后彻底退出或重启IINA, 然后即可正常播放视频.

---

Bilibili macOS客户端

这是一个适合佛系B站用户使用的客户端, 没有弹幕, 没有评论, 用它你会感到很孤独.


## 2020-11-13 更新0.0.2版本

- B站前一阵修改了一点点东西, 导致0.0.1版本已不可用. 0.0.2版本中已修复.
- 侧边栏添加了新选项###追番###
- 添加了搜索


## Preview



![Light](./thumbs/01.jpg)

![Dark](./thumbs/02.jpg)

![Play](./thumbs/03.jpg)

![关注](./thumbs/04.jpg)

![追番](./thumbs/bangumiFollowing.jpg)




## Getting Started

- macOS 11+, 也就是说系统低于`Big Sur`就用不了. 现在macOS 11只有beta版.

- 视频播放使用IINA播放器. 没有写内置播放器, 这个应该普遍都装了吧. 没有安装的去这里: [https://github.com/iina/iina](https://github.com/iina/iina)

- `系统偏好设置`  -> `安全性与隐私`  ->  允许`任何来源`

![system](./thumbs/system.jpg)


- 第一次运行需扫描屏幕的二维码登录. 掏出你的手机, 点开B站移动端, 扫码后手机上点确定. 最后点击屏幕的确认键进行登录确认.

- 登录时, 如果你的IINA播放器本来就是打开状态, 请手动让IINA彻底退出.



  Done.



## TODO

- [x] 搜索
- [ ] 关注的某个UP视频索引翻页, 目前只显示最近的100个
- [ ] 等等等等..., 太多了就不说了


## 已知问题

- 有时图片忽大忽小
- 有时UI抖动
- 等等等等...



## 致谢名单

- 我自己
- 王老简
