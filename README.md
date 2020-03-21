SKCraft Launcher
================

※注意：日本語訳（意訳）です。

modpackを簡単にインストールしたいですか？  
SKCraft Launcherプラットフォームは次の場合に適しています。

:heavy_check_mark: 独自のニュースフィードや、ロゴ、ブランディングが必要な場合  
:heavy_check_mark: modpackをいつでも更新できるようにしたい場合  
:heavy_check_mark: 他の人に依存したくない場合  
:heavy_check_mark: セットとして提供したいmodpackある場合  
:heavy_check_mark: 秘密のコードでのみアクセス可能な「隠された」modpackを提供したい場合

次の場合は適していません。

:small_orange_diamond: modpackを作成しておいておくだけの場合  
:small_orange_diamond: ファイルをダウンロードするためのwebサイトや場所がない場合  
:small_orange_diamond: ランチャーの配布を行わない場合

## What We Do Right

このランチャーを使用してmodpackを作成するのは非常に簡単です。  
  :one: コンフィグとModsをフォルダーにドラッグアンドドロップします。  
  :two: ありません! XML / JSONファイル？？？  
  :three: modpackを作成するための素晴らしいインターフェースがあります。（コマンドラインも利用可能です）

このランチャーには、あなたが期待するすべての標準機能があります。  
  :one: ダウンロードのレジューム機能  
  :two: 差分更新  
  :three: 重複削除（更新やmodpack間のファイルが重複している場合は、ディスク容量を節約します）

「LiteLoader」や、「Forge」、「.jar mods」がサポートされています。  
 リソースパックや、configsフォルダやmodsフォルダにないランダムなmodファイルを配置することもできます。

何らかのWebサイトが必要ですが、PHPのような複雑な物は必要ありません。

技術的には、Gitまたは任意のVCSからCIサーバーを使用して、modpackを生成することができます。

## Getting Started

作業には数時間かかることが見込まれます。しかし、最小限の技術的経験のある人を対象とした各ステップのスクリーンショットを含む [detailed wiki](https://github.com/SKCraft/Launcher/wiki) があります。
また、評価を行うためのサンプルファイルが用意されています。サンプルファイルを用いてサイトにアップロードし、ランチャーが機能するかどうかを確認できます。

## Pretty Pictures

GUIツールを使用してmodpackを作成する場合、次のように表示されます。

![Modpack Creator](readme/pack_manager.png)

![Modpack Creator](readme/modpack_creator.png)

![Build Modpacks](readme/packages_generator.png)

modpackの作成は、各フォルダーにドラッグアンドドロップするだけで行えます。

* src/**config**/
* src/**mods**/
* src/**resourcepacks**/
* loaders/

LiteLoaderとForgeを *loaders* フォルダーに配置します。

### More Pictures

使用できるランチャーのダークバージョンがあります。

![Skinned](readme/launcher_skinned.png)

ユーザーはオプションの mod / feature を選択できます。

![Optional Features](readme/features.png)

ランチャーは自分自身を更新できます。また、ポータブルモードでも使用できます。

### The Light Theme

![Main Launcher](readme/launcher.png)

![Options](readme/options.png)

![Console](readme/log.png)

## Contributing

Pull requests can be submitted on GitHub, but we will accept them at our discretion. Please note that your code must follow Oracle's Java Code Conventions.

Contributions by third parties must be dual licensed under the two licenses described within LICENSE.txt (GNU Lesser General Public License, version 3, and the 3-clause BSD license).

## License

The launcher is licensed under the GNU Lesser General Public License, version 3.
