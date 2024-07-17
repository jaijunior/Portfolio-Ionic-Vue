<template>
  <ion-page>
    <ion-header :translucent="true">
    
    </ion-header>
    <ion-content :fullscreen="true">
       <ion-grid>
          <ion-row class="ion-justify-content-between">
            <ion-col size="4" offset="1">
              <ion-thumbnail >
                <img alt="JaiJunior Icon" :src="logo" />
              </ion-thumbnail>
            </ion-col>
            <ion-col size="4" offset="1"> 
              <social-network-vue/>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col
            class="biography-text-column"
            size-xs="12"
            size-sm="12" 
            size-xl="8"
            offset-xl="2"            
            size-md="10" 
            offset-md="1" 
            size-lg="8" 
            offset-lg="2">
              <biography-card-vue/>
            </ion-col>
            
          </ion-row>
          <ion-row>
            <ion-col size-xs="6" size-md="3" size-lg="3" size-xl="2" offset-xl="2">
              <gif-card-vue/>
            </ion-col>
            <ion-col size-xs="6" size-md="3" size-lg="3" size-xl="2">
              <gif-card-vue/>
            </ion-col>
            <ion-col size-xs="6" size-md="3" size-lg="3" size-xl="2">
              <gif-card-vue/>
            </ion-col>
            <ion-col size-xs="6" size-md="3" size-lg="3" size-xl="2">
              <gif-card-vue/>
            </ion-col>
          </ion-row>
       </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script>
import SocialNetworkVue from '../components/SocialNetwork.vue';
import BiographyCardVue from '../components/BiographyCard.vue';
import GifCardVue from '../components/GifCard.vue';
import { IonContent,
          IonHeader,
          IonPage,
          IonTitle, 
          IonToolbar, 
          IonRow, 
          IonCol, 
          IonItem,
          IonLabel,
          IonGrid,
          IonCard,
          IonCardHeader,
          IonCardSubtitle,
          IonAccordionGroup,
          IonAccordion,
          IonThumbnail } from '@ionic/vue';
import { IonIcon } from '@ionic/vue';

import logo from '@/assets/jaijunior_logo.png';

export default {
  components: {
    IonContent, 
    IonHeader, 
    IonPage, 
    IonTitle, 
    IonToolbar, 
    IonIcon,
    IonRow,
    IonCol,
    IonItem,
    IonLabel,
    IonGrid,
    IonCard,
    IonCardHeader,
    IonCardSubtitle,
    IonAccordionGroup,
    IonAccordion,
    IonThumbnail,
    
    SocialNetworkVue,
    BiographyCardVue,
    GifCardVue
  },
  data() {
    return {
      logo
    };
  },
}
</script>

<style scoped>

</style>
