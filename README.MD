# Cisco Packet Tracer Ağ Yapılandırma Çalışması

Bu proje, Cisco Packet Tracer kullanılarak yapılan DHCP yapılandırmaları ve ağ bağlantılarını kapsamaktadır. Amacımız, temel ağ yapılandırma becerilerini geliştirmek ve DHCP'nin ağ ortamında nasıl çalıştığını anlamaktır.

## İçerik

- **21100011016_Odev4.pdf**: Ağ yapılandırma işlemlerine dair rapor ve detaylı açıklamalar.
- **21100011016_Odev4.pkt**: Cisco Packet Tracer dosyası, ağın yapılandırıldığı dosya.

## Projede Yapılan Çalışmalar

### NETWORK – 1 (192.168.1.0/24)
1. **Ağ Bağlantısı**: Ağ uygun şekilde kablolanarak mantıksal görüntü elde edildi.
2. **R1 Router IP Ataması**: 192.168.1.1 IP adresi R1 routerına atandı.
3. **Statik IP Atamaları**: Sunucu ve istemcilere uygun IP adresleri, subnet mask ve default gateway değerleri girildi.
4. **DHCP Yapılandırması**: 192.168.1.10’dan başlayan ve 100 IP içeren bir IP havuzu oluşturuldu.
5. **Dinamik IP Tahsisi**: Her üç istemciye DHCP üzerinden dinamik IP tahsisi yapıldı.

### NETWORK – 2 (192.168.2.0/24)
6. **Ağ Bağlantısı**: R1 ve R2 routerları “Serial DTE” kablosu ile bağlandı ve mantıksal görüntü elde edildi.
7. **R2 Router IP Ataması**: 192.168.2.1 IP adresi R2 routerına atandı.
8. **Router IP Atamaları**: R1 ve R2 arayüzlerine 10.0.0.1 ve 20.0.0.1 IP adresleri atandı.
9. **Yönlendirme Protokolü**: Her iki router arasında yönlendirme protokolü tanımlandı.
10. **Ping Testi**: PC3’ten PC0’a ping atılarak bağlantının doğruluğu test edildi.

### DHCP Relay Konfigürasyonu
11. **IP Havuzu Eklenmesi**: 2. Ağ için IP ataması yapılacak bir IP havuzu tanımlandı.
12. **DHCP Relay**: R2 üzerinde DHCP sunucusunun adresi belirtildi.
13. **Dinamik IP Tahsisi**: PC3 istemcisine DHCP üzerinden dinamik IP ataması yapıldı.

## Kullanılan Araçlar

- **Cisco Packet Tracer**: Ağ simülasyonu ve yapılandırma aracı. [Cisco Packet Tracer'ı indirin](https://www.netacad.com/courses/packet-tracer)
- **Raporlar ve Ekran Görüntüleri**: Yapılan işlemlere dair ekran görüntüleri ve açıklamalar PDF dosyasında sunulmuştur.

## Nasıl Kullanılır?

1. **Packet Tracer Dosyasını Açın**: `21100011016_Odev4.pkt` dosyasını Cisco Packet Tracer ile açarak ağ yapılandırmalarını inceleyebilirsiniz.
2. **PDF Raporunu İnceleyin**: `21100011016_Odev4.pdf` dosyasında, yapılan işlemler ve konfigürasyon adımları detaylandırılmıştır.

---

Bu çalışma, ağ protokol yapılandırmalarını ve DHCP'nin çalışma prensiplerini öğrenmek için hazırlanmıştır.

