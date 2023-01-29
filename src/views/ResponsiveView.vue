<script setup>
import SectionTitle from "@/components/SectionTitle.vue";
import SectionMain from "@/components/SectionMain.vue";
import LayoutAuthenticated from "@/layouts/LayoutAuthenticated.vue";
</script>

<template>
  <LayoutAuthenticated>
    <SectionTitle first>Mobile & Tablet</SectionTitle>

    <SectionMain>
      <div
        class="md:w-10/12 shadow-2xl md:mx-auto rounded-3xl border-8 border-white overflow-hidden"
      >
        <img
          src="https://honekun.com.mx/proyects/admin-two/placeholder_admin_two.png"
          class="block"
        />
      </div>
    </SectionMain>

    <SectionTitle>Small laptop 1024px</SectionTitle>

    <SectionMain>
      <div
        class="md:w-10/12 shadow-2xl md:mx-auto rounded-3xl border-8 border-white overflow-hidden"
      >
        <img
          src="https://honekun.com.mx/proyects/admin-two/placeholder_admin_two.png"
          class="block"
        />
      </div>
    </SectionMain>

    <SectionMain>
      <div
        class="md:w-10/12 shadow-2xl md:mx-auto rounded-3xl border-8 border-white overflow-hidden"
      >
        <img
          src="https://honekun.com.mx/proyects/admin-two/placeholder_admin_two.png"
          class="block"
        />
      </div>
    </SectionMain>

    <SectionTitle>Laptop & desktop</SectionTitle>

    <SectionMain>
      <div
        class="md:w-10/12 shadow-2xl md:mx-auto rounded-3xl border-8 border-white overflow-hidden"
      >
        <img
          src="https://honekun.com.mx/proyects/admin-two/placeholder_admin_two.png"
          class="block"
        />
      </div>
    </SectionMain>
  </LayoutAuthenticated>
</template>
