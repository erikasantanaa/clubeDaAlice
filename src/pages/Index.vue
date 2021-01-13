<template>
  <q-page class="bg-grey-2">
    <div class="row top-center flex-center bg-secondary justify-center" style="height: 350px ">
      <q-img style="height: 350px" src="../assets/BANNER-SITE.jpg" />
    </div>

    <div class="row justify-center">
      <!-- props-->
      <demo-card :imagem="img1" :title="titulo1" :text="texto1" :link1="link1" :link2="link2" />

      <q-card flat class=" col-5 q-my-lg q-mr-lg q-ml-md bg-grey-2">
        <q-card-section class="q-pa-none">
          <div class="q-col-gutter-sm row">

            <div class="col-6 flex justify-end">
              <q-img class="image-border square-card custom-image-pink" src="../assets/image-card-2a.jpg" >
                <div class="absolute-full flex flex-center">
                  <q-icon name="facebook" class="q-mt-md" size="md" />
                  <p class="text-bold text-center" style="font-size: 10px">
                    #Healthy # ilovelocalfruits Make every day your day with
                    pure squeezed Vitamin C that helps support a healthy immune
                    @clubedaaliceoficial
                  </p>
                </div>
              </q-img>
            </div>

            <div class="col-6 flex justify-start">
              <q-img class="image-border square-card" src="../assets/image-card-2a.jpg" >
                <p class="absolute-bottom text-bold text-white q-ml-sm">
                  Título da Tag Facebook
                </p>
                <q-icon class="absolute-bottom-right q-my-md q-mr-sm text-white" size="sm" name="fab fa-facebook" />
              </q-img>
            </div>

            <div class="col-6 justify-end flex">
              <q-img class="image-border square-card custom-image-pink" src="../assets/book1.jpg" >
                <div class="absolute-full flex flex-center">
                  <q-icon name="fab fa-instagram" class="q-mt-md" size="md" />
                  <p class="text-bold text-center" style="font-size: 10px">
                    #Healthy # ilovelocalfruits Make every day your day with
                    pure squeezed Vitamin C that helps support a healthy immune
                    @clubedaaliceoficial
                  </p>
                </div>
              </q-img>
            </div>

            <div class="col-6 flex justofy-start">
              <q-img class="image-border square-card" src="../assets/book2.jpg">
                <p class="absolute-bottom text-bold text-white q-ml-sm">
                  Título da Tag Facebook
                </p>
                <q-icon class="absolute-bottom-right q-my-md q-mr-sm text-white" size="sm" name="fab fa-instagram" />
              </q-img>
            </div>
          </div>
        </q-card-section>
      </q-card>
    </div>
    <div class="q-mx-xl">
      <q-separator spaced inset />
    </div>

    <div class="row justify-center">
      <q-card class="border col-10 q-my-lg q-mx-xl">
        <q-img style="width: 100%" src="../assets/banner-aliceplay.jpg" />
      </q-card>
    </div>

    <div class=" row q-mt-md">
      <div class="text-h5 text-bold text-secondary" style="margin-left: 8rem">
        Clube da Alice na TV
      </div>
    </div>

    <div class="row justify-center">
      <q-card class=" col-4 q-my-lg q-ml-lg q-mr-md bg-cyan-1">
        <img src="../assets/print-alice-tv.jpg" />

        <q-card-section>
          <div class="text-h6 text-secondary">Título do Vídeo</div>
          <div class=" text-caption text-grey-7">
            Mussum Ipsum, cacilds vidis litro abertis. Suco de cevadiss deixa as
            pessoas mais interessantis. Casamentiss faiz malandris se pirulitá.
            Todo mundo vê os porris que eu tomo, mas ninguém vê os tombis que eu levo!
          </div>
        </q-card-section>

        <q-separator inset />

        <q-card-section class="q-pt-sm row text-center text-pink">
          <div class="col">
            <q-icon color="blue-9" name="fas fa-thumbs-up" />
            <q-icon class="q-mx-sm" color="red" name="fas fa-heart" /> 88
          </div>

          <div class="col">
            <q-icon class="q-mx-sm" color="grey-7" name="fas fa-comment" />
            Comentários
          </div>

          <div class="col">
            <q-icon class="q-mx-sm" color="grey-7" name="far fa-eye" />6.7 mil
            visualizações
          </div>
        </q-card-section>
      </q-card>

      <div class="col-5 q-my-lg q-ml-lg q-mr-md">
        <q-card class="bg-cyan-1">
          <q-card-section horizontal>
            <q-img class="col-5" src="../assets/produzir-conteudo-banner.jpg" />
            <q-card-section class="text-grey-7">
              <p class="text-secondary text-bold">Título do Video</p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              Necessitatibus aspernatur dolore suscipit error nesciunt officiis,
              praesentium id. Laudantium culpa sint reiciendis quasi natus
              expedita assumenda velit quibusdam, quis possimus! Illo!
            </q-card-section>
          </q-card-section>
          <q-card-section class="q-pt-sm row text-center text-pink">
            <div class="col">
              <q-icon color="blue-9" name="fas fa-thumbs-up" />
              <q-icon class="q-mx-sm" color="red" name="fas fa-heart" /> 88
            </div>
            <div class="col">
              <q-icon class="q-mx-sm" color="grey-7" name="fas fa-comment" />
              Comentários
            </div>
            <div class="col">
              <q-icon class="q-mx-sm" color="grey-7" name="far fa-eye" />6.7 mil
              visualizações
            </div>
          </q-card-section>
        </q-card>

        <q-card class="bg-cyan-1 q-mt-lg">
          <q-card-section horizontal>
            <q-img class="col-5" src="../assets/produzir-conteudo-banner.jpg" />
            <q-card-section class="text-grey-7">
              <p class="text-secondary text-bold">Título do Video</p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              Necessitatibus aspernatur dolore suscipit error nesciunt officiis,
              praesentium id. Laudantium culpa sint reiciendis quasi natus
              expedita assumenda velit quibusdam, quis possimus! Illo!
            </q-card-section>
          </q-card-section>
          <q-card-section class="q-pt-sm row text-center text-pink">
            <div class="col">
              <q-icon color="blue-9" name="fas fa-thumbs-up" />
              <q-icon class="q-mx-sm" color="red" name="fas fa-heart" /> 88
            </div>
            <div class="col">
              <q-icon class="q-mx-sm" color="grey-7" name="fas fa-comment" />
              Comentários
            </div>
            <div class="col">
              <q-icon class="q-mx-sm" color="grey-7" name="far fa-eye" />6.7 mil
              visualizações
            </div>
          </q-card-section>
        </q-card>
      </div>
    </div>

    <div class="row justify-center">
      <q-btn
        rounded
        class="col-1 q-my-lg"
        outline
        color="secondary"
        label="Ver todos"
      />
    </div>
  </q-page>
</template>

<script>
import DemoCard from 'src/components/DemoCard.vue'
export default {
  name: 'PageIndex',
  components: {
    DemoCard
  },
  data () {
    return {
      img1: 'https://www.clubedaalice.com.br/wp-content/uploads/2020/05/pot-blog-1.jpg',
      titulo1: 'Empreendedorismo do batom',
      texto1: 'Mussum Ipsum, cacilds vidis litro abertis. Suco de cevadiss deixa as pessoas mais interessantis. Casamentiss faiz malandris se pirulitá.Todo mundo vê os porris que eu tomo, mas ninguém vê os tombis que eu levo!',
      link1: '/ShortNews',
      link2: '/NewsPapers'
    }
  }
}
</script>
<style lang="sass" scoped>
.custom-image-pink
  filter: hue-rotate(300deg) saturate(300%)

.image-border
  border-radius: 12px

.border
  border-radius: 15px

.square-card
  width: 200px
  height: 200px
</style>
