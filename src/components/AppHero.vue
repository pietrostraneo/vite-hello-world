<script>
import AppTitle from './AppTitle.vue';
export default {
    components: {
        AppTitle
    },
    data() {
        return {
            subtitle: "Ho installato bootstrap con npm, l'ho importato sia su app che sui component ma non riesco a farlo funzionare."
        }
    },
}
</script>
<template lang="">
    <div>
        <div class="jumbotron">
        <AppTitle />
        <p>Sto provando a fare un jumbotron carino ma non ci riesco! &#128526</p>
        <hr>
        <p>{{subtitle}}</p>
        <p>
            <button><a href="http://www.google.com/">Ora vai su google &#128150</a></button>
        </p>
        </div>
    </div>
</template>
<style lang="">
    
</style>