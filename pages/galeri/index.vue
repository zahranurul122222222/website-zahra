<template>
    <div class="container-fluid">
        <div class="text-center judul">
            <h1>Galeri</h1>
            <p class="text-secondary mb-4">Berikut adalah galeri-galeri sekolah</p>
        </div>

        <div class="">
            <div class="row justify-cotent-center">
                <div class="col-md-3 mb-4" v-for="(foto, i) in fotos" :key="i">
                    <img :src="foto.img" class="img-fluid rounded" style="object-fit: cover; width: 100%; height: 150px;" alt="">
                </div>
            </div>
        </div>
    </div>
</template>
<script setup>
useHead({
    title: "Galeri"
})
const supabase = useSupabaseClient();
const fotos = ref([]);
const getgaleri = async () => {
    const { data } = await supabase.from("galeri").select(`*`)
    if (data) fotos.value = data;
};
onMounted(() => {
    getgaleri();
});
</script>

<style scoped>
.judul {
    margin-top: 100px;
}
</style>