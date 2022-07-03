# NekoAgent

## 功能

- 开启刷沙
- 黑曜石柱不重置
- 使切石机造成伤害
- 使潜影贝重生
- 允许拴住村民
- 向玩家发送虚构的4级权限数据包
- 添加 `/mspt <ms>` 指令，可修改tps
- 修改服务器mod名

## 使用

```bash
java -javaagent:NekoAgent-1.0-SNAPSHOT.jar -jar paper.jar
```

## 禁用功能

```bash
java -javaagent:NekoAgent-1.0-SNAPSHOT.jar=enableSandDuplication -jar paper.jar
java -javaagent:NekoAgent-1.0-SNAPSHOT.jar=disableObsidianSpikesReset -jar paper.jar
java -javaagent:NekoAgent-1.0-SNAPSHOT.jar=enableStoneCutterDamage+enableShulkerSpawningInEndCities -jar paper.jar
```

## 功能数据值

- enableSandDuplication
- disableObsidianSpikesReset
- enableStoneCutterDamage
- enableShulkerSpawningInEndCities
- enableLeashableViallagers
- enableSetMSPTCommand
- enableFakePermissionLevel4
- maxShulkersCount=4
- minShulkersCount=1

## Build

```bash
gradlew build
```

## 作者

原作  Shirasawa
接坑  MikeWu597

## License

[MIT](./LICENSE)
