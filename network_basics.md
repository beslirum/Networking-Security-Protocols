# Temel Ağ Kavramları ve Yapıları

## Ağ Nedir?

Bir ağ (network), bilgisayar sistemleri veya diğer cihazlar arasında veri ve bilgi iletimini sağlayan bir iletişim altyapısını ifade eder. Ağlar, genellikle bilgisayarlar arasında dosya paylaşımı, internet erişimi ve diğer çeşitli hizmetlerin sağlanması için kullanılır.

## Ağ Temelleri

### 1. IP Adresleri

IP adresleri, ağdaki cihazların benzersiz tanımlayıcılarıdır. IPv4 ve IPv6 olmak üzere iki ana türü vardır.

Örnek IPv4 Adresi: `192.168.0.1`

#### IP Adres Türleri

- **Public IP:** İnternet üzerinde benzersiz ve genel erişilebilir IP adresi.
- **Private IP:** İnternal ağlarda kullanılan özel IP adresleri.

### 2. Alt Ağlar

Alt ağlar, büyük ağları daha küçük ve yönetilebilir parçalara bölen bir yapıdır. Bu, ağ trafiğini düzenlemek ve güvenlik sağlamak için kullanılır.

#### Alt Ağ Oluşturma

Örnek Alt Ağ: `192.168.1.0/24`

#### Alt Ağ Türleri

- **Sabit Alt Ağ:** Belirli bir bölge veya ofis için oluşturulan sabit alt ağ.
- **Dinamik Alt Ağ:** İhtiyaca göre otomatik oluşturulan ve genişleyen alt ağ yapısı.

### 3. OSI Modeli

OSI (Open Systems Interconnection) modeli, ağ protokollerinin ve iletişim süreçlerinin yedi katmana bölündüğü bir standarttır. Katmanlar, ağdaki işlevleri ve iletişim süreçlerini tanımlar.

- **Fiziksel Katman**
- **Veri Bağlantısı Katmanı**
- **Ağ Katmanı**
- **Taşıma Katmanı**
- **Oturum Katmanı**
- **Sunum Katmanı**
- **Uygulama Katmanı**

#### İlgili Konular

- **NAT (Network Address Translation):** Ağlar arasında IP adresleri dönüştürme süreci.
- **Firewall:** Ağ güvenliğini sağlamak için kullanılan güvenlik duvarı.

## Örnek Senaryolar

### Senaryo 1: IP Adresi Atama

Aşağıda, bilgisayarlar arasında IP adreslerinin nasıl atanacağını gösteren basit bir senaryo bulunmaktadır.

- Bilgisayar 1 IP Adresi: `192.168.1.2`
- Bilgisayar 2 IP Adresi: `192.168.1.3`

### Senaryo 2: Alt Ağ Kullanımı

Bu senaryoda, büyük bir ağın alt ağlara bölünmesi ve her alt ağın farklı bir bölgeyi temsil etmesi gösterilmektedir.

- Alt Ağ 1: `192.168.2.0/24` - Yönetim Bölgesi
- Alt Ağ 2: `192.168.3.0/24` - Üretim Bölgesi

---
