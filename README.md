# Definition and Purpose of the Study, Literature Review

## News Classification

#### Definition of the Study

This study involves the use of Artificial Neural Networks (ANNs), a machine learning model inspired by the human brain, to categorize news articles into different categories. It includes training an ANN model on a dataset of news articles that are already categorized into specific classes or topics. Subsequently, this trained model is used to classify the categories of another dataset of news articles.

#### Purpose of the Study

###### News Classification Using Artificial Neural Networks
The primary goal is to classify news articles into different categories based on the dataset used for training. This leverages Artificial Neural Networks (ANNs) to automatically analyze and categorize news articles.

###### Predicting News Categories
After training the ANN model using a news category dataset, this trained model was then employed to predict the categories of another news dataset. This step involves applying the trained model to new, unseen data in order to evaluate its performance and generalize its ability to accurately classify news articles.

#### Literature Review

###### Previous Approaches to News Classification
Previous studies or literature that used various methods (ANN, NLP techniques) for news classification were reviewed. When considering the strengths and limitations of these approaches, it was observed that the performance and training outcomes of the ANN model used in our study were lower compared to other methods.

###### Feature Representation
Earlier research employed different techniques to represent text data, such as word embeddings (Word2Vec, GloVe), TF-IDF (Term Frequency–Inverse Document Frequency), or more complex representations (BERT, GPT models).

###### Application of Artificial Neural Networks in News Classification
Literature demonstrating the effectiveness of ANNs specifically for news classification tasks was compared. Again, when evaluating strengths and limitations of similar approaches, our ANN model’s performance and training results were lower than those of other methods.

###### Challenges and Solutions in News Classification 
Due to the structure of the various datasets used, the training of the ANN model yielded very different outcomes. By trial and error, I selected and formed both the most suitable dataset and the most appropriate model to achieve the best results. Despite obtaining high validation scores multiple times, the classification results were often quite inaccurate. Therefore, among the options, I utilized the model and dataset that yielded the most accurate results.

###### Evaluation Metrics
To measure the performance of my ANN model in sentiment analysis (in the context of classifying news), I plotted various evaluation metrics commonly used in classification tasks, including the confusion matrix, training and validation loss, training and validation accuracy, precision, recall, F1 score, and ROC curves.

## Sentiment Analysis

#### Definition of the Study

This study involves the use of Artificial Neural Networks (ANNs), inspired by the human brain, to categorize news comments into different categories. It includes training an ANN model on a dataset of news comments that are categorized (positive–negative–neutral). Subsequently, this trained model is used to predict the categories (i.e., sentiments: positive–negative–neutral) of another dataset comprising news comments.

#### Purpose of the Study

###### Sentiment Analysis Using Artificial Neural Networks
The goal is to classify news comments into different categories (sentiments) based on the dataset used for training. This leverages Artificial Neural Networks (ANNs) to automatically analyze news comments.

#### Literature Review

###### Neural Networks in Sentiment Analysis
Various studies in Natural Language Processing (NLP) employ neural networks for text classification tasks. NLP and ANN techniques have been used for tasks such as sentiment analysis, document classification, and topic modeling.

###### Feature Representation
Previous research has employed different techniques to represent text data, including word embeddings (Word2Vec, GloVe), TF-IDF (Term Frequency–Inverse Document Frequency), or more complex representations (BERT, GPT models).

###### Evaluation Metrics
To measure the performance of my ANN model in news classification, I plotted several evaluation metrics commonly used in classification tasks, including the confusion matrix, training and validation loss, training and validation accuracy, precision, recall, F1 score, and ROC curves.

###### Challenges and Solutions in Sentiment Analysis
The structure of many of the datasets used led to very different outcomes in training the ANN model. By trial and error, I selected and created both the most suitable dataset and the model to achieve the most accurate results. Despite obtaining high validation scores multiple times, the analysis results were often very inaccurate. Even though the number of comments was low, I used the comments from news sites that provided me with the most accurate results.



# Çalışmanın Tanımı ve Amacı, Literatür Bilgisi

## Haber Sınıflandırma

#### Çalışmanın Tanımı:

Çalışma, haber makalelerini farklı kategorilere ayırmak için insan beyninden ilham alan bir tür makine öğrenme modeli olan Yapay Sinir Ağlarının kullanımını içerir. Belirli sınıflara veya konulara kategorize edilmiş haber makalelerini içeren bir veri kümesi kullanarak bir ANN modelinin eğitimini kapsar. Daha sonra, bu eğitilmiş model, haber makalelerinden oluşan başka bir veri kümesinin kategorilerini sınıflandırmak için kullanılır.

#### Çalışmanın Amacı

Yapay Sinir Ağlarını Kullanarak Haber Sınıflandırması: İlk amaç, haber makalelerini eğitim için kullanılan veri kümesine göre farklı kategorilere sınıflandırmak için yapay sinir ağlarının kullanılmasıdır. Bu, haber makalelerini otomatik olarak analiz etmek ve kategorize etmek için Yapay Sinir Ağları’ndan (ANN) yararlanılmıştır.

Haber Kategorilerinin Tahmini: Bir haber kategorisi veri kümesi kullanarak ANN modelini eğittikten sonra, başka bir haber veri kümesinin kategorilerini tahmin etmek için bu eğitilmiş model kullanıldı. Bu adım, eğitimli modeli performansını değerlendirmek ve haber makalelerini doğru bir şekilde sınıflandırma yeteneğini genelleştirmek için yeni, görünmeyen verilere uygulanmasını içerir.

#### Literatür Bilgisi

###### Haber Sınıflandırmasına Önceki Yaklaşımlar
Haber sınıflandırması için farklı yöntemler (ANN, NLP teknikleri) kullanan önceki çalışmaları veya literatürü gözden geçirildi. Bu yaklaşımların güçlü ve sınırlı yönleri açısından bakıldığı zaman kullandığımız ANN modeli performans ve eğitim sonuçları diğer yöntemlere göre daha düşük kalmıştır.

###### Özellik Temsili
Önceki araştırmalar, kelime gömmeleri (Word2Vec, GloVe), TF-IDF (Term Frequency-Inverse Document Frequency) veya daha karmaşık temsiller (BERT, GPT modelleri) gibi metin verilerini temsil etmek için farklı yaklaşımlar kullanılmış.

###### Haber Sınıflandırmasında Yapay Sinir Ağlarının Uygulanması
ANN'yi özellikle haber sınıflandırma görevleri için kullanmanın etkinliğini gösteren literatürle karşılaştırıldı. ANN modelinin benzer yaklaşımların güçlü ve sınırlı yönleri açısından bakıldığı zaman kullandığımız ANN modeli performans ve eğitim sonuçları diğer yöntemlere göre daha düşük kalmıştır.

###### Haber Sınıflandırmasındaki Zorluklar ve Çözümler
Kullanılan birçok veri setinin yapısı gereği ANN modelinin eğitiminde çok farklı sonuçlar vermiştir. Hem modelimi hem de en uygun veri setini deneme yanılma yöntemiyle seçip oluşturarak en doğru sonuçları almaya çalıştım. Birçok kez alınan yüksek doğrulama değerlerine rağmen sınıflandırma sonuçları tam aksine çok hatalıydı. Bu sebeple aralarında bana en doğru sonuçları veren modeli ve veri setini kullandım.

###### Değerlendirme Metrikleri
ANN modelimin duygu analizindeki performansını ölçmek için hata matrisi, eğitim ve doğrulama ve kaybı, eğitim ve doğrulama doğruluğu, hassasiyet, hatırlama, F1 skoru, ROC eğrileri dahil olmak üzere sınıflandırma modellerinin performansını ölçmek için kullanılan çeşitli değerlendirme metriklerinin grafiklerini çıkarttım.

## Duygu Analizi

#### Çalışmanın Tanımı

Çalışma, haber yorumlarının analizini farklı kategorilere ayırmak için insan beyninden ilham alan Yapay Sinir Ağlarının kullanımını içerir. Belirli sınıflara veya konulara kategorize (pozitif-negatif-nötr) edilmiş haber yorumlarını içeren bir veri kümesi kullanarak bir ANN modelinin eğitimini kapsar. Daha sonra, bu eğitilmiş model, haber yorumlarından oluşan başka bir veri kümesinin kategorilerini (yani duyguları: pozitif-negatif-nötr) tahmin etmek için kullanılır.

#### Çalışmanın Amacı

Yapay Sinir Ağlarını Kullanarak Duygu Analizi: Haber yorumlarını eğitim için kullanılan veri kümesine göre farklı kategorilere (duygulara) sınıflandırmak için yapay sinir ağlarının kullanılmasıdır. Bu, haber yorumlarını otomatik olarak analiz etmek için Yapay Sinir Ağları’ndan (ANN) yararlanılmıştır.

#### Literatür Bilgisi:

###### Duygu Analizinde Sinir Ağları
Doğal dil işlemede (NLP) çeşitli çalışmalar, metin sınıflandırma görevleri için sinir ağlarını kullanmaktadır. Duygu analizi, belge sınıflandırması ve konu modellemesi gibi görevler için NLP ve ANN teknikleri kullanılmıştır.

###### Özellik Temsili
Önceki araştırmalar, kelime gömmeleri (Word2Vec, GloVe), TF-IDF (Term Frequency-Inverse Document Frequency) veya daha karmaşık temsiller (BERT, GPT modelleri) gibi metin verilerini temsil etmek için farklı yaklaşımlar kullanılmış.

###### Değerlendirme Metrikleri
ANN modelimin haber sınıflandırmasındaki performansını ölçmek için hata matrisi, eğitim ve doğrulama ve kaybı, eğitim ve doğrulama doğruluğu, hassasiyet, hatırlama, F1 skoru, ROC eğrileri dahil olmak üzere sınıflandırma modellerinin performansını ölçmek için kullanılan çeşitli değerlendirme metriklerinin grafiklerini çıkarttım.

###### Duygu Analizindeki Zorluklar ve Çözümler
Kullanılan birçok veri setinin yapısı gereği ANN modelinin eğitiminde çok farklı sonuçlar vermiştir. Hem modelimi hem de en uygun veri setini deneme yanılma yöntemiyle seçip oluşturarak en doğru sonuçları almaya çalıştım. Birçok kez alınan yüksek doğrulama değerlerine rağmen analiz sonuçları tam aksine çok hatalıydı. Yorum sayısının az olmasına rağmen yorumların çekildiği haber sitelerinden bana en doğru sonucu veren haber yorumlarını kullandım.
