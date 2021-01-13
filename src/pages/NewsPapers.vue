<template>
  <q-page class="bg-grey-2">
    <div class="row justify-center">
      <q-card class="col-6 q-my-lg  bg-grey-2" flat>
        <q-card-section>
          <div class=" text-secondary text-center text-h1 q-pa-lg">
            Empreendedorismo do batom
          </div>
          <div class="q-ma-xl">
            <q-img class="rounded-borders" src="../assets/batom-valorizar-boca.jpg" style="width: 100%" />
          </div>

          <div class="text-caption text-grey">
            <p>Mussum Ipsum, cacilds vidis litro abertis. Cevadis im ampola pa arma uma
            pindureta. Todo mundo vê os porris que eu tomo, mas ninguém vê os tombis
            que eu levo! Mauris nec dolor in eros commodo tempor. Aenean aliquam molestie
            leo, vitae iaculis nisl. Detraxit consequat et quo num tendi nada.</p>

            <p>Nullam volutpat risus nec leo commodo, ut interdum diam laoreet.
            Sed non consequat odio. Manduma pindureta quium dia nois paga.
            Suco de cevadiss deixa as pessoas mais interessantis.
            Mais vale um bebadis conhecidiss, que um alcoolatra anonimis.</p>

            Praesent malesuada urna nisi, quis volutpat erat hendrerit non.
            Nam vulputate dapibus. Posuere libero varius. Nullam a nisl ut ante
            blandit hendrerit. Aenean sit amet nisi. Sapien in monti palavris qui
            num significa nadis i pareci latim. Praesent vel viverra nisi.
            Mauris aliquet nunc non turpis scelerisque, eget.
          </div>
          <!-- espaço -->
          <div class="q-mx-xl">
            <q-separator spaced inset />
          </div>
          <!-- card dicas de maquiagem -->
          <div>
          <q-img style="height: 220px " class="rounded-borders" src="../assets/banner-make.jpg" />
          </div>
        </q-card-section>
          <!-- icons -->
        <q-card-actions class="justify-end">

          <q-icon color="secondary" size="xs" class="q-ml-md" name="fab fa-facebook-f" />

          <q-icon color="secondary" size="xs" class="q-ml-md" name="fab fa-google-plus-g" />
          <q-icon color="secondary" size="xs" class="q-ml-md" name="fab fa-twitter" />
          <q-icon color="secondary" size="xs" class="q-ml-md" name="fab fa-pinterest-p" />
        </q-card-actions>
      </q-card>
    </div>
    <!-- espaço -->
    <div class="q-mx-xl">
      <q-separator spaced inset />
    </div>
    <!-- botao -->
    <div class="row justify-center">
      <q-btn rounded class="col-1 q-my-lg" outline color="secondary" label="Voltar" to="/" />
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
<style lang="sass" scoped>

</style>
