<template>
<page>
 <div class="row">
<div class="col">
  </div>
<div class="col-4">
    <q-card
     class="cursor-pointer"
     @click="goTo('https://meet.google.com/jrx-revz-unh')"
     flat
    >
      <q-card-section>
        <div class="text-h6">meet</div>
      </q-card-section>
        <q-img src="~assets/meet.png" height="30vh"/>
      <q-card-section>
        <div class="text-h6"><a href="https://meet.google.com/jrx-revz-unh">https://meet.google.com/jrx-revz-unh</a></div>
      </q-card-section>
    </q-card>
</div>
<div class="col">
  </div>
  </div>
  <div class="row">
    <div class="col">
  </div>
    <div class="col-3 ">
     <q-card
     class="cursor-pointer"
     @click="goTo('https://github.com/mohamara-dev')"
     flat
    >
      <q-card-section>
        <div class="text-h6">github</div>
      </q-card-section>
        <q-img src="~assets/github.webp" height="30vh"/>
      <q-card-section>
        <div class="text-h6"><a href="https://github.com/mohamara-dev">https://github.com/mohamara-dev</a></div>
      </q-card-section>
    </q-card>
    </div>
    <div class="col-3">
      <q-card
     class="cursor-pointer"
     @click="goTo('https://aparat.com/mohamara.dev')"
     flat
    >
      <q-card-section>
        <div class="text-h6">aparat</div>
      </q-card-section>
        <q-img src="~assets/aparat.png" height="30vh" />
      <q-card-section>
        <div class="text-h6"><a href="https://aparat.com/mohamara.dev">https://aparat.com/mohamara.dev</a></div>
      </q-card-section>
    </q-card>
    </div>
<div class="col">
  </div>
    </div>
    </page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage',
  data() {
    return {
      data:'data1'
    }
  },
  methods: {
    goTo(url){
      location.assign(url)
    }
  }
})
</script>
