Network Protocols
--

**Taşıma katmanı ağ protokolleri**
--

- TCP

Bir bilgisayar başka bir bilgisayarla iletişim kurmak istediğinde, bu iki bilgisayar arasındaki iletişimin iyi ve güvenilir olması gerekir, böylece verilerin doğru şekilde alınmasını garanti edebilir.

Örneğin, bir web sayfasını görüntülemek veya bir dosya indirmek veya bir e-postaya bakmak istediğinizde, web sayfasını hiçbir şey eksik olmadan olduğu gibi ve sırayla görüntülemeyi beklersiniz. Veya bir dosya indiriyorsanız, dosyanın sadece bir kısmını değil, tüm dosyayı istersiniz, çünkü veriler eksikse veya sıra dışıysa, bu sizin için için herhangi bir fayda sağlamaz.

TCP burada devreye girer bu yüzden. TCP İletim Kontrol Protokolü (Transmission Control Protocol) anlamına gelir ve bu TCP / IP Ağı kullanılan ana protokoller biridir. Bir web sayfasını TCP olmadan görüntülerseniz, web sayfanız tamamen karışabilir. Görüntüler eksik olabilir veya metin ters ve sıra dışı olabilir.

Artık TCP, bağlantı odaklı bir protokoldür, bu da temelde iletişim kuran iki bilgisayar arasındaki bir oturum onaylaması anlamına gelir. Böylece iki bilgisayar, herhangi bir iletişim gerçekleşmeden önce bir bağlantıyı doğrular. Ve bunu üç yönlü bir el sıkışma kullanarak yapar. Dolayısıyla ilk adım, bir bilgisayarın SYN adlı bir mesaj göndermesidir. Daha sonra alıcı , gönderene mesajı aldığını bildiren bir onay mesajı gönderir ve son olarak gönderen bilgisayar alıcıya başka bir alındı mesajı gönderir. Ve bu gerçekleştiğinde, veriler teslim edilebilir. TCP hakkında unutulmaması gereken bir diğer önemli husus da, verilerin teslimini garanti etmesidir. Yani bir veri paketi yoldan çıkarsa ve ulaşmazsa, TCP onu yeniden gönderecektir. 

- UDP

UDP, TCP'ye çok benzer. UDP ayrıca veri göndermek ve almak içindir. Ancak temel fark, UDP'nin bağlantısız olmasıdır. Bu, bir oturum oluşturulmadığı ve veri teslimini garanti etmediği anlamına gelir. Dolayısıyla, bir bilgisayar verilerini gönderdiğinde, verilerin diğer uçta alınıp alınmadığı gerçekten umursamaz ve bu nedenle UDP "ateşle ve unut" (fire-and-forget) protokolü olarak bilinir, çünkü veri gönderir ve ona ne olduğu gerçekten umrunda olmaz. Unutulmaması gereken bir diğer nokta da, veri dağıtımını garanti etmemenin gerektirdiği daha az ek yük nedeniyle UDP'nin TCP'den daha hızlı olmasıdır.

**Uygulama katmanı ağ protokolleri**
--

- DHCP 

Her bilgisayar veya cihaz, iletişim amacıyla bir ıp adresine sahip olmalıdır. IP adresi, ağdaki bir bilgisayar veya aygıt için bir tanımlayıcıdır. Ve bir bilgisayara bir IP adresi atamanın iki yolu vardır. Statik IP veya Dinamik IP kullanılarak yapılabilir. Artık statik bir IP, bir kullanıcının bir IP adresine sahip bir bilgisayarı veya cihazı manuel olarak atadığı yerdir. Şimdi bu, ağ oluşturmanın başlangıcında yapılan orjinal yöntemdi. Dolayısıyla, bir ağdaki her bilgisayar için bilgisayarın ağ yapılandırma sayfasını açmanız ve manuel olarak bir IP adresi girmeniz gerekiyordu. Ancak bir IP adresine ek olarak, bir alt ağ maskesi (subnet mask) varsayılan ağ geçidi ve bir DNS sunucusu da yazmanız gerekir. Ve ağa başka bir bilgisayar veya cihaz eklemek istediğinizde, aynı şeyi yapmanız gerekiyordu. Tahmin edebileceğiniz gibi, özellikle çok sayıda bilgisayara sahip büyük bir ağla uğraşıyorsanız, bu çok fazla iş olabilir. Ayrıca, tüm IP adreslerinin benzersiz olduğundan emin olmalısınız çünkü aynı IP adresini iki kez atarsanız, bir IP çakışmasına neden olur ve bu bilgisayarların ağa erişememsine neden olur.
