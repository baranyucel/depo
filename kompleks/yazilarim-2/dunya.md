---
layout: kompleksler
title: Blockchain - Mutabakat Algoritmaları
meta:
type: yazilarim-2
discoverer: Giuseppe Piazzi
discovered: 1950-01-01
orbit: 7.6 years
radius: 787 km
tilt: 7°
image: blockchain-1.jpeg
source: https://mars.nasa.gov/
---

- Blok Zinciri teknolojisi, üzerine inşa edilen kripto paralar ve merkeziyetsiz finans ekosistemi haricinde gelecekte, Tedarik Zinciri, Sağlık Hizmetleri, Yönetişim Sistemleri ve Nesnelerin İnterneti gibi birçok alanda yaygın bir biçimde kullanılacaktır.
- Bu bağlamda yazıda öncelikle Blok Zinciri teknolojisine değinip daha sonra çalışma metodunu anlayabilmek adına bazı mutabakat algoritmalarını inceleyeceğiz.

<h2>Blok Zinciri</h2>
- Blok zinciri teknolojisi, herhangi bir aracıya ihtiyaç duyulmadan, dağınık veri yapısında, kullanıcılar tarafından onaylanan blokların sistematik bir biçimde arka arkaya eklenmesiyle zincirlerin oluşması prensibine dayanır.
- Merkeziyetsiz ve dağıtık yapısından dolayı blok zinciri merkezi bir hatadan etkilenmeyeceği gibi kişilere veya kurumlara güven duyulmasını gerektirmeyecektir. Güvenlik sistemi ve işleyiş birbirlerine güvenmeyen madenciler tarafından sağlanır. Blok zinciri yalnız Bitcoin’in değil birçok kripto paranın da kullandığı bir teknolojidir.
- Bununla birlikte kripto paralar, şirketler vb. yapılar kendilerine ait blok zincirlere sahip olabilir. Blok zincirleri şeffaf yapılardır. Blok zinciri üzerinde işlem yapan bir kişi hangi işlemlerin hangi tarihlerde gerçekleştiğini görebilir.
- Fakat blok zinciri üzerinde gerçekleşen işlemlerde gönderici ve alıcı bilgisi olarak sadece cüzdan adresleri yer aldığından kimlik bilgilerinin gizli kalması sağlanır. Bir işlemin onaylanması için madencilik yapan kişilerin onayı ile sağlanır. Madenciler ortak havuzda toplanan işlemlerden bir blok oluşturur.
- Hangi madencinin bloğunun blok zincirine ekleneceği ise matematiksel problemlerin çözülmesi ile belirlenir. Bu problemler kriptografi ile oluşturulduğundan çözülmesi için yüksek işlem gücü gerekir. Problemi ilk çözen yani en yüksek işlem gücüne sahip olan madenci bloğu, blok zincirine ekler.
- Diğer madenciler ise yeni eklenen bloğu kendi zincirlerinde günceller. Yeni bir bloğun oluşturulup blok zincirine eklendiğinde bunu ekleyen madencinin 2 tip geliri vardır.
- Birincisi yeni blok ekleme ödülüdür. Bu ödül aynı zamanda sistemde ki yeni para arzının da tek kaynağıdır. Paranın kontrolü merkezi bir yapıda olmadığından paranın basılması yani isteğe bağlı üretilmesi söz konusu değildir. Blok oluşturma ödülü ile madenciler ödül olarak belirli miktarlarda Bitcoin elde eder. Bitcoin aynı zamanda arzı sınırlı bir kripto para birimidir. Bu sebeple her 4 yılda bir blok ödülü yarıya indirilir.
- Madencilerin elde edeceği ikinci gelir ise işlem komisyonudur. Kullanıcıların gerçekleştirdiği her işlemde gönderici belirli miktarda komisyon ödemektedir. Bu ödeme zorunlu olmamakla birlikte işlemin aktarım süresinin kısalması için zorunludur.

 <img src="/img/kompleks/sayfaici-1.png"  alt="">

<h2>Mutabakat Algoritmaları</h2>
- Mutabakat algoritmaları, kullanıcıların kendi aralarında yaptıkları işlemlerin onaylanması için tasarlanmış mekanizmadır. Blok zincirleri merkezi olmadığından dağıtık sistemler olarak oluşturulmuştur. İşlemlerin geçerliliği için dağıtık node’ların mutabakata varması gerekmektedir.
- Bu noktada mutabakat algoritmaları protokol kurallarına uyulmasını sağlayarak kullanıcıların işlemlerini güvenli bir biçimde gerçekleştirmelerini sağlar.

<h2>Emek İspatı</h2>

<img src="/img/kompleks/emekispati.png"  alt="">

- Emek İspatı (Proof of Work) kavramı ilk olarak CynthiaDwork ve MoniNaor tarafından istenmeyen e-postalar ile mücadele etmek amacıyla kullanıldı. Emek ispatı blok zinciri üzerinde çalışan ilk mutabakat algoritmasıdır. İlk olarak Bitcoin (BTC) tarafından kullanıldı.
- Bitcoin ’de bir blok yayınlanmadan önce o bloğun güvenliğini belirleyen ve bir önceki blokların güvenliğini arttıran kriptografik özet fonksiyonu kullanılarak bir bulmaca tanımlanır ve bu bulmacayı çözen ilk düğüm bu bloğu yayınlama hakkına sahip olmaktadır.
- Bu bulmacanın çözümünde yoğun miktarda enerji harcanmakta olup ve bu çözümün kendisi ‘kanıt/ispat’ olarak tanımlanmaktadır. Emek ispatı uygulanabilir bir mutabakat protokolü ortaya koymuştur.
- Bu sayede P2P (kullanıcıdan kullanıcıya) para transferlerinde aracı ihtiyacını ortadan kaldırarak işlem masraflarında büyük oranda düşüş sağlamıştır.

<h2>Hisse İspatı</h2>

<img src="/img/kompleks/hisseispati.png"  alt="">

- Hisse İspatı (Proof of Stake) mutabakat algoritması, Emek ispatı yönteminin en çok kullanılan alternatifidir. Hisse ispatının ortaya çıkış amacı Emek ispatı yönteminde ki sorunları ve eksiklikleri ortadan kaldırmaktır.
- Emek ispatı bilindiği üzere CPU(İşlemci) lar üzerinden yürütülen bir algoritma olduğundan yüksek enerji maliyeti ve donanım gerektirir. Emek ispatı, enerji kaynağı ve donanım gibi dışarıdan gelecek yatırımlara ihtiyaç duyar.
- Hisse ispatında ise yatırım kripto paranın kendisine yapılır.
- Hisse İspatında madencilik faaliyetleri bir nevi cüzdanda bulunan coinler ile yürütülür. Kişinin cüzdanında ne kadar çok coin bulunursa blok onaylayıcı olarak seçilme olasılığı o kadar yüksek olur.
- Özet olarak bu yapının anlamı, kullanıcıların blok onaylayıcısı olma şansına sahip olma olasılığının elinde bulundurdukları para oranına eşit olmasıdır.

<h2>Delege Edilmiş Hisse İspatı</h2>

<img src="/img/kompleks/delegelihisseispati.png"  alt="">

- Blok zinciri mutabakat algoritmalarının karşılaştıkları en önemli sorun, gittikçe daha merkezi hale gelmeleri ve blok oluşturma verimliliğinin reel ihtiyaçların çok gerisinde kalmasıdır.
- Bu doğrultuda blok oluşturma hakkının adil bir biçimde atanabilmesi ve merkezileşmenin önlenebilmesi için Delege Edilmiş Hisse İspatı ( Delegated Proof of Stake) mutabakat algoritmaları geliştirilmiştir.
- Hisse İspatının doğuşunda ki en önemli etkenlerden biri Emek İspatında ki ölçeklenebilirlik sorunuydu. Emek ispatında ki işlem süreleri günlük ticaret için uygun değildir. Bununla beraber Hisse İspatı ve Emek İspatında blok oluşturma hakkına sahip olmak için çeşitli imkanlara sahip olmak gerekir.
- Örneğin Emek ispatında blok oluşturma şansını arttırabilmek için yüksek işlem gücüne sahip CPU’ lara sahip olmak gerekir. Hisse İspatında ise blok oluşturma hakkına sahip olmak için kişinin cüzdanında hisse yani mutabakatın yapılacağı paradan bulundurması gerekir. Delege Edilmiş Hisse İspatında da blokların oluşturulması için benzer bir yol izlenir.
- Kullanıcılar, oy kullanarak blokların doğrulanmasını sağlayacak kişiyi seçer. Oy mekanizması ise Hisse İspatına benzer bir yöntemle ilerlemektedir. Cüzdanında en çok para bulunduran en çok oy hakkına sahip olur. Ancak bu sistemde blok üreticileri demokratik oylama ile seçileceğinden, yapacakları hatalarda saf dışı bırakılma riski taşırlar.
- Bunun yanı sıra Delege edilmiş hisse ispatı, oylama sistemi sayesinde blok oluşturma sürecini hızlandırdığından saniye başına gerçekleşen işlem hızı Emek İspatı ve Hisse İspatından fazladır

<h2>Faydalanılan Kaynaklar</h2>
- Melaine Swan, Blockchain Blueprint for a New Economy
- Barış Alnıaçık, Kripto Paraların Dünya ve Türkiye’deki Güncel Durumu Üzerine Bir İnceleme
- Süleyman Kardaş, Blokzincir Teknolojisi Uzlaşma Protokolleri
- Fahad Saleh, Blockchain Without Waste: Proof-of-Stake
- Binance Akademi, Blockchain Mutabakat Algoritmaları
- Fan Yang, Delegated Proof of Stake With Downgrade
