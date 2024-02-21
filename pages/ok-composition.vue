<template>
    <div>
        <h1>Component OK (composition)</h1>
        <!-- <form-kit></form-kit> -->

        <p>Check console. You should see:</p>

        <ul>
            <li>Component OK (composition) - setup</li>
            <li>Component OK (composition) - mounted</li>
        </ul>

        <nuxt-link to="/">← Retour</nuxt-link>
    </div>
</template>

<script setup>
console.log('Component OK (composition) - setup');

onMounted(() => {
    console.log('Component OK (composition) - mounted');
});
</script>
