## How to release dev

```shell
helm upgrade --install book-release ./ --values ./values.yaml --recreate-pods --namespace frontend-dev
```

## How to release prod

```shell
helm upgrade --install book-release ./ --values ./values.yaml --recreate-pods --namespace frontend-prod
```