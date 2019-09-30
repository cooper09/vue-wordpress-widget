<template>
  <v-container fluid>
    <v-row align="center">
      <v-col class="d-flex" cols="12" sm="6">
        <v-select
          :items="items"
          label="Get Quote"
        ></v-select>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
 data: () => ({
      items: [
        'Custom Home Build',
        'Office Renovation',
        'Solar Installation',
        'Restaurant Renovation',
        'Kitchen Remodel',
        'Bathroom Remodel',
        'Whole Home Remodel',
        'Medium Multi-Family Remodel',
        'Electrical Work',
        'Hardwood Flooring'],
    }),
};//export default
</script>
