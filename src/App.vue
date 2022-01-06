<script lang="ts">
import { HttpError } from '@uview-ui';

import Vue from 'vue';
export default Vue.extend({
  mpType: 'app',
  onLaunch() {
    const a: HttpError = { config: {}, errMsg: '' };
    console.log(a);

    console.log('App Launch');
  },
  onShow() {
    console.log('App Show');
  },
  onHide() {
    console.log('App Hide');
  },
});
</script>

<style>
/*每个页面公共css */
</style>
