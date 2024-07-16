<template>
    <div>
        <ion-icon :icon="logoLinkedin" size="large" class="ion-padding"></ion-icon>
        <ion-icon :icon="logoGithub" size="large" class="ion-padding"></ion-icon>
        <ion-icon :icon="logoTwitch" size="large" class="ion-padding"></ion-icon>
    </div>
</template>

<script>
import {IonIcon} from '@ionic/vue'
import { logoLinkedin, logoGithub, logoTwitch } from 'ionicons/icons';
export default {
    components: {
        IonIcon
    },
    setup() {
        return { logoLinkedin, logoGithub, logoTwitch }
    }

}
</script>

<style>

</style>