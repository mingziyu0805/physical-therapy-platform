# physical-therapy-platform# 🏥 运动分析与康复评估平台
# Movement Analysis & Rehabilitation Platform

[English](#english) | [中文](#中文) | [한국어](#한국어)

## 中文

### 项目简介
这是一个专业的物理治疗数据分析平台，提供：

✨ **核心功能**
- 📊 **三级分析系统**
  - 初级：单关节角度分析与ROM计算
  - 中级：多关节运动学分析
  - 高级：治疗前后对比与效果评估
  
- 🌍 **多语言支持**
  - 中文 (简体)
  - English
  - 한국어
  - Español
  - 日本語

- 📁 **数据处理**
  - 支持CSV、Excel、JSON格式
  - 实时数据分析
  - 自动生成报告

- 📈 **临床应用**
  - 关节运动范围(ROM)评估
  - 步态模式分析
  - 治疗效果量化
  - 患者进展跟踪

### 快速开始

#### 在线访问（推荐）
1. 访问：https://[你的GitHub用户名].github.io/physical-therapy-platform
2. 无需安装，立即使用

#### 本地运行
1. 克隆仓库
```bash
git clone https://github.com/[你的用户名]/physical-therapy-platform.git
cd physical-therapy-platform
```

2. 用浏览器打开 `index.html`
```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

### 使用步骤

#### 步骤1：准备数据
确保CSV文件包含以下列：
```
time, gait_phase, hip_angle, knee_angle, ankle_angle
```

示例数据：
```csv
0.00, 0.00, 8.5, 3.2, 5.1
0.01, 1.00, 9.2, 3.8, 4.9
0.02, 2.00, 10.1, 4.5, 4.7
```

#### 步骤2：上传文件
1. 点击"上传"按钮
2. 选择CSV/Excel/JSON文件
3. 系统自动分析

#### 步骤3：查看结果
- 📊 关节角度曲线图
- 📋 ROM统计表格
- 📈 对比分析图表
- 📑 可导出报告

### 参考值

| 关节 | 运动 | 正常ROM | 单位 |
|-----|------|--------|------|
| 髋关节 | 屈曲/伸展 | 120°/20° | 度 |
| 膝关节 | 屈曲/伸展 | 140°/0° | 度 |
| 踝关节 | 背屈/跖屈 | 20°/50° | 度 |

### 技术栈
- 前端：HTML5, CSS3, JavaScript
- 数据处理：客户端解析
- 部署：GitHub Pages
- 浏览器兼容：Chrome, Firefox, Safari, Edge (最新两个版本)

### 文件结构
```
physical-therapy-platform/
├── index.html              # 主页面 (1个文件，包含所有代码)
├── _config.yml            # GitHub Pages配置
├── DEPLOYMENT_GUIDE.md    # 详细部署指南
├── README.md              # 本文件
├── data/                  # 示例数据
│   └── sample_data.csv
└── LICENSE                # MIT许可证
```

### 部署到GitHub Pages

#### 快速5步部署
1. Fork或创建新仓库
2. 上传 `index.html`
3. 进入Settings → Pages
4. 选择 "main" 分支
5. 完成！网站自动发布

**详细指南：** 见 [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md)

### 常见问题

**Q: 数据会被上传到服务器吗？**
A: 不会。所有数据处理都在您的浏览器本地进行，隐私完全保护。

**Q: 支持多大的文件？**
A: 取决于浏览器内存，通常可处理10MB以上的文件。

**Q: 可以离线使用吗？**
A: 可以，下载HTML文件后直接在浏览器打开即可。

**Q: 如何修改参考值？**
A: 编辑HTML中的 `referenceData` 对象（约第400行）。

### 贡献指南
欢迎提交bug报告和功能建议：
1. 点击"Issues"
2. 描述问题或建议
3. 提交Issue

### 许可证
MIT License - 可自由使用、修改和分发

### 联系方式
📧 Email: your-email@example.com
💬 讨论区: GitHub Discussions
🔗 官网: [你的网站]

### 更新日志

**v1.0.0 (2024-01-01)**
- ✨ 首次发布
- 📊 支持三级分析系统
- 🌍 支持5种语言
- 📁 支持CSV/Excel/JSON
- 🎨 响应式设计

### 致谢
感谢所有贡献者和用户的支持！

---

## English

### About
Professional physical therapy data analysis platform featuring:

✨ **Key Features**
- 📊 **Three-Level Analysis**
  - Beginner: Single joint angle analysis & ROM calculation
  - Intermediate: Multi-joint kinematics analysis
  - Advanced: Pre/post treatment comparison & effect assessment
  
- 🌍 **Multi-Language Support**
  - English
  - 中文 (Simplified Chinese)
  - 한국어 (Korean)
  - Español (Spanish)
  - 日本語 (Japanese)

- 📁 **Data Processing**
  - Support CSV, Excel, JSON formats
  - Real-time data analysis
  - Automatic report generation

- 📈 **Clinical Applications**
  - Range of Motion (ROM) assessment
  - Gait pattern analysis
  - Treatment effect quantification
  - Patient progress tracking

### Quick Start

**Online** (Recommended):
1. Visit: https://[your-github-username].github.io/physical-therapy-platform
2. No installation needed, use immediately

**Local**:
1. Clone repository
```bash
git clone https://github.com/[your-username]/physical-therapy-platform.git
```
2. Open `index.html` in browser

### Usage

**Step 1**: Prepare data with columns: `time, gait_phase, hip_angle, knee_angle, ankle_angle`

**Step 2**: Upload CSV/Excel/JSON file

**Step 3**: View analysis results with charts and statistics

### Reference Values

| Joint | Motion | Normal ROM | Unit |
|-------|--------|-----------|------|
| Hip | Flexion/Extension | 120°/20° | degrees |
| Knee | Flexion/Extension | 140°/0° | degrees |
| Ankle | Dorsiflexion/Plantarflexion | 20°/50° | degrees |

### Deployment

1. Create GitHub repository
2. Upload files
3. Settings → Pages → Select "main" branch
4. Website automatically published!

**Full Guide**: See [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md)

### FAQ

**Q: Is my data sent to servers?**
A: No. All processing happens locally in your browser.

**Q: Can I use offline?**
A: Yes, download the HTML file and open in browser.

**Q: Can I modify it?**
A: Yes, MIT License allows free modification and distribution.

### License
MIT License

---

## 한국어

### 프로젝트 소개
전문적인 물리치료 데이터 분석 플랫폼으로 다음을 제공합니다:

✨ **주요 기능**
- 📊 **3단계 분석 시스템**
  - 초급: 단일 관절 각도 분석 및 ROM 계산
  - 중급: 다중 관절 운동학 분석
  - 고급: 치료 전후 비교 및 효과 평가

- 🌍 **5개 언어 지원**
  - 한국어
  - 中文
  - English
  - Español
  - 日本語

- 📁 **데이터 처리**
  - CSV, Excel, JSON 형식 지원
  - 실시간 데이터 분석
  - 자동 보고서 생성

### 빠른 시작

**온라인** (추천):
1. 방문: https://[GitHub-사용자명].github.io/physical-therapy-platform
2. 설치 불필요, 즉시 사용

**로컬**:
```bash
git clone https://github.com/[사용자명]/physical-therapy-platform.git
```

### 참고값

| 관절 | 운동 | 정상 ROM | 단위 |
|-----|------|--------|------|
| 엉덩이 | 굴곡/신전 | 120°/20° | 도 |
| 무릎 | 굴곡/신전 | 140°/0° | 도 |
| 발목 | 배굴/족저굴 | 20°/50° | 도 |

### 배포
1. GitHub 저장소 생성
2. 파일 업로드
3. Settings → Pages → "main" 선택
4. 자동 배포 완료!

### 라이선스
MIT License

---

## 📊 비교표 (Comparison Table)

| 기능 | 초급 | 중급 | 고급 |
|-----|------|------|------|
| 단일관절분석 | ✅ | ✅ | ✅ |
| 다중관절분석 | ❌ | ✅ | ✅ |
| ROM 계산 | ✅ | ✅ | ✅ |
| 통계검증 | ❌ | ❌ | ✅ |
| 치료전후비교 | ❌ | ❌ | ✅ |
| 품질점수 | ❌ | ❌ | ✅ |

---

**⭐ 이 프로젝트가 유용했다면 Star를 눌러주세요! (Star if this project helps you!)**

최종 업데이트: 2024년
