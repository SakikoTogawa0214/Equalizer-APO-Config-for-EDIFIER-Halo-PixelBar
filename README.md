[简体中文](./README.md) | [English](#english-summary)

这是一个基于 **Equalizer APO** 和 **ReaXcomp (VST)** 的音频配置文件，能够改善**“看视频/电影时人声轻微说话听不清”**的问题。

## 🛠️ 安装与配置步骤 (Setup Guide)

### 1. 前置准备
1. 下载并安装 [Equalizer APO](https://sourceforge.net/projects/equalizerapo/)（安装后需重启电脑，并确保已勾选你的默认音频输出设备）。
2. 下载免费的 VST 插件包 [ReaPlugs (64-bit)](https://www.reaper.fm/reaplugs/) 并完成安装。

### 2. 应用配置文件
打开 Equalizer APO 的安装目录（通常为 `C:\Program Files\EqualizerAPO\config\config.txt`），将提供的配置粘贴到该文件或通过你喜欢的 GUI（例如 Peace）加载相关设置。

---

## English Summary

This repository provides Equalizer APO configuration and guidance to improve vocal clarity and soft-dialogue intelligibility on the EDIFIER Halo PixelBar desktop speaker. It focuses on using targeted peak (parametric) filters and multiband compression (ReaXcomp-style settings) to make speech and quiet dialogue more present and easier to understand at low listening levels.

Key points

- Purpose: Enhance soft dialogue and speech clarity for the EDIFIER Halo PixelBar, especially at low volumes or for quiet speech.
- Approach: Carefully tuned peak/parametric EQ filters to address masking and frequency balance, combined with multiband compression to reduce dynamic differences that make quiet speech hard to hear.
- Intended users: Listeners who want clearer vocals without raising overall volume, and users comfortable applying Equalizer APO configuration files (and optionally using ReaXcomp or equivalent multiband compression in a DAW or plugin host).

Quick start

1. Install Equalizer APO (Windows) and confirm it is enabled for your EDIFIER Halo PixelBar (or the system output you use).
2. Copy the provided Equalizer APO configuration (.txt/.cfg) into the Equalizer APO config folder or load it using your preferred GUI (e.g., Peace if you use it).
3. If you use ReaXcomp (or an equivalent multiband compressor), load the provided multiband settings into your plugin host or ReaPlugs instance and enable the processing chain; otherwise the EQ-only configuration still helps noticeably.
4. Play familiar content (movies or dialogues) and adjust any global gain or band gains slightly to suit your room and listening level. Avoid extreme boosts — small changes (±1–3 dB) often yield the best results.

Tips and safety

- Start with moderate volume when tuning; aggressive boosts can cause distortion and speaker damage.
- If you hear pumping or unwanted compression artifacts, reduce the compression ratio or widen crossover bands.
- There is no one-size-fits-all setting — small room acoustics and placement differences can change perceived clarity. Use the configuration as a starting point and fine-tune by ear.

Files included (high level)

- Equalizer APO configuration file(s): ready-to-load EQ settings for the Halo PixelBar.
- (Optional) Multiband compressor presets or notes: ReaXcomp-style settings you can import into ReaPlugs/your DAW.
- README and usage notes: overview, installation steps, and tuning tips.

Contributing

Contributions, testing reports, and improvement suggestions are welcome. If you make adjustments for a different listening environment or firmware revision, please open an issue or a pull request with your recommended changes and a short explanation of the listening setup used for testing.

License and contact

Please check the repository LICENSE file for licensing details. For questions or help, open an issue on GitHub or contact the repository owner.
