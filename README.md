[![C++ Core Guidelines](cpp_core_guidelines_logo_text.png)](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)

c++是一种更小、更简单、更安全的语言。
>-- <cite>Bjarne Stroustrup</cite>

[c++核心指南](CppCoreGuidelines.md)是由Bjarne Stroustrup领导的一项协作工作，很像c++语言本身。它们是跨许多组织进行了许多人年的讨论和设计的结果。它们的设计鼓励通用性和广泛采用，但是可以自由地复制和修改它们，以满足您的组织的需要

## Getting started

这个指南可在[CppCoreGuidelines](CppCoreGuidelines.md)找到。文档在[GH-flavored MarkDown](https://github.github.com/gfm/)中。它有意保持简单(主要是ASCII格式)，以允许自动后期处理，如语言翻译和重新格式化。编辑人员维护一个[用于浏览的格式化版本](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)。注意，它是手工集成的，并且可能比主分支中的版本稍早一些。

指南是一个不断发展的文档，没有严格的“发布”节奏。Bjarne Stroustrup定期检查文档，并在介绍中增加版本号。[签入增加版本号](https://github.com/isocpp/CppCoreGuidelines/releases)被标记到git中。

许多指南使用了只有头文件的指南支持库。一个应用实现可以在[GSL: 指南支持库](https://github.com/Microsoft/GSL)获得。

## 背景和范围

指南的目的是帮助人们有效地使用现代c++。我们所说的“现代c++”是指c++ 11、c++ 14和c++ 17。换句话说，如果您现在就可以开始，您希望您的代码在5年后是什么样子?10年后?

本指南主要关注相对较高层次的问题，比如接口、资源管理、内存管理和并发性。这些规则会影响应用程序体系结构和库设计。遵循这些规则将导致代码是静态类型安全的，没有资源泄漏，并且捕获的编程逻辑错误比现在代码中常见的要多得多。而且它会运行得很快——你可以做正确的事情。

我们不太关心底层的问题，比如命名约定和缩进样式。然而，这方面没有主题可以帮助程序员。

我们最初的规则集中强调安全性(各种形式)和简单性。他们可能太严格了。我们希望引入更多的异常来更好地适应现实世界的需要。我们还需要更多的规则。

你会发现有些规则与你的期望相悖，甚至与你的经验相悖。如果我们没有建议你以任何方式改变你的编码风格，我们就失败了!请尝试验证或推翻规则!特别是，我们真的希望我们的一些规则能够得到度量或更好的示例的支持。

您会发现一些规则很明显，甚至是微不足道的。请记住，指导方针的目的之一是帮助那些缺乏经验或来自不同背景或语言的人跟上进度。

这些规则被设计为由分析工具支持。违反规则将被标记为相关规则的引用(或链接)。我们并不期望您在尝试编写代码之前记住所有的规则。

这些规则旨在逐步引入到代码库中。我们计划为此开发工具，希望其他人也能这样做。

## Contributions and LICENSE

欢迎提出改进意见和建议。随着我们对该文档的理解不断提高，以及可用库的语言和集合的不断改进，我们计划修改和扩展该文档。更多细节可在[contribution](./ contribution.md)和[LICENSE](./LICENSE)找到。

感谢[DigitalOcean](https://www.digitalocean.com/?refcode=32f291566cf7&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=CopyPaste)托管标准c++基金会网站。
