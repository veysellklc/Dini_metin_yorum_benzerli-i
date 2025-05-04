# Dini_metin_yorum_benzerligi
Word2Vec modeli ile dini metinlerin karşılaştırılması
Bu proje Kuran ve İncil metinlerinden lemmatize/stemlenmiş ayetlerin Word2Vec modelleri ile eğitilerek anlamsal benzerliklerinin karşılaştırılmasını amaçlamaktadır.
Aşağıdaki komutları kullanarak gerekli kütüphaneleri yükleyebilirsiniz:
pip install -r requirements.txt


Veri Seti
Kuran ve İncil metinleri kullanıldı.
Metinler lemmatize ve stemleme ön işlemlerinden geçirildi.
tf-idf vektörleme işlemleri yapıldı

Model Nasıl Oluşturulur
Verileri tokenle (lemma veya stem)
Word2Vec modeli için parametreler belirlenir:
vector_size
window
min_count
model_type (cbow/skipgram)


Kullanım Amacı
Bu projem, dini metinler arasında
Anlamsal yakınlık
Tema eşleşmesi
Kavramsal örtüşme
gibi analizleri kolaylaştırmak için kullanılabilir.

