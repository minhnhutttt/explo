<template>
    <button
        type="button"
        class="mb-2 flex h-[91px] w-full justify-between bg-white px-4 py-3.5 max-md:flex-col md:h-[86px] md:items-center md:px-6 md:py-5"
    >
        <div
            class="text-left max-md:space-x-1 max-md:leading-none md:flex md:w-[136px] md:flex-col"
        >
            <span class="text-sm md:hidden">Block</span>
            <span class="text-sm font-bold text-[#1242D5]">1668907</span>
            <span class="text-xs text-[#666] md:mt-[5px] md:text-[13px]"
                >16 secs ago</span
            >
        </div>
        <div
            class="flex items-center max-md:w-full max-md:items-end max-md:justify-between md:ml-6"
        >
            <div class="mr-4 md:mr-[50px]">
                <div class="text-left">
                    <span class="text-sm font-bold">Fee Recipient</span>
                    <span class="ml-2 text-sm font-bold text-[#1242D5]"
                        >beaverbuild</span
                    >
                </div>
                <div class="text-left leading-none">
                    <span class="text-sm font-bold text-[#1242D5]"
                        >149 txns</span
                    >
                    <span class="ml-1 text-xs text-[#666]">in 12 secs</span>
                </div>
            </div>
            <div class="border border-[#CCC] px-2 py-[5px] text-xs font-bold">
                0.04823 Eth
            </div>
        </div>
    </button>
</template>
