# poteto

可爱紧凑的卡通伙伴，形象受 Lauren Tan / poteto 启发，带着圆眼镜、深棕发、深色衣服与烤地瓜。厨房小助手只出现在部分状态；角色名字始终是 **poteto**。工作循环表现思考、简短指示和助手回应。

A compact cartoon companion inspired by Lauren Tan / poteto, with round glasses, dark-brown hair, dark clothes and a roasted sweet potato. Kitchen helpers appear in selected states. The character's name is always **poteto**. The work loop depicts thought, a short cue and a helper response.

发布与创作者署名 / Publisher and creator credit: [gentt1024](https://github.com/gentt1024).

![All animation states and look directions](previews/all-states.gif)

![Chief work loop](previews/work.gif)

## 下载 / Downloads

- [v1.0.0 Release](https://github.com/gentt1024/poteto/releases/tag/v1.0.0)
- [最新安装包 / Latest poteto.zip](https://github.com/gentt1024/poteto/releases/latest/download/poteto.zip)
- [最新精灵图 / Latest spritesheet.png](https://github.com/gentt1024/poteto/releases/latest/download/spritesheet.png)

`poteto.zip` 根目录只有 `pet.json` 和 `spritesheet.png`。首次公开发行版本为 **v1.0.0**；`spriteVersionNumber: 2` 表示图集布局版本。

The ZIP contains only `pet.json` and `spritesheet.png` at its root. The first public release is **v1.0.0**. `spriteVersionNumber: 2` identifies the atlas layout version.

## 内容 / Contents

- 9 个标准动画状态与 16 个视线方向，共 73 个有效帧。 / Nine standard animation states plus sixteen look directions, 73 valid frames.
- 透明 RGBA PNG，1536 × 2288，8 × 11 网格，单格 192 × 208。 / Transparent RGBA PNG, 1536 × 2288, an 8 × 11 grid with 192 × 208 cells.
- 工作循环约 0.82 秒，动作偏快且有明确停顿。部分旧状态保留颜色与风格差异，64px 下细节较弱。 / The work loop is about 0.82 seconds, brisk and stepped. Some older states retain color/style differences; fine details are weaker at 64px.

## 本地安装 / Local installation

1. 下载并解压 `poteto.zip`，得到同级 `pet.json` 与 `spritesheet.png`。 / Download and extract `poteto.zip` to obtain the two root files.
2. 按[社区格式说明](https://codexpet.xyz/spec/)，将两个文件放入 `~/.codex/pets/poteto/`。已有同名目录时先备份，避免覆盖。 / Following the community format reference, place both files in `~/.codex/pets/poteto/`; back up an existing folder first.
3. 重新打开 Codex，在当前版本提供的宠物界面中查找 `poteto`。 / Reopen Codex and look for `poteto` in the pet interface available in your version.

已在本机验证 JSON、图像解码、透明通道、尺寸、连续有效帧和发行包内容。官方 manifest schema 兼容性尚未独立确认，也未进行 Codex 桌面实际导入测试；这些需要在目标版本上验证。

JSON, image decoding, transparency, dimensions, consecutive populated frames and package contents have been checked locally. Official manifest schema compatibility and an actual Codex desktop import have not been independently verified; check these with your target version.

## 来源与使用权 / Sources and rights

这是非官方、AI 辅助制作的同人作品。没有获得 Lauren Tan、OpenAI 或参考画师背书的证据。形象与助手参考素材的权利人、授权范围和再分发许可仍未全部确认。公开发布不表示第三方权利已获清理，也不授予 MIT、CC BY 或其他开放素材许可。详见 [CREDITS.md](CREDITS.md)。

This is an unofficial, AI-assisted fan-inspired work. No endorsement from Lauren Tan, OpenAI or the reference artists is claimed. Rights holders, likeness permissions and redistribution permissions for the helper references remain unconfirmed. Public availability does not mean third-party rights have been cleared, and no MIT, CC BY or other open asset license is granted. See [CREDITS.md](CREDITS.md).
