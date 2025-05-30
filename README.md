# Dizi.Film.senaryo.analizi
dizi film senaryo analizi yapay zeka ödevi son kısım
Proje Hakkında:
Bu proje, film senaryoları arasındaki benzerlikleri tespit etmeye yönelik bir metin madenciliği uygulamasıdır. Senaryo metinleri lemmatizasyon ve stemming gibi ön işleme adımlarından geçirilmiş; ardından Word2Vec ve TF-IDF modelleriyle temsil edilerek benzerlik analizleri gerçekleştirilmiştir.

# Kullanılan Teknolojiler ve Kütüphaneler
Python 3.x
pandas
numpy
gensim
scikit-learn (sklearn)

# Projeyi Çalıştırmak için

Gerekli kütüphaneleri yükleyin:
bash
pip install pandas numpy gensim scikit-learn

Veri dosyalarını hazırlayın:
Aşağıdaki CSV dosyaları D:/YapayZekaÖdevi/ klasöründe olmalıdır:
imsdb_senaryolar_lemmatized.csv
imsdb_senaryolar_stemmed.csv
imsdb_senaryolar_lemmatized_tfidf2.csv
imsdb_senaryolar_stemmed_tfidf2.csv

Model klasörünü oluşturun:
Word2Vec modelleri D:/YapayZekaÖdevi/models/ dizinine kaydedilecektir. Kod çalıştırılmadan önce bu klasör oluşturulmalıdır.
Notebook veya .py dosyasını çalıştırın:
Eğitim için: Word2Vec modellerini eğit kısmını çalıştırın.
Benzerlik analizleri için: tfidf_benzerlik.py veya w2v_benzerlik.py dosyalarını çalıştırın.
