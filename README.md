# Nahida Mini Codex Pet

[English](./README_EN.md) | 简体中文

一个受《原神》纳西妲启发制作的 Codex 桌面宠物包，采用小体型 Q 版像素风格，可以作为 Codex 的桌面陪伴宠物使用。

## 预览

![预览 01](assets/gif/preview_01.gif)

<details>
<summary>查看更多预览</summary>

![预览 02](assets/gif/preview_02.gif)

![预览 03](assets/gif/preview_03.gif)

![预览 04](assets/gif/preview_04.gif)

![预览 05](assets/gif/preview_05.gif)

![预览 06](assets/gif/preview_06.gif)

![预览 07](assets/gif/preview_07.gif)

![预览 08](assets/gif/preview_08.gif)

![预览 09](assets/gif/preview_09.gif)

</details>

## 文件

- `dist/pet.json` - Codex 宠物配置文件。
- `dist/spritesheet.webp` - 8 x 9 的 Codex 宠物精灵图集。

## 安装方法

将 `dist` 文件夹中的文件复制到你的 Codex 宠物目录中：

```bash
mkdir -p ~/.codex/pets/nahida-mini-codex-pet-v1
cp dist/pet.json ~/.codex/pets/nahida-mini-codex-pet-v1/pet.json
cp dist/spritesheet.webp ~/.codex/pets/nahida-mini-codex-pet-v1/spritesheet.webp
```

如果你使用的是 Windows，也可以手动创建类似下面的目录：

```text
D:\.codex\pets\nahida-mini-codex-pet-v1\
```

然后把这两个文件复制进去：

```text
pet.json
spritesheet.webp
```

最终目录结构应该类似这样：

```text
nahida-mini-codex-pet-v1/
├── pet.json
└── spritesheet.webp
```

如果宠物列表没有立刻刷新，请重启 Codex。

## 包信息

- 宠物 ID：`nahida-mini-codex-pet-v1`
- 显示名称：`Nahida Mini`
- 图集尺寸：`1536x1872`
- 单元格尺寸：`192x208`
- 文件格式：带透明通道的 WebP

## 说明

这是一个粉丝自制的 Codex 桌面宠物包。

本项目不是 HoYoverse、米哈游或《原神》的官方资源，也未获得相关官方主体的赞助、授权或认可。

本项目仅用于个人学习、展示与非商业使用。
