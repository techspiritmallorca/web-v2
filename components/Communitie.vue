<script>
export default {
    props: ['name', 'url', 'img', 'bg_black'],
    computed: {
        computedImgSrc() {
            return require(`@/assets/communities/${this.img}`);
        }
    }
}
</script>

<template>
    <div class="col-md-6 col-lg-4 col-xl-3 mb-5">
        <a class="card lift" :href="url" target="_blank">
            <div class="img-wrapper">
                <div v-if="bg_black" class="bg-black">
                    <img 
                        class="card-img-top" 
                        :src=computedImgSrc
                        :alt=name
                    />    
                </div>
                <img v-else
                    class="card-img-top" 
                    :src=computedImgSrc
                    :alt=name
                />
            </div>
            <div class="card-body text-center py-3">
                <h6 class="card-title mb-0">{{ name }}</h6>
            </div>
        </a>
    </div>
</template>