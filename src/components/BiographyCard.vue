<template>
  <ion-card>
    <ion-card-header>
        <ion-card-title>Hello, I`m Jairo</ion-card-title>
        <ion-card-subtitle>Software Developer</ion-card-subtitle>
    </ion-card-header>

    <ion-card-content>
        <ion-grid>
        <ion-row>
            <ion-col>
    
            <ion-img 
                src="https://docs-demo.ionic.io/assets/madison.jpg"
                alt="The Wisconsin State Capitol building in Madison, WI at night">
                </ion-img>
            </ion-col>
            <ion-col>
                
            </ion-col>
        </ion-row>
        </ion-grid>
    </ion-card-content>
    </ion-card>
</template>

<script>
import {IonCard,
        IonCardHeader,
        IonCardTitle,
        IonCardSubtitle,
        IonCardContent,
        IonGrid,
        IonRow,
        IonCol,
        IonImg
} from '@ionic/vue'
export default {
    components: {
        IonCard,
        IonCardHeader,
        IonCardTitle,
        IonCardSubtitle,
        IonCardContent,
        IonGrid,
        IonRow,
        IonCol,
        IonImg
    }

}
</script>

<style>

</style>