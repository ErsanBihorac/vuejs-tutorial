<template>
    <h2>
        {{ greeting }} {{ name }} a.k.a. {{ heroName }}
    </h2>
</template>

<script>
export default {
    name: 'GreetComponent',
    props: ['name', 'greeting', 'heroName']
}
</script>

<style scoped></style>