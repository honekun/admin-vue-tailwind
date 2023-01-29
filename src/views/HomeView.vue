<script setup>
import { ref, onMounted } from "vue";
import { mdiChartTimelineVariant, mdiGithub } from "@mdi/js";
import * as chartConfig from "@/components/Charts/chart.config.js";
import SectionMain from "@/components/SectionMain.vue";
import BaseButton from "@/components/BaseButton.vue";
import LayoutGuest from "@/layouts/LayoutGuest.vue";
import SectionTitleLineWithButton from "@/components/SectionTitleLineWithButton.vue";
import SectionBannerStarOnGitHub from "@/components/SectionBannerStarOnGitHub.vue";

const chartData = ref(null);

const fillChartData = () => {
  chartData.value = chartConfig.sampleChartData();
};

onMounted(() => {
  fillChartData();
});
</script>

<template>
  <LayoutGuest>
    <SectionMain>
      <SectionTitleLineWithButton
        :icon="mdiChartTimelineVariant"
        title="Home"
        main
      >
        <BaseButton
          href="https://github.com/justboil/admin-two-vue-tailwind"
          target="_blank"
          :icon="mdiGithub"
          label="Star on GitHub"
          color="contrast"
          rounded-full
          small
        />
      </SectionTitleLineWithButton>

      <SectionBannerStarOnGitHub class="mt-32 mb-6" />
    </SectionMain>
  </LayoutGuest>
</template>
