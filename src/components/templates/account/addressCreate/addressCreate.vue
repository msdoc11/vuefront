<template>
  <section class="vf-t-account-address-create">
    <vf-m-card class="mb-0" no-body>
      <vf-m-card-body class="px-md-5 py-5">
        <vf-o-address-create-form :countries="countries" :zones="zones" />
      </vf-m-card-body>
    </vf-m-card>
  </section>
</template>
<script>
export default {
  props: {
    countries: {
      type: Object,
      default() {
        return null;
      }
    },
    zones: {
      type: Object,
      default() {
        return null;
      }
    }
  }
};
</script>
