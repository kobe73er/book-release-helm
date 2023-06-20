## How to release
```
helm upgrade --install book-release ./ --values ./values.yaml --recreate-pods --namespace frontend
```