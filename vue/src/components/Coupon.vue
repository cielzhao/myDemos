<template>
	<div class="wrapper">
		<Header></Header>
		<Nav></Nav>
		<div id="main">
			<div class="container">
				<CouponCate></CouponCate>
				<CouponSort></CouponSort>
				<CouponLive></CouponLive>
			</div>
		</div>
		<Footer></Footer>
	</div>
</template>

<script>
import Header from './Header'
import Nav from './Nav'
import CouponCate from './CouponCate'
import CouponSort from './CouponSort'
import CouponLive from './CouponLive'
import Footer from './Footer'

export default {
  name: 'Index',
  components: {
    'Header': Header,
    'Nav': Nav,
    'CouponCate': CouponCate,
    'CouponSort': CouponSort,
    'CouponLive': CouponLive,
    'Footer': Footer,
  },
  computed:{

  },
  methods:{
  }
}
</script>

<style>

</style>