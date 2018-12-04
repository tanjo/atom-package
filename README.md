# Atom のインストール済みパッケージ

複数デバイス間での共有が目的

## export

```
apm list --installed --bare > atom-package.txt
```

## import

```
apm install --packages-file atom-package.txt
```

## 参考
- [Atomの設定・パッケージを複数端末で共有したいメモ \- Qiita](https://qiita.com/from_kyushu/items/1a7444aeb27af90ccd96)
