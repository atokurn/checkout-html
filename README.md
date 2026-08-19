# antigravity/test-html

Koleksi prototipe HTML & UI standalone yang dikelompokkan ke dalam subfolder berbasis kategori dan disajikan sebagai aset statis.

## Struktur Direktori

```text
main/
├── index.html                  # Launcher Hub (dengan pencarian dinamis & filter kategori)
├── README.md                   # Dokumentasi proyek & daftar halaman
├── PROJECT_AUDIT.md            # Hasil audit teknis
├── wrangler.jsonc              # Konfigurasi static assets Cloudflare
├── placeholder.svg             # Asset SVG placeholder
├── img/                        # Folder gambar terpusat
├── dashboards/                 # Prototipe dashboard & seller center
│   ├── tiktok-shop.html        # Tokopedia & TikTok Shop Seller Center (Kelola Pesanan)
│   ├── dashboard-content.html  # Anibeam Admin Dark Mode Content Catalog Dashboard
│   ├── dashboard-sales.html    # Zendenta Sales Analytics Dashboard
│   ├── finance-dashboard.html  # Findexa Dark Theme Finance Dashboard
│   ├── product-table.html      # Inventory & Product Management Table
│   ├── product-workspace.html  # Glossy Browser-frame Product Workspace
│   └── streamflix-dashboard.html # Streamflix Video Streaming Admin UI
├── travel/                     # Alur aplikasi travel & e-commerce checkout
│   ├── trips.html              # Tripkini Mobile Travel Marketplace
│   ├── checkout.html           # Ringkasan Transaksi & Checkout
│   └── payment-methods.html    # Pemilihan Metode Pembayaran
├── games/                      # Mini game & eksperimen interaktif
│   └── game-tamagochi.html     # Retro Tamagotchi Virtual Pet
└── experiments/                # Eksperimen layout & komponen
    └── masonry.html            # Marketplace Masonry Product Feed
```

## Daftar Halaman & Kategori

### 1. Dashboards & Workspaces (`dashboards/`)
- `tiktok-shop.html`: Tokopedia & TikTok Shop Seller Center dengan filter chips, drawer filter samping, menu urutkan 9 kriteria, mode tampilan kartu/daftar, dan pencarian instan.
- `dashboard-content.html`: Anibeam Admin Dark Mode Content Catalog dengan 6 kartu metrik, filter dropdown (Type, Visibility, Monetization, Availability), tabel manga/anime, drawer filter samping, dan aksi batch.
- `dashboard-sales.html`: Dashboard analitik penjualan branded Zendenta.
- `finance-dashboard.html`: Dashboard finansial bertema gelap branded Findexa dengan Chart.js.
- `product-table.html`: Tabel inventaris produk desktop dengan status seleksi dan aksi batch.
- `product-workspace.html`: Antarmuka manajemen produk dengan frame browser glossy.
- `streamflix-dashboard.html`: Admin panel streaming video bergaya Netflix.

### 2. Travel & E-Commerce Flow (`travel/`)
- `trips.html`: Aplikasi mobile travel marketplace (Tripkini) dengan carousel rekomendasi dan destinasi populer.
- `checkout.html`: Alur checkout dan rincian pembayaran.
- `payment-methods.html`: Pemilihan metode pembayaran (E-wallet, Virtual Account, Kartu).

### 3. Games & Interaktif (`games/`)
- `game-tamagochi.html`: Mini game simulasi hewan virtual retro Tamagotchi.

### 4. Layout Experiments (`experiments/`)
- `masonry.html`: Eksperimen feed kategori dan katalog produk layout masonry bergaya Pinterest.

## Menjalankan Secara Lokal

Buka langsung file `index.html` pada peramban web (*browser*), atau gunakan server statis sederhana:

```bash
python3 -m http.server 8000
```

Lalu buka `http://localhost:8000/index.html`.
