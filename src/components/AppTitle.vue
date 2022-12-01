<template>
    <div>
        <h1>{{ titlePage() }}</h1>
    </div>
</template>

<script>
export default {
    data() {
        return {
            user: {
                title: "La mia prima app con Vite!"
            }
        };
    },
    methods: {
        titlePage() {
            return this.user.title;
        }
    }
};
</script>