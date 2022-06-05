# Mikeneko65
(English version is [here](./README.md))  

Mikeneko65はkkatanoさんが開発・公開している[Bakeneko65(v3)](https://github.com/kkatano/bakeneko-65)からフォークした65%サイズのメカニカルキーボードです。  

![Mikeneko 65](./image/mikeneko-65.jpg)

Oリングガスケットマウント(フリクションフィット)の特性を活かしつつ、フォームを追加してキーボード内部の隙間や空間を減らすことで、打鍵感と打鍵音を向上させました。

## OSS版Bakeneko65とMikeneko65の違い
OSS版Bakeneko65(v3)とMikeneko65の主な違いは下記のとおりです。
- ホットスワップ(ソケット)に対応、ホットスワップ対応に伴い、キーレイアウトを固定化
- プレートの形状を変更し、スクリューインタイプのスタビライザーに対応
- PCBフォーム、ケースフォーム、ソケットフォーム、、スイッチパッドを追加
- [Remap](https://remap-keys.app/)に対応

ケースは変更しておらず、OSS版Bakeneko65と互換性があります。  

## 仕様
- サイズ: 315 x 110 x 30mm
- タイピング角度: 6度
- 重量: 760g前後
- Oリング: AS568-264またはAS568-263のシリコン素材を推奨

## キーレイアウト
![Mikeneko 65 layouts](./image/keyboard-layout.png)

## ファームウェア
- [viaバイナリ](./qmk_firmware/mikeneko65_via.hex) ・・・ VIAに対応したファームウェアのバイナリファイルです。通常はこちらをご利用ください。
- [defaultバイナリ](./qmk_firmware/mikeneko65_default.hex) ・・・ VIAに対応していないファームウェアのバイナリファイルです。
- [QMKソースコード](./qmk_firmware) ・・・ [QMK](https://github.com/qmk/qmk_firmware)に取り込まれています。
- [VIAソースコード](./keyboards) ・・・ [VIA](https://github.com/the-via/keyboards)に取り込まれています。

## コミュニティ
Mikeneko65に関する雑談・ご質問・ご意見は[takishimのDiscordサーバー](https://discord.com/channels/927936241805189171/927936242283319308)でお願いします。  
(kkatanoさんのDiscordサーバーでMikeneko65について問い合わせることはご迷惑になるのでご遠慮ください)

## ライセンス
MIT [英語](https://opensource.org/licenses/MIT) [日本語](https://licenses.opensource.jp/MIT/MIT.html)

## 免責
すべてのファイルは、ご自身の責任においてご利用ください。

## 謝辞
- **kkatanoさん** ・・・ Bakeneko65のデータをOSSで公開していただいたおかげで、時間を忘れて没頭できる趣味に出会うことができました。
- **ai03さん, kb-elmoさん** 彼らが開発・公開してるドーターボードを利用させてただきました。
- **desuchanさん** スクリューインに対応したプレートのデータを流用させていただきました。
- **各Discordサーバーの皆さん** ・・・ 様々なことを教えていただき、学ばせていただきました。
