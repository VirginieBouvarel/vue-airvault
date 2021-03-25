<template>
  <div class="contact">
    <h2>Nous contacter</h2>
    <div class="contact__content">
        <div class="contact__box">
        <i class="contact__icon fas fa-phone-alt"></i>
        <p>(+33)6.12.34.56.78</p>
        </div>
        <div class="contact__box">
        <i class="contact__icon fas fa-clock"></i>
        <p>Du Lundi au vendredi</p>
        <p>08:00-12:30 / 13:30-18:00</p>
        </div>
        <div class="contact__box">
        <i class="contact__icon fas fa-envelope"></i>
        <p>contact@airvault.com</p>
        </div>
    </div>

  </div>
</template>


<style lang="scss" scoped>
.contact {
    padding:3rem 1rem;
    font-size:15px;
    text-align:center;

    h2 {
    color: #45C5FF;
    border-bottom:2px solid #45C5FF;
    max-width:355px;
    margin:0 auto 6rem;
    padding-bottom:1rem;
    }

    &__content {
        margin-top:2rem;
    }

    &__box {
        width:100%;
        text-align:center;
        line-height:2;
        margin-bottom:4rem;

        p {
            margin:0 0 1rem 0;
        }
    }

    &__icon {
        color:#45C5FF;
        font-size:2rem;
        margin-bottom:2rem;
    }
}

@media screen and (min-width: 800px) {
    .contact {
        &__content {
            width:80%;
            margin: 0 auto;
            display:flex;
            align-items:flex-start;
            justify-content: space-between;
        }
    }
}

</style>