<!--* 
* @description: 中国人民财产保险单
* @author: wp 
* @update: wp (2018-03-23 10:55) 
*-->
<template>
    <section>
        <section id="rm_print" class="bxd_rsb picc">
            <div class="bxd_header no-print">万网车辆盗抢保障服务系统保险函</div>
            <div class="bxd_center">
               <div class="bc">
                    <p class="no-print">因您自愿安装使用的四川万网鑫成信息科技有限公司（以下简称：万网）车辆盗抢保障服务系统向我公司投保了产品责任保险，为使您在使用该产品时更加安全放心，现将有关注意事项及操作办法声明如下：</p>
                   <p  class="no-print">一、投保人及被保险人：四川万网鑫成信息科技有限公司</p>
                   <p  class="no-print">二、保险标的：购买万网车辆盗抢保障服务系统并安装万网车载智能终端的合法车辆</p>
                   <p class="no-print">三、保险范围：中华人民共和国境内（不含港、澳、台）</p>
                   <p class="no-print">四、保险责任：
                    <p class="no-print text">1、在本保险函约定销售期限内购买万网车辆盗抢保障服务系统并安装万网车载智能终端的合法车辆，在本保险函约定服务期限内发生全车被盗抢、抢夺且60天内未找回的，由中国人民财产保险股份有限公司在约定的赔偿限额内按照车辆保险金额的100%进行赔偿（以同期市场行情价格为基准）。</p>
                    <p class="no-print text">2、在车辆全车被盗抢、抢劫期间内，被盗车辆遭受破坏需要修复的合理费用，由中国人民财产保险股份有限公司在约定的赔偿限额内按照车辆修复金额进行赔偿。</p>
                   </p>
                   <p class="no-print">五、除外责任：除上述保险责任外的其他事故，包括但不限于车辆部分零部件或附属设施被盗抢、抢劫；车辆被有关国家机关罚没、扣押；车主私自对万网车辆智能终端进行拆除、改装而导致的事故；车主因与他人的民事、经济纠纷而被抢劫、抢夺、扣押等事故；因不可抗因素导致万网车载智能终端损坏车主拒绝万网售后服务及车主恶意行为等均属于除外责任。</p>
                   <p class="no-print displayBlock">六、本保函销售期限自</p>
                   <p class="display">
                        <input type="text" v-model="ruleForm.yearFirstChange" class="year yxqDate" readonly><p class="display no-print">年</p>
                        <input type="text" v-model="ruleForm.monthChange" class="month yxqDate" readonly><p class="display no-print">月</p>
                        <input type="text" v-model="ruleForm.dateChange" class="month yxqDate" readonly><p class="display no-print">日零时起至占 </p>
                        <input type="text" v-model="ruleForm.yearLastChange" class="year yxqDate" readonly><p class="display no-print">年</p>
                        <input type="text" v-model="ruleForm.monthChange" class="month yxqDate" readonly><p class="display no-print">月</p>
                        <input type="text" v-model="ruleForm.dateChange" class="month yxqDate" readonly><p class="display no-print">日二十四时止。</p>
                   </p>
                   <p class="no-print displayBlock">七</p>
                   <p class="display">
                        <input type="text" v-model="ruleForm.yearFirst" class="year yxqDate" readonly><p class="display no-print">年</p>
                        <input type="text" v-model="ruleForm.monthFirst" class="month yxqDate" readonly><p class="display no-print">月占</p>
                        <input type="text" v-model="ruleForm.dateFirst" class="month yxqDate" readonly><p class="display no-print">日零时起至 </p>
                        <input type="text" v-model="ruleForm.yearLast" class="year yxqDate" readonly><p class="display no-print">年</p>
                        <input type="text" v-model="ruleForm.monthLast" class="month yxqDate" readonly><p class="display no-print">月</p>
                        <input type="text" v-model="ruleForm.dateLast" class="month yxqDate" readonly><p class="display no-print">日二十四时；在保险期限内如车辆转让，必须办理更名过户手续，自车辆过户次日起，新车主可享有本保险权利；保险责任在首次全车被盗抢、抢劫事故发生且无法找回，并由中国人民财产保险股份有限公司进行赔付后自动终止。</p>
                    </p>
                    <p class="no-print">八、理赔手续及相关义务：1、全车被盗抢后，车主应立即向当地县级以上公安部门报案，同时向万网服务中心（报案电话：028-85315020）报案，由万网在24小时内向保险公司报案；2、全车被盗窃、抢劫事故发生索赔时，车主须提供《机动车登记证书》、机动车来历凭证、公安机关报、立案证明、本保险函以及保险公司要求的其他相关资料。</p>
                    <p class="no-print">九、赔偿处理：1、全车被盗窃、抢劫且60天内未找回的，在中国人民财产保险股份有限公司确认索赔单证齐全有效后，由四川万网鑫成信息科技有限公司按约定赔付标准先行赔付，并签署权益转让书；2、中国人民财产保险股份有限公司在收到权益转让书后，在约定的赔偿限额内全额赔偿。</p>
                    <p class="no-print display">十、特别声明：若投保车辆为金融机构贷款所购，未还清金融机构贷款前，车主同意金融机构为第一受益人，并约定受赔偿金融机构为占位：</p>
                    <p class="display">
                        <input type="text" v-model="ruleForm.one" class="one yxqDate" readonly>
                    </p>
               </div>
            </div>   
            <div class="height"></div>
            <div class="bxd_djb table">
                <ul>
                    <li style="left:0;">
                        <label class="label_w no-print">车主姓名</label>
                        <span><input type="text" v-model="ruleForm.yxqDate2" class="yxqDate yxqDate2" readonly></span>
                    </li>
                    <li>
                        <label class="label_w no-print">身份证号</label>
                        <span><input type="text" v-model="ruleForm.yxqDate3" class="yxqDate yxqDate3" readonly></span>
                    </li>
                </ul>
                <ul>
                    <li>
                        <label class="label_w no-print">车架号</label>
                        <span><input type="text" v-model="ruleForm.yxqDate4" class="yxqDate yxqDate4" readonly></span>
                    </li>
                </ul>
                <ul>
                    <li>
                        <label class="label_w no-print">车牌号码</label>
                        <span><input type="text" v-model="ruleForm.yxqDate5" class="yxqDate yxqDate5" readonly></span>
                    </li>
                    <li>
                        <label class="label_w no-print">发动机号</label>
                        <span><input type="text"  v-model="ruleForm.yxqDate6" class="yxqDate yxqDate6" readonly></span>
                    </li>
                    <li>
                        <label class="no-print"></label>
                        <span><input type="text" v-model="ruleForm.yxqDate7" class="yxqDate yxqDate7" readonly></span>
                    </li>
                </ul>
                <ul>
                    <li>
                        <label class="no-print width">新车购置价人民币大写</label>
                        <span><input type="text" v-model="ruleForm.yxqDate8" class="yxqDate yxqDate8" readonly></span>
                        <span><input type="text" v-model="ruleForm.yxqDate9" class="yxqDate yxqDate9" readonly></span>
                    </li>
                    <li>
                        <label class="no-print width">保险金额人民币大写</label>
                        <span><input type="text" v-model="ruleForm.yxqDate10" class="yxqDate yxqDate8" readonly></span>
                        <span><input type="text" v-model="ruleForm.yxqDate11" class="yxqDate yxqDate9" readonly></span>
                    </li>
                    <li>
                        <label class="no-print width">万网车辆盗抢保障费用人民币大写</label>
                        <span><input type="text" v-model="ruleForm.yxqDate12" class="yxqDate yxqDate8" readonly></span>
                        <span><input type="text" v-model="ruleForm.yxqDate13" class="yxqDate yxqDate9" readonly></span>
                    </li>
                </ul>
            </div>

        </section>
        <el-col :span="24">
            <el-button type="primary" @click="printRs" style="margin-left:5px;float:right;">确认打印</el-button>
            <el-button style="margin-left:5px;float:right;" @click="printSuccess">打印完成</el-button>
        </el-col>
    </section>
</template>
<style type="text/css">
    .bxd_rsb{
        width: 794px;
        margin: 0 auto;
        padding: 23px 20px 0 20px;
    }
    .bxd_rsb input{
        color:#000;
        font-size: 16px;
        text-align: center;
    }
    .picc .text{text-indent: 2em;}
    .picc .yxqDate{
        width: 200px;
        border:0;
        border-bottom: 1px solid #555;
    }
    .picc .bxd_header{
        height: 110px;
        font-size: 40px;
        text-align: center;
    }
    .picc .bxd_center{
        font-size: 12px;
        line-height: 20px;
        overflow: hidden;
    }
    .picc .bxd_djb_header{
        height: 50px;
    }
    .picc .bxd_djb{
        height: 250px;
    }
    .picc .bxd_djb ul{
        line-height: 32px;
    }
    .picc .bxd_djb ul li{
        display: inline-block;
        position: relative;
        left: -30px;
    }
    .bc{
        width: 720px;
        height: 670px;
        overflow: hidden;
        line-height: 25px;
        margin-top: 5px;
    }
    .picc .table ul{line-height: 26px;}
    .picc .year{width: 40px;}
    .picc .month{width: 25px;}
    .picc .one{width: 560px;text-align: left;}
    .picc .width{width: 210px;display: inline-block;}
    .picc .displayBlock{display: inline-block;}
    .picc .display{display: inline;}
    .picc .height{height: 20px;}

    
    .picc .yxqDate2{
        position: absolute;
        bottom: 18px;
        left: 25px;
        width: 600px;
        text-align: left;
        font-size: 12px;
    }
    .picc .yxqDate3{
        width: 500px;
    }
    .picc .yxqDate4{
        width: 350px;
        position: relative;
        top: 2px;
    }
    .picc .yxqDate5{
        width: 135px;
        text-align: left;
    }
    .picc .yxqDate6{
        width: 190px;
        text-align: left;
    }
    .picc .yxqDate7{
        width: 240px;
        text-align: left;
        font-size: 12px;
    }
    .picc .yxqDate8{
        width: 290px;
        text-align: left;
    }
    .picc .yxqDate9{
        width: 100px;
    }
    .label_w {
        width: 80px;
        text-align: center;
        display: inline-block;
    }
    .label_w1{
        width: 207px;
    }
    @media print{  
        .picc .yxqDate{
            border:0;
            background-color: transparent;
        }
    }
</style>
<script>
    import '../../../../static/js/Print';
    import util from '../../../common/js/util';
    export default {
        // props:['flowData'],
        data() {
            return {
              ruleForm:{
                yearFirst:'',
                monthFirst:'',
                dateFirst:'',
                yearLast:'', 
                monthLast:'', 
                dateLast:'',
                yearFirstChange:'',
                monthChange:'',
                dateChange:'',
                yearLastChange:'', 
                one:'',
                yxqDate2:'',
                yxqDate3:'',
                yxqDate4:'',
                yxqDate5:'',
                yxqDate6:'',
                yxqDate7:'',
                yxqDate8:'',
                yxqDate9:'',
                yxqDate10:'',
                yxqDate11:'',
                yxqDate12:'',
                yxqDate13:'',
              },
              flowData:null,
            }
        },
        watch: {  
                flowData: {  
            　　　　handler(newValue, oldValue) {
                                this.getData(newValue);
            　　　　},  
            　　　　deep: true  
            　　}  
        },
        methods: {
            //确认打印
            printRs(){
                Print('#rm_print');
            },
            //打印完成
            printSuccess(){
                this.$emit('closeDialog');
            },
             // 得到数据
            getData(res){
                if(res.flowData.effectivedate){
                    // 保险期限
                    this.ruleForm.yearFirst = util.formatDate.format(new Date(res.flowData.effectivedate), 'yyyy-MM-dd').split('-')[0];
                    this.ruleForm.monthFirst = util.formatDate.format(new Date(res.flowData.effectivedate), 'yyyy-MM-dd').split('-')[1];
                    this.ruleForm.dateFirst = util.formatDate.format(new Date(res.flowData.effectivedate), 'yyyy-MM-dd').split('-')[2];
                    // 销售期限
                    this.ruleForm.yearFirstChange = new Date(res.flowData.effectivedate).getFullYear();
                    this.ruleForm.monthChange = '01';
                    this.ruleForm.dateChange = '01';
                    this.ruleForm.yearLastChange = new Date(res.flowData.effectivedate).getFullYear()+1;
                }
                if(res.flowData.expiredate){
                    this.ruleForm.yearLast = util.formatDate.format(new Date(res.flowData.expiredate), 'yyyy-MM-dd').split('-')[0];
                    this.ruleForm.monthLast = util.formatDate.format(new Date(res.flowData.expiredate), 'yyyy-MM-dd').split('-')[1];
                    this.ruleForm.dateLast = util.formatDate.format(new Date(res.flowData.expiredate), 'yyyy-MM-dd').split('-')[2];
                }
                this.ruleForm.one = res.flowData.bankid || res.flowData.bank_name;
                this.ruleForm.yxqDate2 = res.flowData.owner_name;
                this.ruleForm.yxqDate3 = res.flowData.owner_idcard;
                this.ruleForm.yxqDate4 = res.flowData.VehicleInfo_vin;
                this.ruleForm.yxqDate5 = res.flowData.VehicleInfo_licenseplatenum;
                this.ruleForm.yxqDate6 = res.flowData.VehicleInfo_enginenum;
                this.ruleForm.yxqDate7 = res.flowData.VehicleInfo_model_number || res.flowData.VehicleInfo_modle;
                this.ruleForm.yxqDate8 = util.changeMoneyToChinese(res.flowData.indemnitylimit);
                this.ruleForm.yxqDate9 = res.flowData.indemnitylimit;
                this.ruleForm.yxqDate10 = util.changeMoneyToChinese(res.flowData.indemnitylimit);
                this.ruleForm.yxqDate11 = res.flowData.indemnitylimit;
                this.ruleForm.yxqDate12 = util.changeMoneyToChinese(res.flowData.price);
                this.ruleForm.yxqDate13 = res.flowData.price;
            },
        },
      
    }
</script>