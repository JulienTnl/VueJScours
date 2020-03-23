<template>
    <div>
    <input v-model="texte"  placeholder="Rentrer le texte"/>

    {{texte|majusculesTexte}}

    </div>
</template>
<script>
export default {
    name: 'Majuscules',
    data: function() {
        return {
            texte: "text",
        }
    },
 filters: {
     majusculesTexte: function(texte) {
        return texte.toUpperCase()
        }
    }
}
</script>

<style>

</style>