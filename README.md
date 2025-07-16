# 🧠 Prompt Engineering Uygulamaları

Bu projede, **OpenAI GPT-3.5-Turbo** modeli kullanılarak çeşitli **prompt oluşturma teknikleri** test edilmiştir. Amaç, doğal dil işleme tabanlı modellerin çıktı kalitesini artırmak için farklı istem türlerinin etkilerini gözlemlemektir.

## 📌 Kullanılan Yöntemler

Projede aşağıdaki prompt engineering stratejileri uygulanmıştır:

- **Zero-shot Prompting**  
  Modele herhangi bir örnek verilmeden, doğrudan sorular sorulur.

- **Few-shot Prompting**  
  Modele, sorudan önce birkaç örnek sunularak bağlam kazandırılır.

- **Chain-of-Thought Prompting**  
  Modelin düşünme sürecini adım adım açıklaması teşvik edilir.

- **Role Prompting**  
  Modele belirli bir rol (örneğin öğretmen veya gazeteci) atanarak yanıt şekli yönlendirilir.

- **Style & Length Constraint Prompting**  
  Yanıtın stiline ve uzunluğuna (örneğin karakter sayısı) sınır getirilir.

- **Format-Constrained (JSON) Prompting**  
  Modelden belirli bir çıktı formatında (örneğin JSON) yanıt istenir.

- **Self-Reflection Prompting**  
  Modelden önce bir argüman oluşturması, ardından kendi argümanının güçlü ve zayıf yönlerini değerlendirmesi istenir.


## 🛠️ Kullanılan Teknolojiler

- Python  
- OpenAI Python SDK (`openai`)  
- `python-dotenv` (API anahtarı yönetimi)  
- Jupyter Notebook  

---

## 🔐 API Anahtarı Kullanımı

Bu projede, OpenAI API anahtarı `.env` dosyası aracılığıyla yüklenmektedir. Güvenlik nedeniyle bu dosya `.gitignore` listesine eklenmelidir.

`.env` dosyasına aşağıdaki satırı eklemeniz yeterlidir:

```
OPENAI_API_KEY=kendi_openai_anahtarınızı_yazın
```

> 📝 Anahtarınızı [OpenAI platformu](https://platform.openai.com/account/api-keys) üzerinden edinebilirsiniz.


