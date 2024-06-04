## Çalışmanın Tanımı ve Amacı, Literatür Bilgisi

#### Haber Sınıflandırma

--> Çalışmanın Tanımı:

Çalışma, haber makalelerini farklı kategorilere ayırmak için insan beyninden ilham alan bir tür makine öğrenme modeli olan Yapay Sinir Ağlarının kullanımını içerir. Belirli sınıflara veya konulara kategorize edilmiş haber makalelerini içeren bir veri kümesi kullanarak bir ANN modelinin eğitimini kapsar. Daha sonra, bu eğitilmiş model, haber makalelerinden oluşan başka bir veri kümesinin kategorilerini sınıflandırmak için kullanılır.

--> Çalışmanın Amacı:

Yapay Sinir Ağlarını Kullanarak Haber Sınıflandırması: İlk amaç, haber makalelerini eğitim için kullanılan veri kümesine göre farklı kategorilere sınıflandırmak için yapay sinir ağlarının kullanılmasıdır. Bu, haber makalelerini otomatik olarak analiz etmek ve kategorize etmek için Yapay Sinir Ağları’ndan (ANN) yararlanılmıştır.

Haber Kategorilerinin Tahmini: Bir haber kategorisi veri kümesi kullanarak ANN modelini eğittikten sonra, başka bir haber veri kümesinin kategorilerini tahmin etmek için bu eğitilmiş model kullanıldı. Bu adım, eğitimli modeli performansını değerlendirmek ve haber makalelerini doğru bir şekilde sınıflandırma yeteneğini genelleştirmek için yeni, görünmeyen verilere uygulanmasını içerir.

--> Literatür Bilgisi:

Haber Sınıflandırmasına Önceki Yaklaşımlar: Haber sınıflandırması için farklı yöntemler (ANN, NLP teknikleri) kullanan önceki çalışmaları veya literatürü gözden geçirildi. Bu yaklaşımların güçlü ve sınırlı yönleri açısından bakıldığı zaman kullandığımız ANN modeli performans ve eğitim sonuçları diğer yöntemlere göre daha düşük kalmıştır.

Özellik Temsili: Önceki araştırmalar, kelime gömmeleri (Word2Vec, GloVe), TF-IDF (Term Frequency-Inverse Document Frequency) veya daha karmaşık temsiller (BERT, GPT modelleri) gibi metin verilerini temsil etmek için farklı yaklaşımlar kullanılmış.

Haber Sınıflandırmasında Yapay Sinir Ağlarının Uygulanması: ANN'yi özellikle haber sınıflandırma görevleri için kullanmanın etkinliğini gösteren literatürle karşılaştırıldı. ANN modelinin benzer yaklaşımların güçlü ve sınırlı yönleri açısından bakıldığı zaman kullandığımız ANN modeli performans ve eğitim sonuçları diğer yöntemlere göre daha düşük kalmıştır.

Haber Sınıflandırmasındaki Zorluklar ve Çözümler: Kullanılan birçok veri setinin yapısı gereği ANN modelinin eğitiminde çok farklı sonuçlar vermiştir. Hem modelimi hem de en uygun veri setini deneme yanılma yöntemiyle seçip oluşturarak en doğru sonuçları almaya çalıştım. Birçok kez alınan yüksek doğrulama değerlerine rağmen sınıflandırma sonuçları tam aksine çok hatalıydı. Bu sebeple aralarında bana en doğru sonuçları veren modeli ve veri setini kullandım.

Değerlendirme Metrikleri: ANN modelimin duygu analizindeki performansını ölçmek için hata matrisi, eğitim ve doğrulama ve kaybı, eğitim ve doğrulama doğruluğu, hassasiyet, hatırlama, F1 skoru, ROC eğrileri dahil olmak üzere sınıflandırma modellerinin performansını ölçmek için kullanılan çeşitli değerlendirme metriklerinin grafiklerini çıkarttım.


#### Duygu Analizi

--> Çalışmanın Tanımı:

Çalışma, haber yorumlarının analizini farklı kategorilere ayırmak için insan beyninden ilham alan Yapay Sinir Ağlarının kullanımını içerir. Belirli sınıflara veya konulara kategorize (pozitif-negatif-nötr) edilmiş haber yorumlarını içeren bir veri kümesi kullanarak bir ANN modelinin eğitimini kapsar. Daha sonra, bu eğitilmiş model, haber yorumlarından oluşan başka bir veri kümesinin kategorilerini (yani duyguları: pozitif-negatif-nötr) tahmin etmek için kullanılır.

--> Çalışmanın Amacı:
Yapay Sinir Ağlarını Kullanarak Duygu Analizi: Haber yorumlarını eğitim için kullanılan veri kümesine göre farklı kategorilere (duygulara) sınıflandırmak için yapay sinir ağlarının kullanılmasıdır. Bu, haber yorumlarını otomatik olarak analiz etmek için Yapay Sinir Ağları’ndan (ANN) yararlanılmıştır.

--> Literatür Bilgisi:

Duygu Analizinde Sinir Ağları: Doğal dil işlemede (NLP) çeşitli çalışmalar, metin sınıflandırma görevleri için sinir ağlarını kullanmaktadır. Duygu analizi, belge sınıflandırması ve konu modellemesi gibi görevler için NLP ve ANN teknikleri kullanılmıştır.

Özellik Temsili: Önceki araştırmalar, kelime gömmeleri (Word2Vec, GloVe), TF-IDF (Term Frequency-Inverse Document Frequency) veya daha karmaşık temsiller (BERT, GPT modelleri) gibi metin verilerini temsil etmek için farklı yaklaşımlar kullanılmış.

Değerlendirme Metrikleri: ANN modelimin haber sınıflandırmasındaki performansını ölçmek için hata matrisi, eğitim ve doğrulama ve kaybı, eğitim ve doğrulama doğruluğu, hassasiyet, hatırlama, F1 skoru, ROC eğrileri dahil olmak üzere sınıflandırma modellerinin performansını ölçmek için kullanılan çeşitli değerlendirme metriklerinin grafiklerini çıkarttım.

Duygu Analizindeki Zorluklar ve Çözümler: Kullanılan birçok veri setinin yapısı gereği ANN modelinin eğitiminde çok farklı sonuçlar vermiştir. Hem modelimi hem de en uygun veri setini deneme yanılma yöntemiyle seçip oluşturarak en doğru sonuçları almaya çalıştım. Birçok kez alınan yüksek doğrulama değerlerine rağmen analiz sonuçları tam aksine çok hatalıydı. Yorum sayısının az olmasına rağmen yorumların çekildiği haber sitelerinden bana en doğru sonucu veren haber yorumlarını kullandım. 
