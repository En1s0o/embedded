# Rust Embedded 笔记



这是一个 demo，并没有实际使用。



## 参考资料

- 书籍

  https://docs.rust-embedded.org/book/intro/index.html

- 词汇表

  https://braun-embedded.com/glossary/

- 快速开始

  https://github.com/rust-embedded/cortex-m-quickstart

- STM32 Rust

  https://github.com/stm32-rs/stm32-rs

  支持的设备

  https://stm32-rs.github.io/stm32-rs

- STM32 HAL

  访问 https://github.com/stm32-rs 获取，例如：

  https://github.com/stm32-rs/stm32f4xx-hal

- 最小化程序

  https://github.com/johnthagen/min-sized-rust



## 环境准备

- 工具链

  参考 https://jonathanklimt.de/electronics/programming/embedded-rust/rust-on-stm32-2/

  ```shell
  rustup update
  rustup target list # 查看工具链
  rustup target install thumbv7m-none-eabi # 交叉编译工具链
  cargo install cargo-flash # 程序烧写（可选）
  ```

