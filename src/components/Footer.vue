<template>
    <div class="feet">
        <h4>Abdul-Azeez Kemp | Web Developer <ion-icon name="code-slash-outline"></ion-icon></h4>
        <div class="footer-bar">
            <a href="https://github.com/abdulkemp" class="git"><ion-icon name="logo-github"></ion-icon></a>
            <a href="https://www.facebook.com/profile.php?id=100085081810832" class="face"><ion-icon name="logo-facebook"></ion-icon></a>
            <a href="https://www.linkedin.com/in/abdul-azeez-kemp-3b468121a/" class="link"><ion-icon name="logo-linkedin"></ion-icon></a>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Footer'
    }
</script>

<style scoped>
.feet{
    display:block;
    background-color: transparent;
    color:white;
    justify-content: center;
    align-content: center;
    /* padding-left: 40%; */
    /* margin-top: 40px; */
}
.footer-bar{
    font-size: 20px;
    display: flex;
    justify-content: center;
    align-content: center;
    /* padding-left: 40%; */
}
</style>