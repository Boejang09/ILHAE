<template>
  <div>
    <!-- Navbar -->
    <header class="navbar">
      <a href="#" class="logo">ILHAE</a>

      <nav class="nav-links">
        <a href="#tentang">Tentang</a>
        <a href="#program">Program</a>
        <a href="#prestasi">Prestasi</a>
        <a href="#kegiatan">Kegiatan</a>
      </nav>

      <a href="#bergabung" class="nav-button">
        Bergabung
      </a>
    </header>

    <main>
      <!-- Hero -->
      <section class="hero">
        <div class="hero-content">
          <p class="hero-label">
            KOMUNITAS MAHASISWA INFORMATIKA
          </p>

          <h1>
            Belajar.<br />
            Berkarya.<br />
            Berprestasi.
          </h1>

          <p class="hero-description">
            ILHAE menjadi ruang bagi mahasiswa Informatika
            untuk belajar, mengembangkan kemampuan, mengikuti
            kompetisi, dan menciptakan karya bersama.
          </p>

          <div class="hero-actions">
            <a href="#bergabung" class="hero-button">
              Bergabung dengan ILHAE
            </a>

            <a href="#tentang" class="hero-link">
              Kenali ILHAE
              <span>→</span>
            </a>
          </div>
        </div>

        <div class="hero-logo">
          <img
            src="/images/logo-ilhae.png"
            alt="Logo ILHAE"
          />
        </div>
      </section>

      <!-- Tentang -->
      <section id="tentang" class="about">
        <div class="about-heading">
          <p class="section-label">
            TENTANG ILHAE
          </p>

          <h2>
            Tempat mahasiswa Informatika
            berkembang bersama.
          </h2>
        </div>

        <div class="about-content">
          <p class="about-lead">
            Informatics Laboratory Hub for Achievement & Excellent
            atau ILHAE merupakan komunitas mahasiswa Informatika
            yang menjadi ruang untuk belajar, berkarya, berkompetisi,
            dan berkembang bersama.
          </p>

          <p>
            Melalui kegiatan belajar, pengembangan proyek, persiapan
            kompetisi, dan kolaborasi, ILHAE mendorong mahasiswa untuk
            mengembangkan kemampuan sekaligus menghasilkan karya yang
            bermanfaat.
          </p>
        </div>
      </section>

      <!-- Program -->
      <section id="program" class="program">
        <div class="program-header">
          <p class="section-label">
            PROGRAM ILHAE
          </p>

          <h2>
            Belajar tidak berhenti
            di ruang kelas.
          </h2>
        </div>

        <div class="program-list">
          <article class="program-item">
            <span class="program-number">01</span>

            <div class="program-info">
              <h3>Pengembangan Kemampuan</h3>

              <p>
                Kegiatan belajar dan berbagi pengetahuan untuk
                memperkuat kemampuan teknis maupun pemecahan masalah.
              </p>
            </div>

            <span class="program-arrow">↗</span>
          </article>

          <article class="program-item">
            <span class="program-number">02</span>

            <div class="program-info">
              <h3>Persiapan Kompetisi</h3>

              <p>
                Mempersiapkan mahasiswa untuk mengikuti berbagai
                kompetisi di bidang teknologi dan informatika.
              </p>
            </div>

            <span class="program-arrow">↗</span>
          </article>

          <article class="program-item">
            <span class="program-number">03</span>

            <div class="program-info">
              <h3>Pengembangan Proyek</h3>

              <p>
                Mendorong mahasiswa mengubah ide menjadi proyek
                digital yang dapat dikembangkan dan digunakan.
              </p>
            </div>

            <span class="program-arrow">↗</span>
          </article>

          <article class="program-item">
            <span class="program-number">04</span>

            <div class="program-info">
              <h3>Kolaborasi</h3>

              <p>
                Membangun lingkungan yang mendorong mahasiswa
                untuk saling berbagi, bekerja sama, dan berkembang.
              </p>
            </div>

            <span class="program-arrow">↗</span>
          </article>
        </div>
      </section>

      <!-- Prestasi -->
      <section id="prestasi" class="achievements">
        <div class="achievements-heading">
          <p class="section-label">
            PRESTASI
          </p>

          <h2>
            Dari proses menjadi
            pencapaian.
          </h2>

          <p class="achievements-intro">
            Setiap pencapaian dimulai dari proses belajar,
            kerja sama, dan keberanian untuk mencoba.
          </p>
        </div>

        <div class="achievement-list">
          <article class="achievement-item">
            <div class="achievement-year">
              2026
            </div>

            <div class="achievement-content">
              <p class="achievement-category">
                KOMPETISI
              </p>

              <h3>
                HACKATHON IYREF - SRE ITB
              </h3>

              <p>
                Mengembangkan TaniBijak, solusi digital di bidang pertanian yang memanfaatkan teknologi web dan machine learning untuk membantu pengelolaan lahan dan rekomendasi pertanian. 
                Tim berhasil meraih peringkat 4 pada babak semifinal kompetisi.
              </p>
            </div>

            <div class="achievement-result">
              Semifinal/ 4th
            </div>
          </article>

          <article class="achievement-item">
            <div class="achievement-year">
              2026
            </div>

            <div class="achievement-content">
              <p class="achievement-category">
                PROYEK
              </p>

              <h3>
                Nama Proyek
              </h3>

              <p>
                Deskripsi singkat mengenai proyek yang
                dikembangkan oleh anggota ILHAE.
              </p>
            </div>

            <div class="achievement-result">
              Pencapaian
            </div>
          </article>

          <article class="achievement-item">
            <div class="achievement-year">
              2025
            </div>

            <div class="achievement-content">
              <p class="achievement-category">
                KOMPETISI
              </p>

              <h3>
                Nama Kompetisi
              </h3>

              <p>
                Deskripsi singkat mengenai pengalaman
                atau pencapaian anggota ILHAE.
              </p>
            </div>

            <div class="achievement-result">
              Finalis
            </div>
          </article>
        </div>
      </section>

      <!-- Kegiatan -->
      <section id="kegiatan" class="activities">
        <div class="activities-header">
          <div>
            <p class="section-label">
              KEGIATAN
            </p>

            <h2>
              Ruang untuk
              <br />
              terus berkembang.
            </h2>
          </div>

          <p class="activities-intro">
            Kegiatan ILHAE menjadi ruang bagi mahasiswa untuk
            belajar bersama, mempersiapkan kompetisi, dan
            mengembangkan proyek secara kolaboratif.
          </p>
        </div>

        <div class="activity-list">
          <article class="activity-item">
            <div class="activity-date">
              <strong>01</strong>
              <span>KEGIATAN</span>
            </div>

            <div class="activity-info">
              <p class="activity-category">
                PEMBELAJARAN
              </p>

              <h3>Belajar Bersama</h3>

              <p>
                Sesi belajar bersama untuk membahas teknologi
                dan keterampilan yang relevan dengan bidang Informatika.
              </p>
            </div>

            <span class="activity-arrow">↗</span>
          </article>

          <article class="activity-item">
            <div class="activity-date">
              <strong>02</strong>
              <span>KEGIATAN</span>
            </div>

            <div class="activity-info">
              <p class="activity-category">
                KOMPETISI
              </p>

              <h3>Persiapan Kompetisi</h3>

              <p>
                Persiapan tim melalui latihan, diskusi,
                pembagian peran, dan pengembangan solusi.
              </p>
            </div>

            <span class="activity-arrow">↗</span>
          </article>

          <article class="activity-item">
            <div class="activity-date">
              <strong>03</strong>
              <span>KEGIATAN</span>
            </div>

            <div class="activity-info">
              <p class="activity-category">
                KOLABORASI
              </p>

              <h3>Project Collaboration</h3>

              <p>
                Membangun proyek bersama dari tahap ide,
                pengembangan, hingga menghasilkan karya.
              </p>
            </div>

            <span class="activity-arrow">↗</span>
          </article>
        </div>
      </section>

      <!-- Bergabung -->
      <section id="bergabung" class="join">
        <div class="join-content">
          <p class="section-label">
            BERGABUNG DENGAN ILHAE
          </p>

          <h2>
            Siap berkembang
            bersama?
          </h2>

          <p class="join-description">
            Bergabung bersama mahasiswa Informatika lainnya,
            temukan pengalaman baru, dan kembangkan kemampuan
            melalui kegiatan serta proyek bersama ILHAE.
          </p>

          <a href="#" class="join-button">
            Daftar sebagai Anggota
            <span>→</span>
          </a>
        </div>

        <div class="join-note">
          <p>
            Terbuka untuk mahasiswa yang ingin belajar,
            berkarya, dan berkembang bersama.
          </p>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer class="footer">
      <div class="footer-main">
        <div class="footer-brand">
          <a href="#" class="footer-logo">
            ILHAE
          </a>

          <p>
            Informatics Laboratory Hub for Achievement & Excellent.
            Ruang bagi mahasiswa Informatika untuk belajar,
            berkarya, dan berkembang bersama.
          </p>
        </div>

        <div class="footer-links">
          <div class="footer-column">
            <p class="footer-title">
              Navigasi
            </p>

            <a href="#tentang">Tentang</a>
            <a href="#program">Program</a>
            <a href="#prestasi">Prestasi</a>
            <a href="#kegiatan">Kegiatan</a>
          </div>

          <div class="footer-column">
            <p class="footer-title">
              Bergabung
            </p>

            <a href="#bergabung">
              Daftar sebagai Anggota
            </a>

            <a href="#">
              WhatsApp
            </a>
          </div>
        </div>
      </div>

      <div class="footer-bottom">
        <p>
          © 2026 ILHAE. Seluruh hak cipta dilindungi.
        </p>

        <p>
          Komunitas Mahasiswa Informatika
        </p>
      </div>
    </footer>
  </div>
</template>