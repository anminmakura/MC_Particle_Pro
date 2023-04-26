<h1 align="center">Blender Addon: MC Particle Pro</h1>
<h3 align="center">Documentation page for developers and purchasers of MC Particle Pro.</h3>

![Mcpp_icon_git](https://user-images.githubusercontent.com/39670701/234449788-ba50e993-7d3f-4c24-8186-38567ea49800.png)

<p align="left"> <img src="https://komarev.com/ghpvc/?username=anminmakura&label=Profile%20views&color=0e75b6&style=flat" alt="anminmakura" /> </p>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/anminmakura" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="anminmakura" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/https://www.youtube.com/c/anminmakura" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="https://www.youtube.com/c/anminmakura" height="30" width="40" /></a>
<a href="https://discord.gg/https://discord.gg/fsy5Hytexb" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="https://discord.gg/fsy5Hytexb" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.blender.org/" target="_blank" rel="noreferrer"> <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>


# 概要

MC Particle Proは、Blender用のエクスポートアドオンです。Blender内のオブジェクトの頂点を変換することで、パーティクルコマンドを基本として、コマンド位置等を必要としたコマンドを立体的かつ直感的に操作することができます。生成したコマンドはクリップボードに書き出すか、.mcfunctionとして書き出すことができます。これによりMinecraftのデータパックから簡単に呼び出せます。



## インストール方法

現在MC Particle Proはシンプルなアドオンで、.pyファイルの1つだけで構成されています。インストールには通常のBlenderアドオンのインストール方法を使用します。

- 7zipやwinrar等でzipファイルを解凍後、中身のpyを取り出します。
- Blenderを起動し、環境設定からアドオンメニューに移動します。
- 画面の右上にある「インストール」を押し、解凍したMC_Particle_pro_(version).pyを選択してインストールします。
- アドオン一覧からMC Particle Proを探し、チェックボックスをオンにします。



## 使い方

MC Particle Proは3DViewに追加されるアドオンのパネルで操作します。パネルはNキーで表示・非表示が切り替えられます。

- パーティクルコマンドの種類やパラメーターを設定します。
- エクスポートしたいオブジェクトを選択します。
- オブジェクトの頂点情報やマテリアル情報などを取得します。
- クリップボードに書き出すか、.mcfunctionとして書き出すかを選択します。
- Blenderの開始・終了のフレームの間のオブジェクトのアニメーションをフレーム単位で書き出すこともできます。

詳細な使い方は[こちら](https://www.youtube.com/watch?v=xxxxxx)の動画をご覧ください。
(動画はまだないです)


## お詫びと注意事項

.mcfunctionやdatapack等の管理や仕様の把握、また内部のexecuteコマンドを使っての複雑な条件付け等は各使用者に委ねています。
上記の件について私は一切助言等は出来ないので予めご了承ください。



### Blender Support Version
Currently the supported and confirmed working Blender versions are 3.4.0 to 3.5.0.



## License

MC Particle Pro Addon (C) 2023 anminmakura
Created by anminmakura
License : GNU General Public [License version3](http://www.gnu.org/licenses/)
