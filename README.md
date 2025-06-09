# Java全栈工程师之路：AI协同与企业级项目实战

面向编程新手的Java全栈开发教程，强调AI协同编程和企业级实践。

## 项目概述

这是一个基于Quarto Book的Java教材项目，采用渐进式学习方法，通过微项目和企业级宏项目相结合的方式，帮助编程新手从零基础成长为Java全栈工程师。

## 核心特色

- 🤖 **AI协同编程**：与Cursor等AI工具深度集成，体验现代编程方式
- 📚 **新手友好**：从零开始，循序渐进，充满鼓励性的学习体验
- 🏗️ **项目驱动**：通过实际项目学习，理论与实践相结合
- 🎯 **企业导向**：突出Java在企业级开发中的优势和最佳实践
- 💡 **对比学习**：与Python等语言对比，突出Java的独特价值

## 教材结构

### 第一部分：Java基础核心（章节1-6）
- 微项目驱动的系统性学习
- 从"个性化问候器"到"多线程下载模拟器"
- 循序渐进建立Java核心概念

### 第二部分：企业级项目实战（章节7-12）
- "IntelliRecommend"智能内容平台项目
- 模拟敏捷开发流程
- 引入Git、Docker、单元测试等企业实践

## 快速开始

### 环境要求

- Java JDK 17 (LTS版本)
- Cursor AI编辑器或其他现代IDE
- 现代操作系统（Windows 10+, macOS 10.15+, Linux）

### 安装指南

1. **安装JDK 17**
   ```bash
   # macOS (使用Homebrew)
   brew install openjdk@17
   
   # Ubuntu/Debian
   sudo apt install openjdk-17-jdk
   
   # Windows - 下载安装包
   # https://adoptium.net/
   ```

2. **安装Cursor编辑器**
   - 访问 [cursor.sh](https://cursor.sh)
   - 下载并安装适合你操作系统的版本

3. **验证安装**
   ```bash
   java --version
   javac --version
   ```

### 运行示例

```bash
# 编译并运行第一章示例
cd code-examples/chapter-01
javac PersonalizedGreeter.java
java PersonalizedGreeter
```

## 构建教材

本项目使用Quarto Book进行内容组织和发布：

```bash
# 预览
quarto preview

# 构建
quarto render

# 构建PDF
quarto render --to pdf
```

## 学习路径

### 初学者路径
1. 从第1章开始，逐章学习
2. 完成每章的动手练习
3. 积极与AI协作，解决遇到的问题
4. 参与学习社群讨论

### 有经验开发者路径
1. 快速浏览第1-3章，了解Java基础
2. 重点关注第4-6章的高级特性
3. 深入学习第7-12章的企业级实践

## AI协同编程指南

### 推荐的AI工具
- **Cursor**：专门为AI协作设计的代码编辑器
- **GitHub Copilot**：强大的代码补全工具
- **ChatGPT/Claude**：优秀的编程学习伙伴

### AI协作最佳实践
1. **清晰描述需求**：详细说明你想实现的功能
2. **提供足够上下文**：告诉AI你的项目背景
3. **逐步验证**：理解AI的建议，不要盲目复制
4. **主动学习**：向AI询问"为什么"，深入理解原理

## 贡献指南

我们欢迎社区贡献！你可以：

- 🐛 报告错误或问题
- 💡 提出改进建议
- 📝 改进文档和示例
- 🌟 分享学习心得

## 技术支持

- 📖 查看[Wiki文档](./wiki)
- 💬 加入学习讨论群
- 🤖 善用AI助手解决问题
- 📧 联系教学团队

## 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

## 致谢

感谢所有为这个项目贡献内容、建议和反馈的朋友们！

---

**开始你的Java全栈工程师之旅吧！** 🚀

记住：每一个伟大的程序员都是从第一行代码开始的。让AI成为你的编程伙伴，一起创造属于你的代码世界！ 