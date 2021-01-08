<template>
  <div>
    <h2>Home</h2>
    <Transactions></Transactions>
    <EditTransactions></EditTransactions>
  </div>
</template>

<script>
import Transactions from '@/components/Transactions.vue'
import EditTransactions from '@/components/EditTransactions'

export default {
  components: {
    EditTransactions,
    Transactions
  }
}
</script>

<style scoped>

</style>
