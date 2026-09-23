---
layout: post
title: "hayatın bloatware'larını temizlemek"
date: 2026-09-23 11:00:00 +0300
---

Sistem kaynaklarını tüketen en büyük şey, hiçbir zaman o yazılımın çekirdeğindeki karmaşıklık değildir; üzerine sonradan yamanmış, temel bir işlevi olmayan ama sürekli arka planda çalışan o lanet bloatware'lardır. Bugün kendi zihnime dışarıdan baktığımda bunu görüyorum. Çok temel, basit bir döngüyü işletirken bile CPU'nun anlamsızca %100'e vurması gibi bir his. Sorun donanımda değil, sorun benim bu sisteme yüklenmesine izin verdiğim gereksiz bağımlılıklarda.

Bir problemi ilk prensiplerine indirgemek; kodu yazarken ya da sıfırdan bir mimari kurarken, minimalist, hacker estetiğiyle yaklaşmak, sıfırdan bire gitmek işin doğasında var. Gereksiz hiçbir satıra, fazladan hiçbir parametreye tahammülüm yok. Ama iş kendi zihnime, kendi hayatıma gelince neden bu kadar fazla abstraction katmanına izin veriyorum? Geleceğe dair o kontrol edemediğim bilinmezlikler, anlamsız senaryolar, dış dünyanın gürültüsü vesaire... Bunların hepsi zihnimdeki birer bloatware; sisteme hiçbir katma değer sağlamıyorlar, bir çıktı üretmiyorlar, sadece deli gibi RAM tüketiyorlar.

Tıpkı Nevada 250'nin ateşleme sistemiyle veya yakıt enjeksiyonuyla uğraşırken yaptığım gibi yapmam lazım. Motor tekliyorsa veya çalışmıyorsa, gidip en alakasız, en karmaşık sensörlerden teşhise başlamazsın. Temel bileşenlere inersin: hava, yakıt ve kıvılcım var mı? Çalışma prensibi bu kadar basit. Zihni de aynı bu mekanik kesinlikle, bu acımasız sadelikle optimize etmek zorundayım.

Bir düşünce, bir kaygı benim kontrol alanımda değilse, onu sistemden `kill -9` ile acımadan sonlandırmam gerekiyor. Benim inandığım estetik; karmaşık, süslü ve ağır olan değil, en az parçayla en saf haliyle çalışan şeydir. Makinelere entegre ettiğim computer vision algoritmalarındaki sadelik gibi: veriyi al, işle, sonuca git. Aradaki o gürültüye, acabalara yer yok.
