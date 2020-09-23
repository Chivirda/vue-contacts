<template>
  <div class="contact-list">
    <ContactCard />
    <ContactCard />
    <ContactCard />
    <ContactCard />
    <ContactCard />
    <ContactCard />
    <ContactCard />
    <ContactCard />
    <ContactCard />
  </div>
</template>

<script>
import ContactCard from '@/components/ContactCard.vue'

export default {
  name: 'Home',
  components: {
    ContactCard
  }
}
</script>
