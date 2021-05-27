<script>
    import Swiper from "swiper/esm/svelte/swiper.svelte";
    import SwiperSlide from "swiper/esm/svelte/swiper-slide.svelte";
    import SwiperCore, { Navigation, Pagination } from "swiper";
    SwiperCore.use([Navigation, Pagination]);
    import "swiper/swiper-bundle.css";
</script>

<Swiper style="width: 300px" slidesPerView={1} navigation>
    <SwiperSlide>foo</SwiperSlide>
    <SwiperSlide>bar</SwiperSlide>
</Swiper>