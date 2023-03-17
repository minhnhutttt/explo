<template>
    <button
        type="button"
        class="mb-2 flex h-[91px] w-full justify-between bg-white px-4 py-3.5 max-md:flex-col md:h-[86px] md:items-center md:px-6 md:py-5"
    >
        <div
            class="text-left max-md:space-x-2 max-md:leading-none md:flex md:w-[136px] md:flex-col"
        >
            <span class="inline-block w-9 text-sm md:hidden">TX#</span>
            <span
                class="truncate text-sm font-bold text-[#1242D5] max-md:inline-block max-md:w-[126px] max-md:leading-[0.8]"
                >0x4520e7ca5f30x4520e7ca5f3</span
            >
            <span class="mt-[5px] text-[13px] text-[#666]">16 secs ago</span>
        </div>
        <div
            class="flex items-center max-md:w-full max-md:items-end max-md:justify-between md:ml-6"
        >
            <div class="mr-4 md:mr-[50px]">
                <div class="text-left">
                    <span class="inline-block w-9 text-sm">From</span>
                    <span class="ml-2 text-sm font-bold text-[#1242D5]"
                        >0xDAFEA4…92c98Bc5</span
                    >
                </div>
                <div class="text-left">
                    <span class="inline-block w-9 text-sm">To</span>
                    <span class="ml-2 text-sm font-bold text-[#1242D5]"
                        >0xd4E96e…4F7605b7</span
                    >
                </div>
            </div>
            <div class="border border-[#CCC] px-2 py-[5px] text-xs font-bold">
                0.05422 Eth
            </div>
        </div>
    </button>
</template>
