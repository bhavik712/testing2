<template>
  <form-input :fieldProperties="ageField"></form-input>
</template>

<script>
import { FormInput } from "vue-component-lib-bhavik";
import "vue-component-lib-bhavik/style.css";
export default {
  name: "app",
  components: {
    FormInput,
  },
  data() {
    return {
      ageField: {
        label: "Age",
        name: "userAge",
        type: "number",
        placeholder: "Enter Your Age",
      },
    };
  },
};
</script>
