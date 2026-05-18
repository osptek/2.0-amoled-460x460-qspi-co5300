# 2.0" 460×460 AMOLED QSPI module (CO5300) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 2.0-inch **AMOLED** panel, **460×460** resolution |
| Interface | **QSPI** |
| Driver IC | **CO5300** |
| Spec ID | **`2.0-amoled-460x460-qspi-co5300`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, interface and initialization documentation |
| `examples/` | **Sample projects** grouped by feature |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **LVGL8** baseline, or **LVGL8 / LVGL9** with **esp-lvgl-adapter** |
| `with-te/` | Tear-related samples (**屏幕防撕裂代码**) |
| `eaf/` | EAF animation (**eaf动画代码**) |
| `freetype/` | FreeType fonts (**freetype字体代码**) |
| `jpg-decoder/` | JPG decode (**jpg解码代码**) |
| `lottie/` | Lottie animation (**lottie动画代码**) |

### Sample project paths

#### Baseline and esp-lvgl-adapter

| Description | Path |
|:--|:--|
| LVGL8 baseline | `examples/esp32s3-idf5_co5300-qspi_lvgl8/` |
| esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/` |
| esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/` |

#### Tear-related (`with-te/`)

| Description | Path |
|:--|:--|
| esp-lvgl-adapter + LVGL8 + AMOLED with TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/` |
| esp-lvgl-adapter + LVGL9 + AMOLED with TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/` |

#### EAF (`eaf/`)

| Description | Path |
|:--|:--|
| EAF boot animation | `examples/eaf/esp32s3-idf5_co5300-qspi_eaf-boot-animation_spiffs_lvgl9/` |
| EAF playback | `examples/eaf/esp32s3-idf5_co5300-qspi_esp-lv-eaf-player_spiffs_lvgl9/` |

#### FreeType (`freetype/`)

| Description | Path |
|:--|:--|
| FreeType font sample | `examples/freetype/esp32s3-idf5_co5300-qspi_esp-lv-freetype_spiffs_lvgl9/` |

#### JPG decode (`jpg-decoder/`)

| Description | Path |
|:--|:--|
| JPG decode sample | `examples/jpg-decoder/esp32s3-idf5_co5300-qspi_esp-lv-decoder_spiffs_lvgl9/` |

#### Lottie (`lottie/`)

| Description | Path |
|:--|:--|
| Lottie animation sample | `examples/lottie/esp32s3-idf5_co5300-qspi_esp-lv-lottie-player_spiffs_lvgl9/` |
