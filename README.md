# PicSynth

<p align="center">
  <strong>EN</strong> | <a href="#中文说明">中文</a>
</p>

---

> Transform any image into music through color, brightness, and saturation analysis.

**PicSynth** is an innovative audio-visual synthesis tool that converts images into complete musical compositions, featuring melodies, bass lines, and drum patterns.

## Features

- **Image-to-Music Conversion** - Analyzes pixel colors to generate melodies
- **Smart Atmosphere Detection** - Auto-recommends scales and parameters based on image mood
- **FM Synthesis Engine** - Rich, evolving timbres with full envelope control
- **Multi-Track Output** - Melody, Bass line, and Drum machine
- **18 Musical Scales** - From Pentatonic to Chromatic, including exotic scales
- **Real-Time Control** - Adjust all parameters while playing
- **Responsive Design** - Works on desktop and mobile browsers

## Quick Start

1. Open `index.html` in a modern browser (or visit the GitHub Pages site)
2. Click **"Initialize"** to start the audio engine
3. Upload an image using the file selector
4. Music plays automatically! Click the canvas to pause/resume

## How It Works

| Image Property | Maps To | Effect |
|----------------|---------|--------|
| Hue (0-360) | Pitch | Different colors = Different notes |
| Saturation | FM Modulation | Vivid = Complex timbre |
| Lightness | Volume + Duration | Bright = Loud and Long |

### Intelligent Presets

When you upload an image, PicSynth analyzes:
- Overall brightness -> BPM speed
- Contrast -> Note duration
- Saturation -> Randomness & Reverb
- Dominant hue -> Scale recommendations
- Hue variety -> Drum preset

## Control Modules

| Module | Parameters |
|--------|------------|
| Rhythm & Sequencer | BPM (40-300), Note Duration, Grid Size |
| Pitch & Scale | 18 scales, Base Octave (2-6), Randomness |
| FM Synthesis | Oscillators, Harmonicity, Mod Index, Detune, ADSR |
| Filters & EQ | Two filters with Type, Freq, Q, Gain |
| Amp Envelope | Attack, Decay, Sustain, Release |
| Effects | Reverb wet/dry |
| Bass Line | Pitch offset, Probability, Root emphasis, Filter |
| Drum Machine | 5 presets, 4 instruments with individual controls |

## Best Images

| Recommended | Not Ideal |
|-------------|-----------|
| Rich colors with contrast | Solid colors |
| Gradients and transitions | Too dark or too bright |
| Abstract art, landscapes | Dense uniform textures |

## Preset Recipes

| Style | Settings |
|-------|----------|
| EDM/Dance | BPM: 128-140, Scale: Pentatonic, Drums: Dense |
| Ambient | BPM: 60-80, Scale: Lydian, Reverb: 0.6-0.8 |
| Experimental | BPM: 180-240, Scale: Chromatic, Mod: 150-200 |
| Jazz/Blues | BPM: 90-120, Scale: Blues/Dorian |

## Technical Details

- **Dependencies**: p5.js 1.6.0, Tone.js 14.8.49 (CDN)
- **Browser Support**: Chrome 80+, Firefox 75+, Edge 80+, Safari 14+
- **Performance**: Grid Size <= 32, Image < 2000x2000

## Project Structure

```
PicSynth/
├── index.html       # Main application
├── Doc.html         # User guide (Chinese)
├── README.md        # This file
└── LICENSE          # MIT License
```

## License

MIT License - see [LICENSE](LICENSE) for details.

---

<a name="中文说明"></a>

# PicSynth 中文说明

<p align="center">
  <a href="#picsynth">EN</a> | <strong>中文</strong>
</p>

---

> 通过分析图片的颜色、亮度和饱和度，将任意图像转换为音乐。

**PicSynth** 是一个创新的音频视觉合成工具，能够将图片转换为包含旋律、低音线和鼓组的完整音乐作品。

## 功能特性

- **图像转音乐** - 分析像素颜色生成旋律
- **智能氛围检测** - 根据图片情绪自动推荐音阶和参数
- **FM 合成引擎** - 丰富的音色，完整的包络控制
- **多轨输出** - 旋律、低音线、鼓组
- **18 种音阶** - 从五声音阶到半音阶，包含异域音阶
- **实时控制** - 播放时调整所有参数
- **响应式设计** - 支持桌面和移动浏览器

## 快速开始

1. 在浏览器中打开 `index.html`（或访问 GitHub Pages 网站）
2. 点击 **"启动音序器 (Initialize)"** 启动音频引擎
3. 使用文件选择器上传图片
4. 音乐自动播放！点击画布可暂停/继续

## 工作原理

| 图像属性 | 映射到 | 效果 |
|----------|--------|------|
| 色相 (0-360) | 音高 | 不同颜色 = 不同音符 |
| 饱和度 | FM 调制 | 鲜艳 = 复杂音色 |
| 亮度 | 音量 + 时长 | 亮 = 响且长 |

### 智能预设

上传图片时，PicSynth 会分析：
- 整体亮度 -> BPM 速度
- 对比度 -> 音符时长
- 饱和度 -> 随机性和混响
- 主色调 -> 推荐音阶
- 色相多样性 -> 鼓组预设

## 控制模块

| 模块 | 参数 |
|------|------|
| 节奏与音序器 | BPM (40-300)、音符时长、网格大小 |
| 音高与音阶 | 18 种音阶、基准八度 (2-6)、随机性 |
| FM 合成核心 | 振荡器、谐波比、调制指数、失谐、ADSR |
| 滤波器与均衡 | 双滤波器，类型、频率、Q 值、增益 |
| 振幅包络 | 起音、衰减、延音、释放 |
| 效果器 | 混响干湿比 |
| 低音线 | 音高偏移、触发概率、根音倾向、滤波器 |
| 鼓组 | 5 种预设，4 种乐器独立控制 |

## 推荐图片

| 适合 | 不适合 |
|------|--------|
| 颜色丰富、对比鲜明 | 纯色 |
| 有渐变和过渡 | 过暗或过亮 |
| 抽象画、风景照 | 密集均匀的纹理 |

## 预设配方

| 风格 | 设置 |
|------|------|
| 电子舞曲 | BPM: 128-140, 音阶: 五声, 鼓组: Dense |
| 环境音乐 | BPM: 60-80, 音阶: Lydian, 混响: 0.6-0.8 |
| 实验音乐 | BPM: 180-240, 音阶: 半音, Mod: 150-200 |
| 爵士/布鲁斯 | BPM: 90-120, 音阶: Blues/Dorian |

## 技术信息

- **依赖库**: p5.js 1.6.0, Tone.js 14.8.49 (CDN 加载)
- **浏览器支持**: Chrome 80+, Firefox 75+, Edge 80+, Safari 14+
- **性能建议**: 网格大小 <= 32，图片尺寸 < 2000x2000

## 项目结构

```
PicSynth/
├── index.html       # 主应用程序
├── Doc.html         # 使用教程（中文详细版）
├── README.md        # 本文件
└── LICENSE          # MIT 许可证
```

## 许可证

MIT License - 详见 [LICENSE](LICENSE)

---

<p align="center">
  <strong>Transform your images into unique musical experiences!</strong><br>
  <strong>将你的图片转化为独特的音乐体验！</strong>
</p>
