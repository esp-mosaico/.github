# 发布到 ESP-Mosaico 组织首页

本仓库 **`esp-mosaico/.github`** 维护组织主页，GitHub 使用默认分支上的 `profile/README.md` 展示公开首页。

`README.md` 为默认英文版，`README_zh-CN.md` 为中文版。两份文档顶部都有语言切换按钮，点击后打开对应语言的 README 文件。

1. 在独立分支修改两份 README 和相关素材，保持中英文内容一致。
2. 提交并推送该分支，通过 Pull Request 将变更合入 `main`。组织主页在合并后更新。
3. 两份 README 中的图片与语言切换地址使用 `main`；如果更改默认分支，请同步修改 `https://raw.githubusercontent.com/esp-mosaico/.github/main/` 和 `https://github.com/esp-mosaico/.github/blob/main/` 这两个前缀。
4. 合并后打开 https://github.com/esp-mosaico ，检查默认英文首页、双向语言切换、图片、动图和跳转链接。

```text
esp-mosaico/.github
└── profile/
    ├── README.md
    ├── README_zh-CN.md
    ├── PUBLISH.md
    └── assets/
        ├── README.md
        ├── lang-en.svg
        ├── lang-zh.svg
        ├── mosaico-coreboard.webp
        ├── chatcoding.gif
        ├── vibecoding.gif
        ├── modules.gif
        ├── multi-device.gif
        ├── device-overview-en.webp
        └── device-overview-zh.png
```

图片使用指向本仓库 `main` 分支的完整地址，避免组织 Overview 与仓库文件页对相对路径的解析差异。分支中新加的图片和语言页面在合并前无法通过这些地址访问；本地素材均位于 `assets/`。

维护时同步更新中英文内容，优先更新各仓库的职责和入口，避免把短期版本号、Star 数或未发布能力写成长期承诺。动图为官方原始演示，未经重新编码；来源见 [素材说明](assets/README.md)。

GitHub 官方规则：[自定义组织个人资料](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile#adding-a-public-organization-profile-readme)。
