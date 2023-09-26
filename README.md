##İçindekiler
- [Açıklama](##Açıklama)

## Açıklama
Merhaba Arkadaşlar bu dökümantasyon **CI/CD** süreçlerine dair tüm bilgileri içermektedir. Örnekleri proje dosyası içerisinde bulabilirsiniz. İyi Çalışmalar. 

 # Gitlab CI CD Rehberi
 ## CI/CD Temelleri

* **Continuous Integration (CI)(Sürekli Entegrasyon)**
* **Continuous Delivery (CD)(Sürekli Teslimat)**
* **Continuous Deployment (CD)(Sürekli Dağıtım)** 

## CI ve CD Arasında ki fark 
  ## Continuous İntegration (CI)(Sürekli Entegrasyon):
    * Sürekli entegrasyon (CI) içinde geliştiriciler, mümkün olduğunca sık olarak değişikliklerini ana dal'a birleştirirler.
    * Değişiklikler, bir derleme oluşturularak ve otomatik birim testler çalıştırılarak doğrulanır.
    *    Bu, entegrasyon zorluklarını önlemeye ve yeni taahhütler yapıldığında uygulamanın bozulmadığını kontrol etmeye yardımcı olur.
    
    ![CI](https://github.com/YakuphanSarikaya/CI-CD/assets/107619783/4c239a8a-b2fd-4151-a384-a6f5fba77487)


                                                                  

   ## Continuous Delivery (CD)(Sürekli Teslimat)
     * Sürekli entegrasyonun bir uzantısı olarak, tüm kod değişikliklerini otomatik olarak bir test ve/veya **Staging** ortamına dağıtan süreç.
     * Son üretim dağıtımı manuel olacaktır.
     * Sürekli teslimatın amacı, her zaman üretim ortamına dağıtıma hazır bir kod tabanına sahip olmaktır.
     
     ![cd](https://github.com/YakuphanSarikaya/CI-CD/assets/107619783/4310a391-3e0a-4357-b695-12ca8aa09a75)
  **Staging Nedir** 
  "Staging," yazılım geliştirme sürecinde kullanılan bir terimdir ve genellikle canlı üretim ortamına geçmeden önce kullanılan bir test ortamını ifade eder. Staging ortamı, yazılımın son değişikliklerinin ve güncellemelerinin test edildiği bir aşamadır. Bu aşamada, yazılımın performansı, uyumluluğu ve istikrarı gibi faktörler test edilir. Staging ortamında yapılan testler, herhangi bir hata veya sorunu tespit etmek ve bunları gidermek için kullanılır.

Staging, canlı üretim ortamına geçiş öncesi son kontrol ve onay aşaması olarak kullanılır. Bu sayede, canlı üretim ortamına geçiş sırasında beklenmeyen sorunların önlenmesine yardımcı olur ve yazılımın güvenli bir şekilde kullanıcılara sunulmasını sağlar.
