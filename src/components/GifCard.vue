<template>
  <ion-card >
    <img 
        alt="Silhouette of mountains" 
        src="https://31.media.tumblr.com/4abdd6188a5f6056ef8e706d536b9528/tumblr_ms35q4JhSy1rm6gkpo1_500.gif" 
        class="card-img"/>
    <ion-card-header>
        <ion-card-title>Card Title</ion-card-title>
        <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
    </ion-card-header>

    <ion-card-content>
        Here's a small text description for the card content. Nothing more, nothing less.
    </ion-card-content>
    </ion-card>
</template>

<script>

export default {
    components: {

    },
    props: {

    }
}
</script>

<style scoped>
.card-img {
    width: 100%;
}
</style>