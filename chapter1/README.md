# 第1章 Rust工具链安装和介绍

本章主要讲解Rust工具链的安装步骤，以及安装过程中涌现出来必须要掌握的知识点。

包括以下内容：
1. Rust工具链安装原理。软件安装过程中能体现出来很多软件本身的知识，安装过程搞清楚，就能学会一大堆知识，也能解决很多问题。
2. MS build tool的安装。Rust工具链安装之前，必须有一个C语言的编译器，在windows平台上这个C语言编译器可以通过安装ms build tool来获得。
3. Rustup下载及安装。Rustup是Rust工具链的安装工具，和多版本Rust工具链的管理工具。
4. Rust安装过程的知识点。安装过程中，需要选择host-triple、toolchain、component、target等,这些概念必须搞清楚，为后续学习清理知识堵点。
5. Rustup管理多工具链的方法。Rustup也是Rust工具链的多版本管理工具，具体管理多个版本工具链的方法。
6. Cargo管理项目的方法。Cargo是rust中的依赖管理工具和构建管理工具，基本的依赖管理方法和构建管理方法需要在开始正文之前介绍。