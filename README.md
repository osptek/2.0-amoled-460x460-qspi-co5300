# 2.0 寸 460×460 AMOLED QSPI 模组（CO5300）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 2.0 英寸 **AMOLED**，分辨率 **460×460** |
| 接口 | **QSPI** |
| 驱动芯片 | **CO5300** |
| 规格标识 | 产品资料中常用 **`2.0-amoled-460x460-qspi-co5300`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、接口与初始化相关文档 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **LVGL8** 基础，或 **esp-lvgl-adapter** 的 **LVGL8 / LVGL9** 示例 |
| `with-te/` | **屏幕防撕裂代码** |
| `eaf/` | **eaf动画代码** |
| `freetype/` | **freetype字体代码** |
| `jpg-decoder/` | **jpg解码代码** |
| `lottie/` | **lottie动画代码** |

### 示例工程路径

#### 基础与 esp-lvgl-adapter

| 说明 | 路径 |
|:--|:--|
| LVGL8 基础示例 | `examples/esp32s3-idf5_co5300-qspi_lvgl8/` |
| esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/` |
| esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/` |

#### 屏幕防撕裂代码（`with-te/`）

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-adapter + LVGL8 + AMOLED，含 TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/` |
| esp-lvgl-adapter + LVGL9 + AMOLED，含 TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/` |

#### eaf动画代码（`eaf/`）

| 说明 | 路径 |
|:--|:--|
| EAF 开机动画 | `examples/eaf/esp32s3-idf5_co5300-qspi_eaf-boot-animation_spiffs_lvgl9/` |
| EAF 播放 | `examples/eaf/esp32s3-idf5_co5300-qspi_esp-lv-eaf-player_spiffs_lvgl9/` |

#### freetype字体代码（`freetype/`）

| 说明 | 路径 |
|:--|:--|
| FreeType 字体示例 | `examples/freetype/esp32s3-idf5_co5300-qspi_esp-lv-freetype_spiffs_lvgl9/` |

#### jpg解码代码（`jpg-decoder/`）

| 说明 | 路径 |
|:--|:--|
| JPG 解码示例 | `examples/jpg-decoder/esp32s3-idf5_co5300-qspi_esp-lv-decoder_spiffs_lvgl9/` |

#### lottie动画代码（`lottie/`）

| 说明 | 路径 |
|:--|:--|
| Lottie 动画示例 | `examples/lottie/esp32s3-idf5_co5300-qspi_esp-lv-lottie-player_spiffs_lvgl9/` |
