# AI'Han Academy — RAG & Fine-Tuning Learning Lab

**RAG, Fine-Tuning, Embedding, Vector Search, LoRA, PEFT ve modern üretken yapay zekâ mimarilerini etkileşimli olarak öğrenmek için hazırlanmış tarayıcı tabanlı eğitim laboratuvarı.**

**A browser-based educational laboratory for interactively learning RAG, Fine-Tuning, Embeddings, Vector Search, LoRA, PEFT, and modern generative AI architectures.**

---

## Türkçe

### Proje Hakkında

**AI'Han Academy RAG & Fine-Tuning Learning Lab**, Retrieval-Augmented Generation (RAG) ve Fine-Tuning kavramlarını yalnızca teorik açıklamalarla değil, etkileşimli simülasyonlar ve karşılaştırmalı senaryolarla öğretmek amacıyla geliştirilmiştir.

Laboratuvar; kullanıcıların belge seçme, metin parçalama, indeksleme, bilgi getirme, yeniden sıralama, bağlam oluşturma ve yanıt üretme süreçlerini adım adım deneyimlemesini sağlar.

Fine-Tuning bölümünde ise eğitim verisi hazırlama, JSONL veri yapısı, epoch, learning rate, training loss, validation loss, LoRA ve PEFT gibi temel kavramlar görselleştirilir.

> Bu proje gerçek bir büyük dil modelini tarayıcı içinde eğitmez. Eğitim amacıyla RAG ve Fine-Tuning süreçlerinin çalışma mantığını anlaşılır ve etkileşimli biçimde simüle eder.

---

## Temel Özellikler

### RAG Laboratuvarı

- Hazır bilgi havuzlarıyla çalışma
- Kullanıcının kendi belgesini ekleyebilmesi
- `.txt`, `.md`, `.csv` ve `.json` dosyalarını kullanabilme
- Belgeleri küçük parçalara ayırma
- Chunk boyutu ve chunk overlap ayarları
- Anahtar kelime tabanlı arama
- Anlamsal benzerlik simülasyonu
- Hibrit arama
- Vektör benzerliği ve cosine similarity
- Top-K retrieval
- Reranking
- Kaynak chunk’larını görüntüleme
- Base Model, Prompt-Only ve RAG yanıtlarını karşılaştırma
- Groundedness ve faithfulness kavramlarını inceleme
- Retrieval precision ve retrieval recall değerlendirmeleri
- Kaynak temelli yanıt üretme
- Halüsinasyon riskini gözlemleme

### Fine-Tuning Laboratuvarı

- Fine-Tuning eğitim örnekleri oluşturma
- Instruction, input ve output yapısını inceleme
- JSONL veri seti hazırlama
- Eğitim verisini doğrulama
- JSONL veri setini dışa aktarma
- Epoch ayarı
- Learning rate ayarı
- Train-validation ayrımı
- Training loss ve validation loss grafikleri
- Overfitting davranışını gözlemleme
- LoRA rank ayarı
- PEFT yaklaşımını öğrenme
- Base model ve uyarlanmış model davranışlarını karşılaştırma
- Üslup uyarlama senaryoları
- Çıktı biçimi öğretme
- Sınıflandırma görevleri
- Kurumsal yanıt politikası oluşturma

### Modern Yapay Zekâ Kavramları

Projede aşağıdaki kavramlar açıklanmaktadır:

- Retrieval-Augmented Generation
- Fine-Tuning
- Supervised Fine-Tuning
- Parameter-Efficient Fine-Tuning
- LoRA
- Embedding
- Vector Database
- Semantic Search
- Keyword Search
- Hybrid Search
- Reranking
- Chunking
- Chunk Overlap
- Context Window
- Context Engineering
- Prompt Engineering
- Grounding
- Faithfulness
- Hallucination
- Guardrails
- Evaluation
- Observability
- Agent ve araç kullanımı
- İnsan denetimi
- Hibrit RAG ve Fine-Tuning mimarileri

---

## RAG Nedir?

**RAG — Retrieval-Augmented Generation**, bir dil modelinin cevap üretmeden önce dış kaynaklardan ilgili bilgileri bulmasını sağlayan bir mimaridir.

Temel süreç şöyledir:

```text
Kullanıcı Sorusu
       ↓
Sorgu Analizi
       ↓
Embedding Oluşturma
       ↓
Vektör veya Hibrit Arama
       ↓
İlgili Belgeleri Getirme
       ↓
Reranking
       ↓
Bağlam Oluşturma
       ↓
Dil Modeli
       ↓
Kaynak Destekli Yanıt
