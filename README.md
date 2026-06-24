<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesona Sumatera Utara - Pariwisata Resmi</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css" rel="stylesheet">
    <style>
        :root {
            --primary-color: #115e59;
            --secondary-color: #14b8a6;
            --dark-color: #0f172a;
            --light-bg: #f8fafc;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--light-bg);
            color: #334155;
            scroll-behavior: smooth;
        }
        .navbar-brand {
            font-weight: 700;
            letter-spacing: 1px;
        }
        .hero-section {
            background: linear-gradient(rgba(15, 23, 42, 0.6), rgba(15, 23, 42, 0.6)), url('WhatsApp Image 2026-06-14 at 16.38.31.jpeg?					auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
            height: 90vh;
            display: flex;
            align-items: center;
            color: white;
        }
        .card-destinasi {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: none;
            border-radius: 12px;
            overflow: hidden;
        }
        .card-destinasi:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 24px rgba(0,0,0,0.15);
        }
        .testimonial-card {
            background: white;
            border-left: 5px solid var(--secondary-color);
            border-radius: 8px;
        }
    </style>
</head>
<body>

    <!-- 1. NAVBAR & 2. DROPDOWN & 3. NAV LINKS -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top shadow">
        <div class="container">
            <a class="navbar-brand text-info" href="#beranda"><i class="bi bi-compass-fill me-2"></i>SumutTour</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto text-uppercase small fw-bold">
                    <li class="nav-item"><a class="nav-link active" href="#beranda">Beranda</a></li>
                    <li class="nav-item"><a class="nav-link" href="#destinasi">Destinasi</a></li>
                    <li class="nav-item"><a class="nav-link" href="#paket">Paket Wisata</a></li>
                    <li class="nav-item"><a class="nav-link" href="#galeri">Galeri</a></li>
                    <li class="nav-item"><a class="nav-link" href="#testimoni">Testimoni</a></li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown">
                            Info Layanan
                        </a>
                        <ul class="dropdown-menu dropdown-menu-end">
                            <li><a class="dropdown-item" href="#pemesanan">Form Pemesanan</a></li>
                            <li><hr class="dropdown-divider"></li>
                            <li><a class="dropdown-item" href="#kontak" data-bs-toggle="modal" data-bs-target="#contactModal">Kontak Darurat</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- 4. HERO SECTION / JUMBOTRON & 5. BADGE & 6. BUTTONS -->
    <section id="beranda" class="hero-section text-center text-md-start">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <span class="badge bg-info text-dark mb-3 px-3 py-2 text-uppercase fw-bold shadow-sm">Wonderful Indonesia</span>
                    <h1 class="display-3 fw-bold mb-3 text-white">Jelajahi Keindahan <span class="text-info">Sumatera Utara</span></h1>
                    <p class="lead mb-4 text-white-50">Temukan pesona alam magis Danau Toba, keajaiban Salju Panas Tinggi Raja, kegagahan Gunung Sibayak, 			hingga petualangan rimba Taman Nasional Gunung Leuser.</p>
                    <a href="#destinasi" class="btn btn-info btn-lg px-4 me-2 py-3 fw-bold text-dark shadow">Mulai Petualangan <i class="bi bi-arrow-right 			ms-2"></i></a>
                    <a href="#paket" class="btn btn-outline-light btn-lg px-4 py-3 fw-bold">Lihat Paket</a>
                </div>
            </div>
        </div>
    </section>

    <!-- 7. COMPONENT: Alert Banner -->
    <div class="container mt-4">
        <div class="alert alert-warning alert-dismissible fade show" role="alert">
            <i class="bi bi-exclamation-triangle-fill me-2"></i> <strong>Penawaran Spesial:</strong> Diskon hingga 25% untuk pemesanan paket wisata Danau 		Toba & Pendakian Sibayak bulan ini!
            <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
        </div>
    </div>

    <!-- 8. GRID SYSTEM, 9. CARD, & 10. COLLAPSE -->
    <section id="destinasi" class="py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="fw-bold text-dark">Destinasi Populer</h2>
                <p class="text-muted">Tempat-tempat eksotis yang wajib Anda kunjungi di Sumatera Utara</p>
            </div>

            <div class="row g-4">
                <!-- Card 1: Toba -->
                <div class="col-md-6 col-lg-3">
                    <div class="card card-destinasi h-100 shadow-sm">
                        <img src="DanauToba.jpeg?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="Danau Toba" style="height: 200px; object-fit: 					cover;">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">Danau Toba</h5>
                            <p class="card-text text-muted small">Danau vulkanik terbesar di dunia dengan keindahan alam memukau dan kekayaan budaya suku 				Batak.</p>
                        </div>
                        <div class="card-footer bg-transparent border-0 pb-3">
                            <button class="btn btn-outline-info w-100 fw-semibold btn-sm" data-bs-toggle="collapse" data-bs-target="#detailToba">Lihat 					Detail</button>
                            <div class="collapse mt-2" id="detailToba">
                                <div class="card card-body bg-light text-muted small p-2">
                                    Fasilitas: Hotel Berbintang, Kapal Feri, Tour Guide Lokal, Wisata Budaya Tomok.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Card 2: Salju Panas Tinggi Raja -->
                <div class="col-md-6 col-lg-3">
                    <div class="card card-destinasi h-100 shadow-sm">
                        <img src="SaljuPanasTinggiRaja.jpeg?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="Salju Panas Tinggi Raja" 				style="height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">Salju Panas Tinggi Raja</h5>
                            <p class="card-text text-muted small">Cagar alam unik di Simalungun berupa bukit kapur putih menyerupai salju dengan aliran air 				panas belerang alami.</p>
                        </div>
                        <div class="card-footer bg-transparent border-0 pb-3">
                            <button class="btn btn-outline-info w-100 fw-semibold btn-sm" data-bs-toggle="collapse" data-bs-target="#detailTinggiRaja">Lihat 				Detail</button>
                            <div class="collapse mt-2" id="detailTinggiRaja">
                                <div class="card card-body bg-light text-muted small p-2">
                                    Aktivitas: Fotografi terasering kapur, menikmati kolam air panas alami, dan tracking area cagar alam tersembunyi.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Card 3: Gunung Sibayak -->
                <div class="col-md-6 col-lg-3">
                    <div class="card card-destinasi h-100 shadow-sm">
                        <img src="GunungSibayak.jpeg?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="Gunung Sibayak" style="height: 200px; 				object-fit: cover;">
                        <div class="card-body">
                            <div class="d-flex justify-content-between align-items-center mb-1">
                                <h5 class="card-title fw-bold mb-0">Gunung Sibayak</h5>
                                <span class="badge bg-success text-white px-2 py-1" style="font-size: 10px;">New</span>
                            </div>
                            <p class="card-text text-muted small">Gunung berapi aktif di Berastagi yang ramah pemula, menyajikan keindahan kawah belerang 				dan pesona matahari terbit.</p>
                        </div>
                        <div class="card-footer bg-transparent border-0 pb-3">
                            <button class="btn btn-outline-info w-100 fw-semibold btn-sm" data-bs-toggle="collapse" data-bs-target="#detailSibayak">Lihat 				Detail</button>
                            <div class="collapse mt-2" id="detailSibayak">
                                <div class="card card-body bg-light text-muted small p-2">
                                    Fasilitas: Jalur aman pemula, Golden Sunrise hunting, dilanjutkan Pemandian Air Panas Sidebuk-debuk.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Card 4: Taman Nasional Gunung Leuser -->
                <div class="col-md-6 col-lg-3">
                    <div class="card card-destinasi h-100 shadow-sm">
                        <img src="GunungLeuser.jpeg?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="Taman Nasional Gunung Leuser" style="height: 			200px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title fw-bold">Gunung Leuser</h5>
                            <p class="card-text text-muted small">Situs Warisan Dunia UNESCO yang melindungi keanekaragaman hayati hutan hujan tropis kaya 				satwa langka.</p>
                        </div>
                        <div class="card-footer bg-transparent border-0 pb-3">
                            <button class="btn btn-outline-info w-100 fw-semibold btn-sm" data-bs-toggle="collapse" data-bs-target="#detailLeuser">Lihat 				Detail</button>
                            <div class="collapse mt-2" id="detailLeuser">
                                <div class="card card-body bg-light text-muted small p-2">
                                    Aktivitas: Jungle trekking berpemandu, pengamatan Orangutan Sumatera, riset botani, dan ekowisata alam liar.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 11. LIST GROUP & 12. PROGRESS BAR & 13. SPINNER -->
    <section id="paket" class="py-5 bg-white">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="fw-bold text-dark">Paket Wisata Unggulan</h2>
                <p class="text-muted">Pilih paket perjalanan terbaik yang disesuaikan dengan waktu dan budget Anda</p>
            </div>

            <div class="row align-items-center">
                <div class="col-lg-6">
                    <div class="list-group shadow-sm">
                        <a href="#pemesanan" class="list-group-item list-group-item-action p-3 active bg-info border-info text-dark">
                            <div class="d-flex w-100 justify-content-between align-items-center">
                                <h6 class="mb-1 fw-bold">Paket 3 Hari 2 Malam (Toba Exclusive)</h6>
                                <span class="badge bg-dark text-white rounded-pill">Best Seller</span>
                            </div>
                            <p class="mb-1 small text-dark-50">Kunjungan lengkap ke Parapat, Samosir, Tomok, dan Berastagi.</p>
                            <small class="fw-bold">Rp 2.450.000 / pax</small>
                        </a>
                        <a href="#pemesanan" class="list-group-item list-group-item-action p-3">
                            <div class="d-flex w-100 justify-content-between align-items-center">
                                <h6 class="mb-1 fw-bold">Paket 2 Hari 1 Malam (Sibayak Sunrise Trekking)</h6>
                                <span class="badge bg-success text-white rounded-pill">Hiking</span>
                            </div>
                            <p class="mb-1 small text-muted">Pendakian santai berburu Sunrise, camping ceria, dan relaksasi pemandian air panas sulfur.</p>
                            <small class="text-info fw-bold">Rp 1.200.000 / pax</small>
                        </a>
                        <a href="#pemesanan" class="list-group-item list-group-item-action p-3">
                            <div class="d-flex w-100 justify-content-between align-items-center">
                                <h6 class="mb-1 fw-bold">Paket Day Trip (Salju Panas Tinggi Raja Exotic)</h6>
                                <span class="badge bg-secondary text-white rounded-pill">Nature Tour</span>
                            </div>
                            <p class="mb-1 small text-muted">Eksplorasi bukit kapur salju belerang unik, berendam air hangat, dan hunting foto estetik.</p>
                            <small class="text-info fw-bold">Rp 750.000 / pax</small>
                        </a>
                        <a href="#pemesanan" class="list-group-item list-group-item-action p-3">
                            <div class="d-flex w-100 justify-content-between align-items-center">
                                <h6 class="mb-1 fw-bold">Paket 4 Hari 3 Malam (Leuser Jungle Expedition)</h6>
                                <span class="badge bg-warning text-dark rounded-pill">Adventure</span>
                            </div>
                            <p class="mb-1 small text-muted">Petualangan menyusuri ekosistem hutan hujan tropis asli, edukasi satwa, dan melihat Orangutan 				langsung.</p>
                            <small class="text-info fw-bold">Rp 3.150.000 / pax</small>
                        </a>
                    </div>
                </div>

                <div class="col-lg-6 mt-4 mt-lg-0 px-lg-5">
                    <h4 class="fw-bold mb-4 text-dark"><i class="bi bi-percent text-info me-2"></i>Ketersediaan Kuota Bulan Ini</h4>
                    
                    <div class="mb-3">
                        <div class="d-flex justify-content-between small mb-1">
                            <span>Paket Toba Exclusive</span>
                            <span class="fw-bold">85% Terisi</span>
                        </div>
                        <div class="progress" style="height: 10px;">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 85%"></div>
                        </div>
                    </div>

                    <div class="mb-3">
                        <div class="d-flex justify-content-between small mb-1">
                            <span>Salju Panas Tinggi Raja Exotic</span>
                            <span class="fw-bold">60% Terisi</span>
                        </div>
                        <div class="progress" style="height: 10px;">
                            <div class="progress-bar bg-success" role="progressbar" style="width: 60%"></div>
                        </div>
                    </div>

                    <div class="mb-3">
                        <div class="d-flex justify-content-between small mb-1">
                            <span>Sibayak Sunrise Trekking</span>
                            <span class="fw-bold">75% Terisi</span>
                        </div>
                        <div class="progress" style="height: 10px;">
                            <div class="progress-bar bg-warning" role="progressbar" style="width: 75%"></div>
                        </div>
                    </div>

                    <div class="mb-3">
                        <div class="d-flex justify-content-between small mb-1">
                            <span>Leuser Jungle Expedition</span>
                            <span class="fw-bold">40% Terisi</span>
                        </div>
                        <div class="progress" style="height: 10px;">
                            <div class="progress-bar bg-primary" role="progressbar" style="width: 40%"></div>
                        </div>
                    </div>
                    
                    <div class="d-flex align-items-center text-muted mt-4 small">
                        <div class="spinner-border spinner-border-sm text-info me-2" role="status"></div>
                        <span>Sistem memperbarui sisa kuota pendaftaran secara real-time.</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 14. CAROUSEL & 15. CAROUSEL INDICATORS (UPDATED: 4 SLIDES) -->
    <section id="galeri" class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="fw-bold text-dark">Galeri Wisata</h2>
                <p class="text-muted">Dokumentasi keindahan panorama alam Sumatera Utara</p>
            </div>

            <div class="row justify-content-center">
                <div class="col-lg-9">
                    <div id="galleryCarousel" class="carousel slide shadow-lg rounded-3 overflow-hidden" data-bs-ride="carousel">
                        <div class="carousel-indicators">
                            <button type="button" data-bs-target="#galleryCarousel" data-bs-slide-to="0" class="active"></button>
                            <button type="button" data-bs-target="#galleryCarousel" data-bs-slide-to="1"></button>
                            <button type="button" data-bs-target="#galleryCarousel" data-bs-slide-to="2"></button>
                            <button type="button" data-bs-target="#galleryCarousel" data-bs-slide-to="3"></button>
                        </div>
                        <div class="carousel-inner">
                            <!-- Slide 1: Danau Toba -->
                            <div class="carousel-item active" data-bs-interval="3000">
                                <img src="DanauToba.jpeg?auto=format&fit=crop&w=1200&h=550&q=80" class="d-block w-100" alt="Danau Toba">
                                <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded">
                                    <h5>Keindahan Magis Danau Toba</h5>
                                    <p>Lanskap perbukitan hijau mengitari danau purba kaldera terbesar dunia.</p>
                                </div>
                            </div>
                            <!-- Slide 2: Salju Panas Tinggi Raja -->
                            <div class="carousel-item" data-bs-interval="3000">
                                <img src="SaljuPanasTinggiRaja.jpeg?auto=format&fit=crop&w=1200&h=550&q=80" class="d-block w-100" alt="Tinggi Raja">
                                <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded">
                                    <h5>Keajaiban Kawah Tinggi Raja</h5>
                                    <p>Situs geologi unik dengan formasi batu kapur putih bersih berbalut air panas belerang.</p>
                                </div>
                            </div>
                            <!-- Slide 3: Gunung Sibayak (TAMBAHAN) -->
                            <div class="carousel-item" data-bs-interval="3000">
                                <img src="GunungSibayak.jpeg?auto=format&fit=crop&w=1200&h=550&q=80" class="d-block w-100" alt="Gunung Sibayak">
                                <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded">
                                    <h5>Pesona Puncak Gunung Sibayak</h5>
                                    <p>Keindahan kawah belerang aktif dengan panorama golden sunrise yang memikat.</p>
                                </div>
                            </div>
                            <!-- Slide 4: Gunung Leuser (TAMBAHAN) -->
                            <div class="carousel-item" data-bs-interval="3000">
                                <img src="GunungLeuser.jpeg?auto=format&fit=crop&w=1200&h=550&q=80" class="d-block w-100" alt="Gunung Leuser">
                                <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded">
                                    <h5>Petualangan Hutan Hujan Gunung Leuser</h5>
                                    <p>Eksplorasi ekosistem hutan tropis liar pelindung flora endemik dan satwa langka.</p>
                                </div>
                            </div>
                        </div>
                        <button class="carousel-control-prev" type="button" data-bs-target="#galleryCarousel" data-bs-slide="prev">
                            <span class="carousel-control-prev-icon"></span>
                        </button>
                        <button class="carousel-control-next" type="button" data-bs-target="#galleryCarousel" data-bs-slide="next">
                            <span class="carousel-control-next-icon"></span>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 16. BREADCRUMB NAVIGATION -->
    <section id="testimoni" class="py-5 bg-white">
        <div class="container">
            <nav aria-label="breadcrumb">
                <ol class="breadcrumb bg-light p-3 rounded shadow-sm">
                    <li class="breadcrumb-item"><a href="#beranda" class="text-decoration-none text-info">Beranda</a></li>
                    <li class="breadcrumb-item active" aria-current="page">Testimoni Wisatawan</li>
                </ol>
            </nav>

            <div class="text-center mb-5">
                <h2 class="fw-bold text-dark">Testimoni Pengunjung</h2>
            </div>

            <div class="row g-4">
                <div class="col-md-6">
                    <div class="p-4 testimonial-card shadow-sm">
                        <p class="text-muted italic">"Liburan ke Danau Toba bareng keluarga bener-bener gak terlupakan. Pelayanannya ramah banget, hotelnya 			langsung menghadap ke danau!"</p>
                        <h6 class="fw-bold mb-0">Arthur</h6>
                        <small class="text-muted">Jakarta</small>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="p-4 testimonial-card shadow-sm">
                        <p class="text-muted italic">"Trekking subuh di Sibayak capeknya langsung kebayar pas dapet momen golden sunrise di atas kawah. 			Keren parah asli!"</p>
                        <h6 class="fw-bold mb-0">Edward Cullen</h6>
                        <small class="text-muted">Medan</small>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 17. FORM INPUT GROUP & 18. BUTTON GROUP & 19. CARD HEADER/BODY & 20. FORM SELECT -->
    <section id="pemesanan" class="py-5 bg-light">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="card shadow-lg border-0 rounded-3">
                        <div class="card-header bg-dark text-white p-4">
                            <h4 class="mb-0 fw-bold"><i class="bi bi-journal-check text-info me-2"></i>Form Pemesanan Tiket & Paket</h4>
                        </div>
                        <div class="card-body p-4 p-md-5">
                            <form>
                                <div class="mb-3">
                                    <label class="form-label fw-bold">Nama Lengkap</label>
                                    <div class="input-group">
                                        <span class="input-group-text"><i class="bi bi-person"></i></span>
                                        <input type="text" class="form-control" placeholder="Masukkan nama Anda" required>
                                    </div>
                                </div>

                                <div class="row g-3 mb-3">
                                    <div class="col-md-6">
                                        <label class="form-label fw-bold">Nomor WhatsApp</label>
                                        <div class="input-group">
                                            <span class="input-group-text">+62</span>
                                            <input type="tel" class="form-control" placeholder="8123456xxx" required>
                                        </div>
                                    </div>
                                    <div class="col-md-6">
                                        <label class="form-label fw-bold">Pilih Paket Wisata</label>
                                        <select class="form-select" required>
                                            <option value="" disabled selected>-- Pilih Paket --</option>
                                            <option value="toba">Paket 3D2N Toba Exclusive</option>
                                            <option value="sibayak">Paket 2D1N Sibayak Sunrise Trekking</option>
                                            <option value="tinggiraja">Paket Day Trip Salju Panas Tinggi Raja</option>
                                            <option value="leuser">Paket 4D3N Leuser Jungle Expedition</option>
                                        </select>
                                    </div>
                                </div>

                                <div class="mb-4">
                                    <label class="form-label fw-bold">Metode Pembayaran</label>
                                    <div class="btn-group w-100" role="group">
                                        <input type="radio" class="btn-check" name="pay" id="p1" checked>
                                        <label class="btn btn-outline-secondary" for="p1">Transfer Bank</label>
                                        <input type="radio" class="btn-check" name="pay" id="p2">
                                        <label class="btn btn-outline-secondary" for="p2">E-Wallet / QRIS</label>
                                    </div>
                                </div>

                                <!-- 21. UTILITY CLASS -->
                                <div class="d-grid">
                                    <button type="submit" class="btn btn-info text-dark fw-bold btn-lg shadow-sm py-3">Kirim Formulir Pemesanan</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 22. MODAL DIALOG & 23. MODAL CONTENT & 24. MODAL HEADER/FOOTER -->
    <div class="modal fade" id="contactModal" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered">
            <div class="modal-content">
                <div class="modal-header bg-danger text-white">
                    <h5 class="modal-title fw-bold"><i class="bi bi-telephone-fill me-2"></i>Hubungi Kontak Darurat</h5>
                    <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body p-4">
                    <p class="text-muted">Layanan Call Center Pelanggan Aktif 24 Jam saat Anda di Lapangan Tour:</p>
                    <h4 class="text-danger fw-bold">+62 811-6789-0000</h4>
                </div>
                <div class="modal-footer bg-light">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Tutup</button>
                    <a href="tel:+6281167890000" class="btn btn-danger fw-semibold">Panggil Sekarang</a>
                </div>
            </div>
        </div>
    </div>

    <!-- 25. FOOTER -->
    <footer class="bg-dark text-white-50 py-5">
        <div class="container text-center text-md-start">
            <div class="row g-4">
                <div class="col-md-6">
                    <h5 class="text-white fw-bold mb-3"><i class="bi bi-compass-fill text-info me-2"></i>SumutTour</h5>
                    <p class="small">Situs resmi penyedia layanan paket informasi pariwisata terpercaya. Dibuat khusus sebagai syarat pemenuhan nilai UAS 		OBE Universitas Potensi Utama.</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <h6 class="text-white fw-bold mb-3">Kantor Operasional</h6>
                    <p class="small mb-0">Jl. K.L. Yos Sudarso, Kota Medan, Sumatera Utara.</p>
                    <p class="small">&copy; 2026 SumutTour Pariwisata. All Rights Reserved.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap 5 JS Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
