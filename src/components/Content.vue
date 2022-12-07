<template>
     <div>
        <Navigation/>
      <v-card tile class="back" height="200">
      </v-card>
   <!-- infos -->
          <v-card tile flat class="mx-6 my-6">
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">1. Objet</h2>
                <p>Cette méthode de mesure de la densité est applicable aux liquides. L'application ne doit pas être utilisée pour : <br> Liquides qui corrodent l'aréomètre (par exemple : échantillons contenant plus de 2 % de fluorure libre ou une solution d'hydroxyde de sodium très concentrée).</p>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">2. Domaine d'application</h2>
                <p>Cette procédure s’applique au laboratoire Henkel Reghaia.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">3. Document de Référence</h2>
                 <v-list-item two-line>
                    <v-list-item-content>
                        <v-list-item-title><strong>- ISO 9000 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Principes essentiels et vocabulaire.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9001 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Exigences.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9002 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Lignes directrices pour l’application de l’ISO 9001:2015.</v-list-item-subtitle>
                    </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">4. Définitions et Abréviations</h2>
                <p>Non indiquées.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">5. Responsabilités et Autorités</h2>
                <p>Le technicien contrôle qualité est responsable sur l’analyse. <br> Le responsable laboratoire est responsable sur la validation des méthodes.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
            <h2 class="titre">6. Processus</h2>
                <v-list-item two-line>
                <v-list-item-content>
                    <v-list-item-title><strong>1 - Aperçu de la méthode</strong></v-list-item-title>
                    <v-list-item-subtitle>L'hydromètre est placé dans un liquide. Après décantation, le poids spécifique peut être lu sur l'échelle de l'hydromètre à la surface du liquide.</v-list-item-subtitle>
                    <v-list-item-title><strong>2 - Appareil</strong></v-list-item-title>
                        <v-list-item>
                            <v-list-item-content>
                                <v-list-item-title>- Thermostat avec une précision de température d'au moins +/- 0,1°C.</v-list-item-title>
                                <v-list-item-title>- Thermomètre, échelles de 0,1°C ou moins, calibré.</v-list-item-title>
                                <v-list-item-title>- Aréomètre(s) DIN 12791, 20 °C, classe H, précision de 0,001 g/cm3, étalonné.</v-list-item-title>
                                <v-list-item-title>- Pot hydromètre (cylindre en verre).</v-list-item-title>
                            </v-list-item-content>
                        </v-list-item>
                    <v-list-item-title><strong>3 - Procédure</strong></v-list-item-title>
                     <v-list-item>
                            <v-list-item-content>
                                <v-list-item-title>- Refroidir/chauffer le produit à la température spécifiée (normalement 20 °C).</v-list-item-title>
                                <v-list-item-title>- Remplissez le bocal propre et sec de l'aréomètre (cylindre en verre) avec suffisamment de produit pour faire flotter l'aréomètre.</v-list-item-title>
                                <v-list-item-title>- Placez lentement l'hydromètre approprié dans le bocal. Ne forcez pas l'hydromètre sous la surface.</v-list-item-title>
                                <v-list-item-title>- Laisser suffisamment de temps à l'hydromètre pour se stabiliser avant de lire. Veillez à ce que l'hydromètre ne touche pas la paroi du cylindre.</v-list-item-title>
                            </v-list-item-content>
                        </v-list-item>
                    <v-list-item-title><strong>4 - Calcul et rapport</strong></v-list-item-title>
                    <v-list-item>
                            <v-list-item-content>
                                <v-list-item-title>- Lire la valeur au 0,001 le plus proche.</v-list-item-title>
                                <v-list-item-title>- Reporter le résultat en densité (g/cm3 ou g/ml).</v-list-item-title>
                            </v-list-item-content>
                        </v-list-item>
                    <v-list-item-title><strong>5 - Précision</strong></v-list-item-title>
                    <v-list-item-subtitle>N / A</v-list-item-subtitle>

                     <v-list-item-title><strong>6 - Sécurité</strong></v-list-item-title>
                    <v-list-item-subtitle>N / A</v-list-item-subtitle>

                     <v-list-item-title><strong>7 - Remarques</strong></v-list-item-title>
                    <v-list-item-subtitle>Les instructions d'étalonnage et les données d'étalonnage doivent être disponibles. La méthode de test est basée sur DIN 51757 – 94.</v-list-item-subtitle>
                </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
           </v-card>
             <!-- Footer -->
            <v-footer flat bottom padless>
                <v-col><strong>PR SHEQ VR A.5-01– Procédure de Veille Réglementaire</strong> <br> <div class="primary--text"> Propriété exclusive de HENKEL Algérie Unité de Production Réghaia. <br> Toute reproduction intégrale ou partielle ainsi que son utilisation par, ou la communication à, des tiers, sans accord préalable écrit de l’auteur est illicite.</div> Le R-SMI est responsable de la gestion et l’application de cette procédure.</v-col>
            </v-footer>
    </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({

    }),
  }
</script>
<style scoped>
.confirm-card {
  overflow: hidden;
}
.titre{
    color: #ff0011;
}
.back{
    background: url('../../public/labo3.jpg');
}
</style>