<template>
    <div>
        <h1>Component OK</h1>
        <!-- The comment below is not causing any issue: -->
        <!-- <random-unexisting-component></random-unexisting-component> -->

        <p>Check console. You should see:</p>

        <ul>
            <li>Component OK - setup</li>
            <li>Component OK - created</li>
            <li>Component OK - mounted</li>
        </ul>

        <nuxt-link to="/">← Retour</nuxt-link>
    </div>
</template>

<script>
export default {
    setup() {
        console.log('Component OK - setup');
    },
    created() {
        console.log('Component OK - created');
    },
    mounted() {
        console.log('Component OK - mounted');
    },
}
</script>
