<template>
    <div class="container-fluid">
        <div class="welcome card rounded-3 img-fluid w-100 bg-light mb-5 position-relative">
            <img src="~/assets/img/welcome.png" alt="" class="rounded-3"
                style="height: auto; max-height: 530px; object-fit: cover; width: 100%;">
        </div>

        <div class="card" style="width: 100%;">
            <div class="row justify-content-center">
                <div class="col-md-4">
                    <img src="assets/img/kepsek.png" class="img-fluid rounded-start" alt="...">
                    <h1 class="card-text text-center">Kurniawan, S.Pd, M.Pd.</h1>
                </div>
                <div class="col-md-8">
                    <div class="card-body text-center">
                        <h2 class="card-title">Sambutan Kepala Sekolah</h2>
                        <h4 class="card-text">Assalamualaikum Warahmatullahi Wabarakatuh</h4>
                        <p>Selamat datang di SMKN 4 Tasikmalaya. Segala puji dan syukur kita panjatkan kehadirat Allah
                            SWT, semoga kita semua ada dalam lindungan-Nya. Dan atas perkenan-Nya pula kami dapat
                            menghadirkan website SMK Negeri 4 Tasikmalaya ini. Kami berharap dengan adanya website di
                            SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami
                            sehingga dapat mempererat tali silaturrahmi antara sekolah dengan masyarakat demi kemajuan
                            kita bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan,
                            masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat
                            kami harapkan untuk pengembangan ke depan.</p>
                        <p>Akhirnya, saya mengucapkan terimakasih yang sebesar-besarnya kepada semua pihak yang tidak
                            dapat disebutkan satu segala bantuan dan persatu atas fasilitasnya yang telah diberikan
                            semoga semua yang kita lakukan bermanfaat bagi masyarakat. Wassalamu'alaikum Warahmatullahi
                            Wabarakatuh.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="mt-5">
            <div class="col">
                <div class="card d-flex p-3 bg-light justify-content-center text-center">
                    <div class="row row-cols-1 row-cols-md-4 g-3">
                        <div class="col">
                            <div>
                                <h4>Siswa</h4>
                                <h3>1500</h3>
                            </div>
                        </div>
                        <div class="col">
                            <div>
                                <h4>Guru</h4>
                                <h3>80</h3>
                            </div>
                        </div>
                        <div class="col">
                            <div>
                                <h4>Ekstrakurikuler</h4>
                                <h3>18</h3>
                            </div>
                        </div>
                        <div class="col">
                            <div>
                                <h4>Kompentensi Keahlian</h4>
                                <h3>5</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="d-flex justify-content-center mt-5">
            <h1>Berita</h1>
        </div>


        <div class="container p-5">
            <div class="row justify-content-center">
                <div class="col-md-3">
                    <div class="card bg-light mb-5">
                        <img src="assets/img/safetyriding.webp" alt="Image" style="object-fit: cover; height: auto;">
                        <div class="card-text text-center">
                            <h5>Cegah geng motor SMKN 4 Tasikmalaya luncurkan eskul unik</h5>
                            <a href="/berita/1" class="btn-sm">Baca Selengkapnya</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card bg-light mb-5">
                        <img src="assets/img/download.jpg" alt="Image" style="object-fit: cover; height: auto;">
                        <div class="card-text text-center">
                            <h5>Polsek Cibeureum Sosialisasikan Larangan Knalpot Brong dan Geng Motor di SMKN 4 Kota
                                Tasikmalaya</h5>
                            <a href="/berita/2" class="btn-sm">Baca Selengkapnya</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
useHead({
    title: "Beranda"
})
</script>

<style scoped>
.welcome {
    margin-top: 90px;
}

.welcome-text {
    margin-top: -40px;
}
</style>