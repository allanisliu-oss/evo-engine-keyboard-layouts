# EVO Engine Keyboard Layouts (Dragonfly / Kite / Brick)

This repository publishes three keyboard layout designs for learning, personal customization, and community collaboration.

## Files

- `dragonfly.json` / `kite.json` / `brick.json`: layout source files
- `dragonfly.svg` / `kite.svg` / `brick.svg`: vector previews
- `dragonfly.png` / `kite.png` / `brick.png`: rendered previews

## Design Note

`TextStrip` is a narrow top sub-area of the `TouchBar` (touch region). It is mainly used for horizontal gestures such as timeline scrubbing and horizontal code/document scrolling.

## Design Philosophy

- Zero-displacement workflow: keep typing, navigation, and pointer actions within the same hand reach to reduce repeated mouse travel.
- Split-unibody logic: preserve split ergonomics while keeping one integrated chassis for better desk stability and simpler portability.
- Central editing cluster: place numbers, operators, arrow/navigation, and delete actions in the center for short, linear edit paths.
- Touch-assisted productivity: combine a large touch region with a focused `TextStrip` lane for precise horizontal control tasks.

## TextStrip Usage

- What it is: the top narrow horizontal lane of the `TouchBar`.
- Gesture type: horizontal slide only.
- Typical uses:
  - Video timeline scrubbing (fine left/right seek)
  - Horizontal code editor scrolling
  - Wide document/canvas horizontal panning
- Suggested behavior:
  - Keep normal touch region for pointer movement
  - Use `TextStrip` only for horizontal control to avoid accidental diagonal cursor jumps
  - Optional haptic ticks can improve step feedback during scrubbing

## License

Design files in this repository are licensed under **CC BY-NC-SA 4.0**.

- Personal and non-commercial use is allowed
- Commercial use (including mass production, sales, and OEM/ODM distribution) requires prior written authorization
- Derivatives must include attribution and be shared under the same license

See [LICENSE](./LICENSE), [NOTICE.md](./NOTICE.md), and [COMMERCIAL_LICENSE.md](./COMMERCIAL_LICENSE.md).

## Commercial Contact

- Email: `allanisliu@gmail.com`
- Subject: `Commercial License Request - EVO Keyboard Layout`

---

# EVO Engine 键位设计（Dragonfly / Kite / Brick）

本仓库公开三套键盘键位设计，用于学习、个人改造与社区交流。

## 文件说明

- `dragonfly.json` / `kite.json` / `brick.json`：布局源文件
- `dragonfly.svg` / `kite.svg` / `brick.svg`：矢量预览图
- `dragonfly.png` / `kite.png` / `brick.png`：渲染预览图

## 设计说明

`TextStrip` 是 `TouchBar`（触控区）顶部的一条窄分区，主要用于横向手势，例如视频时间轴拖拽和代码/文档横向滚动。

## 设计思路

- 零位移工作流：尽量把输入、导航和指针操作压缩在同一手部活动范围内，减少键盘与鼠标之间的往返位移。
- 分体一体化：保留分区人体工学，同时维持一体机身，提升桌面稳定性与便携性。
- 中央编辑矩阵：把数字、运算符、方向/导航和删除操作集中在中区，形成更短的编辑路径。
- 触控增强效率：大触控区负责通用操作，`TextStrip` 专注横向精细控制。

## TextStrip 用法

- 定义：`TouchBar` 顶部的一条窄横向分区。
- 手势：仅处理左右滑动。
- 常见用途：
  - 视频时间轴精细拖拽
  - 代码编辑器横向滚动
  - 宽文档/画布横向平移
- 建议交互：
  - 普通触控区用于常规指针移动
  - `TextStrip` 仅做横向控制，降低误触导致的斜向跳动
  - 可选震感刻度用于提升拖拽反馈

## 许可证

本仓库设计文件采用 **CC BY-NC-SA 4.0** 许可。

- 允许个人和非商业用途
- 商用（含量产、销售、代工分发）需事先书面授权
- 二次创作需署名，并以相同许可方式共享

详见 [LICENSE](./LICENSE)、[NOTICE.md](./NOTICE.md)、[COMMERCIAL_LICENSE.md](./COMMERCIAL_LICENSE.md)。

## 商用授权联系

- 邮箱：`allanisliu@gmail.com`
- 标题：`Commercial License Request - EVO Keyboard Layout`
