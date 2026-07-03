# StellarPass - Web3 Biletleme Sistemi 🎟️ (VibeCoding 3.0)

StellarPass, aracı kurumları ve devasa komisyon kesintilerini ortadan kaldıran, organizatörler ile katılımcıları doğrudan buluşturan merkeziyetsiz bir **Web3 etkinlik biletleme** sistemidir.

Bu proje, Stellar ağının (Testnet) hızını ve 0.00001 XLM gibi neredeyse sıfır olan işlem ücretlerini kullanarak, günlük hayattaki biletleme krizine (Mikro-ticketing) somut bir çözüm üretmek amacıyla geliştirilmiştir.

## 💡 Fikir ve Problem Tanımı

### Çözülen Problem
Günümüzde etkinlik (konser, tiyatro, konferans) biletleri satan merkezi aracı kurumlar, bilet fiyatının üzerine **%10 ile %20 arasında** değişen hizmet bedelleri ve komisyonlar eklemektedir. Ayrıca organizatörler, bilet satış gelirlerini haftalar sonra alabilmektedir. 

### Yaratıcı Çözüm: StellarPass
StellarPass ile kullanıcılar, organizatörün "Public Key" (Açık Anahtar) adresine bilet ücretini (XLM olarak) saniyeler içinde ve komisyonsuz gönderirler.
- **Anında İşlem:** Ödeme Stellar ağında 3-5 saniyede onaylanır.
- **Şeffaflık:** Cüzdanınızdaki işlem geçmişi, bilet koçanınız (kanıtınız) olarak görev yapar. Kapıdaki görevliye, başarıyla onaylanan "Tx Hash"inizi göstererek içeri girebilirsiniz.
- **Aracısız Ekonomi:** Organizatör, parasını aracı kurum beklemeksizin saniyeler içinde kendi cüzdanında görür.

## ⚙️ Teknik Uygulama ve Özellikler

Proje, kusursuz çalışan bir cüzdan entegrasyonu ve etkinlik biletleme deneyimi sunar:
- **VibeCoding AI Summit 2026 Açılış Sayfası:** Etkileyici "Abstract AI" arka planlı ve geri sayım sayaçlı Premium Hero Section.
- **Freighter Cüzdan Entegrasyonu:** Kullanıcılar tek tıkla cüzdanlarını bağlar, testnet bakiyelerini anında görüntüler.
- **Dijital V.I.P Bilet ve Sosyal Flex:** Bilet işlemi onaylandığında QR kodlu dinamik bir Dijital Bilet oluşur. Altındaki tek tıkla X'te (Twitter) paylaşım butonu, projenin viral organik büyüme potansiyelini (Social Proof) sergiler.
- **Tamamen Responsive:** Modern, Glassmorphism tarzında UI/UX tasarımı. Gece/Gündüz modu, canlı parçacık animasyonları ve QR Kod tarayıcı özellikleri mevcuttur.

## 🤖 Kullanılan Teknolojiler ve AI Partnerliği

- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6+). Herhangi bir ağır framework kullanılmadan, en yüksek performans ve modüler yapı için tasarlandı.
- **Web3 / Blockchain:** Stellar JavaScript SDK, Freighter Wallet API, Horizon Testnet API.
- **AI Kullanımı (VibeCoding):** Projenin sıfırdan mimari dizaynı, hata çözümü (debugging), UI animasyonları (parçacıklar, konfetiler) ve UX stratejisi tamamen **Google Antigravity (Agentic AI - Gemini)** tarafından "prompt mühendisliği" ile yazılmıştır. AI, sadece bir yardımcı olarak değil; projenin "Ürün Tasarımcısı" ve "Baş Geliştiricisi" (Lead Developer) rolünü üstlenerek değer katmıştır.

## 🚀 Kurulum (Local'de Çalıştırma)

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Repoyu bilgisayarınıza indirin (Clone):
   ```bash
   git clone https://github.com/Nihatcihan/VibeCoding3.0.git
   cd VibeCoding3.0
   ```
2. Basit bir yerel sunucu (Live Server, Python HTTP Server veya Dotnet Serve) başlatın. Örneğin:
   ```bash
   npx serve .
   ```
   *veya*
   ```bash
   dotnet serve -o -p 8080
   ```
3. Tarayıcınızda `http://localhost:8080` adresine giderek StellarPass'i deneyimleyin!
4. **Not:** Freighter tarayıcı eklentinizin kurulu olduğundan ve "Testnet" ağının seçili olduğundan emin olun.

## 🏆 Teslim Edilmesi Gerekenler

- **GitHub Repo Linki:** [github.com/Nihatcihan/VibeCoding3.0](https://github.com/Nihatcihan/VibeCoding3.0)
- Proje kısa açıklaması, AI kullanım detayları ve Problem Tanımı yukarıda detaylıca listelenmiştir.

---
*Geleceği inşa etmeye devam ediyoruz! 🚀*

<br><br>

---
# 🇬🇧 English Version

# StellarPass - Web3 Ticketing System 🎟️ (VibeCoding 3.0)

StellarPass is a decentralized **Web3 event ticketing** system that eliminates intermediaries and massive commission fees by directly connecting organizers with attendees.

This project was developed to provide a concrete solution to the everyday micro-ticketing crisis by leveraging the speed of the Stellar network (Testnet) and its near-zero transaction fees (e.g., 0.00001 XLM).

## 💡 Idea and Problem Definition

### The Problem
Today, centralized ticketing platforms add service fees and commissions ranging between **10% and 20%** on top of the ticket price. Moreover, event organizers often have to wait weeks to receive their ticket sales revenue.

### The Creative Solution: StellarPass
With StellarPass, users send the ticket fee (in XLM) directly to the organizer's Public Key in seconds, with zero platform commissions.
- **Instant Transactions:** Payments are confirmed on the Stellar network in 3-5 seconds.
- **Transparency:** Your wallet's transaction history serves as your ticket stub (proof of purchase). You can enter the event by showing the successfully confirmed "Tx Hash" to the staff at the door.
- **Intermediary-Free Economy:** The organizer sees the funds in their own wallet within seconds, without waiting for a third-party platform.

## ⚙️ Technical Implementation and Features

The project offers a flawlessly working wallet integration and event ticketing experience:
- **VibeCoding AI Summit 2026 Landing Page:** A premium Hero Section with a stunning "Abstract AI" background and a live countdown timer.
- **Freighter Wallet Integration:** Users can connect their wallets with a single click and instantly view their testnet balances.
- **Digital V.I.P Ticket & Social Flex:** A dynamic Digital Ticket with a QR code is generated upon successful payment. The "Share on X (Twitter)" button beneath it demonstrates the project's viral organic growth potential (Social Proof).
- **Fully Responsive:** Modern, Glassmorphism-style UI/UX design. Features include Dark/Light mode toggles, live particle animations, and a built-in QR Code scanner.

## 🤖 Technologies Used and AI Partnership

- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6+). Designed for maximum performance and modularity without the overhead of heavy frameworks.
- **Web3 / Blockchain:** Stellar JavaScript SDK, Freighter Wallet API, Horizon Testnet API.
- **AI Utilization (VibeCoding):** The project's architectural design from scratch, debugging, UI animations (particles, confetti), and UX strategy were entirely written by **Google Antigravity (Agentic AI - Gemini)** via prompt engineering. The AI acted not just as an assistant, but as the "Product Designer" and "Lead Developer" of the project.

## 🚀 Installation (Running Locally)

To run the project on your own machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Nihatcihan/VibeCoding3.0.git
   cd VibeCoding3.0
   ```
2. Start a simple local server (e.g., Live Server, Python HTTP Server, or Dotnet Serve):
   ```bash
   npx serve .
   ```
   *or*
   ```bash
   dotnet serve -o -p 8080
   ```
3. Open `http://localhost:8080` in your browser to experience StellarPass!
4. **Note:** Make sure you have the Freighter browser extension installed and the "Testnet" network selected.

## 🏆 Deliverables

- **GitHub Repository Link:** [github.com/Nihatcihan/VibeCoding3.0](https://github.com/Nihatcihan/VibeCoding3.0)
- Project summary, AI utilization details, and Problem Definition are detailed above.

---
*Continuing to build the future! 🚀*
