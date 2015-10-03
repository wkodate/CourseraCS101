# Hardware

### Hardware

https://class.coursera.org/cs101-selfservice/wiki/view?page=hardware1

* hardwareはコンピュータの物理部分で、softwareコンピュータ上で動作するコードを参照する
* ピアノはhardwareで音楽はsoftware

##### Chip and Transistors

* トランジスタは重要なビルディングブロック。増幅器として動作する。ソリッドステートなデバイスなので動かない
* チップは小指サイズのシリコン
* チップはトランジスタを10億オーダーで含んでいる。CPIチップ、メモリチップ、フラッシュチップなど
* silicon(チップ、ソーラーパネル)とsilicone(シリコンゴムの物質)は異なる

##### Moore's Law

* トランジスタは18-24ヶ月ごとに小さくなってチップ内で倍の量になる
* computer1大あたりのトランジスタは安くなり、よりパワフルになる

##### Computer Hardware

* コンピュータは主にCPI, RAM, Disk or Flash の3つで構成される

1. CPU
  * Central Processing Unit。コンピュータの脳
  * コードの実行
  * コンピュータは1秒で20億の処理を実行でき、その役割はCPUが担っている
  * Byteは情報保持の単位。1byteは1文字。bとかXとか
2. RAM
  * Random Access Memory。一時的なストレージ
  * 変数への格納はRAMにロードしている
  * RAMはvolatile(揮発性)でpersistent(永続性)ではない
3. Persistent Storage: Hard Drive, Flash Drive
  * 永続的なストレージ
  * non volatile(不揮発性)であり、電源がオフになっても保存される
  * Hard drive(Hard Disk)は、スピンディスクの磁気パターンとしてbyteを保存する
  * Flash drive(Flash memory)はチップ内の電子としてbyteを保存する
  * Flash storageとしては、USB, SDカード、フラッシュチップ等がある。SSDとかもそう
  * File Systemは、永続ストレージに保持されているバイトを体系化する。ファイルに名前をつけたり、コピーや削除、記憶の方式などを管理できる

##### Microcontroller - Cheap Computer Chip

* MCU。マイクロコントローラ。
* 小さいCPU, RAM, ストレージを持ち、それらをひとつのチップ上に集積

##### Arduino Computer

* Arduinoはオープンソースのマイクロコントローラチップを搭載したボード
