pwd / Bulunduğun dizine bakın
--

pwd komutu çalışmakta olduğunuz dizini gösterir.
```
pwd
```
cd / Dizinler arası geçiş yapın
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
ls / Dosya ve klasörleri listeleyin
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
cp / Dosyaları kopyalayın
--

a.txt adlı bir dosyanız varsa ve bu dosyanın şu adlı bir kopyasını istiyorsanız b.txt:
```
cp a.txt b.txt
```
Bir dizini kopyalamak için, -r eklemeniz gerekir
```
cp -r directory-1 directory-2
```
mv / Dosyaları veya dizinleri taşıyın.
--

"todo.txt" dosyasını "Belgeler" dizinine taşır:
```
mv todo.txt /home/herazur/Documents
```

mkdir / Yeni bir dizin oluşturun.
--

```
mkdir deneme
```

rmdir / Boş dizinleri silin.
--
```
rmdir directory1
```

rm -fr / Dolu dizini silin
--

```
rm -fr directory1
```

rm / dosya silin
--
```
rm file1
```
cat / Bir dosyanın içeriğini ekranda görüntüleyin.
```
cat
```
touch / boş bir dosya oluşturun
--
```
touch file1
```
clear / komut satırı ekranını/penceresini temizleyin.
--
```
clear
```
chmod / Bir dosyanın izinlerini değiştirin.
--
todo.txt" dosyasını herkes tarafından okunabilir, yazılabilir ve yürütülebilir hale getirecektir:
```
chmod 777 todo.txt
```

sudo / Yönetici veya kök izinleri gerektiren görevleri gerçekleştirin.
--
```
sudo
```
history / Komut geçmişine bak
--
```
history
```

kill / Bir işlemi durdurun.
--
```
kill
```

ssh / Ağ üzerinden başka bir Linux makinesinde uzaktan oturum açın.
--
```
ssh userr@ip
```
top / sisteminizde kullanılan kaynakları görüntüler.
--
```
top
```
