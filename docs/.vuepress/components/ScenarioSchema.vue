<template>
  <JsonSchema :schema="schema"/>
</template>
<script>
import { default as schema } from "../../../lib/urbanopt/reporting/default_reports/schema/scenario_schema.json";
export default {
  name: "ScenarioSchema",
  data() {
    return { schema };
  }
};
</script>
