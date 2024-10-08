# MLServer用

[![](https://jitpack.io/v/xyz.mlserver/MLServerUtil.svg)](https://jitpack.io/#xyz.mlserver/MLServerUtil)
[![Twitter](https://img.shields.io/twitter/follow/monster_2408?style=social)](https://twitter.com/monster_2408)
[![Discord](https://discord.com/api/guilds/556844677115150366/widget.png)](https://discord.mlserver.xyz)
[Website](https://monster2408.com)

[Java Docs](https://docs.mlserver.jp/MLServerUtil/)

```xml
<project>
    <repositories>
        <repository>
            <id>jitpack.io</id>
            <url>https://jitpack.io</url>
        </repository>
    </repositories>
    
    <dependencies>
        <dependency>
            <groupId>xyz.mlserver</groupId>
            <artifactId>MLServerUtil</artifactId>
            <version>VERSION</version>
        </dependency>
    </dependencies>
</project>
```

## スポンサー判定
- スポンサーかどうかは`sponsor.tier1`，`sponsor.tier1`，`sponsor.tier1`を持っているかで判断
- 判定基準はMinecraftアカウントと同期しているDiscordアカウントがスポンサー役職を持っているかで判定
- Discordでのスポンサー処理は外部サービスである [Ko-fi](https://ko-fi.com/mlserver) で行う

# JavaDocの生成
JavaバージョンとJavadocバージョンの違いでエラーが出たため標準の機能でなく`mvn`を使用することになったため以下コマンドを使用すること
```shell
mvn javadoc:javadoc
```