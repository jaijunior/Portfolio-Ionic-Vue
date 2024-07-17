<template>
  <ion-card>
    <img 
        :alt="img_alt" 
        :src="img_src" 
        class="card-img"/>
    <ion-card-header>
        <ion-card-title>{{ title }}</ion-card-title>
        <ion-card-subtitle>{{ subtitle }}</ion-card-subtitle>
    </ion-card-header>

    <ion-card-content>
        {{ content }}
    </ion-card-content>
    </ion-card>
</template>

<script>

export default {
    components: {

    },
    props: {
        img_alt: {
            type:String,
            required:false
        },
        img_src: {
            type:String,
            required:false
        },
        title: {
            type: String,
            required: false
        },
        subititle: {
            type: String,
            required: false
        },
        content: {
            type: String,
            required: false
        }
        
    }
}
</script>

<style scoped>
.card-img {
    width: 100%;
}
</style>