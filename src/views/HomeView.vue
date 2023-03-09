<template>
  <div class="home">
    <HeroArea/>
    <FeaturedCategory/>
    <TrendingProduct/>
    <BannerSection/>
    <SpecialOffer/>
    <HomeProduct/>
    <BrandSection/>
    <BlogSection/>
    <ShippingInfo/>
  </div>
</template>

<script>
import HeroArea from '@/components/home/HeroArea.vue';
import FeaturedCategory from '@/components/home/FeaturedCategory.vue';
import TrendingProduct from '@/components/home/TrendingProduct.vue';
import BannerSection from '@/components/home/BannerSection.vue';
import SpecialOffer from '@/components/home/SpecialOffer.vue';
import HomeProduct from '@/components/home/HomeProduct.vue';
import BrandSection from '@/components/home/BrandSection.vue';
import BlogSection from '@/components/home/BlogSection.vue';
import ShippingInfo from '@/components/home/ShippingInfo.vue';

export default {
  name: 'HomeView',
  components: {HeroArea,FeaturedCategory,TrendingProduct,BannerSection,SpecialOffer,HomeProduct,BrandSection,BlogSection,ShippingInfo}
}
</script>
