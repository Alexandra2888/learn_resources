<template>
<h2>Add Resource</h2>
</template>

<script>
export default {
    data() {
        return {
            selectedTab: 'stored-resources'
        };
    },
    methods: {
        setSelectedTab(tab) {
            this.selectedTab = tab;
        }
    }
}
</script>