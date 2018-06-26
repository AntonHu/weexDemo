<template>
	<div>
		<wxc-cell title='手机号'>
			<input slot="value" type='number' placeholder="666"/>
		</wxc-cell>
		<wxc-cell title='验证码'>
			<
		</wxc-cell>
	</div>
</template>

<script>
  import Nat from 'natjs'
  import {wxcCell,WxcButton } from 'weex-ui'
  
  export default {
	components: { wxcCell,WxcButton  },
    methods: {
      wxcCellClicked (e) {
//      Nat.alert(e)
      }
    }
  };
</script>