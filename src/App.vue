<template>
    <NavBarName />
    <TableName />
</template>

<script>
import NavBarName from './components/NavBar.vue'
import TableName from './components/Table.vue'

export default {
    name: 'App',
    components: {
        NavBarName,
        TableName
    }
}
</script>
