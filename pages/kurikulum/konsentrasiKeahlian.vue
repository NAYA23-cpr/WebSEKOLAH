<template>
<div class="jurusan mt-5 pt-5">
            <h3 class="m-5">KOMPETENSI KEAHLIAN</h3>
            <div class="scroll-container">
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/tkjt.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">TEKNIK JARINGAN KOMPUTER DAN TELEKOMUNIKASI</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/pplg.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title"> PENGEMBANGAN PERANGKAT LUNAK DAN GIM</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/tbsm.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">TEKNIK SEPEDAH MOTOR</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/dkv.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">DESAIN KOMUNIKASI VISUAL</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/toi.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">TEKNIK OTOMASI INDUSTRI</h5>
                    </div>
                </div>
            </div>
        </div>
        <div class="jurusan mt-5 pt-5">
        <h3 class="m-5">GURU-GURU</h3>
        <h3 class="m-5 ">TOTAL : 56</h3>
            <div class="scroll-container">
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/paadi.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">PAK ADI</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/pahilmi.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title"> PAK HILMI</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/buana.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">BU ANA</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/paderi.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">PA DERI</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="/assets/img/kepalasekolah.png" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">KEPALA SEKOLAH</h5>
                    </div>
                </div>
            </div>
        </div>
        <div class="stat text-center bg-dark text-light">
            <div>
                <h1>siswa</h1>
                <h2>15000</h2>
            </div>
        </div>
</template>
<style>
.scroll-container {
    display: flex;
    overflow-x: auto;
    gap: 1rem;
    padding: 1rem 0;
    scrollbar-width: thin;
}

.scroll-container::-webkit-scrollbar {
    height: 8px;
}

.scroll-container::-webkit-scrollbar-thumb {
    background-color: #087a8e;
    border-radius: 4px;
}

.scroll-container::-webkit-scrollbar-track {
    background-color: #3297ad;
}
.scroll {
    max-height: 150px;
    overflow-y: auto; 
}

.card {
    flex: 0 0 auto;
}

.sambutan {
    width: 50%;
    position: absolute;
    top: 68%;
    right: 25%;
}

.berita {
    background-color: #4870A4;
}
</style>

<!-- <script setup> 
const supabase = useSupabaseClient()
const berita = ref([])

const getBerita = async () => {
  const { data, error } = await supabase
    .from('berita')
    .select('*')
  if (error) {
    console.error('Error Berita:', error)
  } else {
    berita.value = data
  }
}

onMounted(() => {
  getBerita()
})
</script> -->