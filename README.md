# Yuewei Ling Homepage

## 页面修改
```
├── _config.yml                # 配置文件
├── _data/
│   └── navigation.yml         # 导航菜单
├── _pages/
│   ├── about.md               # 主页
│   └── includes/              # 主页各部分内容
│       ├── intro.md           # About Me 个人简介
│       ├── education.md       # 教育背景与培训
│       ├── pub.md             # Publications 发表论文
│       ├── presentations.md   # Presentations 学术报告/会议
│       ├── patents.md         # Patents 专利
│       ├── teaching.md        # Teaching 教学经历
│       ├── service.md         # Service 学术服务
│       ├── honers.md          # Honors & Awards 荣誉奖项
```
- 修改时主要关注几个页面：
    - 页面左侧内容在_config.yml中修改；
    - 头部菜单在navigation.yml修改；
    - 各个菜单的详情页在includes/下的页面；

## 生成 GitHub Star 徽章
Shields.io 的 GitHub Star 徽章 URL 格式如下：

```text
https://img.shields.io/github/stars/<GITHUB_USER>/<REPO>?
```
- <GITHUB_USER>：GitHub 用户名或组织名（如:yuewei-ling）

- <REPO>：仓库名（如:yueweiling.github.io

- <STYLE_OPTIONS>（可选）：

    - style=social（默认样式，带 GitHub 图标）

    - style=flat（扁平化设计）

    - style=flat-square（方形扁平设计）

    - logo=github（自定义 GitHub 图标）