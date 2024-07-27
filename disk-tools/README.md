Тэг меняем при изменении состава утилит ИЛИ добавлении скриптов.

Сборка образа:
```shell
docker build disk-tools --label "git-commit=$(git rev-parse HEAD)" --tag bin.yodhaapp.com/it/ops-support/images/disk-tools:1
docker push bin.yodhaapp.com/it/ops-support/images/disk-tools:1
```
