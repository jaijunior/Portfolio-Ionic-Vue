<template>
  <ion-card>
    <ion-card-header>
        <ion-card-title>
            <ion-text 
            color="tertiary" 
            mode="md">
                Jairo Júnior
            </ion-text>
        </ion-card-title>
        <ion-card-subtitle>Desenvolvedor de Software</ion-card-subtitle>
    </ion-card-header>

    <ion-card-content>
        <ion-grid>
        <ion-row class="ion-wrap ion-justify-content-center">
            <ion-col>    
                <ion-img 
                    src="https://docs-demo.ionic.io/assets/madison.jpg"
                    alt="The Wisconsin State Capitol building in Madison, WI at night">
                </ion-img>
            </ion-col>
            <ion-col>
               <p class="biography-text">
                    <ion-text color="dark">
                        Desenvolvedor de software e estudante de <ion-text color="tertiary">Ciência da Computação</ion-text> pela UniAmérica+
                            . Formado como <ion-text color="tertiary">Técnico em Informática</ion-text> pelo Colégio Eniac, sou apaixonado por tecnologia e inovação
                    </ion-text>
               </p>
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

<style scoped>
ion-card-title {
    font-size: 1.8rem;
}

ion-card {
    margin: 16px;
}

.biography-text {
    font-size: 1rem;
    text-align: start;
    line-height: 1.5;
    display: flex;
    justify-content: center;
    align-items: center;
}

ion-card-header {
    text-align: center;
}

 ion-card-title {
    font-size: 1.5rem;
    font-weight: bold;
}

ion-card-subtitle {
    font-size: 1rem;
    color: #666;
}

ion-img {
    border-radius: 30px;
    min-width: 300px;
    max-width: 600px;
}


ion-col {
    display: flex;
    justify-content: center;
    align-items: center;
}

@media (min-width: 950px) {
	.biography-text {
        font-size: 1rem;
        line-height: 1.5;
    }
}

@media (min-width: 1150px) {
	.biography-text {
        font-size: 1.3rem;
        line-height: 1.5;
    }
}

@media (min-width: 1350px) {
	.biography-text {
        font-size: 1.6rem;
        line-height: 1.5;
    }
}

@media (min-width: 1500px) {
	.biography-text {
        font-size: 1.8rem;
        line-height: 1.5;
    }
}
@media (min-width: 1630px) {
	.biography-text {
        font-size: 1.9rem;
        line-height: 1.5;
    }
}

@media (min-width: 1920px) {
	.biography-text {
        font-size: 2rem;
        line-height: 1.4;
    }
}

</style>