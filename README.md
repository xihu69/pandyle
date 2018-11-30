# pandyle

pandyle是一个基于jquery的MVVM库。它为jquery提供了基本的模板和组件功能。pandyle秉承jquery -- **write less, do more** 的设计理念，主要关注点即在于**简单**，它的大小只有7kb（压缩后），易学易用，努力减少你书写的代码量，并且更贴合传统的jquery的书写方式。

## 特点

- 简单：非常简单易上手，无需学习webpack、es6等前端知识，基本看一遍文档即可进行开发
- 兼容性良好：pandyle的兼容性取决于jquery版本，因此使用1.X版本的jquery即可兼容至ie8浏览器
- 约定优先的组件：pandyle采用约定优先的原则来设计组件，默认情况下只需在components目录下创建html文件即可作为组件使用，无需任何代码
- 同步操作：pandyle的所有操作都是同步的，代码的逻辑非常清晰（但是性能上有所牺牲）

## 适用场景

- 老项目重构：这可能是pandyle最能发挥作用的场景。很多老项目中使用了大量的jquery代码及jquery插件，使用其他框架进行重构的话可能会引起大量的修改，使用pandyle能以最小的代价对老项目完成mvvm的改造
- 兼容性要求较高的项目：一些特定领域的项目可能仍然要求兼容ie8甚至ie8以下的浏览器，不适合使用三大框架，这种情况下可以尝试使用pandyle作为替代
- 后端人员开发：pandyle对后端开发者是友好的，无需掌握现代前端的一系列工具和语法，后端开发者可以轻松上手
- 小项目：对小项目来说，pandyle的开发效率可能更高，有兴趣的可以尝试一下

## 文档

[在wiki中查看文档](https://github.com/RenRongrong/pandyle/wiki)

## 交流

你可以加入QQ群进行技术交流：524640426

