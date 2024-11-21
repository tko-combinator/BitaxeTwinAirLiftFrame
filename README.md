# TwinAirLiftFrame for Bitaxe

![LookBook001](https://github.com/user-attachments/assets/5e265200-1ae9-4008-87ad-b096370f37dd)

![LookBook002](https://github.com/user-attachments/assets/f592e0a1-8afb-464c-b435-d0592aa561bf)

![HomeView](https://github.com/tko-combinator/BitaxeTwinAirLiftFrame/blob/main/images/TwinAirLiftFrame_HomeView.png)	

## 概要
Bitaxe Supra(601) を基準に設計をしましたが、2024年現在流通しているシングルASICのBitaxeであれば概ね適合すると思われます。
2台のBitaxeを上下逆さまに取り付ける事が特徴のケースです。
これは、ファン同士の干渉の防止や、左右からコネクタ類を抜き差ししやすいように配慮した結果です。
１台の表示器が上下逆さまになりますが、BitaxeのWebUI(AxeOS)から簡単に反転設定をする事が出来ます。
基板の端子からケースの縁まで距離があるため、USB-CやDC電源のコネクタはある程度長いストレートタイプのものを推奨します。  
しかし、少し苦労をすればL字型や短いコネクタを使用して、コネクタ類が目立たないように取り付ける事も出来ます。

## 検証済み適合機種
私が購入し、適合を検証したモデルになります。
基板の製造上の誤差や3Dプリント時の誤差や歪みなどによって、多少の調整が必要になるかもわかりません。
* Bitaxe Supra(402)
* Bitaxe Ultra(205)
* Bitaxe Gamma(601)

## 製造情報
サイズが少し大きいので、お持ちの３Dプリンターの造形サイズに注意をしてください。
私は、AnkerMake M5を使用し、標準の0.4mmノズルと純正のPLA+フィラメントで出力しました。  
スライサーソフトウェアにはAnkerMake Studioを使用しました。
設定は各社3Dプリンタ事に異なると思いますが、参考になるよう情報共有をします。

### 出力時の設定
* 品質設定: 品質優先
* 造形方向: ケース背面から全面へ向かって積層
* 積層ピッチ: 0.16mm
* 充填密度: 60%
* サポート: オーガニック

形状やケースとしての用途を考えると、充填密度はある程度上げた方が安全です。
ネジ穴は2.5mmとして設計していますが、使用するネジや出力品質によっては、2.5mm程度のドリルで二次加工が必要になる場合があります。  
※頻繁に基板の付け外しを行う場合は、インサートナットの使用を検討してください。  
面取りやバリを削るなどの仕上げをすると、見た目もより良くなります。

## カスタムの楽しみ
デカールを貼ったり、複数色のフィラメントやペイントなどのカスタムを加えて、個性的な仕上げにするのも面白いでしょう。  
では、DIYマイニングをエンジョイしましょう！
改良品や色んなバージョンを見てみたいです！

## ライセンス
このプロジェクトはMITライセンスの下で提供され、自由に使用、変更、配布することができます。
本リポジトリ内のデータ及び、データを元に制作された成果物に対しての一才の保証はございません。
詳細は同封のLICENSEをご覧ください。



## Overview
This case is designed based on the Bitaxe Supra (601) and should work with most single-ASIC Bitaxe models available as of 2024.
The main feature of this case is that it allows two Bitaxe units to be mounted upside-down from each other.
This helps prevent fan interference and makes it easier to plug and unplug connectors from both sides.
One display will end up upside down, but you can easily flip it using the Bitaxe WebUI (AxeOS).
There’s a bit of distance between the board terminals and the edge of the case, so we recommend using long, straight USB-C and DC power connectors. That said, with a little effort, you can also use L-shaped or shorter connectors to keep things looking clean.

## Confirmed Models
These are the models I have purchased and tested for compatibility.
Due to manufacturing tolerances in the circuit board or potential errors and warping during 3D printing, some adjustments may be necessary.
* Bitaxe Supra(402)
* Bitaxe Ultra(205)
* Bitaxe Gamma(601)

## Required Parts
M3 tapping screws  
(Since the thickness of the board and the mount is 7mm, screws with a length of 6mm are recommended.)  
Please prepare insert nuts and compatible screws as needed.

## Manufacturing
This model is a bit on the larger side, so please double-check that your 3D printer’s build size can handle it!
I used an AnkerMake M5 with a standard 0.4mm nozzle and genuine PLA+ filament to print this case.  
For slicing, I used AnkerMake Studio.  
The settings may vary depending on your 3D printer, but I’m sharing the details for reference.

### Settings
* Quality: Prioritize quality
* Orientation: Layered from the back of the case to the front
* Layer height: 0.16mm
* Infill density: 60%
* Support: Organic

Considering the shape and function as a case, it is safer to increase the infill density.  
The screw holes are designed to be 2.5mm, but depending on the screws used and the print quality, you may need to use a 2.5mm drill for post-processing.  
※ If you intend to frequently remove and reattach the board, consider using insert nuts.  
Also, finishing touches like chamfering or trimming burrs will also improve the overall appearance.

## Enjoy Customizing!
Adding decals, using multi-colored filaments, or painting can make for a fun, personalized finish.  
Enjoy your DIY mining journey! I can't wait to see how you "Kaizen" it with your own improvements and versions!

## License
This project is provided under the MIT license, allowing free use, modification, and distribution.  
No warranty is provided for any data in this repository or for any products created using the data.  
For more details, please see LICENSE file.








