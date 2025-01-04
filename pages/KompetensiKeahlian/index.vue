<template>
    <div class="container-fluid d-flex flex-column min-vh-100">
        <div class="keahlian d-flex justify-content-center">
            <h1>Kompentensi Keahlian</h1>
        </div>
        <div class="d-flex justify-content-center align-items-center flex-wrap gap-3 p-5">
            <div class="card bg-light mb-3" style="max-width: 540px;">
                <div class="row align-items-center">
                    <div class="col-md-4 p">
                        <img src="assets/img/tkj.png" class="img-fluid rounded-start" alt="...">
                    </div>
                    <div class="col-md-8">
                        <div class="card-body">
                            <h5 class="card-title text-center">Teknik Jaringan Komputer dan Telekomunikasi</h5>
                            <p class="card-text">Konsentrasi keahlian ini fokus pada penguasaan konsep dan praktik dalam
                                membangun, mengelola, dan mengamankan jaringan komputer. Siswa akan mempelajari
                                teknologi jaringan, administrasi server, troubleshooting, serta konfigurasi perangkat
                                jaringan seperti router dan switch.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card bg-light mb-3" style="max-width: 540px;">
                <div class="row align-items-center">
                    <div class="col-md-4 p ">
                        <img src="assets/img/rpl.png" class="img-fluid rounded-start" alt="...">
                    </div>
                    <div class="col-md-8">
                        <div class="card-body">
                            <h5 class="card-title text-center">Pengembangan Perangkat Lunak dan Gim</h5>
                            <p class="card-text">Konsentrasi keahlian ini mempelajari cara merancang, mengembangkan, dan
                                memelihara perangkat lunak, termasuk aplikasi berbasis desktop, web, dan mobile. Siswa
                                juga diajarkan teknik pembuatan gim, seperti desain level, animasi, dan pemrograman gim,
                                menggunakan teknologi dan perangkat lunak terkini.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card bg-light mb-3" style="max-width: 540px;">
                <div class="row align-items-center">
                    <div class="col-md-4 p">
                        <img src="assets/img/dkv.png" class="img-fluid rounded-start" alt="...">
                    </div>
                    <div class="col-md-8">
                        <div class="card-body">
                            <h5 class="card-title text-center">Desain Komunikasi Visual</h5>
                            <p class="card-text">Konsentrasi keahlian ini mengajarkan seni dan teknik dalam menciptakan
                                desain visual yang komunikatif dan menarik. Materi meliputi desain grafis, fotografi,
                                ilustrasi, dan media digital untuk kebutuhan branding, promosi, atau media publikasi.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card bg-light mb-3" style="max-width: 540px;">
                <div class="row align-items-center">
                    <div class="col-md-4 p">
                        <img src="assets/img/tsm.png" class="img-fluid rounded-start" alt="...">
                    </div>
                    <div class="col-md-8">
                        <div class="card-body">
                            <h5 class="card-title text-center">Teknik Bisnis dan Sepeda Motor</h5>
                            <p class="card-text">Konsentrasi keahlian ini mempelajari teknik perawatan, perbaikan, dan
                                modifikasi sepeda motor, sekaligus menanamkan keterampilan kewirausahaan. Siswa
                                diajarkan cara membuka dan mengelola bisnis bengkel, termasuk aspek pemasaran dan
                                manajemen.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card bg-light mb-3" style="max-width: 540px;">
                <div class="row align-items-center">
                    <div class="col-md-4 p">
                        <img src="assets/img/toi.png" class="img-fluid rounded-start" alt="...">
                    </div>
                    <div class="col-md-8">
                        <div class="card-body">
                            <h5 class="card-title text-center">Teknik Otomasi Industri</h5>
                            <p class="card-text">Konsentrasi keahlian ini berfokus pada teknologi otomotif yang
                                diterapkan dalam skala industri. Siswa akan belajar tentang sistem mekanik kendaraan
                                modern, produksi komponen otomotif, dan pengelolaan peralatan industri yang berkaitan
                                dengan otomotif.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<script setup>
useHead({
    title: "Kompetensi Keahlian"
})
</script>

<style scoped>
.keahlian {
    margin-top: 100px;
}
</style>