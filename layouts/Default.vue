<template>
  <div>
    <test-header></test-header>
    <test-main></test-main>
    <test-prefooter></test-prefooter>
    <test-footer></test-footer>
    <test-rights></test-rights>
  </div>
</template>

<script >
import TestHeader from '../components/test/TestHeader'
import TestMain from '../components/test/TestMain'
import TestPrefooter from '../components/test/TestPrefooter'
import TestFooter from '../components/test/TestFooter'
import TestRights from '../components/test/TestRights'
export default {
  components: {
    TestHeader,
    TestMain,
    TestPrefooter,
    TestFooter,
    TestRights
  }
}
</script>

<style lang="scss" src="../css/main.scss">

</style>
