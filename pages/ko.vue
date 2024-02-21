<template>
    <div>
        <h1>Component KO</h1>
        <!-- The comment below is causing the issue: -->
        <!-- <form-kit></form-kit> -->

        <p>Check console. You should see:</p>

        <ul>
            <li>Component KO - created</li>
            <li>Component KO - mounted</li>
        </ul>

        <p><strong>Component KO - setup</strong> is not shown in the console.</p>

        <nuxt-link to="/">← Retour</nuxt-link>
    </div>
</template>

<script>
export default {
    setup() {
        console.log('Component KO - setup');
    },
    created() {
        console.log('Component KO - created');
    },
    mounted() {
        console.log('Component KO - mounted');
    },
}
</script>
