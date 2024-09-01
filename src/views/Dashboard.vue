<template>
  <div class="row g-5 gx-xxl-8">
    <div class="col-xxl-4">
      <ListWidget2 widget-classes="card-xl-stretch mb-xl-8"></ListWidget2>
    </div>
    <div class="col-xxl-8">
      <TableWidget5
        widget-classes="card-xxl-stretch mb-5 mb-xxl-8"
      ></TableWidget5>
    </div>
  </div>
  <!--end::Dashboard-->
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TableWidget5 from "@/components/widgets/tables/Widget5.vue";
import ListWidget2 from "@/components/widgets/lists/Widget2.vue";

export default defineComponent({
  name: "main-dashboard",
  components: {
    TableWidget5,
    ListWidget2,
  },
});
</script>
