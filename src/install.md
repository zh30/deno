# 安装

Deno 是一个没有依赖性的单独的可执行文件。您可以使用下面的安装程序进行安装，也可以从 [发行页面](https://github.com/denoland/deno/releases) 下载发行二进制文件。

- 使用 Shell（macOS，Linux）:
  ```bash
  curl -fsSL https://deno.land/x/install/install.sh | sh
  ```
- 使用 PowerShell（Windows）:
  ```bash
  iwr https://deno.land/x/install/install.ps1 -useb | iex
  ```
- 使用 Rust 的 Cargo 包管理器（Windows，macOS，Linux）:
  ```bash
  cargo install deno
  ```
- 使用 Homebrew（macOS）:
  ```bash
  brew install deno
  ```
- 使用 Chocolatey（Windows）:
  ```bash
  choco install deno
  ```
- 使用 Scoop（Windows）:
  ```bash
  scoop install deno
  ```
  有关更多安装选项，请参阅 [deno_install](https://github.com/denoland/deno_install)。

# 验证是否安装成功

```bash
deno --version
```

如果打印出的信息类似于下面这样

```bash
deno 1.0.0
v8 8.4.300
typescript 3.9.2
```

那么恭喜你，已经安装成功了。
