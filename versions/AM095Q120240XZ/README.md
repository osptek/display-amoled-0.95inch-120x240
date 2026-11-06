<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 0.95″ AMOLED 显示屏 120×240（AM095Q120240XZ）</h1>

<p align="center"><b>AMOLED 模组 · SPI · SH8501G</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: SPI" src="https://img.shields.io/badge/Interface-SPI-27AE60?style=flat-square" />
  <img alt="Driver: SH8501G" src="https://img.shields.io/badge/Driver-SH8501G-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 0.95 寸 120×240 AMOLED 模组宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 0.95 英寸 |
| 类型 | AMOLED |
| 分辨率 | 120×240 |
| 外形尺寸 | 12.8 x 27.35 mm |
| 有效显示区域 | 10.8 x 21.6 mm |
| 接口 | SPI |
| 驱动 IC | SH8501G |
| 触摸驱动 | — |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`SH_8501_A0_Data_Sheet_Preliminary_V0_0_UCS_210401_Truly_7722af3bde.pdf`](./datasheets/SH_8501_A0_Data_Sheet_Preliminary_V0_0_UCS_210401_Truly_7722af3bde.pdf) |
| 规格文档 | [`AM_095_Q120240_XZ_d0c3fdd1ce.pdf`](./datasheets/AM_095_Q120240_XZ_d0c3fdd1ce.pdf) |
| 转接板资料 | [`AM095Q120240XZ转接板V1.0.pdf`](./adapter/AM095Q120240XZ%E8%BD%AC%E6%8E%A5%E6%9D%BFV1.0.pdf) |
| 其他资料 | [`SH8501A_SPI4_bringup_conclusion.md`](./misc/SH8501A_SPI4_bringup_conclusion.md) |

## 仓库结构

```text
display-amoled-0.95inch-120x240/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── AM095Q120240XZ/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        ├── adapter/          # 转接板资料 + 转接板图片
        └── misc/             # 其他资料
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
