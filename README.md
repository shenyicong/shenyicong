<div align="center">
  <img src="assets/banner.svg" alt="沈奕聪 — 嵌入式 · 数据分析 · 前端开发" width="100%" />

  <br/>

  <a href="https://github.com/shenyicong">
    <img src="https://komarev.com/ghpvc/?username=shenyicong&label=PROFILE+VIEWS&color=00f0ff&style=flat-square" alt="Profile views" />
  </a>
  <a href="https://github.com/shenyicong?tab=followers">
    <img src="https://img.shields.io/github/followers/shenyicong?label=FOLLOWERS&style=flat-square&color=7b61ff" alt="Followers" />
  </a>
  <img src="https://img.shields.io/badge/FOCUS-EMBEDDED%20%7C%20DATA%20%7C%20WEB-ff2d95?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/STATUS-BUILDING-00ff9d?style=flat-square" alt="Status" />
</div>

<img src="assets/divider.svg" width="100%" />

```console
shenyicong@github:~$ whoami
→  学生开发者 / 从寄存器到浏览器

shenyicong@github:~$ cat focus.txt
→  单片机:   AT89C51 · 传感器驱动 · 电机控制 · 状态机
→  数据:     Python 采集 · 清洗 · 统计 · 可视化
→  Web:      HTML / CSS / JS · 交互与业务逻辑

shenyicong@github:~$ echo $PHILOSOPHY
→  "能跑起来只是及格，能解释清楚才算学会。"
```

<img src="assets/divider.svg" width="100%" />

## ⚡ 技术栈

<div align="center">

**— 嵌入式 / Embedded —**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![AT89C51](https://img.shields.io/badge/AT89C51-1a1a2e?style=for-the-badge&logo=microchip&logoColor=00f0ff)
![Keil](https://img.shields.io/badge/Keil%20uVision4-0a0f1e?style=for-the-badge&logo=arm&logoColor=00f0ff)
![Proteus](https://img.shields.io/badge/Proteus-0a0f1e?style=for-the-badge&logo=circuitverse&logoColor=7b61ff)

<!-- 传感器 / 外设 -->
![DS18B20](https://img.shields.io/badge/DS18B20-1a1a2e?style=flat-square&logo=thermometer&logoColor=00f0ff)
![LCD12864](https://img.shields.io/badge/LCD12864-1a1a2e?style=flat-square&logo=lcd&logoColor=7b61ff)
![L298](https://img.shields.io/badge/L298%20Motor-1a1a2e?style=flat-square&logo=robot&logoColor=ff2d95)

**— 数据 / Data —**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-0a0f1e?style=for-the-badge&logo=plotly&logoColor=00f0ff)

**— Web / 工具 —**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

<img src="assets/divider.svg" width="100%" />

## 🧩 精选项目

<table>
<tr>
<td width="50%" valign="top">

### 🌡️ 智能风扇系统
> *AT89C51 · C · Proteus*

温度闭环控制的完整嵌入式系统。DS18B20 采集 → 单片机运算 → L298 驱动电机调速，LCD12864 实时显示。

**技术要点**
- 单总线时序驱动（`Qnewire.c` 手写位操作）
- 五键交互状态机：START / STOP / `+` / `-` / MODE
- 显示与采集分离的模块化架构

`main.c` `LCD12864.c` `DS18B20.c`

[→ 查看仓库](https://github.com/shenyicong/smart-fan-at89c51)

</td>
<td width="50%" valign="top">

### 📊 车型数据可视化分析
> *Python · 爬虫 · 数据清洗*

面向易车网的车型数据采集与多维分析管线。

**技术要点**
- 分层清洗：缺失值 / 异常值 / 重复值识别与处理
- 数值 + 分类特征分别处理策略
- 可视化驱动的结论输出

`requests` `pandas` `matplotlib`

[→ 查看仓库](https://github.com/shenyicong/yiche-car-analysis)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🍜 外卖管理系统
> *HTML · CSS · JavaScript*

纯前端实现的完整业务闭环，订单流转全程可视化。

**技术要点**
- 商品 → 购物车 → 下单 → 订单状态的链路设计
- 原生 JS 状态管理，无框架依赖
- 响应式布局

`vanilla JS`

</td>
<td width="50%" valign="top">

### 🚀 星骸战甲 ASTRA FRAME
> *Three.js · WebGL · 原生 JS*

浏览器端第三人称科幻射击演示。程序化生成战场与贴图，逐步揭开地图迷雾。

**技术要点**
- 全程序化贴图：分形噪声 → 高度图 → 法线贴图，零外部资源
- 迷雾视野系统：标量场 + 着色器遮罩，未探索区域不渲染敌人
- 性能优化：固定步长逻辑、实例化网格、对象池、动态像素比

`Three.js` `ShaderMaterial` `WebAudio`

[→ 查看仓库](https://github.com/shenyicong/astra-frame)

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" />

## 📈 活跃度

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=shenyicong&show_icons=true&theme=radical&hide_border=true&bg_color=0a0f1e&title_color=00f0ff&icon_color=7b61ff&text_color=c9d1d9&include_all_commits=true&count_private=true" alt="GitHub Stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shenyicong&layout=compact&theme=radical&hide_border=true&bg_color=0a0f1e&title_color=00f0ff&text_color=c9d1d9&langs_count=8" alt="Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=shenyicong&theme=radical&hide_border=true&background=0a0f1e&stroke=00f0ff&ring=ff2d95&fire=ff2d95&currStreakLabel=00f0ff" alt="Streak" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shenyicong&bg_color=0a0f1e&color=00f0ff&line=7b61ff&point=ff2d95&area=true&hide_border=true" width="95%" alt="Activity Graph" />

</div>

<img src="assets/divider.svg" width="100%" />

## 🎯 当前动态

```yaml
正在学习:
  - 嵌入式系统设计模式与可维护性
  - Python 数据管道的工程化
  - Git 工作流与协作规范

正在构建:
  - 星骸战甲 ASTRA FRAME（Web 端实时射击）
  - 智能风扇系统的代码重构
  - 车型数据分析的可复现流程

开放合作:
  - 嵌入式 / 数据方向的实习与项目合作
```

<img src="assets/divider.svg" width="100%" />

<div align="center">

**「把复杂问题拆到能讲清楚为止。」**

<br/>

![Visitors](https://raw.githubusercontent.com/shenyicong/shenyicong/output/github-contribution-grid-snake-dark.svg)

<sub>最后更新 · 2026</sub>

</div>
