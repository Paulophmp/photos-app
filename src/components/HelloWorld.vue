<template>
    <v-card
            class="mx-auto"
            max-width="400"
    >
        <v-img
                class="white--text"
                height="200px"
                src="https://i.ytimg.com/vi/Hlz7ass3gRk/maxresdefault.jpg"

        >
            <v-card-title class="align-end fill-height">Top 10 Australian beaches</v-card-title>
        </v-img>

        <v-card-text>
            <span>Number 10</span><br>
            <span class="text--primary">
        <span>Whitehaven Beach</span><br>
        <span>Whitsunday Island, Whitsunday Islands</span>
      </span>
        </v-card-text>

        <v-card-actions>
            <v-btn
                    text
                    color="orange"
            >
                Share
            </v-btn>
            <v-btn
                    text
                    color="orange"
            >
                Explore
            </v-btn>
        </v-card-actions>
    </v-card>
</template>

<script>
    export default {
        name: 'Inicio',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h3 {
        margin: 40px 0 0;
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    li {
        display: inline-block;
        margin: 0 10px;
    }
    a {
        color: #42b983;
    }
</style>
