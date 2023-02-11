<template>
    <v-container fluid class="center-screen">
        <v-card
            v-model="dialog"
            width="350"
            height="auto"
        > 
            <v-container >
                <div  justify="center" align="center">
                    <v-img src="/iconos/acoount.png" width="100"/>
                    <v-text-field
                        color="purple darken-2"
                        label="Nombre Usuario"
                        required
                    />
                    <v-text-field
                        color="purple darken-2"
                        label="Contraseña"
                        required
                    />
                    <v-btn color="primary">
                        Iniciar Sesion
                    </v-btn>
                </div>
            </v-container>
        </v-card>
    </v-container>
</template>
<style lang="scss">
  .center-screen {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
  }
</style>
<script>
export default {
    data() {
        return{
            dialog: true
        }
    },
}
</script>