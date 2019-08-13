<template>
    <div>
        <div id="slider" class="mui-slider">
				<div id="sliderSegmentedControl" class="mui-scroll-wrapper mui-slider-indicator mui-segmented-control mui-segmented-control-inverted">
					<div class="mui-scroll">
						<a class="mui-control-item mui-active" href="#item1mobile">
							推荐
						</a>
						<a class="mui-control-item" href="#item2mobile">
							热点
						</a>
						<a class="mui-control-item" href="#item3mobile">
							北京
						</a>
						<a class="mui-control-item" href="#item4mobile">
							社会
						</a>
						<a class="mui-control-item" href="#item5mobile">
							娱乐
						</a>
						<a class="mui-control-item" href="#item6mobile">
							科技
						</a>
						<a class="mui-control-item" href="#item6mobile">
							科技
						</a>
						<a class="mui-control-item" href="#item6mobile">
							科技
						</a>
						<a class="mui-control-item" href="#item6mobile">
							科技
						</a>
					</div>
				</div>
        </div>
    </div>
</template>

<script>
import mui from "../../lib/mui/js/mui.min.js";
export default {
    data() {
        return {}
    },
    created() {

    },
    mounted() {
        mui(".mui.scroll-wrapper").scroll({
            deceleration: 0.0005
        });
    },
    methods: {

    }
    
}
</script>

<style lang="scss" scoped>
* {
    touch-action: pan-y;
}

</style>
