# VignettesHub（AI生成病例集）

## 概要
VignettesHub 是由 OPQRST 公司开发的项目，旨在使用 AI 生成模拟医学病例。通过提供典型的疾病示例，有助于理解罕见疾病的症状、检查、治疗和后续过程。目前，我们也在制作由医生修订的版本。本项目适用于自学、教育及科研目的。目前也正在扩展至日语以外的多种语言。

## 特点
- **多语言支持**：不仅提供日语，也支持其他语言的病例  
- **AI生成内容**：使用 OpenAI 的多个模型，通过自定义提示词生成  
- **专家监督**：由医生修订和审阅（计划中）  
- **教育用途**：适用于自学和教学场景  

## 使用方法
1. 克隆或下载此仓库。  
2. 浏览所需语言和疾病的文件夹。  
3. 查看或下载病例文件进行使用。  

## 目录结构
VignettesHub
├── 中国語（北京語）/（按语言分类）
│   ├── AI-generated/（AI原始生成文本）
│   │   ├── gpt-4o-2024-08-06/（按模型分类）
│   │   │   ├── Vignette/（根据诊断名生成的病例）
│   │   │   └── Dialogue/（基于病例生成的医患对话）
│   │   └── gpt-4o-mini-2024-07-18/
│   └── MD-modified/（医生修订过的文本）
├── English/
├── Spanish/
├── 日本語/
⋮
## 使用模型
目前使用的是 OpenAI 提供的模型。有关模型的详细信息，请参考以下链接：  
[https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)

## 许可证
本项目采用 MIT 许可证开源。详情请参阅 LICENSE 文件。

## 免责声明
- 本项目提供的病例仅供教育与科研用途，不可作为医疗行为的参考。  
- 虽力求准确，但不保证内容的完整性与时效性。  
- 因使用本项目造成的任何损失，OPQRST 公司及开发者概不承担任何责任。  

## 贡献
欢迎报告错误或提出改进建议。详情请参考 `CONTRIBUTING.md` 文件。

## 联系方式
如有问题或建议，请提交 issue 或通过以下方式联系：

**邮箱**：contact@opqrst.co.jp  
**官网**：[https://opqrst.co.jp/](https://opqrst.co.jp/)