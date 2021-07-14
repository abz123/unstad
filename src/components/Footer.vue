<template>
    <footer class="footer">
        <div class="container">
            <span>{{theme.footer}}</span>
        </div>
    </footer>
</template>

<script>
import theme from '../../data/theme.json'

export default {
    data() {
        return {
          //settings: require("../../data/theme.json")
          theme
        }
    }
}
</script>

<style scoped>
.footer {
    font-size: 0.8rem;
    padding: 6rem 0;
}
</style>
