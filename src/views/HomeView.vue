<template>
  <div
    class="lg:bg-[url('@/assets/images/home-header.png')] md:py-[296px] py-36 bg-[url('@/assets/images/home-header-sm.png')] bg-cover w-full bg-no-repeat ">
    <div class="container">
      <div class="text-right">
        <h2 class=" md:text-4xl text-primary-default  text-right">Promise-Desert 2020 早春系列</h2>
        <span class="md:text-7xl text-primary-default  text-2xl font-bold">看得清，才能看得遠</span>
        <div class="text-right">
          <button class="btn-primary text-xl py-[6px] px-3 mt-2">
            <router-link :to="{ name: 'Products' }">
              立即購買
            </router-link>
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="md:py-[80px] bg-secondary-default py-10 ">
    <div class="container">
      <h2 class="md:text-6xl md:mb-12  text-primary-default text-2xl font-bold text-center ">用專業的心，做專業的事</h2>
      <ul class="lg:grid-cols-4 md:grid md:grid-cols-2 md:gap-6 md:flex-row flex justify-center flex-col">
        <li class=" text-center ">
          <i class="icon icon-money mt-8 mb-6"></i>
          <p class=" text-primary-default text-2xl font-bold mb-2">
            單一價格
          </p>
          <span>
            無論任何度數皆不需追加費用即可擁有適合自己的薄型球面鏡片。
          </span>
        </li>
        <li class="text-center ">
          <i class="icon icon-clock  mt-8 mb-6"></i>
          <p class=" text-primary-default text-2xl font-bold mb-2">
            20 分鐘即可取件
          </p>
          <span>
            為了您的寶貴時間著想，以豐富專業知識與技術將結帳到交件的時間縮減至最快 20 分鐘即可完成。
          </span>
        </li>
        <li class=" text-center ">
          <i class="icon icon-favorite mt-8 mb-6"></i>
          <p class=" text-primary-default text-2xl font-bold mb-2">
            安心售後服務
          </p>
          <span>
            我們提供長達 120 天的保固售後服務，不限會員資格皆享有免費深層保養及專業維修服務。
          </span>
        </li>
        <li class="text-center">
          <i class="icon icon-glass mt-8 mb-6"></i>
          <p class=" text-primary-default text-2xl font-bold mb-2">
            關於鏡片
          </p>
          <span>
            使用世界知名頂級品牌，抗UV、防汙鍍膜薄型非球面鏡片。
          </span>
        </li>
      </ul>
    </div>
  </div>
  <div class="md:py-[80px] py-10 container">
    <h2 class="md:mb-12 md:text-6xl text-primary-default text-2xl font-bold text-center mb-6">經典系列鏡框</h2>
    <ul class="lg:grid-cols-3 grid grid-cols-1 md:gap-6 ">
      <li class=" mb-6">
        <img class="md:mx-auto mb-2" src="@/assets/images/home-section3-1.png" alt="OPTICAL">
        <p class=" text-primary-light text-5xl font-black italic text-center">OPTICAL</p>
      </li>
      <li class=" mb-6">
        <img class="md:mx-auto mb-2" src="@/assets/images/home-section3-2.png" alt="SUNGLASSES">
        <p class=" text-primary-light text-5xl font-black italic text-center">SUNGLASSES</p>
      </li>
      <li>
        <img class="md:mx-auto mb-2" src="@/assets/images/home-section3-3.png" alt="FUNCTIONAL">
        <p class=" text-primary-light text-5xl font-black italic text-center">FUNCTIONAL</p>
      </li>
    </ul>
  </div>
  <div class=" bg-[url('@/assets/images/index-bg-sm.png')] bg-cover w-full bg-no-repeat py-10">
    <div class="container">
      <h2 class="md:text-6xl md:mb-12 text-white text-2xl text-center mb-6 font-bold ">聯名設計鏡框</h2>
      <ul class="lg:grid-cols-2 lg:gap-0 grid grid-cols-1 gap-6">
        <li>
          <img class="md:hidden block" src="@/assets/images/home-section4-1-sm.png" alt="DOUBLE A+">
          <img class="md:block hidden w-full" src="@/assets/images/home-section4-1.png" alt="DOUBLE A+">
          <p class=" text-primary-light bg-white text-5xl font-black text-center py-2 ">DOUBLE A+</p>
        </li>
        <li>
          <img class="md:hidden block" src="@/assets/images/home-section4-2-sm.png" alt="YOUTH">
          <img class="md:block hidden w-full" src="@/assets/images/home-section4-2.png" alt="YOUTH">
          <p class=" text-primary-light bg-white text-5xl font-black text-center py-2 ">YOUTH</p>
        </li>
      </ul>
    </div>
  </div>
  <div class="md:py-[80px] py-10 container">
    <h2 class="md:text-6xl md:mb-12 text-primary-default text-2xl text-center mb-6 font-bold">顧客推薦</h2>
    <ul class="lg:grid-cols-4 md:grid md:grid-cols-2 md:gap-6">
      <li class=" mb-4 shadow-card">
        <img src="@/assets/images/home-section5-1.png" alt="">
        <div class=" flex justify-between flex-col  p-4 ">
          <div>
            <p class=" mb-2">Jessy</p>
            <p>眼鏡品質優良，下次還會想來這邊購買！</p>
          </div>
          <span class=" mt-12 text-gary text-sm">2021/06/20</span>
        </div>
      </li>
      <li class=" mb-4 shadow-card">
        <img src="@/assets/images/home-section5-2.png" alt="">
        <div class=" flex justify-between flex-col  p-4 ">
          <div>
            <p class=" mb-2">凱倫</p>
            <p>做工細緻、鏡架很輕盈，待久也不會覺得有負擔，推薦給大家！</p>
          </div>
          <span class=" mt-12 text-gary text-sm">2021/04/18</span>
        </div>
      </li>
      <li class=" mb-4 shadow-card">
        <img src="@/assets/images/home-section5-3.png" alt="">
        <div class=" flex justify-between flex-col  p-4 ">
          <div>
            <p class=" mb-2">悠悠</p>
            <p>謝謝客服人員的詳細回答，成功買到了喜歡的眼鏡，下次會再回購！</p>
          </div>
          <span class=" mt-12 text-gary text-sm">2020/12/25</span>
        </div>
      </li>
      <li class=" mb-4 shadow-card">
        <img src="@/assets/images/home-section5-4.png" alt="">
        <div class=" flex justify-between flex-col  p-4 ">
          <div>
            <p class=" mb-2">Kyuan</p>
            <p>服務很好，品質沒有任何問題，非常喜歡。</p>
          </div>
          <span class=" mt-12 text-gary text-sm">2020/10/31</span>
        </div>
      </li>
    </ul>
  </div>
  <div class="md:py-[80px] py-10 bg-secondary-default">
    <div class="container">
      <div class="lg:w-1/2 md:w-10/12 md:mx-auto">
        <h2 class="md:text-6xl text-primary-default text-2xl text-center mb-6 font-bold">聯絡我們</h2>
        <p class=" mb-6">我們相當重視您的意見，若您有任何疑問，可先參考「常見問題」，若仍有任何問題，請填妥以下資料，我們會在近期與您聯繫。</p>
        <div class=" mb-4">
          <label class=" block mb-2 " for="name">姓名</label>
          <input class=" block w-full  py-[6px] pl-3 border border-black" type="text" id="name" placeholder="陳小明">
        </div>
        <div class=" mb-4">
          <label class=" block mb-2 " for="phone">聯絡電話</label>
          <input class=" block w-full  py-[6px] pl-3 border border-black" type="tel" id="phone"
            placeholder="0912-345-678">
        </div>
        <div class=" mb-4">
          <label class=" block mb-2 " for="mail">電子郵件</label>
          <input class=" block w-full  py-[6px] pl-3 border border-black" type="email" id="mail"
            placeholder="example@email.com">
        </div>
        <div class=" mb-4">
          <label class=" block mb-2 " for="feeback">意見反應</label>
          <textarea class=" block w-full  py-[6px] pl-3 border border-black" id="feeback" cols="30" rows="5"
            placeholder="請輸入您的意見"></textarea>
        </div>
        <div class=" mb-6 flex items-start">
          <input class="mr-1 block w-6 h-6" type="checkbox" id="check">
          <label for="check">我同意隱私權政策，並同意依隱私權政策中所述的方式處理自己的資料。</label>
        </div>
        <button class="md:w-1/2 md:mx-auto md:block md:mt-12  btn-primary py-4 w-full">確認送出</button>
      </div>
    </div>


  </div>
</template>

<script setup lang="ts">
</script>
