<template>
  <div
    class="flex flex-col items-center justify-center bg-cover pt-[72px]"
    :style="{
      backgroundImage: 'url(' + require('@/assets/images/bg.png') + ')',
    }"
  >
    <div class="w-[720px] pt-11 pb-12">
      <h2 class="text-center text-2xl font-semibold text-white">
        The Ethereum Blockchain Explorer
      </h2>
      <div
        class="relative mt-[22px] flex h-12 items-center rounded-lg bg-white"
      >
        <div class="relative flex-1">
          <input
            type="text"
            class="w-full border-0 pl-[50px] outline-none"
            placeholder="Search by Address / Txn Hash / Block / Token / Domain Name"
          />
          <span class="absolute left-4">
            <svg
              id="IconーSearch"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
            >
              <path
                id="Path_3"
                data-name="Path 3"
                d="M0,0H24V24H0Z"
                fill="none"
              />
              <path
                id="Path_4"
                data-name="Path 4"
                d="M16.2,14.952,20,18.746,18.746,20l-3.794-3.8A7.976,7.976,0,1,1,16.2,14.952Zm-1.777-.657a6.2,6.2,0,1,0-.133.133l.133-.133Z"
                transform="translate(1 1)"
                fill="#1739a0"
              />
            </svg>
          </span>
        </div>
        <div class="flex h-6 items-center border-l border-[#CCC] pl-6 pr-8">
          <button class="flex items-center">
            <svg
              id="Icon-Filter"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
            >
              <path
                id="Path_27"
                data-name="Path 27"
                d="M0,0H24V24H0Z"
                fill="none"
              />
              <path
                id="Path_28"
                data-name="Path 28"
                d="M10,18h4V16H10ZM3,6V8H21V6Zm3,7H18V11H6Z"
                fill="#1242d5"
              />
            </svg>
            <span class="text-sm text-[#222] ml-2">All Filters</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
