```markdown
# Obsidian Web Clipper 视频学习笔记模板

这个仓库用于保存 Obsidian Web Clipper 的视频学习笔记模板，以及每次更新的变更记录。

## 当前版本

- 模板显示名称：`笔记10.27-1:50`
- Windows 文件名：`笔记10.27-1-50.json`
- 适用页面：B站、YouTube，以及具备逐字稿或本地转写结果的视频页面。

## 当前笔记结构

导入后，笔记按如下层级生成：

```markdown
# 00、视频原标题

B站视频链接：https://www.bilibili.com/video/...

## 视频信息
- 平台：B站
- 作者/频道：...
- 视频时长：...
- 发布时间：...
- 剪藏日期：...
- 语言：...

# 课程主标题

## 目录
- 主题一
- 主题二

## 1. 章节标题 - 00:00
- 核心结论
  - 具体定义、案例、工具或步骤

## AI 总结
课程总结正文。
```

## 导入方法

1. 打开 Chrome 中的 Obsidian Web Clipper 设置。
2. 进入“模板管理”，选择“导入模板”。
3. 选择仓库中的 `笔记10.27-1-50.json`。
4. 若已有同名模板，选择覆盖。
5. 打开视频页面，等待字幕或本地转写完成后再剪藏。

## 平台名称规则

- Bilibili / 哔哩哔哩：统一显示为“B站”。
- Douyin：显示为“抖音”。
- Xiaohongshu：显示为“小红书”。
- YouTube：显示为“YouTube”。

视频链接统一采用以下格式：

```markdown
B站视频链接：https://www.bilibili.com/video/...
抖音视频链接：https://www.douyin.com/...
小红书视频链接：https://www.xiaohongshu.com/...
YouTube视频链接：https://www.youtube.com/...
```

## 开源项目规则

当视频简介或逐字稿中明确提供项目名称和真实仓库地址时，笔记会增加“开源项目”章节，记录：

- 项目名称
- 开源平台
- 项目地址

没有明确项目地址时，模板不会猜测或伪造链接。

## 版本记录

每次模板更新的功能、修复内容与已知限制，请查看 [CHANGELOG.md](CHANGELOG.md)。
```
