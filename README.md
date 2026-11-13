# fuzzy-binder-cli

Mobile developer @Epic Games

折腾中的小玩具

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 安装

```bash
git clone https://github.com/USER/fuzzy-binder-cli.git
cd fuzzy-binder-cli
cargo build --release
```

## 备注

就是给自己省点事，没做太多抽象。

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## License

MIT
