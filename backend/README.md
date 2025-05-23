# Hikaye Uygulaması - Backend

## Kurulum

1. **Sanal Ortam:**

   ```bash
   python -m venv venv
   source venv/bin/activate

   # Windows için:
   # venv\Scripts\activate
   ```

2. **Bağımlılıklar:**

   ```bash
   pip install -r requirements.txt
   ```

3. **.env dosyası**

   `.env.example` dosyasını kopyalayarak `.env` adında yeni bir dosya oluşturun ve gerekli ortam değişkenlerini ayarlayın.

   ```bash
   cp .env.example .env
   # .env dosyasını düzenleyin
   ```

## Çalıştırma

```bash
uvicorn main:app --reload
```

API varsayılan olarak `http://localhost:8000` adresinde çalışacaktır.
