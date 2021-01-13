<template>
  <q-card class="col-5 q-my-lg q-ml-lg q-mr-md bg-grey-2" flat>
    <div>
      <q-img
        style="height: 220px"
        class="image-border"
        :src=imagem
      />
    </div>

    <q-card-section>
      <div class="text-h6 q-mt-sm q-mb-xs text-secondary">
        {{ title }}
      </div>
      <div class="text-caption text-grey">
        {{ text }}
      </div>
    </q-card-section>

    <q-card-actions class="justify-end">
      <q-btn outline rounded color="secondary" label="Ver Todos" :to="link1" />
      <q-btn outline rounded color="secondary" label="Leia Mais +" :to="link2" />

      <q-btn flat round color="secondary" size="sm" icon="fab fa-facebook-f"/>
      <q-btn flat round color="secondary" size="sm" icon="fab fa-google-plus-g"/>
      <q-icon color="secondary" size="xs" class="q-ml-md" name="fab fa-twitter" />
      <q-icon color="secondary" size="xs" class="q-ml-md" name="fab fa-pinterest-p" />
    </q-card-actions>
  </q-card>
</template>
<script>
export default {
  name: 'DemoCard',
  props: {
    imagem: {
      default: 'https://www.clubedaalice.com.br/wp-content/uploads/2020/05/pot-blog-1.jpg'
    },
    title: {
      type: String,
      default: 'Este é um titulo padrão'
    },
    text: {
      type: String,
      default: 'Este é um texto padrão'
    },
    link1: {
      type: String
    },
    link2: {
      type: String
    }
  }
}
</script>
<style lang="sass" scoped>
.image-border
  border-radius: 12px

</style>
