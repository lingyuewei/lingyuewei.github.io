# Yuewei Ling Homepage

## 页面结构说明
```
├── _config.yml                # 站点配置文件
├── _data/
│   └── navigation.yml         # 顶部导航栏菜单配置
├── _pages/
│   ├── about.md               # 首页内容
│   └── includes/              # 各子页面内容目录
│       ├── intro.md           # 关于我
│       ├── education.md       # 教育背景
│       ├── pub.md             # 出版物
│       ├── presentations.md   # 学术会议
│       ├── patents.md         # 专利授权
│       ├── teaching.md        # 教学经历
│       ├── service.md         # 学术服务
│       ├── honers.md          # 荣誉奖项
```
- 修改时主要关注几个页面：
    - 页面左侧内容在_config.yml中修改；
    - 头部菜单在navigation.yml修改；
    - 各个菜单的详情页在includes/下的页面；

## 生成 GitHub Star 徽章
可使用 Shields.io 生成 GitHub Star 徽章，基本格式如下：

```text
https://img.shields.io/github/stars/<GITHUB_USER>/<REPO>?style=<STYLE_OPTION>
```
- <GITHUB_USER>：GitHub 用户名或组织名（如：yuewei-ling）

- <REPO>：仓库名（如：yuewei-ling.github.io）

- <STYLE_OPTIONS>（可选）：徽章样式参数，包括：

    - style=social：带GitHub图标的社交样式（默认）
    - style=flat：扁平化风格
    - style=flat-square：方形扁平风格
    - logo=github：显示GitHub图标