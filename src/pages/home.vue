<template>
  <div class="home">
            <Ban></Ban>
           <div class="a">
               <p>
                   11111111111
               </p>

           </div>
    </div>
</template>

<script>
import Banner from "../components/Banner"
export default {
name:"",
data() {
return {

}
},
components:{
    Ban:Banner
},
//生命周期 - 创建完成（访问当前this实例）
created() {

},
//生命周期 - 挂载完成（访问DOM元素）
mounted() {

}
}
</script>
<style scoped>
/* @import url(); 引入css类 */
.home{
    .a{
        width:200px;
        height:200px;
        background: #aaa;
        p{
            color:#f00
        }
    }
}
</style>