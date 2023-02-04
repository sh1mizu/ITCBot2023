# ITC bot 2023 取説
- このbotはITC Bot ver.1.1.0を移植したものです。
- 高度な操作ができるため、`BOT使用`のロールが付与されていないと使用できません。
- コマンドは随時追加予定。

# 目次

- [コマンド一覧](https://github.com/kariumi/ITCBot/edit/master/Readme.md#コマンド一覧)
  - [!shuffle](https://github.com/kariumi/ITCBot/edit/master/Readme.md#shuffle) - メンバーをボイスチャンネルに均等に振り分ける
- [更新履歴](https://github.com/kariumi/ITCBot/edit/master/Readme.md#%E6%9B%B4%E6%96%B0%E5%B1%A5%E6%AD%B4)

# コマンド一覧

## \!shuffle

自分が入っているボイスチャンネルの人を指定したボイスチャンネルにランダムに振り分け、自動的に移動させるコマンドです。
```Python
!shuffle [ボイスチャンネルID 1] [ボイスチャンネルID 2] ...

例：
!shuffle 123456789012345678 123456789012345679
```
上記のように指定すると、指定したボイスチャンネルにランダムに振り分けることができます。
```Python
!shuffle [(任意)ロール 1] [(任意)ロール 2] [(任意)ロール 3] [ボイスチャンネルID 1] [ボイスチャンネルID 2] ...

例：
!shuffle @DTM部 @CG部 123456789012345678 123456789012345679
```
上記のようにロールを指定すると、指定したロールのメンバーは均等に振り分けられます。
- ロールは0~3個の間で指定することができます。


  
# 更新履歴
### 2022/12/**
- ITC bot ver1.1.0から移植。

### 2023/2/3
- voteコマンドを削除。

### 2023/2/4
- shuffleコマンドの軽微な修正。
- Readmeを執筆。