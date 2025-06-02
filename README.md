# EduSona – Yapay Zeka Destekli Eğitim Asistanı

https://github.com/user-attachments/assets/4e1a8bbe-3c6a-489c-a138-bd41772dd18f

EduSona, öğrenme deneyimini kişiselleştiren, yapay zeka destekli bir eğitim asistanıdır. Kullanıcının tercihlerini ve öğrenme tarzını anlayarak, içerikleri bireysel ihtiyaçlara göre uyarlayan bu uygulama, öğrenmeyi daha etkili ve verimli hale getirir.

## Özellikler

* **Kişiselleştirilmiş Öğrenme:** Kullanıcının tercih ettiği anlatım tarzı, görsel kullanımı, öğrenme süresi ve örnek ihtiyacına göre içerik sunar.
* **Minimalist Arayüz:** Minimal tasarımlardan ilham alan sade ve odaklanmayı kolaylaştıran bir kullanıcı arayüzü.
* **Yapay Zeka Entegrasyonu:** Google Gemini veya benzeri büyük dil modelleriyle entegre çalışarak, kullanıcıya özel içerikler üretir.
* **Hızlı ve Etkili:** React + Vite ile geliştirilmiş, hızlı ve duyarlı bir uygulama deneyimi sunar.

## Uygulama Akışı

1. **Hoş Geldiniz Ekranı:** Kullanıcıyı karşılayan sade bir giriş ekranı.
2. **Kişisel Tercih Soruları:** Kullanıcının öğrenme tercihlerini belirlemek için 4-5 soruluk bir anket.
3. **Konu Seçimi:** Kullanıcının öğrenmek istediği konunun serbest metin olarak alınması.
4. **İçerik Oluşturma:** Toplanan bilgilerle kişiselleştirilmiş bir prompt oluşturularak yapay zeka API'sine gönderilir.
5. **Sonuç Sunumu:** Yapay zekadan gelen yanıt, kullanıcıya sade ve okunabilir bir formatta sunulur.

## Teknolojiler

* **Frontend:** React + Vite
* **Stil:** Tailwind CSS
* **Yapay Zeka:** Google Gemini API (veya alternatif büyük dil modelleri)

## Kurulum ve Çalıştırma

1. Bu depoyu klonlayın:

   ```bash
   git clone https://github.com/omerfbaltaci/edusona.git
   cd edusona
   ```



2. Gerekli bağımlılıkları yükleyin:

   ```bash
   npm install
   ```



3. Geliştirme sunucusunu başlatın:

   ```bash
   npm run dev
   ```



4. Uygulamayı tarayıcınızda görüntüleyin:

   ```
   http://localhost:5173
   ```



## Ortam Değişkenleri

Yapay zeka API'sine erişim için bir API anahtarına ihtiyacınız vardır. Proje kök dizininde `.env` dosyası oluşturarak aşağıdaki değişkeni ekleyin:

```
VITE_GEMINI_API_KEY=your_api_key_here
```
