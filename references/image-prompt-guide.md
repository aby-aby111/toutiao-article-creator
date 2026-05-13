# AI 配图提示词指南

## 一、配图提示词通用结构

每个配图提示词应使用以下结构：

```
[场景描述] + [主体细节] + [风格/氛围] + [构图/视角] + [技术参数]
```

- **场景描述**：画面发生的地点、时间、环境
- **主体细节**：主要人物/物体的外观、表情、动作
- **风格/氛围**：摄影风格、光线、色调、情绪
- **构图/视角**：景别（远景/中景/特写）、角度（俯视/平视/仰视）
- **技术参数**：分辨率、画质要求

## 二、常用配图风格

### 1. 新闻纪实风格 (Photojournalism)
- 关键词：photojournalism, realistic, documentary style, natural lighting, candid
- 用途：新闻现场、事件还原类图片
- 参考提示词模板：`Photojournalism style, [场景描述], natural lighting, candid shot, realistic textures, 4K, high detail`

### 2. 信息图表风格 (Infographic)
- 关键词：infographic, data visualization, clean layout, modern design
- 用途：数据展示、对比分析类图片
- 参考提示词模板：`Modern infographic design, [数据主题], clean layout, flat design, blue and orange color scheme, high resolution`

### 3. 写实插画风格 (Realistic Illustration)
- 关键词：digital painting, realistic illustration, cinematic lighting
- 用途：场景渲染、概念图类图片
- 参考提示词模板：`Digital painting, [场景描述], cinematic lighting, detailed, atmospheric, 8K, masterpiece`

### 4. 情感特写风格 (Emotional Close-up)
- 关键词：close-up, emotional, portrait photography, shallow depth of field
- 用途：人物表情、情感渲染类图片
- 参考提示词模板：`Close-up portrait, [人物描述], emotional expression, shallow depth of field, warm lighting, photorealistic`

## 三、配图位置标注约定

在文章中，使用以下格式明确标注配图位置：

```
[图片位置: 段落X之后]
[配图提示词: {具体的AI生成提示词}]
```

例如：
```
[图片位置: 导语段之后]
[配图提示词: Photojournalism style, a crowded Chinese city street during rush hour, people looking at their phones with worried expressions, overcast sky, natural lighting, candid documentary shot, 4K, high detail]
```

## 四、针对不同文章类型的配图策略

### 社会热点类
- 第1张：事件现场/关键场景（新闻纪实风格）
- 第2张：数据/统计图（信息图风格）
- 第3张：受影响群体的人物特写（情感特写风格）
- 第4张：相关对比图或未来展望图（写实插画风格）

### 科技类
- 第1张：产品/技术展示（产品摄影风格）
- 第2张：数据对比/趋势图（信息图风格）
- 第3张：使用场景/效果图（写实插画风格）
- 第4张：行业格局/对比（信息图风格）

### 民生/生活类
- 第1张：最典型的真实生活场景（新闻纪实风格）
- 第2张：数据支撑图（信息图风格）
- 第3张：人物情绪特写（情感特写风格）
- 第4张：解决方案/美好愿景（写实插画风格）

## 五、提示词质量检查清单

- [ ] 是否包含场景描述？
- [ ] 是否包含主体细节？
- [ ] 是否指定了风格/氛围？
- [ ] 是否指定了构图/视角？
- [ ] 是否添加了画质参数（4K/high detail/photorealistic等）？
- [ ] 是否标注了图片在文章中的具体位置？
