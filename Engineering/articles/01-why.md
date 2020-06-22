# 为什么要做前端工程化

首先，**工程发展到一定阶段，要出现的必然会出现**。

前端工程化是 JS 历史发展壮大的必要阶段，这就得益于前端生态圈、社区的推进：

- 有无处不在平台：Browser。
- 有最活跃平台：Node.js，Deno 也在兴起。
- 有组织：W3C(web)、ECMA-262(js)、A11y 等。
- 大公司都在使用：Google、Microsoft、Apple、Facebook 等。
- 有众多专家、开发者。

其次是：

- 前端越来越复杂，到今天几乎和后端接近一个量级，得益于 `node` 的兴起。
- 前端范畴越来越广，不仅仅是桌面浏览器，还有移动端网页、混合 app 等。
- 前后端分离。
- 模块化开发，不在从零开发造轮子，引用内部/外部的组件和模块，要进行模块管理。
- 出现各种编译器（转码器），不直接写 `html`、`css`、和`js`代码，用其友好的格式去书写，之后再用工具编译成目标格式，比如：用 `less`、`sass`、`stylus` 编写 CSS，用 `ES6`、`Typescript` 编写 JS。
- 开发流程和团队协作，现在的前端团队小到数人，大到数百人，如何协调多人多团队的工作，保证沟通顺畅，保证权限管理，越来越成为一大问题。

总结：

​ 工程化尽量要做到的就是统一。

​ 工程化包括从创建项目的脚手架到最终发布上线的整个过程，命令行的形式，桌面端的形式（umi ui，我在想，这个功能要不要用起来，可以把脚手架的里 curd/rcs 做成 plugin 集成到 umi ui 中），但这些都不包括编码阶段，和编辑器是分离的，需要单独使用。如果能做一个 ide（ice ？）来集成各种工程化的工具那就完美了。

​ 当然，在未来，css/html 如果也实现了原生的模块化，那工程化这块可能会有翻天覆地的变化了。