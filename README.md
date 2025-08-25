# Fidan_education
New kind of education system 
Fidan Eğitim

Açık Kaynak, Proje Tabanlı, Ahlak Merkezli ve Yapay Zekâ Destekli Eğitim Sistemi

“Öğrenci bir ‘kullanıcı’ değil; Allah’ın emaneti bir fidan. Bizim görevimiz toprağı hazırlamak, suyu ve ışığı doğru ölçüde vermek.”

⸻

✨ Niyet ve Özet

Fidan Eğitim, 5–16 yaş aralığındaki çocukları 10 yılda; ahlak, ilim ve gerçek hayata dönük proje deneyimi ile yetiştirmeyi hedefleyen tamamen açık kaynak bir eğitim girişimidir.
	•	Misyon: Ahlak (Kur’ân ve Sünnet ışığı), fen ve teknoloji ile hikmeti birleştiren, şefkatli ve adaletli bir eğitim yolu kurmak.
	•	Yaklaşım: Zaman/yer zorunluluğu yerine proje tabanlı ilerleme, bireyselleştirilmiş YZ-destekli öğrenme, ustalık temelli değerlendirme.
	•	Erişim: Köyde küçük bir çekirdek okul + dünya çapında dijital platform (açık içerik, açık yazılım).

⸻

🌿 İlkeler (Değerler)
	•	Tevhid ve Ahlak: Niyet Allah rızası, yöntem adalet ve merhamet, hedef fayda ve hikmet.
	•	Fıtratla Uyum: Doğa, toprak, üretim ve tefekkür ile büyüyen müfredat.
	•	Açıklık: Kod açık, içerik açık; toplulukla birlikte gelişim.
	•	Yerel-Öncelikli: Gizlilik, güvenlik ve mahremiyet; local-first tasarım.
	•	Ustalık (Mastery): Sınıf geçme değil, yeterlik kazanma; her çocuk kendi hızında ilerler.
	•	İhsan: Estetik, nezaket, fayda ve kalitede seviye.

⸻

🏗️ Depo Yapısı (Öneri)

/README.md                 → bu dosya
/LICENSE                   → Yazılım + İçerik lisansları
/CODE_OF_CONDUCT.md        → Davranış kuralları
/CONTRIBUTING.md           → Katkı rehberi, RFC süreci
/GOVERNANCE.md             → Şûra esaslı yönetişim modeli

/docs/                     → Belgeler, kılavuzlar, mimari notlar
  /site/                   → (isteğe bağlı) GitHub Pages / MkDocs

/platform/                 → Yazılım (açık kaynak)
  /app/                    → Flutter (web+mobil) istemci
  /api/                    → FastAPI (veya eşdeğer) servisler
  /ai/                     → YZ öğretmen, yönergeler, etik kartlar
  /assessment/             → Ustalık grafı, rozetler, rubrikler

/curriculum/               → Müfredat ağacı (açık içerik)
  /00-kokler/              → 5–7 yaş: Ahlak & alışkanlık & doğa
  /01-filiz/               → 7–9 yaş: Temel fen, dil, blok kodlama
  /02-dal/                 → 9–11 yaş: Matematik, Python, elektronik
  /03-govde/               → 11–13 yaş: Fen (Fizik/Kimya/Biyoloji), web
  /04-meyve/               → 13–16 yaş: Uzmanlık yolları & staj

/projects/                 → Proje setleri (adım adım kitler)
  /solar-oven/             → Güneş fırını (fizik+tasarım)
  /water-filter/           → Su arıtımı (kimya+sağlık)
  /oyster-mushroom/        → İstiridye mantarı yetiştirme (ekoloji)
  /drip-irrigation/        → Damla sulama (tarım+enerji)

/ops/                      → Dağıtım, barındırma, yedekleme (IaC)
/community/                → Topluluk, moderasyon, etkinlikler
/scripts/                  → Yardımcı betikler


⸻

🧭 Yol Haritası (2025 → 2027)

Faz 0 — Tohum (2–4 hafta)
	•	Depo kurulumu, lisanslar, temel belgeler
	•	docs/site ile basit bir web (MkDocs/Docusaurus)
	•	Mimari taslak (app+api+ai), veri ilkeleri (local-first)

Faz 1 — Filiz (6–10 hafta)
	•	MVP Platform:
	•	Flutter istemci: kayıt, profil, proje listesi, günlük akış
	•	FastAPI çekirdek: kullanıcı, proje, portfolyo uçları
	•	YZ-öğretmen iskele: etik yönerge + yönlendirme kartları
	•	3 Pilot Proje: solar-oven, water-filter, oyster-mushroom
	•	Müfredat: 00-kokler taslağı (ahlak+alışkanlık modülleri)

Faz 2 — Dal (8–12 hafta)
	•	Ustalık grafı, rozetler, rubriklerle değerlendirme
	•	Veli/mentor paneli ve topluluk moderasyonu
	•	İçerik paketleri: 01-filiz, 02-dal taslakları

Faz 3 — Gövde (12–16 hafta)
	•	100 pilot öğrenci & 10 mentor ile açık beta
	•	Öğrenci portfolyosu (paylaşılabilir, izinli)
	•	03-govde müfredat taslakları + 5 yeni proje kiti

Faz 4 — Meyve (sürekli)
	•	04-meyve uzmanlık yolları (Yazılım, Tarım, Fen, Sanat)
	•	Staj/çıraklık eşleşmeleri, toplumsal fayda projeleri
	•	Uluslararası yerelleştirme ve kapsayıcılık

⸻

📚 Müfredat Ağacı (Kısa Taslak)

00-Kökler (5–7): Ahlak & alışkanlıklar, dil ve beyan, sayılar ve şekiller, doğa keşfi, hareket ve sanat.

01-Filiz (7–9): Fen temel deneyler (su–ışık–toprak), blok tabanlı kodlama (Scratch/Blockly), Kur’an’dan kısa sûreler ve anlam, topluluk/proje disiplini.

02-Dal (9–11): Matematik (oran–orantı, kesir–ölçme), Python temelleri, basit elektronik (Arduino/mikrodenetleyici), tarım & mantar yetiştirme, güneş fırını.

03-Gövde (11–13): Fen (Fizik/Kimya/Biyoloji), web geliştirme, IPFS ile içerik paylaşımı (seçmeli), ilk yardım ve afet bilinci, toplumsal proje.

04-Meyve (13–16): Uzmanlık yolları (Fen, Yazılım, Tarım, Sanat), staj/çıraklık, bitirme projesi (toplumsal fayda), portfolyo sunumu.

Ahlak modülü her kademede çekirdek: doğruluk, emanet, adalet, sabır, şükür, merhamet, iffetin korunması, kul hakkı.

⸻

🧪 Örnek Projeler (Kısa Tanım)
	•	Solar Oven (Güneş Fırını): Isı, yansıtma, izolasyon; güneş enerjisiyle pişirme. Çıktı: Çalışan prototip + rapor + video.
	•	Water Filter (Su Arıtımı): Kum/çakıl/aktif karbon; hijyen, ölçüm, basit testler. Çıktı: Arıtılmış su örneği + güvenlik notları.
	•	Oyster Mushroom (İstiridye Mantarı): Sterilizasyon, miselyum, nem–ısı kontrolü. Çıktı: Küçük hasat + süreç günlüğü.
	•	Drip Irrigation (Damla Sulama): Basit depo + damla hatları, güneş paneliyle pompa. Çıktı: Otomasyonlu sulama döngüsü.

Her projede: amaç, malzeme listesi, güvenlik, adımlar, ölçme ve yansıtma bölümleri bulunur.

⸻

🧠 YZ Öğretmen (AI Tutor) Tasarımı
	•	Rol: Yönlendirici koç; ödev çözen değil, soru sorduran ve düşündüren.
	•	Etik Kartlar: Yaş uygunluk, dinî hassasiyet, güvenlik, çevrimiçi riskler.
	•	Yerel-Öncelik: Kimliksiz, izinsiz veri toplamayan; mümkün olduğunda cihaz üzerinde çalışan.
	•	Kaynaklandırma: Açık içerik referansları, not edilmiş alıntılar, telif uyumu.
	•	Aile/mentor döngüsü: Veli paneline özet; çocuğun mahremiyetini gözeten ayarlar.

⸻

🎯 Değerlendirme ve Portfolyo
	•	Ustalık Rozetleri: Her yeterliğe karşılık rozet (örn. “Isı Transferi Temelleri”).
	•	Rubrikler: Açık ölçütler; proje öncesi/sonrası öz-değerlendirme.
	•	Portfolyo: Fotoğraf, video, rapor ve kaynak kod; paylaşım izinli.
	•	Ahlak Günlüğü: Kısa günlük muhasebe; şükür, sabır, yardım kaydı.

⸻

🔐 Gizlilik, Güvenlik ve Mahremiyet
	•	Local-first: Veriler öncelikle kullanıcı cihazında.
	•	Açık kaynak: Kod, içerik ve model yönerge dosyaları incelenebilir.
	•	Çocuk Koruma: İçerik filtreleri, raporlama, yetişkin denetimi, kapalı DM yok.
	•	Telemetri: Varsayılan kapalı; açılırsa açıkça izinli, anonim ve asgari.

⸻

⚖️ Lisanslama (Çift Lisans Önerisi)
	•	Yazılım: AGPL-3.0 (ağ üzerinden sunulan türevler dâhil paylaşım zorunluluğu)
	•	İçerik (müfredat/projeler/dokümantasyon): CC BY-SA 4.0

İhtiyaca göre MPL-2.0 veya Apache-2.0 + Commons lisansları değerlendirilebilir.

⸻

🧑‍⚖️ Yönetişim (Şûra Modeli)
	•	Şûra Kurulu: 5–9 kişilik, farklı uzmanlıklar (ahlak, pedagojik formasyon, fen/teknoloji, güvenlik, topluluk).
	•	RFC Süreci: Büyük değişiklikler için docs/rfc-XXXX.md önerisi → topluluk değerlendirmesi → şûra onayı.
	•	Sürümleme: İçerik ve yazılım için ayrı semantik sürümleme.
	•	Topluluk: Açık forumlar, aylık çevrimiçi istişare.

⸻

🤝 Katkı Rehberi (Özet)
	•	İlk katkı: “good first issue” etiketli görevler.
	•	Stil: Açık ve saygılı dil, kaynaklı bilgi, tekrarlanabilir sonuç.
	•	PR’ler: Küçük, odaklı; test ve belge eşlik etsin.
	•	Kod Etiği: Çocuk güvenliğini ve mahremiyetini öncele.

Ayrıntılar için CONTRIBUTING.md dosyasına bakınız.

⸻

🧩 İlk İşler (Issues – Başlangıç Listesi)
	•	LICENSE dosyası ekle (AGPL-3.0 + CC BY-SA 4.0)
	•	CODE_OF_CONDUCT.md (Contributor Covenant TR)
	•	CONTRIBUTING.md ve GOVERNANCE.md
	•	docs/site iskeleti (MkDocs/Docusaurus)
	•	platform/app Flutter iskeleti (kayıt + proje listesi)
	•	platform/api FastAPI iskeleti (kullanıcı + proje uçları)
	•	platform/ai/tutor.md etik yönerge taslağı
	•	curriculum/00-kokler modül haritası
	•	projects/solar-oven içerik taslağı
	•	projects/oyster-mushroom içerik taslağı
	•	assessment/rubrics klasörü ve örnek rubrik

⸻

📝 Şablonlar (Kısaltılmış)

.github/ISSUE_TEMPLATE/feature_request.md

---
name: Özellik Önerisi
about: Yeni bir özellik önerin
labels: enhancement
---

**Sorun / ihtiyaç**
Açıklama:

**Önerilen çözüm**
Kısa madde madde:

**Alternatifler**

**Ek bağlam**
Görseller, linkler, örnekler:

.github/PULL_REQUEST_TEMPLATE.md

## Özet
Kısa açıklama.

## Değişiklikler
- 
- 

## Test Planı
- [ ] Manuel test
- [ ] Birim test(ler)

## İlgili Issue
Closes #ISSUE_NO


⸻

❓SSS (Kısa)

Neden açık kaynak? Çünkü güven, denetlenebilirlik ve yaygınlaşma.

Teknoloji şart mı? Hayır; içerikler yazdırılıp tamamen offline da uygulanabilir.

Aile/mentor rolü ne? Yönlendirme, güvenlik ve değerler aktarımı.

Zorunlu ezber var mı? Ezber değil, anlama ve yaşama esastır.

⸻

🤲 Teşekkür ve Davet

Bu proje, “öğrenci = fidan” ilkesine inanan herkese açık.
Katkı verin, eleştirin, dua edin, paylaşın.

“Eğer şükrederseniz, elbette size (nimetimi) artırırım.” – İbrahim 7
