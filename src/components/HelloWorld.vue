<template>
  <div>
    <nav
      class="navbar navbar-expand-lg navbar-light"
      style="background-color: #545455ff"
    >
      <div class="container-fluid">
        <a class="navbar-brand" href="#"
          ><img
            src="../assets/logo3.png"
            alt="Bootstap"
            class="logo"
            width="120"
            height="70"
            style="left: 1000px"
        /></a>

        <div
          class="collapse navbar-collapse justify-content-end"
          id="navbarSupportedContent"
        >
          <ul class="navbar-nav" style="margin-right: 100px; margin-top: auto">
            <li class="nav-item">
              <a
                class="nav-link active"
                aria-current="page"
                href="home"
                style="color: white; font-size: 30px"
                >Home</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#" style="color: white; font-size: 30px"
                >About</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="produk"
                style="color: white; font-size: 30px"
                >Product</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <section class="hero" id="home">
      <div class="container col-xxl-0 px-2 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div
            class="col-sm-9 col-lg-6"
            style="margin-top: -50px; position: relative; top: -20px"
          >
            <lottie-player
              src="https://assets9.lottiefiles.com/private_files/lf30_fpdvsz3i.json"
              background="transparent"
              speed="1"
              style="width: 100%; height: auto"
              loop
              autoplay
            ></lottie-player>
          </div>
          <div class="col-lg-6">
            <h1 class="display-5 fw-bold lh-1 mb-3">
              START YOUR DAY WITH COFFE
            </h1>
            <p class="lead">
              Nikmatilah setiap tegukan yang menghangatkan hati dan semangatmu.
              Biarkan aroma kopi mengisi ruang dan membuka pintu menuju hari
              yang penuh potensi dan kebahagiaan. Dengan setiap tegukan, rasakan
              energi dan kecerdasan yang mengalir melalui tubuhmu, siap untuk
              menghadapi tantangan dan meraih mimpi-mimpi yang ada di depanmu.
            </p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-start">
              <button
                type="button"
                class="btn btn-outline-secondary btn-lg px-4"
              >
                Order
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="history-coffee" class="section">
      <div class="container col-xxl-0 px-2 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-lg-6 col-sm-9">
            <h2 class="section-title fw-bold lh-1 mb-3" style="">
              OUR HISTOR COFFE
            </h2>
            <p>
              Di sebuah desa kecil yang terpencil, terdapat sebuah cerita
              menarik tentang biji kopi yang tumbuh dengan keajaiban. Petani
              kopi di desa ini dengan penuh semangat dan kesabaran merawat
              tanaman kopi mereka. Mereka mengetahui bahwa untuk menghasilkan
              biji kopi berkualitas tinggi, diperlukan perawatan yang cermat
              mulai dari pemilihan varietas yang tepat hingga pemeliharaan yang
              baik. Dengan mengandalkan pengetahuan turun temurun dan pengalaman
              bertahun-tahun, petani kopi ini memastikan bahwa setiap tahap
              dalam proses budidaya kopi dilakukan dengan penuh dedikasi
            </p>
            <p>
              Setelah buah kopi matang, petani dengan hati-hati memproses biji
              kopi untuk memisahkan biji dari daging buahnya. Biji kopi yang
              terkumpul kemudian menjalani proses fermentasi dan pengeringan
              yang teliti. Petani mengawasi secara ketat agar biji kopi
              dikeringkan dengan baik, sehingga menghasilkan biji kopi yang
              berkualitas tinggi. Setelah proses pengeringan selesai, biji kopi
              siap untuk dipanggang. Dalam proses pemanggangan, petani
              menggunakan keahlian mereka untuk menghasilkan biji kopi dengan
              cita rasa yang unik dan aroma yang memikat. Hasilnya adalah biji
              kopi dari desa kecil ini yang memiliki karakteristik yang luar
              biasa dan menjadi kebanggaan komunitas petani kopi setempat.
            </p>
          </div>
          <div class="col-lg-6">
            <img
              src="../assets/bijikopi.jpg"
              alt="History of Coffee"
              class="img-fluid"
              style="max-width: 100%; height: auto; border-radius: 50px"
            />
          </div>
        </div>
      </div>
    </section>

    <section class="produk text container" id="produk">
      <div class="container">
        <div class="align item-center mb-3" style="margin-top: 200px">
          <div class="col-lg-9 ms-auto me-auto" style="padding-bottom: 50px">
            <h1 class="h1 mb-1 text-dark text-center">Populer produk</h1>
          </div>
          <div class="row">
            <div
              class="col-lg-4 col-sm-6"
              style="
                display: flex;
                flex-direction: column;
                align-items: center;
                text-align: center;
              "
            >
              <img
                src="../assets/produk4.jpg"
                alt=""
                style="max-width: 40%; height: auto; border-radius: 50px"
              />
              <h3 class="text-dark fw-normal pt-3">Latte</h3>
              <p>
                Latte adalah minuman kopi yang terbuat dari espresso dan susu
                steamed (direbus) dengan sedikit busa susu di atasnya. Latte
                biasanya lebih creamy daripada cappuccino karena lebih banyak
                menggunakan susu.
              </p>
            </div>
            <div
              class="col-lg-4 col-sm-6"
              style="
                display: flex;
                flex-direction: column;
                align-items: center;
                text-align: center;
              "
            >
              <img
                src="../assets/produk5.jpg"
                alt=""
                style="max-width: 40%; height: auto; border-radius: 50px"
              />

              <h3 class="text-dark fw-normal pt-3">Mocha</h3>
              <p>
                Mocha adalah minuman kopi yang menggabungkan espresso dengan
                cokelat. Ini biasanya ditambahkan dengan susu steamed, busa
                susu, dan kadang-kadang diberi taburan bubuk kakao di atasnya.
              </p>
            </div>
            <div
              class="col-lg-4 col-sm-6"
              style="
                display: flex;
                flex-direction: column;
                align-items: center;
                text-align: center;
              "
            >
              <img
                src="../assets/produk2.jpg"
                alt=""
                style="max-width: 40%; height: auto; border-radius: 50px"
              />
              <h3 class="text-dark fw-normal pt-3">Flat white</h3>
              <p>
                Flat white adalah minuman kopi yang populer di Australia dan
                Selandia Baru. Ini terdiri dari satu atau dua shot espresso yang
                dituangkan ke dalam susu steamed dan hanya memiliki sedikit busa
                susu di atasnya.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style>
/* .logo{
  position: absolute;
  left: 150px;
  top: -14px;

} */
</style>
