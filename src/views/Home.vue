<template>
  <div id="app">
    <div class="header">
      <div class="minheader">
        <div class="hleft">
          <span>欢迎来到酒仙网!</span>
          <router-link to="/Login"><a href="#">请登录</a></router-link>
          <a href="#">免费注册</a>
        </div>
        <div class="hright">
          <span><a href="#">我的酒仙</a></span>
          <span style="color: #cc0000">CEO邮箱</span>
          <span
            ><a href="#">购物车<span style="color: #cc0000">0</span>件</a></span
          >
          <span style="color: #cc0000">CLUB会员</span>
          <span><a href="#">招商入驻</a></span>
          <span><a href="#">手机逛酒仙</a></span>
          <span><a href="#">网站导航</a></span>
          <span><a href="#">客户服务</a></span>
          <span>客服热线<span style="color: #cc0000">400-617-999</span></span>
        </div>
      </div>
    </div>
    <div class="topFocusBox">
      <img
        src="http://img08.jiuxian.com/bill/2021/1118/706cd927df374db3b88573af67df6487.jpg"
        alt=""
      />
    </div>
    <div class="search">
      <div class="searchicon">
        <div class="leftimg">
          <img src="https://misc.jiuxian.com/logo/logo_137_65.png" alt="" />
          <img
            src="http://img06.jiuxian.com/bill/2019/0507/7d48c51d53fb4dad98998b375a8236d0.gif"
            alt=""
          />
        </div>
        <div class="mainsearch">
          <div class="searchHome">
            <form>
              <input
                id="wd"
                class="search-form"
                type="text"
                name="key"
                value="享好价囤好货，爆款限时直降"
                maxlength="50"
                autocomplete="off"
              />
              <input class="search-btn" type="submit" name="" value="搜索" />
              <input id="area" name="area" type="hidden" value="2" />
            </form>
          </div>
          <div class="hotWords">
            <p>
              <a href="#"
                >五粮液
                <s></s>
              </a>
              <a href="#"
                >茅台
                <s></s>
              </a>
              <a href="#"
                >酒鬼
                <s></s>
              </a>
              <a href="#"
                >拉菲
                <s></s>
              </a>
              <a href="#"
                >黄尾袋鼠
                <s></s>
              </a>
              <a href="#"
                >泸州老窖
                <s></s>
              </a>
              <a href="#"
                >人头马
                <s></s>
              </a>
              <a href="#"
                >董酒
                <s></s>
              </a>
            </p>
          </div>
        </div>
        <div class="headerProtect">
          <a href="#" rel="nofollow"></a>
          <a href="#" rel="nofollow"></a>
          <a href="#" rel="nofollow"></a>
        </div>
      </div>
    </div>
    <div class="navWrap">
      <div class="nav">
        <div class="navCategoryMenu">
          <h2>全部商品分类</h2>
          <ul class="categoryBox">
            <li class="cartItem">
              <div class="catItemCon">
                <h3>
                  <i></i>
                  <a href="#">一键选酒</a>
                </h3>
                <div class="categoryCon">
                  <p>
                    <a href="#">整箱购</a>
                    <a href="#">老酒特卖</a>
                    <a href="#">地域名酒</a>
                  </p>
                  <p><a href="#">有礼有面</a></p>
                </div>
              </div>
            </li>
            <li class="cartItem">
              <div class="catItemCon">
                <h3>
                  <i></i>
                  <a href="#">白酒</a>
                </h3>
                <div class="categoryCon">
                  <p>
                    <a href="#" class="on">茅台</a>
                    <a href="#" class="on">五粮液</a>
                    <a href="#" class="on">酒鬼</a>

                    <a href="#">汾酒</a>
                  </p>
                  <p>
                    <a href="#">浓香型</a>
                    <a href="#" class="on">酱香型</a>
                    <a href="#">贵州</a>
                    <a href="#">四川</a>
                  </p>
                </div>
              </div>
            </li>
            <li class="cartItem">
              <div class="catItemCon">
                <h3>
                  <i></i>
                  <a href="#">葡萄酒</a>
                </h3>
                <div class="categoryCon">
                  <p>
                    <a href="#">法国</a>
                    <a href="#">澳大利亚</a>
                    <a href="#">西班牙</a>
                  </p>
                  <p>
                    <a href="#">中国</a>
                    <a href="#" class="on">拉菲</a>
                    <a href="#">奔富</a>
                    <a href="#">黄尾袋鼠</a>
                  </p>
                </div>
              </div>
            </li>
            <li class="cartItem">
              <div class="catItemCon">
                <h3>
                  <i></i>
                  <a href="#">洋酒</a>
                </h3>
                <div class="categoryCon">
                  <p>
                    <a href="#" class="on">马爹利</a>
                    <a href="#" class="on">人头马</a>
                    <a href="#">尊尼获加</a>
                  </p>
                  <p>
                    <a href="#" class="on">轩尼诗</a>
                    <a href="#" class="on">绝对</a>
                    <a href="#" class="on">百龄坛</a>
                  </p>
                </div>
              </div>
            </li>
            <li class="cartItem">
              <div class="catItemCon">
                <h3>
                  <i></i>
                  <a href="#">啤酒/黄酒/养生酒</a>
                </h3>
                <div class="categoryCon">
                  <p>
                    <a href="#" class="on">青岛</a>
                    <a href="#" class="on">1664</a>
                    <a href="#" class="on">古越龙山</a>

                    <a href="#">劲牌</a>
                  </p>
                  <p><a href="#">狮虎争霸</a></p>
                </div>
              </div>
            </li>
            <li class="cartItem last">
              <div class="catItemCon">
                <h3>
                  <i></i>
                  <a href="#">食尚</a>
                </h3>
                <div class="categoryCon">
                  <p>
                    <a href="#" class="on">酒具</a>
                    <a href="#">茶叶</a>
                    <a href="#" class="on">水饮</a>
                  </p>
                </div>
              </div>
            </li>
          </ul>
          <div class="mav">
            <img
              src="http://img07.jiuxian.com/bill/2021/0520/0e5b57a1ca6c4279a1ae67d586b042ce.jpg"
              alt=""
            />
            <img
              src="http://img06.jiuxian.com/bill/2021/0527/3b2a378918dc49d0abcd4c5de864f008.png"
              alt=""
            />
            <img
              src="http://img06.jiuxian.com/bill/2021/0916/86f4e119315c403db33d223c33ddeefc.png"
              alt=""
            />
          </div>
        </div>
        <ul class="navList">
          <li class="home"><a href="#">首页</a></li>
          <li class="home"><a href="#">CLUB</a></li>
          <li class="home"><a href="#">葡萄酒馆</a></li>
          <li class="home"><a href="#">周末惠</a></li>
          <li class="home"><a href="#">洋酒馆</a></li>
          <li class="home"><a href="#">新品</a></li>
          <li class="home"><a href="#">门店加盟</a></li>
        </ul>
        <div class="navright">
          <img
            src="http://img08.jiuxian.com/bill/2021/1115/0e7ebb06e08748bd8cabac6ab1975570.gif"
            alt=""
          />
        </div>
      </div>
    </div>

    <div class="swiper-container">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <img
            src="http://img06.jiuxian.com/bill/2021/1116/ce1ee1ca77ab496baaaa16b56a4ccfc1.jpg"
            alt=""
          />
        </div>
        <div class="swiper-slide">
          <img
            src="http://img07.jiuxian.com/bill/2021/1115/1f2b03d9c0674eae803581dab33c1557.jpg"
            alt=""
          />
        </div>
        <div class="swiper-slide">
          <img
            src="http://img06.jiuxian.com/bill/2021/1118/45c2cc847e68413fb9a934175fa7a094.jpg"
            alt=""
          />
        </div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
    <div class="mainWrap">
      <div class="clearfixs">
        <div class="indexTabBox">
          <div class="indexTabNav">
            <ul>
              <li
                @click="change(index)"
                :class="currentIndex == index ? 'active' : ''"
                class="on"
                :key="item.id"
                v-for="(item, index) in list"
              >
                {{ item.title }}
              </li>
            </ul>
          </div>
          <div class="indexTabConWrap" v-show="currentIndex == 0">
            <div class="indexTabCon">
              <ul class="clearfix1">
                <li product-box="129994">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-129994.html?src=4766&amp;source=51"
                      target="_blank"
                      title="50°古井贡酒经典500ml*6"
                      ><img
                        src="https://img06.jiuxian.com/2020/0707/494fa3bbf0ee418f812781d82c0d6e6b2.jpg"
                        width="160"
                        height="160"
                        alt="50°古井贡酒经典500ml*6"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-129994.html?src=4766&amp;source=51"
                      target="_blank"
                      title="50°古井贡酒经典500ml*6"
                    >
                      50°古井贡酒经典500ml*6</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="129994" class="jxIndex_nowPrice_129994"
                      >￥279.00</strong
                    ><span
                      ><em clubgoodid="129994"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="67360">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-67360.html?src=4767&amp;source=52"
                      target="_blank"
                      title="53°郎酒红花郎十（10）558ml"
                    >
                      <img
                        src="https://img06.jiuxian.com/2018/0530/70c0fac218d643548825fb126fd49c6a2.jpg"
                        width="160"
                        height="160"
                        alt="53°郎酒红花郎十（10）558ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-67360.html?src=4767&amp;source=52"
                      target="_blank"
                      title="53°郎酒红花郎十（10）558ml"
                    >
                      53°郎酒红花郎十（10）558ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="67360" class="jxIndex_nowPrice_67360"
                      >￥459.00</strong
                    >
                  </div>
                </li>
                <li product-box="34146">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-34146.html?src=4768&amp;source=53"
                      target="_blank"
                      title="【老酒特卖】52°五粮液普五经典款 水晶盒 500ml（2015-2020年随机发非原箱）"
                      ><img
                        src="https://img06.jiuxian.com/2021/0727/ab43a6f557ea44d19bce6f6f9437781d2.jpg"
                        width="160"
                        height="160"
                        alt="【老酒特卖】52°五粮液普五经典款 水晶盒 500ml（2015-2020年随机发非原箱）"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-34146.html?src=4768&amp;source=53"
                      target="_blank"
                      title="【老酒特卖】52°五粮液普五经典款 水晶盒 500ml（2015-2020年随机发非原箱）"
                    >
                      【老酒特卖】52°五粮液普五经典款 水晶盒
                      500ml（2015-2020年随机发非原箱）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="34146" class="jxIndex_nowPrice_34146"
                      >￥1029.00</strong
                    >
                  </div>
                </li>
                <li product-box="511200">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-511200.html?src=4769&amp;source=54"
                      target="_blank"
                      title="法国进口红酒14度朗格巴顿银牌特卖干红葡萄酒750ml*2瓶装+双支装礼袋可送礼"
                      ><img
                        src="https://img06.jiuxian.com/2021/0707/e089c75a15b84cef90a01a9a8eacdb342.jpg"
                        width="160"
                        height="160"
                        alt="法国进口红酒14度朗格巴顿银牌特卖干红葡萄酒750ml*2瓶装+双支装礼袋可送礼"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-511200.html?src=4769&amp;source=54"
                      target="_blank"
                      title="法国进口红酒14度朗格巴顿银牌特卖干红葡萄酒750ml*2瓶装+双支装礼袋可送礼"
                    >
                      法国进口红酒14度朗格巴顿银牌特卖干红葡萄酒750ml*2瓶装+双支装礼袋可送礼</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="511200" class="jxIndex_nowPrice_511200"
                      >￥29.90</strong
                    >
                  </div>
                </li>
                <li product-box="142709">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-142709.html?src=4770&amp;source=55"
                      target="_blank"
                      title="12°悠蜜蓝莓精酿遇见·蓝雪（半甜型）450ml"
                      ><img
                        src="https://img06.jiuxian.com/2021/0127/717ee7165c8e4f1e897b5f4ee48374742.jpg"
                        width="160"
                        height="160"
                        alt="12°悠蜜蓝莓精酿遇见·蓝雪（半甜型）450ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-142709.html?src=4770&amp;source=55"
                      target="_blank"
                      title="12°悠蜜蓝莓精酿遇见·蓝雪（半甜型）450ml"
                    >
                      12°悠蜜蓝莓精酿遇见·蓝雪（半甜型）450ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="142709" class="jxIndex_nowPrice_142709"
                      >￥199.00</strong
                    >
                  </div>
                </li>
                <li product-box="48945">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-48945.html?src=4771&amp;source=56"
                      target="_blank"
                      title="52°酒鬼酒书说500ml"
                      ><img
                        src="https://img06.jiuxian.com/2017/0828/ddfed9608abd476e82591d9825873be52.jpg"
                        width="160"
                        height="160"
                        alt="52°酒鬼酒书说500ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-48945.html?src=4771&amp;source=56"
                      target="_blank"
                      title="52°酒鬼酒书说500ml"
                    >
                      52°酒鬼酒书说500ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="48945" class="jxIndex_nowPrice_48945"
                      >￥299.00</strong
                    >
                  </div>
                </li>
                <li product-box="600">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-600.html?src=4772&amp;source=57"
                      target="_blank"
                      title="52°剑南春 水晶剑白酒500ml"
                      ><img
                        src="https://img06.jiuxian.com/2020/1026/fbbac7da20be4ac2ac9f0a0b33ff9b272.jpg"
                        width="160"
                        height="160"
                        alt="52°剑南春 水晶剑白酒500ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-600.html?src=4772&amp;source=57"
                      target="_blank"
                      title="52°剑南春 水晶剑白酒500ml"
                    >
                      52°剑南春 水晶剑白酒500ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="600" class="jxIndex_nowPrice_600"
                      >￥469.00</strong
                    >
                  </div>
                </li>
                <li product-box="129136">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-129136.html?src=4773&amp;source=58"
                      target="_blank"
                      title="飞天53%vol 500ml贵州茅台酒（带杯）"
                      ><img
                        src="https://img06.jiuxian.com/2021/0204/b0027678e0ad4b11858a6d999f21f5272.jpg"
                        width="160"
                        height="160"
                        alt="飞天53%vol 500ml贵州茅台酒（带杯）"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-129136.html?src=4773&amp;source=58"
                      target="_blank"
                      title="飞天53%vol 500ml贵州茅台酒（带杯）"
                    >
                      飞天53%vol 500ml贵州茅台酒（带杯）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="129136" class="jxIndex_nowPrice_129136"
                      >￥1499.00</strong
                    >
                  </div>
                </li>
                <li product-box="520807">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-520807.html?src=4774&amp;source=59"
                      target="_blank"
                      title="40°英国芝华士12年苏格兰威士忌500ml+40°英国百龄坛特醇苏格兰威士忌500ml+百龄坛50ml+哈瓦纳50ml"
                      ><img
                        src="https://img06.jiuxian.com/2021/0722/46fe8302262d4987ad8b8411b27d4cd42.jpg"
                        width="160"
                        height="160"
                        alt="40°英国芝华士12年苏格兰威士忌500ml+40°英国百龄坛特醇苏格兰威士忌500ml+百龄坛50ml+哈瓦纳50ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-520807.html?src=4774&amp;source=59"
                      target="_blank"
                      title="40°英国芝华士12年苏格兰威士忌500ml+40°英国百龄坛特醇苏格兰威士忌500ml+百龄坛50ml+哈瓦纳50ml"
                    >
                      40°英国芝华士12年苏格兰威士忌500ml+40°英国百龄坛特醇苏格兰威士忌500ml+百龄坛50ml+哈瓦纳50ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="520807" class="jxIndex_nowPrice_520807"
                      >￥168.00</strong
                    >
                  </div>
                </li>
                <li product-box="2">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-2.html?src=4775&amp;source=60"
                      target="_blank"
                      title="43°茅台飞天500ml"
                      ><img
                        src="https://img06.jiuxian.com/2021/0726/923e45cc085248d69d083d436b2a7d8c2.jpg"
                        width="160"
                        height="160"
                        alt="43°茅台飞天500ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-2.html?src=4775&amp;source=60"
                      target="_blank"
                      title="43°茅台飞天500ml"
                    >
                      43°茅台飞天500ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="2" class="jxIndex_nowPrice_2"
                      >￥1029.00</strong
                    >
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <div class="indexTabConWrap" v-show="currentIndex == 1">
            <div class="indexTabCon">
              <ul class="clearfix1">
                <li product-box="129994">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-129994.html?src=4766&amp;source=51"
                      target="_blank"
                      title="50°古井贡酒经典500ml*6"
                      ><img
                        src="https://img07.jiuxian.com/2021/0106/0d4425cd91254e869f4f2eab6f931b5b2.jpg"
                        width="160"
                        height="160"
                        alt="50°古井贡酒经典500ml*6"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-129994.html?src=4766&amp;source=51"
                      target="_blank"
                      title="50°古井贡酒经典500ml*6"
                    >
                      50°古井贡酒经典500ml*6</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="129994" class="jxIndex_nowPrice_129994"
                      >￥279.00</strong
                    ><span
                      ><em clubgoodid="129994"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="67360">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-67360.html?src=4767&amp;source=52"
                      target="_blank"
                      title="53°郎酒红花郎十（10）558ml"
                    >
                      <img
                        src="https://img07.jiuxian.com/2021/0519/f22bb155bad04fd29902a6edf8fa388f2.jpg"
                        width="160"
                        height="160"
                        alt="53°郎酒红花郎十（10）558ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-67360.html?src=4767&amp;source=52"
                      target="_blank"
                      title="53°郎酒红花郎十（10）558ml"
                    >
                      53°郎酒红花郎十（10）558ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="67360" class="jxIndex_nowPrice_67360"
                      >￥459.00</strong
                    >
                  </div>
                </li>
                <li product-box="34146">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-34146.html?src=4768&amp;source=53"
                      target="_blank"
                      title="【老酒特卖】52°五粮液普五经典款 水晶盒 500ml（2015-2020年随机发非原箱）"
                      ><img
                        src="https://img07.jiuxian.com/2019/1229/603fd3faef7044b791dd299dfcad7b3c2.jpg"
                        width="160"
                        height="160"
                        alt="【老酒特卖】52°五粮液普五经典款 水晶盒 500ml（2015-2020年随机发非原箱）"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-34146.html?src=4768&amp;source=53"
                      target="_blank"
                      title="【老酒特卖】52°五粮液普五经典款 水晶盒 500ml（2015-2020年随机发非原箱）"
                    >
                      【老酒特卖】52°五粮液普五经典款 水晶盒
                      500ml（2015-2020年随机发非原箱）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="34146" class="jxIndex_nowPrice_34146"
                      >￥1029.00</strong
                    >
                  </div>
                </li>
                <li product-box="511200">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-511200.html?src=4769&amp;source=54"
                      target="_blank"
                      title="法国进口红酒14度朗格巴顿银牌特卖干红葡萄酒750ml*2瓶装+双支装礼袋可送礼"
                      ><img
                        src="https://img07.jiuxian.com/2021/0708/bfe4c81079844e8ab35c75942be4a13d2.jpg"
                        width="160"
                        height="160"
                        alt="法国进口红酒14度朗格巴顿银牌特卖干红葡萄酒750ml*2瓶装+双支装礼袋可送礼"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-511200.html?src=4769&amp;source=54"
                      target="_blank"
                      title="法国进口红酒14度朗格巴顿银牌特卖干红葡萄酒750ml*2瓶装+双支装礼袋可送礼"
                    >
                      法国进口红酒14度朗格巴顿银牌特卖干红葡萄酒750ml*2瓶装+双支装礼袋可送礼</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="511200" class="jxIndex_nowPrice_511200"
                      >￥29.90</strong
                    >
                  </div>
                </li>
                <li product-box="142709">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-142709.html?src=4770&amp;source=55"
                      target="_blank"
                      title="12°悠蜜蓝莓精酿遇见·蓝雪（半甜型）450ml"
                      ><img
                        src="https://img07.jiuxian.com/2021/0708/bfe4c81079844e8ab35c75942be4a13d2.jpg"
                        width="160"
                        height="160"
                        alt="12°悠蜜蓝莓精酿遇见·蓝雪（半甜型）450ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-142709.html?src=4770&amp;source=55"
                      target="_blank"
                      title="12°悠蜜蓝莓精酿遇见·蓝雪（半甜型）450ml"
                    >
                      12°悠蜜蓝莓精酿遇见·蓝雪（半甜型）450ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="142709" class="jxIndex_nowPrice_142709"
                      >￥199.00</strong
                    >
                  </div>
                </li>
                <li product-box="48945">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-48945.html?src=4771&amp;source=56"
                      target="_blank"
                      title="52°酒鬼酒书说500ml"
                      ><img
                        src="https://img07.jiuxian.com/2021/0708/bfe4c81079844e8ab35c75942be4a13d2.jpg"
                        width="160"
                        height="160"
                        alt="52°酒鬼酒书说500ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-48945.html?src=4771&amp;source=56"
                      target="_blank"
                      title="52°酒鬼酒书说500ml"
                    >
                      52°酒鬼酒书说500ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="48945" class="jxIndex_nowPrice_48945"
                      >￥299.00</strong
                    >
                  </div>
                </li>
                <li product-box="600">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-600.html?src=4772&amp;source=57"
                      target="_blank"
                      title="52°剑南春 水晶剑白酒500ml"
                      ><img
                        src="https://img07.jiuxian.com/2021/0806/f2c880a67cda406a98f6f2ce1b894d232.jpg"
                        width="160"
                        height="160"
                        alt="52°剑南春 水晶剑白酒500ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-600.html?src=4772&amp;source=57"
                      target="_blank"
                      title="52°剑南春 水晶剑白酒500ml"
                    >
                      52°剑南春 水晶剑白酒500ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="600" class="jxIndex_nowPrice_600"
                      >￥469.00</strong
                    >
                  </div>
                </li>
                <li product-box="129136">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-129136.html?src=4773&amp;source=58"
                      target="_blank"
                      title="飞天53%vol 500ml贵州茅台酒（带杯）"
                      ><img
                        src="https://img07.jiuxian.com/2021/0806/f2c880a67cda406a98f6f2ce1b894d232.jpg"
                        width="160"
                        height="160"
                        alt="飞天53%vol 500ml贵州茅台酒（带杯）"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-129136.html?src=4773&amp;source=58"
                      target="_blank"
                      title="飞天53%vol 500ml贵州茅台酒（带杯）"
                    >
                      飞天53%vol 500ml贵州茅台酒（带杯）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="129136" class="jxIndex_nowPrice_129136"
                      >￥1499.00</strong
                    >
                  </div>
                </li>
                <li product-box="520807">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-520807.html?src=4774&amp;source=59"
                      target="_blank"
                      title="40°英国芝华士12年苏格兰威士忌500ml+40°英国百龄坛特醇苏格兰威士忌500ml+百龄坛50ml+哈瓦纳50ml"
                      ><img
                        src="https://img07.jiuxian.com/2021/0806/f2c880a67cda406a98f6f2ce1b894d232.jpg"
                        width="160"
                        height="160"
                        alt="40°英国芝华士12年苏格兰威士忌500ml+40°英国百龄坛特醇苏格兰威士忌500ml+百龄坛50ml+哈瓦纳50ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-520807.html?src=4774&amp;source=59"
                      target="_blank"
                      title="40°英国芝华士12年苏格兰威士忌500ml+40°英国百龄坛特醇苏格兰威士忌500ml+百龄坛50ml+哈瓦纳50ml"
                    >
                      40°英国芝华士12年苏格兰威士忌500ml+40°英国百龄坛特醇苏格兰威士忌500ml+百龄坛50ml+哈瓦纳50ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="520807" class="jxIndex_nowPrice_520807"
                      >￥168.00</strong
                    >
                  </div>
                </li>
                <li product-box="2">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-2.html?src=4775&amp;source=60"
                      target="_blank"
                      title="43°茅台飞天500ml"
                      ><img
                        src="https://img07.jiuxian.com/2021/0806/f2c880a67cda406a98f6f2ce1b894d232.jpg"
                        width="160"
                        height="160"
                        alt="43°茅台飞天500ml"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-2.html?src=4775&amp;source=60"
                      target="_blank"
                      title="43°茅台飞天500ml"
                    >
                      43°茅台飞天500ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="2" class="jxIndex_nowPrice_2"
                      >￥1029.00</strong
                    >
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <div class="indexTabConWrap" v-show="currentIndex == 2">
            <div class="indexTabCon">
              <ul class="clearfix1">
                <li product-box="55264">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-55264.html?src=3888&amp;source=71"
                      target="_blank"
                      title="52°白水杜康一坛老酒1000ml（4瓶装）"
                      ><img
                        src="https://img08.jiuxian.com/2018/1225/822c16fb70ab43c4b50d9da49a6d10bd2.jpg"
                        data-original="https://img08.jiuxian.com/2018/1225/822c16fb70ab43c4b50d9da49a6d10bd2.jpg"
                        width="160"
                        height="160"
                        alt="52°白水杜康一坛老酒1000ml（4瓶装）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-55264.html?src=3888&amp;source=71"
                      target="_blank"
                      title="52°白水杜康一坛老酒1000ml（4瓶装）"
                    >
                      <i class="zhenxuan"></i>
                      52°白水杜康一坛老酒1000ml（4瓶装）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="55264" class="jxIndex_nowPrice_55264"
                      >￥198.00</strong
                    ><span
                      ><em clubgoodid="55264"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="3372">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-3372.html?src=3889&amp;source=72"
                      target="_blank"
                      title="53°黄盖玻瓶汾酒475ml 3瓶装"
                      ><img
                        src="https://img08.jiuxian.com/2016/0331/03c13aa80c9c4dc0b9a5a6c72b04b7752.jpg"
                        data-original="https://img08.jiuxian.com/2016/0331/03c13aa80c9c4dc0b9a5a6c72b04b7752.jpg"
                        width="160"
                        height="160"
                        alt="53°黄盖玻瓶汾酒475ml 3瓶装"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-3372.html?src=3889&amp;source=72"
                      target="_blank"
                      title="53°黄盖玻瓶汾酒475ml 3瓶装"
                    >
                      53°黄盖玻瓶汾酒475ml 3瓶装</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="3372" class="jxIndex_nowPrice_3372"
                      >￥149.00</strong
                    ><span
                      ><em clubgoodid="3372"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="81702">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-81702.html?src=3890&amp;source=73"
                      target="_blank"
                      title="40°法国卡爹拉金典VSOP白兰地700ml*2瓶"
                      ><img
                        src="https://img08.jiuxian.com/2020/0923/664c7ac590294bb68d6e930928502c5e2.jpg"
                        data-original="https://img08.jiuxian.com/2020/0923/664c7ac590294bb68d6e930928502c5e2.jpg"
                        width="160"
                        height="160"
                        alt="40°法国卡爹拉金典VSOP白兰地700ml*2瓶"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-81702.html?src=3890&amp;source=73"
                      target="_blank"
                      title="40°法国卡爹拉金典VSOP白兰地700ml*2瓶"
                    >
                      40°法国卡爹拉金典VSOP白兰地700ml*2瓶</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="81702" class="jxIndex_nowPrice_81702"
                      >￥79.00</strong
                    ><span
                      ><em clubgoodid="81702"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="123985">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-123985.html?src=3891&amp;source=74"
                      target="_blank"
                      title="【包邮】12.5°德国（原瓶进口）图岚朵雷司令半干白葡萄酒（花标）750ml"
                      ><img
                        src="https://img08.jiuxian.com/2020/0330/7ec1fd4efcb249c28b6be5d255536a1b2.jpg"
                        data-original="https://img08.jiuxian.com/2020/0330/7ec1fd4efcb249c28b6be5d255536a1b2.jpg"
                        width="160"
                        height="160"
                        alt="【包邮】12.5°德国（原瓶进口）图岚朵雷司令半干白葡萄酒（花标）750ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-123985.html?src=3891&amp;source=74"
                      target="_blank"
                      title="【包邮】12.5°德国（原瓶进口）图岚朵雷司令半干白葡萄酒（花标）750ml"
                    >
                      【包邮】12.5°德国（原瓶进口）图岚朵雷司令半干白葡萄酒（花标）750ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="123985" class="jxIndex_nowPrice_123985"
                      >￥69.00</strong
                    ><span
                      ><em clubgoodid="123985"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="16516">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-16516.html?src=3892&amp;source=75"
                      target="_blank"
                      title="52°扳倒井52 500ml（双瓶装）"
                      ><img
                        src="https://img08.jiuxian.com/2021/1103/e9482060ff1048ce982525d29b9aee842.jpg"
                        data-original="https://img08.jiuxian.com/2021/1103/e9482060ff1048ce982525d29b9aee842.jpg"
                        width="160"
                        height="160"
                        alt="52°扳倒井52 500ml（双瓶装）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-16516.html?src=3892&amp;source=75"
                      target="_blank"
                      title="52°扳倒井52 500ml（双瓶装）"
                    >
                      52°扳倒井52 500ml（双瓶装）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="16516" class="jxIndex_nowPrice_16516"
                      >￥69.00</strong
                    ><span
                      ><em clubgoodid="16516"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="2929">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-2929.html?src=3893&amp;source=76"
                      target="_blank"
                      title="52°金六福喜酒卡盒装475ml（6瓶装）"
                      ><img
                        src="https://img08.jiuxian.com/2019/1219/df3b6ee06d7c4f49b78982cc4b28484e2.jpg"
                        data-original="https://img08.jiuxian.com/2019/1219/df3b6ee06d7c4f49b78982cc4b28484e2.jpg"
                        width="160"
                        height="160"
                        alt="52°金六福喜酒卡盒装475ml（6瓶装）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-2929.html?src=3893&amp;source=76"
                      target="_blank"
                      title="52°金六福喜酒卡盒装475ml（6瓶装）"
                    >
                      52°金六福喜酒卡盒装475ml（6瓶装）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="2929" class="jxIndex_nowPrice_2929"
                      >￥239.00</strong
                    ><span
                      ><em clubgoodid="2929"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="541041">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-541041.html?src=3894&amp;source=77"
                      target="_blank"
                      title="【酒厂直发】甘肃皇台酒红六鼎52度浓香型纯粮食陈酿高度白酒送礼宴请礼盒装整箱4瓶装"
                      ><img
                        src="https://img08.jiuxian.com/2021/0916/7143681a2e964b71b2c2bd45102875ee2.jpg"
                        data-original="https://img08.jiuxian.com/2021/0916/7143681a2e964b71b2c2bd45102875ee2.jpg"
                        width="160"
                        height="160"
                        alt="【酒厂直发】甘肃皇台酒红六鼎52度浓香型纯粮食陈酿高度白酒送礼宴请礼盒装整箱4瓶装"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-541041.html?src=3894&amp;source=77"
                      target="_blank"
                      title="【酒厂直发】甘肃皇台酒红六鼎52度浓香型纯粮食陈酿高度白酒送礼宴请礼盒装整箱4瓶装"
                    >
                      【酒厂直发】甘肃皇台酒红六鼎52度浓香型纯粮食陈酿高度白酒送礼宴请礼盒装整箱4瓶装</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="541041" class="jxIndex_nowPrice_541041"
                      >￥592.00</strong
                    ><span
                      ><em clubgoodid="541041"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="14090">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-14090.html?src=3895&amp;source=78"
                      target="_blank"
                      title="意大利激情飞扬桃味气泡葡萄酒750ml"
                      ><img
                        src="https://img08.jiuxian.com/2020/0529/1d61ee11aaaf44a8bd1c9c637f9269222.jpg"
                        data-original="https://img08.jiuxian.com/2020/0529/1d61ee11aaaf44a8bd1c9c637f9269222.jpg"
                        width="160"
                        height="160"
                        alt="意大利激情飞扬桃味气泡葡萄酒750ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-14090.html?src=3895&amp;source=78"
                      target="_blank"
                      title="意大利激情飞扬桃味气泡葡萄酒750ml"
                    >
                      意大利激情飞扬桃味气泡葡萄酒750ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="14090" class="jxIndex_nowPrice_14090"
                      >￥39.00</strong
                    ><span
                      ><em clubgoodid="14090"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="133081">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-133081.html?src=3896&amp;source=79"
                      target="_blank"
                      title="【包邮】南非蓝楹花皮诺塔吉桃红葡萄酒750ml"
                      ><img
                        src="https://img08.jiuxian.com/2020/0828/12e6b7a520d54f1e968f49a5dc0179dd2.JPG"
                        data-original="https://img08.jiuxian.com/2020/0828/12e6b7a520d54f1e968f49a5dc0179dd2.JPG"
                        width="160"
                        height="160"
                        alt="【包邮】南非蓝楹花皮诺塔吉桃红葡萄酒750ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-133081.html?src=3896&amp;source=79"
                      target="_blank"
                      title="【包邮】南非蓝楹花皮诺塔吉桃红葡萄酒750ml"
                    >
                      【包邮】南非蓝楹花皮诺塔吉桃红葡萄酒750ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="133081" class="jxIndex_nowPrice_133081"
                      >￥59.00</strong
                    ><span
                      ><em clubgoodid="133081"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="100881">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-100881.html?src=3897&amp;source=80"
                      target="_blank"
                      title="50°金六福六福临门500ml*6"
                      ><img
                        src="https://img08.jiuxian.com/2019/1204/ed683ce0b3034f1b9d1c41f93f2f01a12.jpg"
                        data-original="https://img08.jiuxian.com/2019/1204/ed683ce0b3034f1b9d1c41f93f2f01a12.jpg"
                        width="160"
                        height="160"
                        alt="50°金六福六福临门500ml*6"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-100881.html?src=3897&amp;source=80"
                      target="_blank"
                      title="50°金六福六福临门500ml*6"
                    >
                      50°金六福六福临门500ml*6</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="100881" class="jxIndex_nowPrice_100881"
                      >￥199.00</strong
                    ><span
                      ><em clubgoodid="100881"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <div class="indexTabConWrap" v-show="currentIndex == 3">
            <div class="indexTabCon">
              <ul class="clearfix1">
                <li product-box="59627">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-59627.html?source=81"
                      target="_blank"
                      title="52°酒鬼湘泉老坛500ml（6瓶装）"
                      ><img
                        src="https://img09.jiuxian.com/2019/1114/bc383667e3a34994a75a90421a140d132.jpg"
                        data-original="https://img09.jiuxian.com/2019/1114/bc383667e3a34994a75a90421a140d132.jpg"
                        width="160"
                        height="160"
                        alt="52°酒鬼湘泉老坛500ml（6瓶装）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-59627.html?source=81"
                      target="_blank"
                      title="52°酒鬼湘泉老坛500ml（6瓶装）"
                    >
                      52°酒鬼湘泉老坛500ml（6瓶装）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="59627" class="jxIndex_nowPrice_59627"
                      >￥239.00</strong
                    ><span
                      ><em clubgoodid="59627"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="73255">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-73255.html?source=82"
                      target="_blank"
                      title="53度500ml*6茅台王子酒（金王子）"
                      ><img
                        src="https://img09.jiuxian.com/2018/0731/41f8afccc3384c689f12948c02dce5e12.jpg"
                        data-original="https://img09.jiuxian.com/2018/0731/41f8afccc3384c689f12948c02dce5e12.jpg"
                        width="160"
                        height="160"
                        alt="53度500ml*6茅台王子酒（金王子）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-73255.html?source=82"
                      target="_blank"
                      title="53度500ml*6茅台王子酒（金王子）"
                    >
                      53度500ml*6茅台王子酒（金王子）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="73255" class="jxIndex_nowPrice_73255"
                      >￥1668.00</strong
                    ><span
                      ><em clubgoodid="73255"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="39044">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-39044.html?source=83"
                      target="_blank"
                      title="【官方旗舰店】古井贡酒 米兰世博纪念酒和和 55度750ml*6瓶 箱装 浓香型"
                      ><img
                        src="https://img09.jiuxian.com/2021/1119/04976feca6bc48b7939a229dcc535ca32.jpg"
                        data-original="https://img09.jiuxian.com/2021/1119/04976feca6bc48b7939a229dcc535ca32.jpg"
                        width="160"
                        height="160"
                        alt="【官方旗舰店】古井贡酒 米兰世博纪念酒和和 55度750ml*6瓶 箱装 浓香型"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-39044.html?source=83"
                      target="_blank"
                      title="【官方旗舰店】古井贡酒 米兰世博纪念酒和和 55度750ml*6瓶 箱装 浓香型"
                    >
                      【官方旗舰店】古井贡酒 米兰世博纪念酒和和 55度750ml*6瓶
                      箱装 浓香型</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="39044" class="jxIndex_nowPrice_39044"
                      >￥834.00</strong
                    ><span
                      ><em clubgoodid="39044"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="74938">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-74938.html?source=84"
                      target="_blank"
                      title="中粮长城红红葡萄酒国产甜型红酒750ml（6瓶装）"
                      ><img
                        src="https://img09.jiuxian.com/2021/0716/3473dc723fb948fda523de948aeea2882.jpg"
                        data-original="https://img09.jiuxian.com/2021/0716/3473dc723fb948fda523de948aeea2882.jpg"
                        width="160"
                        height="160"
                        alt="中粮长城红红葡萄酒国产甜型红酒750ml（6瓶装）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-74938.html?source=84"
                      target="_blank"
                      title="中粮长城红红葡萄酒国产甜型红酒750ml（6瓶装）"
                    >
                      中粮长城红红葡萄酒国产甜型红酒750ml（6瓶装）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="74938" class="jxIndex_nowPrice_74938"
                      >￥108.00</strong
                    ><span
                      ><em clubgoodid="74938"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="125512">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-125512.html?source=85"
                      target="_blank"
                      title="西班牙爱之湾（谜蓝+桃红+晶白）莫斯卡托低醇甜起泡葡萄酒750ml 3瓶套装"
                      ><img
                        src="https://img09.jiuxian.com/2020/0424/94fddf33fafc4b099b8201c5690e60e82.jpg"
                        data-original="https://img09.jiuxian.com/2020/0424/94fddf33fafc4b099b8201c5690e60e82.jpg"
                        width="160"
                        height="160"
                        alt="西班牙爱之湾（谜蓝+桃红+晶白）莫斯卡托低醇甜起泡葡萄酒750ml 3瓶套装"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-125512.html?source=85"
                      target="_blank"
                      title="西班牙爱之湾（谜蓝+桃红+晶白）莫斯卡托低醇甜起泡葡萄酒750ml 3瓶套装"
                    >
                      西班牙爱之湾（谜蓝+桃红+晶白）莫斯卡托低醇甜起泡葡萄酒750ml
                      3瓶套装</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="125512" class="jxIndex_nowPrice_125512"
                      >￥89.00</strong
                    ><span
                      ><em clubgoodid="125512"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="92867">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-92867.html?source=86"
                      target="_blank"
                      title="50°古井贡酒 年份原浆(古5)500ml（6瓶装）"
                      ><img
                        src="https://img09.jiuxian.com/2019/1120/7d95449de4e34cc98a0d1088577cd3c42.jpg"
                        data-original="https://img09.jiuxian.com/2019/1120/7d95449de4e34cc98a0d1088577cd3c42.jpg"
                        width="160"
                        height="160"
                        alt="50°古井贡酒 年份原浆(古5)500ml（6瓶装）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-92867.html?source=86"
                      target="_blank"
                      title="50°古井贡酒 年份原浆(古5)500ml（6瓶装）"
                    >
                      50°古井贡酒 年份原浆(古5)500ml（6瓶装）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="92867" class="jxIndex_nowPrice_92867"
                      >￥948.00</strong
                    >
                  </div>
                </li>
                <li product-box="82043">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-82043.html?source=87"
                      target="_blank"
                      title="53度500ml贵州大曲酒（70年代）"
                      ><img
                        src="https://img09.jiuxian.com/2019/0109/ac605ac34d394105b82a0451b699bd992.jpg"
                        data-original="https://img09.jiuxian.com/2019/0109/ac605ac34d394105b82a0451b699bd992.jpg"
                        width="160"
                        height="160"
                        alt="53度500ml贵州大曲酒（70年代）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-82043.html?source=87"
                      target="_blank"
                      title="53度500ml贵州大曲酒（70年代）"
                    >
                      53度500ml贵州大曲酒（70年代）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="82043" class="jxIndex_nowPrice_82043"
                      >￥378.00</strong
                    ><span
                      ><em clubgoodid="82043"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="142217">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-142217.html?source=88"
                      target="_blank"
                      title="【买一送一】沱牌舍得 沱牌 50度 沱牌1940 浓香型 纯粮食白酒 480ml*6整箱装"
                      ><img
                        src="https://img09.jiuxian.com/2021/1112/980527f802484b2b8b83b52137cf786b2.jpg"
                        data-original="https://img09.jiuxian.com/2021/1112/980527f802484b2b8b83b52137cf786b2.jpg"
                        width="160"
                        height="160"
                        alt="【买一送一】沱牌舍得 沱牌 50度 沱牌1940 浓香型 纯粮食白酒 480ml*6整箱装"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-142217.html?source=88"
                      target="_blank"
                      title="【买一送一】沱牌舍得 沱牌 50度 沱牌1940 浓香型 纯粮食白酒 480ml*6整箱装"
                    >
                      【买一送一】沱牌舍得 沱牌 50度 沱牌1940 浓香型 纯粮食白酒
                      480ml*6整箱装</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="142217" class="jxIndex_nowPrice_142217"
                      >￥588.00</strong
                    ><span
                      ><em clubgoodid="142217"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="22310">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-22310.html?source=89"
                      target="_blank"
                      title="法国整箱红酒法国原瓶进口葛雷奥利干红葡萄酒750ml（6瓶套）酒杯酒刀"
                      ><img
                        src="https://img09.jiuxian.com/2017/1024/a4fca3b80f5f44858720f9a339a12d152.jpg"
                        data-original="https://img09.jiuxian.com/2017/1024/a4fca3b80f5f44858720f9a339a12d152.jpg"
                        width="160"
                        height="160"
                        alt="法国整箱红酒法国原瓶进口葛雷奥利干红葡萄酒750ml（6瓶套）酒杯酒刀"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-22310.html?source=89"
                      target="_blank"
                      title="法国整箱红酒法国原瓶进口葛雷奥利干红葡萄酒750ml（6瓶套）酒杯酒刀"
                    >
                      <i class="zhenxuan"></i>
                      法国整箱红酒法国原瓶进口葛雷奥利干红葡萄酒750ml（6瓶套）酒杯酒刀</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="22310" class="jxIndex_nowPrice_22310"
                      >￥169.00</strong
                    ><span
                      ><em clubgoodid="22310"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="60020">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-60020.html?source=90"
                      target="_blank"
                      title="法国勆迪精选干红葡萄酒750ml(6瓶装)"
                      ><img
                        src="https://img09.jiuxian.com/2018/0104/89fcb5609448426b9c0d165ddaea6d332.jpg"
                        data-original="https://img09.jiuxian.com/2018/0104/89fcb5609448426b9c0d165ddaea6d332.jpg"
                        width="160"
                        height="160"
                        alt="法国勆迪精选干红葡萄酒750ml(6瓶装)"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-60020.html?source=90"
                      target="_blank"
                      title="法国勆迪精选干红葡萄酒750ml(6瓶装)"
                    >
                      法国勆迪精选干红葡萄酒750ml(6瓶装)</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="60020" class="jxIndex_nowPrice_60020"
                      >￥279.00</strong
                    ><span
                      ><em clubgoodid="60020"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <div class="indexTabConWrap" v-show="currentIndex == 4">
            <div class="indexTabCon">
              <ul class="clearfix1">
                <li product-box="88665">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-88665.html?source=91"
                      target="_blank"
                      title="【下单立减】52°五粮液 普五（第八代）500ml"
                      ><img
                        src="https://img06.jiuxian.com/2019/0626/71e8c02b56404afc8e63d9409ed7aedd2.jpg"
                        data-original="https://img06.jiuxian.com/2019/0626/71e8c02b56404afc8e63d9409ed7aedd2.jpg"
                        width="160"
                        height="160"
                        alt="【下单立减】52°五粮液 普五（第八代）500ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-88665.html?source=91"
                      target="_blank"
                      title="【下单立减】52°五粮液 普五（第八代）500ml"
                    >
                      【下单立减】52°五粮液 普五（第八代）500ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="88665" class="jxIndex_nowPrice_88665"
                      >￥1399.00</strong
                    ><span
                      ><em clubgoodid="88665"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="518902">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-518902.html?source=92"
                      target="_blank"
                      title="53°郎酒青花郎500ml"
                      ><img
                        src="https://img06.jiuxian.com/2021/0727/c0a4037b22014bf395ae971a0f65dc152.jpg"
                        data-original="https://img06.jiuxian.com/2021/0727/c0a4037b22014bf395ae971a0f65dc152.jpg"
                        width="160"
                        height="160"
                        alt="53°郎酒青花郎500ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-518902.html?source=92"
                      target="_blank"
                      title="53°郎酒青花郎500ml"
                    >
                      53°郎酒青花郎500ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="518902" class="jxIndex_nowPrice_518902"
                      >￥1199.00</strong
                    ><span
                      ><em clubgoodid="518902"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="22367">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-22367.html?source=93"
                      target="_blank"
                      title="54°宝丰荣耀1000ml（献礼版）（双坛装）"
                      ><img
                        src="https://img06.jiuxian.com/2015/1110/db221b8a1f3a487d9af71fe29895b48d2.jpg"
                        data-original="https://img06.jiuxian.com/2015/1110/db221b8a1f3a487d9af71fe29895b48d2.jpg"
                        width="160"
                        height="160"
                        alt="54°宝丰荣耀1000ml（献礼版）（双坛装）"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-22367.html?source=93"
                      target="_blank"
                      title="54°宝丰荣耀1000ml（献礼版）（双坛装）"
                    >
                      54°宝丰荣耀1000ml（献礼版）（双坛装）</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="22367" class="jxIndex_nowPrice_22367"
                      >￥128.00</strong
                    ><span
                      ><em clubgoodid="22367"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="97077">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-97077.html?source=94"
                      target="_blank"
                      title="【买一箱送一箱】法国原瓶进口波尔多梅多克法定产区AOC级 鹏斐伯爵干红葡萄酒750ml*6"
                      ><img
                        src="https://img06.jiuxian.com/2021/0107/1787182cf0734a37a8da43377c107d4c2.jpg"
                        data-original="https://img06.jiuxian.com/2021/0107/1787182cf0734a37a8da43377c107d4c2.jpg"
                        width="160"
                        height="160"
                        alt="【买一箱送一箱】法国原瓶进口波尔多梅多克法定产区AOC级 鹏斐伯爵干红葡萄酒750ml*6"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-97077.html?source=94"
                      target="_blank"
                      title="【买一箱送一箱】法国原瓶进口波尔多梅多克法定产区AOC级 鹏斐伯爵干红葡萄酒750ml*6"
                    >
                      【买一箱送一箱】法国原瓶进口波尔多梅多克法定产区AOC级
                      鹏斐伯爵干红葡萄酒750ml*6</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="97077" class="jxIndex_nowPrice_97077"
                      >￥298.00</strong
                    ><span
                      ><em clubgoodid="97077"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="140012">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-140012.html?source=95"
                      target="_blank"
                      title="（列级庄·名庄·正牌）法国佳得美2017正牌红葡萄酒750ml"
                      ><img
                        src="https://img06.jiuxian.com/2020/1125/4e64bf23e9764cfdab30052b6de239462.jpg"
                        data-original="https://img06.jiuxian.com/2020/1125/4e64bf23e9764cfdab30052b6de239462.jpg"
                        width="160"
                        height="160"
                        alt="（列级庄·名庄·正牌）法国佳得美2017正牌红葡萄酒750ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-140012.html?source=95"
                      target="_blank"
                      title="（列级庄·名庄·正牌）法国佳得美2017正牌红葡萄酒750ml"
                    >
                      （列级庄·名庄·正牌）法国佳得美2017正牌红葡萄酒750ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="140012" class="jxIndex_nowPrice_140012"
                      >￥360.00</strong
                    ><span
                      ><em clubgoodid="140012"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="81982">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-81982.html?source=96"
                      target="_blank"
                      title="52°洋河蓝色经典天之蓝520ml"
                      ><img
                        src="https://img06.jiuxian.com/2019/0104/161e9a8366fb4a6186ce65dadb74c3612.jpg"
                        data-original="https://img06.jiuxian.com/2019/0104/161e9a8366fb4a6186ce65dadb74c3612.jpg"
                        width="160"
                        height="160"
                        alt="52°洋河蓝色经典天之蓝520ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-81982.html?source=96"
                      target="_blank"
                      title="52°洋河蓝色经典天之蓝520ml"
                    >
                      52°洋河蓝色经典天之蓝520ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="81982" class="jxIndex_nowPrice_81982"
                      >￥329.00</strong
                    ><span
                      ><em clubgoodid="81982"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="80122">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-80122.html?source=97"
                      target="_blank"
                      title="52°剑南春750ml"
                      ><img
                        src="https://img06.jiuxian.com/2019/0508/f89d6d7b931f40f48f89aca5539147942.jpg"
                        data-original="https://img06.jiuxian.com/2019/0508/f89d6d7b931f40f48f89aca5539147942.jpg"
                        width="160"
                        height="160"
                        alt="52°剑南春750ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-80122.html?source=97"
                      target="_blank"
                      title="52°剑南春750ml"
                    >
                      52°剑南春750ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="80122" class="jxIndex_nowPrice_80122"
                      >￥859.00</strong
                    ><span
                      ><em clubgoodid="80122"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="63907">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-63907.html?source=98"
                      target="_blank"
                      title="【酒厂直营】扳倒井 52度白酒 1号样酒  浓香型 500ml*4瓶 整箱装"
                      ><img
                        src="https://img06.jiuxian.com/2021/1115/88685b7311934a2c86118abf031d78422.jpg"
                        data-original="https://img06.jiuxian.com/2021/1115/88685b7311934a2c86118abf031d78422.jpg"
                        width="160"
                        height="160"
                        alt="【酒厂直营】扳倒井 52度白酒 1号样酒  浓香型 500ml*4瓶 整箱装"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-63907.html?source=98"
                      target="_blank"
                      title="【酒厂直营】扳倒井 52度白酒 1号样酒  浓香型 500ml*4瓶 整箱装"
                    >
                      【酒厂直营】扳倒井 52度白酒 1号样酒 浓香型 500ml*4瓶
                      整箱装</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="63907" class="jxIndex_nowPrice_63907"
                      >￥99.00</strong
                    ><span
                      ><em clubgoodid="63907"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="653">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-653.html?source=99"
                      target="_blank"
                      title="人头马（Rémy Martin）洋酒 X.O优质香槟区干邑白兰地 700ml"
                      ><img
                        src="https://img06.jiuxian.com/2021/1112/9d2c1a09ac71429a870e877c639740172.jpg"
                        data-original="https://img06.jiuxian.com/2021/1112/9d2c1a09ac71429a870e877c639740172.jpg"
                        width="160"
                        height="160"
                        alt="人头马（Rémy Martin）洋酒 X.O优质香槟区干邑白兰地 700ml"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-653.html?source=99"
                      target="_blank"
                      title="人头马（Rémy Martin）洋酒 X.O优质香槟区干邑白兰地 700ml"
                    >
                      <i class="zhenxuan"></i>
                      人头马（Rémy Martin）洋酒 X.O优质香槟区干邑白兰地 700ml</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="653" class="jxIndex_nowPrice_653"
                      >￥1398.00</strong
                    ><span
                      ><em clubgoodid="653"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
                <li product-box="143268">
                  <div class="indexTabPic">
                    <a
                      href="https://www.jiuxian.com/goods-143268.html?source=100"
                      target="_blank"
                      title="53°郎酒珍品酱香型白酒礼盒装500ml*2"
                      ><img
                        src="https://img06.jiuxian.com/2021/1115/79c859d385a14bd1b454fb2224d8dcb52.jpg"
                        data-original="https://img06.jiuxian.com/2021/1115/79c859d385a14bd1b454fb2224d8dcb52.jpg"
                        width="160"
                        height="160"
                        alt="53°郎酒珍品酱香型白酒礼盒装500ml*2"
                        style="display: inline"
                      />
                    </a>
                  </div>
                  <div class="indexTabTit">
                    <a
                      href="https://www.jiuxian.com/goods-143268.html?source=100"
                      target="_blank"
                      title="53°郎酒珍品酱香型白酒礼盒装500ml*2"
                    >
                      53°郎酒珍品酱香型白酒礼盒装500ml*2</a
                    >
                  </div>
                  <div class="indexTabPrice homegoodPrice">
                    <strong goodid="143268" class="jxIndex_nowPrice_143268"
                      >￥538.00</strong
                    ><span
                      ><em clubgoodid="143268"></em><i class="clubIcon"></i
                    ></span>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="indexTabRight">
          <div class="indexTabNew">
            <div class="indexTabNewNav">
              <ul>
                <li class="s1 os">公告信息</li>
                <li class="s2">促销信息</li>
              </ul>
            </div>
            <div class="indexTabNewCon">
              <div
                name="__home_gonggao"
                class="indexTabNewList"
                style="display: block"
              >
                <!-- 公告信息Start -->
                <ul class="clearfix">
                  <li>
                    <a
                      href="https://help.jiuxian.com/show-446.htm"
                      target="_blank"
                      title="停运公告"
                      rel="nofollow"
                      >停运公告</a
                    >
                  </li>
                  <li>
                    <a
                      href="https://help.jiuxian.com/show-439.htm"
                      target="_blank"
                      title="关于庄藏酱酒"
                      rel="nofollow"
                      >关于庄藏酱酒</a
                    >
                  </li>
                  <li>
                    <a
                      href="https://help.jiuxian.com/show-435.htm"
                      target="_blank"
                      title="club会员权益新"
                      rel="nofollow"
                      >club会员权益新</a
                    >
                  </li>
                  <li>
                    <a
                      href="https://help.jiuxian.com/show-217.htm"
                      target="_blank"
                      title="关于不法分子冒充酒仙网员工推销酒水"
                      rel="nofollow"
                      >关于不法分子冒充酒仙网员工推销酒水</a
                    >
                  </li>
                  <li>
                    <a
                      href="https://help.jiuxian.com/show-319.htm"
                      target="_blank"
                      title="酒仙网对外开放入驻公告"
                      rel="nofollow"
                      >酒仙网对外开放入驻公告</a
                    >
                  </li>
                </ul>
                <!-- 公告信息End -->
              </div>
              <div
                name="__home_cuxiao"
                class="indexTabNewList"
                style="display: none"
              >
                <!-- 促销信息文字广告Start -->
                <ul class="clearfix">
                  <li>
                    <a
                      href="https://shop.jiuxian.com/index-1312.htm?isPreview=1"
                      target="_blank"
                      title="飞天1499限量抢 速来查看"
                      rel="nofollow"
                      >飞天1499限量抢 速来查看</a
                    >
                  </li>
                  <li>
                    <a
                      href="http://shop.jiuxian.com/brand-386/activity-5024.htm?source=23"
                      target="_blank"
                      title="七窖优品 买一送一"
                      rel="nofollow"
                      >七窖优品 买一送一</a
                    >
                  </li>
                  <li>
                    <a
                      href="http://shop.jiuxian.com/brand-381/activity-3796.htm?source=2"
                      target="_blank"
                      title="爆款推荐"
                      rel="nofollow"
                      >爆款推荐</a
                    >
                  </li>
                </ul>
                <!-- 促销信息文字广告End -->
              </div>
            </div>
          </div>
          <div class="indexTuanBox mt10 sliderBox">
            <div name="__home_youlun1" class="indexTuanList">
              <ul class="bigUl" style="margin-left: -268px">
                <li>
                  <a
                    href="http://www.jiuxian.com/goods-96484.html?source=101"
                    target="_blank"
                    rel="nofollow"
                    ><img
                      src="http://img08.jiuxian.com/bill/2021/0119/2509e0eb5b1141ccbfe8456d5ac90a49.jpg"
                      _src=""
                      width="268"
                      height="157"
                  /></a>
                </li>
                <li>
                  <a
                    href="https://www.jiuxian.com/goods-547290.html?source=102"
                    target="_blank"
                    rel="nofollow"
                    ><img
                      src="http://img07.jiuxian.com/bill/2021/0204/4fedadd54a2a4373ab0e8acbfc9c44c5.jpg"
                      _src=""
                      width="268"
                      height="157"
                  /></a>
                </li>

                <li>
                  <a
                    href="http://www.jiuxian.com/goods-96484.html?source=103"
                    target="_blank"
                    rel="nofollow"
                    ><img
                      src="http://img08.jiuxian.com/bill/2021/0119/2509e0eb5b1141ccbfe8456d5ac90a49.jpg"
                      _src=""
                      width="268"
                      height="157"
                  /></a>
                </li>
                <li>
                  <a
                    href="https://www.jiuxian.com/goods-547290.html?source=104"
                    target="_blank"
                    rel="nofollow"
                    ><img
                      src="https://img01.jiuxian.com/img1/loading.gif"
                      _src="http://img07.jiuxian.com/bill/2021/0204/4fedadd54a2a4373ab0e8acbfc9c44c5.jpg"
                      width="268"
                      height="157"
                  /></a>
                </li>
              </ul>
            </div>
            <div class="btnBox smallUl">
              <span class="btnBg">
                <em class="">1</em>
                <em class="on">2</em>
              </span>
            </div>
          </div>
          <div class="indexTuanBox mt10 sliderBox">
            <div name="__home_youlun1" class="indexTuanList">
              <ul class="bigUl" style="margin-left: -268px">
                <li>
                  <a
                    href="http://www.jiuxian.com/goods-96484.html?source=101"
                    target="_blank"
                    rel="nofollow"
                    ><img
                      src="http://img08.jiuxian.com/bill/2021/0119/2509e0eb5b1141ccbfe8456d5ac90a49.jpg"
                      _src=""
                      width="268"
                      height="157"
                  /></a>
                </li>
                <li>
                  <a
                    href="https://www.jiuxian.com/goods-547290.html?source=102"
                    target="_blank"
                    rel="nofollow"
                    ><img
                      src="http://img07.jiuxian.com/bill/2021/0204/4fedadd54a2a4373ab0e8acbfc9c44c5.jpg"
                      _src=""
                      width="268"
                      height="157"
                  /></a>
                </li>

                <li>
                  <a
                    href="http://www.jiuxian.com/goods-96484.html?source=103"
                    target="_blank"
                    rel="nofollow"
                    ><img
                      src="http://img08.jiuxian.com/bill/2021/0119/2509e0eb5b1141ccbfe8456d5ac90a49.jpg"
                      _src=""
                      width="268"
                      height="157"
                  /></a>
                </li>
                <li>
                  <a
                    href="https://www.jiuxian.com/goods-547290.html?source=104"
                    target="_blank"
                    rel="nofollow"
                    ><img
                      src="https://img01.jiuxian.com/img1/loading.gif"
                      _src="http://img07.jiuxian.com/bill/2021/0204/4fedadd54a2a4373ab0e8acbfc9c44c5.jpg"
                      width="268"
                      height="157"
                  /></a>
                </li>
              </ul>
            </div>
            <div class="btnBox smallUl">
              <span class="btnBg">
                <em class="">1</em>
                <em class="on">2</em>
              </span>
            </div>
          </div>
          <div class="mt10">
            <div name="__home_youlun2" class="indexAdFocusList">
              <ul class="indexAdFocusWrap" style="margin-left: -536px"></ul>
            </div>
          </div>
        </div>
      </div>
      <div class="indexAdBox">
        <p>
          <img
            src="http://img09.jiuxian.com/bill/2021/0204/9f315ca4299a47d8be759c2d03b15f4a.png"
            alt=""
          />
        </p>
        <p>
          <img
            src="http://img09.jiuxian.com/bill/2021/0204/9f315ca4299a47d8be759c2d03b15f4a.png"
            alt=""
          />
        </p>
        <p>
          <img
            src="http://img09.jiuxian.com/bill/2021/0204/9f315ca4299a47d8be759c2d03b15f4a.png"
            alt=""
          />
        </p>
      </div>
      <div class="mt11">
        <div class="titlebox">
          <span>优惠推荐</span>
          <div class="rightNavBox">
            <span class="osn"></span>
            <span></span>
            <span></span>
          </div>
        </div>
        <div class="raceList">
          <div class="nm">
            <li>
              <div class="raceListPic">
                <img
                  src="https://img08.jiuxian.com/2019/1105/c53e5541498b4eeeae1797093a91a6df2.jpg"
                  alt=""
                />
              </div>
              <div class="raceListTit">52°泸州老窖六年窖头曲500ml（6瓶装）</div>
              <div class="raceListPrice">￥509.00</div>
            </li>
            <li>
              <div class="raceListPic">
                <img
                  src="https://img08.jiuxian.com/2019/1105/c53e5541498b4eeeae1797093a91a6df2.jpg"
                  alt=""
                />
              </div>
              <div class="raceListTit">52°泸州老窖六年窖头曲500ml（6瓶装）</div>
              <div class="raceListPrice">￥509.00</div>
            </li>
            <li>
              <div class="raceListPic">
                <img
                  src="https://img08.jiuxian.com/2019/1105/c53e5541498b4eeeae1797093a91a6df2.jpg"
                  alt=""
                />
              </div>
              <div class="raceListTit">52°泸州老窖六年窖头曲500ml（6瓶装）</div>
              <div class="raceListPrice">￥509.00</div>
            </li>
            <li>
              <div class="raceListPic">
                <img
                  src="https://img08.jiuxian.com/2019/1105/c53e5541498b4eeeae1797093a91a6df2.jpg"
                  alt=""
                />
              </div>
              <div class="raceListTit">52°泸州老窖六年窖头曲500ml（6瓶装）</div>
              <div class="raceListPrice">￥509.00</div>
            </li>
            <li>
              <div class="raceListPic">
                <img
                  src="https://img08.jiuxian.com/2019/1105/c53e5541498b4eeeae1797093a91a6df2.jpg"
                  alt=""
                />
              </div>
              <div class="raceListTit">52°泸州老窖六年窖头曲500ml（6瓶装）</div>
              <div class="raceListPrice">￥509.00</div>
            </li>
            <li>
              <div class="raceListPic">
                <img
                  src="https://img08.jiuxian.com/2019/1105/c53e5541498b4eeeae1797093a91a6df2.jpg"
                  alt=""
                />
              </div>
              <div class="raceListTit">52°泸州老窖六年窖头曲500ml（6瓶装）</div>
              <div class="raceListPrice">￥509.00</div>
            </li>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import Swiper from "swiper";
import "swiper/css/swiper.css";

export default {
  name: "Home",
  data() {
    return {
      currentIndex: 0,
      list: [
        {
          id: 1,
          title: "疯狂抢购",
        },
        {
          id: 2,
          title: "爆款推荐",
        },
        {
          id: 3,
          title: "居家小酌",
        },
        {
          id: 4,
          title: "整箱钜惠",
        },
        {
          id: 5,
          title: "限量大牌",
        },
      ],
    };
  },

  mounted() {
    new Swiper(".swiper-container", {
      pagination: ".swiper-pagination",
      slidesPerView: 1,
      paginationClickable: true,
      spaceBetween: 30,
      loop: true,
    });
  },
  methods: {
    change(index) {
      this.currentIndex = index;
    },
  },
};
</script>
<style lang="scss" scoped>
#app {
  width: 100%;
  .header {
    width: 100%;
    background: #f2f2f2;
    border-bottom: 1 px solid #e5e5e5;
    height: 26px;
    .minheader {
      width: 1200px;
      height: 26px;
      margin: 0 auto;
      .hleft {
        width: 370px;
        height: 26px;
        float: left;
        color: #999;
        font-size: 12px;
        span {
          margin-right: 6px;
          line-height: 26px;
          float: left;
        }
        a {
          margin-right: 6px;
          line-height: 26px;
          float: left;
          color: #999;
        }

        a:hover {
          color: #cc0000;
        }
      }
      .hright {
        width: 678px;
        height: 26px;
        float: right;
        font-size: 12px;
        span {
          padding: 0 4px 0 7px;
          border-left: 1 px solid #f2f2f2;
          border-right: 1 px solid #f2f2f2;

          a {
            margin-right: 6px;
            line-height: 26px;
            color: #999;
          }

          a:hover {
            color: #cc0000;
          }
        }
      }
    }
  }
  .topFocusBox {
    width: 100%;
    height: 90px;
    img {
      display: block;
      width: 1519.2px;
      height: 90px;
      overflow: hidden;
    }
  }
  .search {
    width: 100%;
    height: 125px;
    .searchicon {
      width: 1200px;
      height: 125px;
      margin: 0 auto;
      .leftimg {
        width: 257 px;
        height: 65 px;
        margin-top: 30px;
        overflow: hidden;
        float: left;
        img {
          width: 137 px;
          height: 65 px;
          margin-right: 10px;
          display: inline-block;
        }
      }
      .mainsearch {
        width: 540px;
        height: 61px;
        margin: 32px 0 0 20px;
        float: left;
        .searchHome {
          height: 38px;
          border: 3px solid #c00;
          position: relative;
          z-index: 222;
          width: 534px;
          form {
            .search-form {
              width: 439px;
              height: 33px;
              line-height: 33px;
              padding: 5px;
              border: 0 none;
              color: #666;
              float: left;
            }

            .search-btn {
              width: 85px;
              height: 32px;
              line-height: 32px;
              text-align: center;
              font-size: 16px;
              color: rgb(255, 255, 255);
              cursor: pointer;
              font-family: 微软雅黑;
              float: right;
              border-width: 0px;
              border-style: initial;
              border-color: initial;
              border-image: initial;
              background: rgb(204, 0, 0);
            }
          }
        }
        .hotWords {
          height: 18px;
          padding-top: 5px;
          width: 540px;
          p {
            height: 18px;
            line-height: 18px;
            overflow: hidden;
            white-space: nowrap;
            position: relative;
            left: -8px;
            z-index: 1;
            a {
              float: left;
              color: #999;
              padding: 0 8px;
              height: 18px;
              position: relative;
              font-size: 12px;
              s {
                display: block;
                height: 12px;
                width: 0;
                font-size: 0;
                line-height: 0;
                border-left: 1px solid #999;
                position: absolute;
                left: -1px;
                top: 3px;
              }
            }
          }
        }
      }
      .headerProtect {
        width: 363px;
        float: right;
        height: 64px;
        margin: 33px 0 0 0;
        background: url(https://misc.jiuxian.com/img/newIndexImg/headerProPic1.png)
          no-repeat top left;
        a {
          display: inline-block;
          width: 106 px;
          height: 43 px;
          margin-left: 15 px;
        }
      }
    }
  }
  .navWrap {
    width: 100%;
    background: #900;
    height: 34px;
    .nav {
      height: 34 px;
      margin: 0 auto;
      position: relative;
      z-index: 99;
      width: 1200px;
      .navCategoryMenu {
        width: 190 px;
        float: left;
        position: relative;
        z-index: 200;
        h2 {
          width: 190px;
          height: 34px;
          line-height: 34px;
          text-align: center;
          cursor: pointer;
          font-family: 微软雅黑;
          font-size: 14px;
          color: rgb(255, 255, 255);
          font-weight: 600;
          box-shadow: rgba(0, 0, 0, 0.2) 4px 2px 5px;
          background: rgb(206, 23, 31);
        }
        .categoryBox {
          width: 190px;
          height: 470px;
          border: none;
          position: absolute;
          top: 34px;
          left: 0px;
          z-index: 99;
          .last {
            height: 65px;
          }
          li {
            float: left;
            width: 190px;
            height: 81px;
            background: #fff;
            border-bottom: 1px solid #e4e4e4;

            .catItemCon {
              width: 163px;
              height: 81px;
              padding: 0 10px;
              border-left: 3px solid #fff;
              h3 {
                line-height: 32px;
                height: 32px;
                font-size: 14px;
                overflow: hidden;
                font-weight: normal;
                padding-top: 3px;
                color: #333;
                i {
                  display: inline-block;
                  width: 14px;
                  height: 20px;
                  margin-right: 10px;
                  vertical-align: middle;
                  position: relative;
                  top: -1px;
                }
                a {
                  color: #666;
                }
                a:hover {
                  color: #333;
                }
              }
              .categoryCon {
                width: 163px;
                overflow: hidden;
                position: relative;
                p {
                  width: 170px;
                  height: 20px;
                  overflow: hidden;
                  margin: 0;
                  a {
                    height: 16px;
                    line-height: 16px;
                    font-size: 12px;
                    padding: 0 4px;
                    color: #666;
                    float: left;
                    margin: 2px 3px 2px 0;
                  }
                  .on {
                    background: #f90;
                    color: rgb(92, 75, 75);
                    border-radius: 3px;
                    line-height: 16px;
                  }
                }
              }
            }
          }
        }
        .mav {
          height: 470px;
          position: absolute;
          top: 34px;
          width: 190px;
          left: 1010px;
          z-index: 7;
          background: lavender;
          img {
            z-index: 8;
            display: block;
            height: 156px;
            position: relative;
            margin-bottom: 1px;
          }
        }
      }
      .navList {
        width: 890 px;
        height: 34px;
        float: left;
        li {
          height: 34px;
          line-height: 34px;
          text-align: center;
          float: left;
          position: relative;
          z-index: 203;
          a {
            display: inline-block;
            height: 34px;
            color: rgb(255, 255, 255);
            font-size: 14px;
            padding: 0 22px;
          }
        }
        li:hover {
          background: #ce171f;
        }
      }
      .navright {
        width: 120px;
        height: 34px;
        overflow: hidden;
        position: absolute;
        right: 0;
        top: 0;
      }
    }
  }

  .swiper-container {
    width: 100%;
    height: 470px;
    position: relative;
    top: -14px;
    .swiper-slide {
      text-align: center;
      font-size: 18px;
      /* Center slide text vertically */
      display: -webkit-box;
      display: -ms-flexbox;
      display: -webkit-flex;
      display: flex;
      -webkit-box-pack: center;
      -ms-flex-pack: center;
      -webkit-justify-content: center;
      justify-content: center;
      -webkit-box-align: center;
      -ms-flex-align: center;
      -webkit-align-items: center;
      align-items: center;
      img {
        width: 100%;
        height: 470px;
        position: absolute;
        left: 0;
        top: 0;
      }
    }
    .swiper-pagination-bullet {
      width: 20px;
      height: 20px;
      text-align: center;
      line-height: 20px;
      font-size: 12px;
      color: #000;
      opacity: 1;
      background: rgba(0, 0, 0, 0.2);
    }
    .swiper-pagination-bullet-active {
      color: #fff;
      background: #007aff;
    }
  }

  .mainWrap {
    width: 100%;
    height: 1000px;
    background: #f9f9f9;
    .clearfixs {
      width: 1200px;
      height: 500px;
      margin: 0 auto;
      .indexTabBox {
        width: 920px;
        float: left;
        background: #fff;
        height: 499 px;
        .indexTabNav {
          overflow: hidden;
          width: 920px;
          height: 38px;
          position: relative;
          ul {
            .active {
              color: #cc0000;
              border-top: 2px solid #cc0000;
              border-bottom: 1px solid #fff;
              height: 35px;
              background: #fff;
            }
            li {
              height: 35px;
              cursor: pointer;
              text-align: center;
              line-height: 35px;
              font-size: 16px;
              color: rgb(102, 102, 102);
              float: left;
              font-family: 微软雅黑;
              border-left: 1px solid rgb(236, 236, 236);
              border-right: 1px solid rgb(236, 236, 236);
              border-bottom: 1px solid rgb(236, 236, 236);
              border-top: 2px solid rgb(236, 236, 236);
              background: rgb(249, 249, 249);
            }
            .on {
              width: 183px;
              height: 32px;
              color: #666;
              line-height: 35px;
              background: #fff;
            }
          }
        }
        .current {
          display: block;
        }
        .indexTabConWrap {
          border: 1px solid #ececec;
          border-top: none;
          height: 460px;
          overflow: hidden;
          .indexTabCon {
            height: 442px;
            margin: 0 auto;
            padding: 10px 0;
            overflow: hidden;
            position: relative;
            width: 910px;
            .clearfix1 {
              height: 432px;
              li {
                width: 182px;
                float: left;
                height: 196px;
                margin-top: 20px;
                a {
                  color: #666;
                  overflow: hidden;
                  font-size: 12px;
                }
                .indexTabPic {
                  position: relative;
                  z-index: 9;
                  width: 160px;
                  padding: 0 11px;
                }
                .indexTabTit {
                  width: 170px;
                  padding: 0 6px;
                  height: 18px;
                  line-height: 18px;
                  text-overflow: ellipsis;
                  overflow: hidden;
                  white-space: nowrap;

                  a {
                    color: #666;
                    overflow: hidden;
                  }
                }
                .indexTabPrice {
                  width: 170px;
                  padding: 0 6px;
                  height: 18px;
                  line-height: 18px;
                  overflow: hidden;
                  white-space: nowrap;
                  z-index: 10;
                  strong {
                    color: #cd0100;
                  }
                }
              }
            }
          }
        }
      }
      .indexTabRight {
        width: 270px;
        float: right;
        height: 500px;
        .indexTabNew {
          width: 270px;
          height: 140px;
          background: #fff;
          overflow: hidden;
          .indexTabNewNav {
            height: 35px;
            position: relative;
            ul {
              li {
                font-size: 16px;
                font-family: 微软雅黑;
                color: rgb(102, 102, 102);
                text-align: center;
                width: 133px;
                height: 35px;
                line-height: 35px;
                position: absolute;
                top: 0px;
                cursor: pointer;
                border-width: 1px;
                border-style: solid;
                border-color: rgb(236, 236, 236);
                border-image: initial;
                background: rgb(249, 249, 249);
              }
              .s1 {
                left: 0;
                width: 133px;
              }
              .s2 {
                left: 135px;
                width: 133px;
              }
              .os {
                border-top: 2px solid #c41921;
                border-bottom: 1px solid #fff;
                height: 34px;
                color: #cc0000;
                line-height: 33px;
                background: #fff;
              }
            }
          }
          .indexTabNewCon {
            border: 1px solid #ececec;
            border-top: none;
            height: 95px;
            padding-top: 10px;
            .indexTabNewList {
              width: 258px;
              margin: 0 auto;
              ul {
                margin-bottom: 0;
                li {
                  float: left;
                  width: 114px;
                  margin-left: 10px;
                  display: inline;
                  text-overflow: ellipsis;
                  overflow: hidden;
                  white-space: nowrap;
                  line-height: 28px;
                  a {
                    color: #666;
                    font-size: 12px;
                  }
                }
              }
            }
          }
        }
        .indexTuanBox {
          width: 268px;
          height: 157px;
          border: 1px solid #ececec;
          background: #fff;
          overflow: hidden;
          position: relative;
          z-index: 1;
          margin-top: 22px;
          .indexTuanList {
            width: 268px;
            height: 157px;
            overflow: hidden;
            position: relative;
            ul {
              li {
                float: left;
                width: 268px;
                height: 157px;
                position: relative;
                a {
                  color: #666;
                }
              }
            }
          }
        }
      }
    }
    .indexAdBox {
      width: 1200px;
      height: 130px;
      margin: 20px auto 0;
      background: #fff;
      p {
        float: left;
        margin: 0 0 0 90px;
      }
    }
    .mt11 {
      width: 1200px;
      height: 299px;
      margin: 10px auto;
      .titlebox {
        width: 1194px;
        height: 40px;
        padding: 0 3px;
        span {
          width: 98px;
          height: 20px;
          margin-top: 10px;
          float: left;
          font-size: 17px;
        }
        .rightNavBox {
          width: 69px;
          height: 9px;
          float: right;
          span {
            width: 9px;
            height: 9px;
            background: #ccc;
            margin-left: 14px;
            cursor: pointer;
          }
          .osn {
            background: #cc0000;
          }
        }
      }
      .raceList {
        width: 1200px;
        height: 257px;
        margin: 0 auto;
        .nm {
          width: 1200px;
          height: 226px;
          background-color: #fff;
          li {
            width: 198px;
            height: 196px;
            margin: 20px 0 10px 0;
            float: left;
            .raceListPic {
              width: 160px;
              height: 160px;
              padding: 0 19px;
              img {
                width: 160px;
                height: 160px;
              }
            }
            .raceListTit {
              color: #666;
              font-size: 12px;
              overflow: hidden;
              text-overflow: ellipsis;
              white-space: nowrap;
            }
            .raceListPrice {
              color: #cd0100;
              font-size: 15px;
            }
          }
        }
      }
    }
  }
}
</style>
