<template>
    <div>
        <headerNav title="我的优惠券"/>
        <van-cell-group>
        <van-field
            center
            clearable
            placeholder="请输入短信验证码"
        >
            <van-button slot="button" size="small" type="primary">兑换</van-button>
        </van-field>
        </van-cell-group>
        <van-tabs >
            <van-tab title="未使用">
                <ul>
                    <li class="couponitem">
                        <div class="couponTop">
                            <div class="cpnamount">
                                <div class="amountWrap">
                                    <div class="amount">
                                            <span class="amountSign">¥</span><span class="amountNum">60</span><!--Regular if10-->                    
                                    </div>
                                    <div class="condition">
                                        <span>无金额门槛</span>
                                    </div>
                                </div>
                            </div>
                            <div class="couponInfoWrap">
                                <div class="cpninfo">
                                    <div class="detail">
                                    <span class="name">购物车专享优惠券60</span></div>
                                        <div class="validity">
                                            <span>2018.09.05-2018.09.28
                                                <van-button type="danger" size="mini">立即使用</van-button>
                                            </span>
                                        </div>
                                        
                                    
                                </div>
                            </div>
                        </div>
                        <div class="couponMid ">
                            <span>指定商品适用</span>
                            <van-icon name="arrow" class="down" />
                        </div>

                        <div class="info" >
                            <div class="text"><span>以下商品适用：<br>SAINT LAURENT PARIS 圣罗兰 ...<br>特例商品不可使用优惠券</span></div>
                            <div class="text">
                            </div>
                        </div>
                    </li>
                    <li class="couponitem show">
                        <div class="couponTop">
                            <div class="cpnamount">
                                <div class="amountWrap">
                                    <div class="amount">
                                            <span class="amountSign">¥</span><span class="amountNum">60</span><!--Regular if10-->                    
                                    </div>
                                    <div class="condition">
                                        <span>无金额门槛</span>
                                    </div>
                                </div>
                            </div>
                            <div class="couponInfoWrap">
                                <div class="cpninfo">
                                    <div class="detail">
                                    <span class="name">购物车专享优惠券60</span></div>
                                        <div class="validity">
                                            <span>2018.09.05-2018.09.28
                                                <van-button type="danger" size="mini">立即使用</van-button>
                                            </span>
                                        </div>
                                        
                                    
                                </div>
                            </div>
                        </div>
                        <div class="couponMid ">
                            <span>指定商品适用</span>
                            <van-icon name="arrow" class="down" />
                        </div>

                        <div class="info" >
                            <div class="text"><span>以下商品适用：<br>SAINT LAURENT PARIS 圣罗兰 ...<br>特例商品不可使用优惠券</span></div>
                            <div class="text">
                            </div>
                        </div>
                    </li>
                </ul>
            </van-tab>
            <van-tab title="使用记录">
                <ul class="gray" >
                    <li class="couponitem">
                        <div class="couponTop">
                            <div class="cpnamount">
                                <div class="amountWrap">
                                    <div class="amount">
                                            <span class="amountSign">¥</span><span class="amountNum">60</span><!--Regular if10-->                    
                                    </div>
                                    <div class="condition">
                                        <span>无金额门槛</span>
                                    </div>
                                </div>
                            </div>
                            <div class="couponInfoWrap">
                                <div class="cpninfo">
                                    <div class="detail">
                                    <span class="name">购物车专享优惠券60</span></div>
                                        <div class="validity">
                                            <span>2018.09.05-2018.09.28</span>
                                        </div>
                                        
                                    
                                </div>
                            </div>
                        </div>
                        <div class="couponMid ">
                            <span>指定商品适用</span>
                        </div>
                    </li>
                </ul>
            </van-tab>
            <van-tab title="已过期">
                <ul class="gray" >
                    <li class="couponitem">
                        <div class="couponTop">
                            <div class="cpnamount">
                                <div class="amountWrap">
                                    <div class="amount">
                                            <span class="amountSign">¥</span><span class="amountNum">60</span><!--Regular if10-->                    
                                    </div>
                                    <div class="condition">
                                        <span>无金额门槛</span>
                                    </div>
                                </div>
                            </div>
                            <div class="couponInfoWrap">
                                <div class="cpninfo">
                                    <div class="detail">
                                    <span class="name">购物车专享优惠券60</span></div>
                                        <div class="validity">
                                            <span>2018.09.05-2018.09.28</span>
                                        </div>
                                        
                                    
                                </div>
                            </div>
                        </div>
                        <div class="couponMid ">
                            <span>指定商品适用</span>
                        </div>
                    </li>
                </ul>
            </van-tab>
        </van-tabs>
    </div>
</template>

<script>
export default {
  components: {
  },
  data() {
    return {
    };
  },
  computed: {
  },
  methods: {
  }
};
</script>

<style lang="less">
.couponitem {
        padding: 0 10px;
  margin-top: 10px;
  position: relative;
  font-size: 12px;
  .couponTop {
    background-color: #fcebeb;
    border-left: 1px solid #f3d4d4;
    border-right: 1px solid #f3d4d4;
    border-bottom: 1px dashed  #f3d4d4;
    border-radius: 8px;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    .cpnamount {
      position: relative;
      height: 90px;
      width: 34.08%;
      text-align: center;
      float: left;
      border-right: 1px dashed #f3d4d4;
    }
    .amountWrap {
      width: 100%;
      position: absolute;
      top: 50%;
      -webkit-transform: translate(0, -50%);
      transform: translate(0, -50%);
      .amount {
        font-size: 15px;
        .amountSign {
          margin-right: 3px;
        }
        .amountNum {
          font-size: 39px;
          line-height: 1;
          font-weight: bold;
        }
      }
    }
  }
  .couponInfoWrap {
    position: relative;
    margin-left: 37.465%;
    height: 90px;
    .cpninfo {
      position: absolute;
      top: 50%;
      -webkit-transform: translate(0, -50%);
      transform: translate(0, -50%);
      width: 100%;
      .detail {
        padding-right: 15px;
        word-break: break-all;
        .name {
          font-size: 13px;
          color: #000;
        }
      }
      .validity {
        font-size: 10px;
      }
    }
  }
  .couponMid {
    position: relative;
    height: 31px;
    line-height: 31px;
    padding-left: 16px;
    font-size: 12px;
    
    background-color: #fcebeb;
    border-left: 1px solid #f3d4d4;
    border-right: 1px solid #f3d4d4;
    border-bottom: 1px solid #f3d4d4;
    border-radius: 8px;
    border-bottom-left-radius: 5px;
    border-bottom-right-radius: 5px;
    i{
        right: 16px;
        position: absolute;
        top: 8px;
         -webkit-transform: rotate(90deg);
        transform: rotate(90deg);   
    }
  }
  
  .info{
      display: none;
      background-color: #fcebeb;
    border-left: 1px solid #f3d4d4;
    border-right: 1px solid #f3d4d4;
    border-bottom: 1px solid #f3d4d4;
    border-bottom-left-radius: 8px;
    border-bottom-right-radius: 8px;
padding: 10px 25px 12px 15px;
    font-size: 12px;
  }
}
  .show{
      
  .couponMid {
          border-bottom: 1px dashed #f3d4d4;
          border-bottom-left-radius: 0;
    border-bottom-right-radius: 0;
    i{
         -webkit-transform: rotate(-90deg);
        transform: rotate(-90deg);   
    }
  }
  .info{
      display: block;
  }
  }
  .gray{
      -webkit-filter: grayscale(100%);filter:progid:DXImageTransform.Microsoft.BasicImage(graysale=1);
  }
</style>
