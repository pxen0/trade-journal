# Trading Journal Pro

A browser-based trading journal for tracking monthly trades, profit and loss (PnL), and risk/reward (R:R). The application supports English, Turkish, Spanish, and Japanese.

## Features

- Yearly overview for 12 months
- Monthly view with four trading weeks and Monday-Friday day cards
- Add or edit a trade for each day
- Track trading pair, PnL, R:R, and notes
- Data is saved in the browser's `localStorage`
- Language selection: English, Turkish, Spanish, and Japanese

## Run Locally

### Option 1: Open the HTML file

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Select a month and click a day card to add a trade.

No installation or internet connection is required.

### Option 2: Use a local server

Using a local server is useful during development.

With Python:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

With Visual Studio Code, install the **Live Server** extension, right-click `index.html`, and choose **Open with Live Server**.

## Data Storage

Trades are stored locally in the browser under `tradingJournalData_v2`. Clearing browser site data or local storage will remove saved trades. The data is not sent to a server.

## Project Structure

```text
trade-cleander/
├── index.html
└── README.md
```

---

# Trading Journal Pro (Türkçe)

Aylık işlemleri, kar/zarar (PnL) ve risk/getiri (R:R) değerlerini takip etmek için hazırlanmış tarayıcı tabanlı işlem günlüğü. Uygulama İngilizce, Türkçe, İspanyolca ve Japonca dillerini destekler.

## Özellikler

- 12 ay için yıllık görünüm
- Dört işlem haftası ve Pazartesi-Cuma gün kartlarından oluşan aylık görünüm
- Her gün için işlem ekleme veya düzenleme
- Parite, kar/zarar, R:R ve not kaydetme
- Verilerin tarayıcıdaki `localStorage` alanına kaydedilmesi
- Dil seçimi: İngilizce, Türkçe, İspanyolca ve Japonca

## Bilgisayarda Çalıştırma

### Seçenek 1: HTML dosyasını açma

1. Bu repoyu indirin veya klonlayın.
2. `index.html` dosyasını güncel bir web tarayıcısında açın.
3. Bir ay seçin ve işlem eklemek için bir gün kartına tıklayın.

Kurulum veya internet bağlantısı gerekmez.

### Seçenek 2: Yerel sunucu kullanma

Yerel sunucu, geliştirme sırasında kullanışlıdır.

Python ile:

```bash
python3 -m http.server 8000
```

Ardından tarayıcıda <http://localhost:8000> adresini açın.

Visual Studio Code kullanıyorsanız **Live Server** eklentisini kurun, `index.html` dosyasına sağ tıklayın ve **Open with Live Server** seçeneğini seçin.

## Verilerin Saklanması

İşlemler tarayıcıda `tradingJournalData_v2` adıyla yerel olarak saklanır. Tarayıcı site verilerini veya local storage alanını temizlemek kayıtlı işlemleri siler. Veriler herhangi bir sunucuya gönderilmez.

## Proje Yapısı

```text
trade-cleander/
├── index.html
└── README.md
```
