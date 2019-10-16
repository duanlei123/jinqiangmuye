<template>
    <div id="CompanyIntroduction">
        <div class="banner container-fuild text-center">关于我们</div>
        <div class="container">
            <div class="row CompanyIntroduction-container">
                <div class="col-xs-12 col-sm-12 col-md-6 wow zoomIn">
                    <img class="img-responsive center-block" src="@/assets/img/about_img.png">
                </div>
                <div class="col-xs-12 col-sm-12 col-md-6">
                    <h3>山西省朔州市晋强木业有限公司</h3>
                    <p class=".text-justify">朔州市晋强木业有限公司成立于2010年08月17日，注册资金32万人民币元，公司坐落于朔州，主要经营木门加工、销售。是山西朔州一带实力雄厚，设备技术先进的大型木制品制造企业</p>
                    <p class=".text-justify">作为中国木门企业，晋强一直以来致力于产品质量及研发工作，弘扬精益求精的工匠精神，不断提高木门及整木定制产品的质量水平，率先获得了欧盟CE认证。
                      晋强人艰苦奋斗、不断拼搏、开拓创新的光辉历程，见证着“争创一流企业”的美好梦想。并以此为新的起点，继续践行“务实创新，追求卓越”的企业精神，进一步完善企业科技创新机制，不断增强产品核心竞争力，成就企业宏伟蓝图！</p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import { WOW } from 'wowjs';
export default {
    name: 'CompanyIntroduction',
    data(){
        return{

        }
    },
    mounted(){
        var wow = new WOW();
        wow.init();
    }
}
</script>
<style scoped>
.banner{
    color: #fff;
    font-size: 30px;
    height: 150px;
    line-height: 150px;
    background-image: url('../assets/img/banner1.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: scroll;
    background-position: center center;
}
.row{
    margin-right: 0;
    margin-left: 0;
}
.CompanyIntroduction-container{
    padding: 100px 0;
    color: #808080;
    transition: all ease 0.5s;
}
.CompanyIntroduction-container>div>p{
    font-size: 14px;
    line-height: 2.5rem;
}
@media screen and (max-width: 997px){
    .CompanyIntroduction-container{
    padding: 10px 0;
    color: #808080;
}
}
</style>

