# components subModule

## 关联和引用

### 首次关联submodule

在需要引用submodule的主仓库相关目录下使用

```
git submodule add https://github.com/linjieFE/components.git
```

### 主干仓库拉取submodule内容

适用于已关联submodule子库的主干仓库。
当本地第一次拉取主干仓库代码时，submodule文件夹可能是空的。
这时需要 在master下运行来拉取同步submodule内容
```
git submodule update --init --recursive
````
