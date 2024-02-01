<template >
    <div>
        <carousel/>
    </div>
    <!-- <div class=" row mt-5 mb-5 p-3 holder">
       <div class="col-12 d-flex justify-content-center first">

<div class="col-4 wrapper-top"></div>
<div class="col-4 wrapper-top"></div>
<div class="col-4 wrapper-top"></div>
       </div>
       <div class="col-12 d-flex justify-content-center second">

        <div class="col-4 wrapper-middel one d-flex justify-content-center">
            <div class="a"></div>
            <div class="b"></div>
        </div>
<div class="col-4 wrapper-middel center">
    <h2>BENTO USING BOOTSRAP</h2>
</div>
<div class="col-4 wrapper-middel three d-flex justify-content-center">
    <div class="c"></div>
    <div class="d"></div>
</div>
       </div>
       <div class="row last">
        <div class="col-12 d-flex justify-content-center him">
            <div class="col-4 uno"></div>
            <div class="col-4 dos"></div>
            <div class="col-4 dres"></div>
        </div>
       </div>
    </div> -->
</template>
<script>
import carousel from '../components/carouselComp.vue';
export default {
    components:{
        carousel,
    }
}
</script>
<style scoped>
    .row{
        /* border: 1px solid white; */
        height:600px;
        transform: translateY(300px) translateX(300px);
        width: 950px !important;
    }
    .wrapper-top {
        border: 1px solid white;
        margin-top: 10px;
        margin-left: 3px;
        height:50px;
        border-radius: 10px;


    }
    .first,.last{
        height: 0px !important;

    }
    .second{
        transform: translateY(-200px);
        height: 50px;
    }
    .wrapper-middel {
        border: 1px solid white;
        margin-top: 10px;
        margin-left: 3px;
        height:50px;
        border-radius: 10px;


    }
    .first{
        transform: translateY(-98px);
    }
    .one,.three{
        padding-bottom: 250px;
        border: none;
    }
    
    .center{
padding-bottom: 300px;
 justify-content: center;
 align-items: center;   
 background-color: orangered; 


}
.a, .b,.c,.d{
    border:1px solid white;
    margin-left: 3px;
    width: 50%;
    border-radius: 10px;
    height: 250px;
    background: yellowgreen;
}
.last{
    transform: translateX(5px) translateY(-90px);
    padding-bottom: 50px;
}
.uno,.dos,.dres{
    border: 1px solid white;
    margin-left: 3px;
    border-radius: 10px;
}

.dos{
    transform: translateX(5px);

    padding-bottom: 50px;
    height: 50px !important;
}
.dres{
    transform: translateX(15px) translateY(-53px) !important;
height: 104px;

}
.uno{
    transform: translateY(-53px);
}
.first>.col-4{
    background: burlywood !important;
}
.him>.col-4{
    background: burlywood !important;
}

</style>