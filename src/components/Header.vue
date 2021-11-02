<template>
    <header>
        <nav class="container">
            <a href="/">
                <img src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/wdev.svg
" alt="WDev" id="logo">
            </a>

            <img src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/menu.svg
" alt="Abrir Menu" id="menu-button">
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
    
    header{
        background-color: var(--color-background-nav);
        width: 100%;
        height: 60px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    nav{
        display: flex;
        justify-content: space-between;
    }

    #logo{
        width: 130px;
    }

    #menu-button{
        width: 30px;
    }
</style>