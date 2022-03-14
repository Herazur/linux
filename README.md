pwd
--

pwd komutu çalışmakta olduğunuz dizini gösterir.
```
pwd
```
cd
--

cd komutu bir dizin ismi ile birlikte yazılırsa o dizine geçiş yapmanı sağlar. Tek başına kullanımı home dizinine geçiş yaptırır. Örneğin Home klasöründen İndirilenler klasörüne geçiş yapmak için;
```
cd İndirilenler/
```
Tek başına kullanımı ya da (~) ile kullanımı home dizinine geçiş yaptırır.
```
cd ~

cd
```
Bir önceki dizine geçiş yapmak için
```
cd ..
```
ls
--

ls komutu bulunduğun dizindeki dosya ve klasörleri gösterir.
```
ls
```
Başka bir dizinin içeriğini listelemek ls ve klasör ismini yazın :
```
ls İndirilenler
```
ls /Kök dizinin içeriğini listelemek için komutu yazın :
```
ls /
```
Üst dizinin içeriğini listelemek için komutu yazın .
```
ls ..
```
İki seviye üst dizin içerikleri için kullanın :
```
ls ../..
```
Kullanıcıların ana dizinindeki içeriği listelemek için komutu yazın :
```
ls ~
```
Yalnızca dizinleri listelemek için komutu yazın:
```
ls -d */
```
Gizli dosyalar veya dizinler dahil olmak üzere dosya veya dizinleri listelemek için aşağıdaki komutu yazın. Linux'ta . ile başlayan her şey gizli dosya olarak kabul edilir:
```
ls -a
```
Dosyaları veya dizinleri listelemek ve son değiştirilme tarihine göre azalan düzende (büyükten küçüğe) sıralamak için komutu yazın:
```
ls -t
```
Dosyaları veya dizinleri listelemek ve boyuta göre azalan düzende (büyükten küçüğe) sıralamak için ls -S( S büyük harftir) komutunu yazın:
```
ls -S
```
Dizinin içeriğini aşağıdakileri içeren sütunlarla bir tablo biçiminde listelemek için aşağıdaki komutu yazın

- içerik izinleri
- içeriğe bağlantı sayısı
- içeriğin sahibi
- içeriğin grup sahibi
- içeriğin bayt cinsinden boyutu
- içeriğin son değiştirilme tarihi / saati
- dosya veya dizin adı
```
ls -l
```
cp
--

a.txt adlı bir dosyanız varsa ve bu dosyanın şu adlı bir kopyasını istiyorsanız b.txt:
```
cp a.txt b.txt
```
