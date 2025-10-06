* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html,
body {
    width: 100%;
    height: 100%;
    margin: 25px;
}

.box1 {
    width: 200px;
    height: 200px;
    background-color: salmon;
}



/* .path {
    clip-path: path("M 10,40 L 70,40 A 10,10 ,0,0,0 80,30 L 80,10 A 10,10 ,0,0,1 90, 0 L 140,0 A 10,10 ,0,0,1 150,10 L 150,190 A 10,10 ,0,0,1 140,200 L 10,200 A 10,10 ,0,0,1 0,190 L 0 50 A 10,10 ,0,0,1 10,40 Z");
    transform: translate3d();
} */

.path {
    clip-path: path("M 10,40 L 70,40 A 10,10,0,0,0 80,30 L 80,10 A 10,10,0,0,1 90, 0 L 140,0 L 150,10 L 150,190 L 140,200 L 10,200 L 0,190 L 0 50 L 10,40 Z");

}

.path2 {
    /* clip-path: path("M 0,0 L 90,0 L 110,40 L 190,40 L 190,190 L 0,190  L 0,0 Z"); */
    clip-path: path("M 10,0 L 90,0 L 120,30 L 190,30 A 10,10,0,0,1 200,40 L 200,190 A 10,10,0,0,1 190,200 L 10,200 A 10,10,0,0,1 0,190 L 0,10 A 10,10,0,0,1 10,0 Z");
    width: 200px;
    height: 200px;
    background-color: rgb(196, 216, 107);

}



















 <div class="main bg-[#111] w-[100vw] h-[100vh] bg-no-repeat text-white">
      <!-- NAVBAR -->
      <nav class="main flex fixed top-0 left-0 w-full items-center justify-between px-20 py-4">
        <!-- Left nav side -->
        <div><p class="font-[jungle2] text-3xl">FREKISH MIND</p></div>

        <!-- center nav side -->
        <div class="flex text-2xl gap-4 px-10 py-2 rounded-full bg-[#222]">
          <a href="" class="text-[#d5f903] font-[jungle1]">Discover</a
          ><a href="" class="font-[jungle1]">MarketPlace</a><a href="" class="font-[jungle1]">About</a>
        </div>

        <!-- right nav side -->
        <div>
          <div class="flex items-center gap-4">
            <button><img src="/images/searchicon.png" alt="" /></button>
            <button class="border text-xl px-5 font-[jungle1] py-2 border-[#d5f903] rounded-full">
              Connect Wallet
            </button>
          </div>
        </div>
      </nav>
    </div>

    <div class="secmain bg-black text-white">
      <div class="flex justify-between px-20 py-4">
        <div>
          <p class="text-[#d5f903] text-xl">Trending</p>
          <p class="text-5xl">Auctions</p>
        </div>
        <div>
          <p>Buy and sell NFT's from the word's top artists,</p>
          <p>More than 10000 premium degiital</p>
        </div>
        <div class="flex items-center gap-4">
          <button class="px-3 py-3 bg-black border border-white rounded-md">
            <img src="/images/arrow-left-fill.png" alt="" /></button
          ><button class="px-3 py-3 bg-black border border-white rounded-md">
            <img src="/images/arrow-right-line.png" alt="" />
          </button>
        </div>
      </div>

      <div class="featuresec flex justify-center">
        <div>
          <div class="path2 bg-pink-400">
            <img src="/images/bgmoneky1.png" alt="" />
          </div>
          <div><button>BID NOW</button></div>
        </div>
      </div>
    </div>



 <div class="featuresec flex  justify-around">
          <!-- card 1 -->
          <div class="flex gap-4 items-center flex-col">
            <div class="p-5 bg-[#222]  rounded-lg">
              <div class="path2 pt-3 bg-purple-500">
                <img src="/images/bgmoneky1.png" class="" alt="" />
              </div>
            </div>
            <div>
              <button
                class="bg-[#222] text-xl px-10 py-2 text-white rounded-lg shadow-sm shadow-purple-500 cursor-pointer"
              >
                BID NOW
              </button>
            </div>
          </div>
          <!-- cart 2 -->
          <div class="flex gap-3 items-center flex-col">
            <div class="p-5 bg-[#222] rounded-lg">
              <div class="path2 pt-5 bg-[#d5f903]">
                <img src="/images/monkey3.png" alt="" />
              </div>
            </div>
            <div>
              <button
                class="bg-[#222] text-xl px-10 py-2 text-white rounded-lg shadow-sm shadow-[#d5f903] cursor-pointer"
              >
                BID NOW
              </button>
            </div>
          </div>

          <!-- card 3 -->
          <div class="flex gap-3 items-center flex-col">
            <div class="p-5 bg-[#222] rounded-lg">
              <div class="path2 pt-5 bg-[#f76c01]">
                <img src="/images/monkey2.png" alt="" />
              </div>
            </div>
            <div>
              <button
                class="bg-[#222] text-xl px-10 py-2 text-white rounded-lg shadow-sm shadow-[#f76c01] cursor-pointer"
              >
                BID NOW
              </button>
            </div>
          </div>
        </div>






    "# FreaskishMind" 
