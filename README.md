
# 👋 你好，我是KAGUYA810

[![Email](https://img.shields.io/badge/邮箱-kaguya810@petalmail.com-blue?style=flat-square&logo=gmail)](mailto:kaguya810@petalmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Kaguya810-black?style=flat-square&logo=github)](https://github.com/kaguya810)
[![B站](https://img.shields.io/badge/Bilibili-月見山・輝夜-blue?style=flat-square&logo=bilibili)](https://space.bilibili.com/35197337)

## 🚗 关于我

```python
class VehicleEngineer(東方厨, Programmer):
    def __init__(self):
        self.name = "YourName"
        self.affiliation = "车辆工程专业学生"
        self.interests = [
            "新能源汽车设计", 
            "计算机视觉应用", 
            "自动化流程开发",
            "东方Project"
        ]
        self.skills = {
            "编程语言": ["Python", "C++", "MATLAB"],
            "框架工具": ["Qt", "OpenCV", "Simulink"],
            "工程领域": ["动力系统设计", "控制系统", "车辆动力学"]
        }
    
    def solve_problems(self):
        return "用代码解决繁琐工程流程"
    
    def contribute(self):
        return "OpenMV2023电赛视觉代码"
```

一名穿梭于机械与代码世界的车辆工程学生。致力于用编程将繁琐的工程流程自动化，让工程师能专注于真正的创造。

## 🔧 技术栈

### 🛠 编程语言
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-orange?style=for-the-badge&logo=mathworks&logoColor=white)

### 📊 框架与工具
![Qt](https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-orange?style=for-the-badge&logo=mathworks&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 🚘 工程领域
![新能源汽车](https://img.shields.io/badge/新能源汽车-3DDC84?style=for-the-badge&logo=tesla&logoColor=white)
![控制系统](https://img.shields.io/badge/控制系统-4285F4?style=for-the-badge)
![计算机视觉](https://img.shields.io/badge/计算机视觉-FF6F00?style=for-the-badge&logo=google-lens&logoColor=white)

## 🌟 精选项目

### 1. 🚀 [新能源汽车动力系统设计工具](https://github.com/kaguya810/EVCar-AutoDesigner)
![MATLAB](https://img.shields.io/badge/-MATLAB-orange) 
![车辆工程](https://img.shields.io/badge/-车辆工程-blue)
> 基于MATLAB的新能源汽车动力系统参数匹配与性能分析工具  
> ✨ 特征：电机参数匹配、电池系统设计、传动比优化、性能分析

```matlab
% 驱动力-阻力平衡分析
function analyze_performance()
    % 参数定义
    v = linspace(0, 140, 500); % 车速范围 (km/h)
    F_drive = calculate_drive_force(v);
    F_resistance = calculate_resistance(v);
    
    % 找到平衡点
    crossover_idx = find(F_drive >= F_resistance, 1, 'last');
    v_max = v(crossover_idx);
    
    fprintf('最高车速: %.1f km/h\n', v_max);
end
```

### 2. 👁️ [OpenMV 2023电赛视觉解决方案](https://github.com/kaguya810/TI2023-E-OpenMV.Part)
![Python](https://img.shields.io/badge/-Python-yellow) 
![OpenCV](https://img.shields.io/badge/-OpenCV-blueviolet)
![OpenMV](https://img.shields.io/badge/-OpenMV-redviolet)
> 2023年全国大学生电子设计竞赛视觉识别解决方案  
> 🏆 提供高效的目标追踪算法

```python
def detect_objects(frame):
    """高效物体检测算法"""
    # 预处理图像
    processed = preprocess_frame(frame)
    
    # 使用优化轮廓检测
    contours = find_contours(processed)
    
    # 特征提取与过滤
    valid_objects = []
    for cnt in contours:
        if is_valid_object(cnt):
            valid_objects.append(extract_features(cnt))
    
    return valid_objects
```

## 📊 开发活动统计

<!-- GitHub统计卡片 -->
<div align="center">
  
![](https://github-readme-stats.vercel.app/api?username=kaguya810&show_icons=true&theme=tokyonight)
![](https://github-readme-streak-stats.herokuapp.com/?user=kaguya810&theme=tokyonight)

</div>


*このコードも幻想のままに~* ✨
