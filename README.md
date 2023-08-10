## How to release dev

```shell
helm upgrade --install book-release ./ --values ./values.yaml --recreate-pods --namespace frontend-dev
```

## How to release prod

```shell
helm upgrade --install book-release ./ --values ./values.yaml --recreate-pods --namespace frontend-prod
```


## 分支管理
- 不同的git分支对应不同的发板环境
- 目前有： main  -  prod，   dev  -  dev