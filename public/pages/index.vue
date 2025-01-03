<template>
    <div class="coutainer-fluid">
        <div class="sambutan-kepala sekolah mb-5 text-center">
            <div class="row align-items-ccenter">
                <div class="col-md-3 mb-3 mb-md-0">
                    <img src="~/assets/kepala-sekolah.jpg" alt="Kepala sekolah" class="img-fluid rounded-circle animate-img"/>
                </div>
                <div class="col-md-9">
                    <h4 class="text-primary">SAMBUTAN KEPALA SEKOLAH</h4>
                    <p class="lead text-muted">
                        Assalamualaikum Warahmatullahi Wabarakatuh, Selamat datang di WEB SMKN4 Tasikmalaya.kami berharap dengan webssite ini, pengunjung dapat mengenal lebih jauh sekolah kami dan mempererat silaturahmi untuk kemajuan bersama.
                    </p>
                    <p class="font-weight-bold text-dark">
                        Kepala sekolah: <span class="text-succes">Kurniawan Spd.mpd</span>
                    </p>
                </div>
            </div>
        </div>
        <div class="row text-center mb-5">
            <div class="col-md-4">
                <div class="statistic-card p-4 shadow-sm">
                    <i class="fa fa-users fa-2x text-primary mb-3"></i>
                    <h2 class="text-primary">Jumlah siswa</h2>
                    <p class="display-4 text-success">{{ statistics.student }}</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="statistic-card p-4 shadow-sm">
                    <i class="fa fa-chalkboard-teacher fa-2x text-primary mb-3"></i>
                    <h2 class="text-primary">Jumlah guru</h2>
                    <p class="display-4 text-success">{{ statistics.teachers }}</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
statistics:{
    student:1500,
    teachers:80,
}
</script>