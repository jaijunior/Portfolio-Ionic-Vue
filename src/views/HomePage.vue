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
            size-xs="12"
            size-sm="12" 
            size-xl="10"
            offset-xl="1"            
            size-md="8" 
            offset-md="2" 
            size-lg="8" 
            offset-lg="2">
              <biography-card-vue/>
            </ion-col>
            
          </ion-row>
          <ion-row>
            <ion-col size-xs="6" size-md="3">
              <gif-card-vue/>
            </ion-col>
            <ion-col size-xs="6" size-md="3">
              <gif-card-vue/>
            </ion-col>
            <ion-col size-xs="6" size-md="3">
              <gif-card-vue/>
            </ion-col>
            <ion-col size-xs="6" size-md="3">
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
#container {
  text-align: center;
  
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  
  color: #8c8c8c;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}

.card-image {
  max-height: 300px;
  width: 100%;
}
</style>
