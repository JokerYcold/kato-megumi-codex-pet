# 素材与第三方说明

本应用为个人桌面陪伴项目，非 OpenAI 官方产品，与《路人女主的养成方法》及其权利方没有关联。

“加藤惠”等角色名称、设定及相关权利归原权利方所有。本项目沿用用户提供的角色图集，并使用 AI 生成衍生动作。项目提供者没有取得原角色的商业或公开分发授权；非商业声明不等同于授权。当前交付用于用户个人体验；分享给朋友前请自行确认相关素材的使用权利，勿作为已获授权的商品出售。


## 运行依赖

- .NET 10 / WPF / Windows Forms：微软 .NET 项目，运行时许可随自包含发布目录提供（LICENSE.txt、ThirdPartyNotices.txt）。
- SQLite：通过 Windows 自带 `winsqlite3.dll` 调用，不单独分发 SQLite 二进制；SQLite 核心采用公有领域声明，https://www.sqlite.org/copyright.html 。
- Codex CLI：由用户单独安装与登录，本包不分发 Codex，也不包含任何账户或登录文件。
- 字体：使用系统 Microsoft YaHei UI 等字体，本包不嵌入或分发字体文件。
- 角色素材：原有用户素材及本次 AI 生成动作；所有生成图已作为静态资源本地打包。
- 音效：由正弦波合成的简短 WAV 提示音，不使用参考项目音频。

## 开发依赖

素材提取与验证脚本使用 Pillow。它仅用于开发，运行便携应用不需要 Python 或 Pillow。Pillow 许可：https://github.com/python-pillow/Pillow/blob/main/LICENSE 。
