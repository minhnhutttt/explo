<template>
    <div class="flex gap-4 max-lg:flex-col md:gap-8 md:px-8">
        <div
            class="w-full border border-[#CCCCCC] bg-white/[0.5] p-4 pb-2 md:w-1/2 md:p-6 md:pb-4"
        >
            <div
                class="flex bg-white p-4 max-md:flex-col max-md:items-center max-md:justify-center"
            >
                <span class="">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="56"
                        height="56"
                        viewBox="0 0 56 56"
                    >
                        <g id="Symbol" transform="translate(-71 -286)">
                            <circle
                                id="Feild"
                                cx="28"
                                cy="28"
                                r="28"
                                transform="translate(71 286)"
                                fill="#1242d5"
                            />
                            <g
                                id="Icon-Dashboard"
                                transform="translate(83 298)"
                            >
                                <path
                                    id="Path_23"
                                    data-name="Path 23"
                                    d="M0,0H32V32H0Z"
                                    fill="none"
                                />
                                <path
                                    id="Path_24"
                                    data-name="Path 24"
                                    d="M15,2A13,13,0,1,1,2,15,13,13,0,0,1,15,2Zm0,2.6A10.4,10.4,0,1,0,25.4,15,10.4,10.4,0,0,0,15,4.6Zm4.983,4.338a.771.771,0,0,1,1.074,1.075q-4.251,5.94-4.677,6.366a1.951,1.951,0,1,1-2.759-2.759q.729-.727,6.362-4.683ZM22.15,13.7a1.3,1.3,0,1,1-1.3,1.3A1.3,1.3,0,0,1,22.15,13.7Zm-14.3,0A1.3,1.3,0,1,1,6.55,15,1.3,1.3,0,0,1,7.85,13.7Zm3.013-4.675a1.3,1.3,0,1,1-1.838,0A1.3,1.3,0,0,1,10.863,9.025ZM15,6.55a1.3,1.3,0,1,1-1.3,1.3A1.3,1.3,0,0,1,15,6.55Z"
                                    transform="translate(1 1)"
                                    fill="#fff"
                                />
                            </g>
                        </g>
                    </svg>
                </span>
                <div
                    class="flex max-md:mt-3 max-md:mb-1 max-md:w-full max-md:justify-between md:ml-8"
                >
                    <div class="font-bold">
                        <p class="mb-1 text-xs text-[#1242D5] md:text-sm">
                            LAST FINALIZED BLOCK
                        </p>
                        <p class="text-base text-[#222222]">16688965</p>
                    </div>
                    <div class="text-right font-bold md:ml-11">
                        <p class="mb-1 text-xs text-[#1242D5] md:text-sm">
                            LAST SAFE BLOCK
                        </p>
                        <p class="text-base text-[#222222]">16688997</p>
                    </div>
                </div>
            </div>
            <div class="flex items-center justify-between py-5">
                <p class="text-base font-bold">Lastest Blocks</p>
                <a
                    href="#"
                    class="flex items-center text-sm font-bold text-[#1242D5]"
                    >View All<svg
                        id="Icon-Arrow-r"
                        xmlns="http://www.w3.org/2000/svg"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                    >
                        <path
                            id="Path_25"
                            data-name="Path 25"
                            d="M0,0H24V24H0Z"
                            fill="none"
                        />
                        <path
                            id="Path_26"
                            data-name="Path 26"
                            d="M13.172,12,8.222,7.05,9.636,5.636,16,12,9.636,18.364,8.222,16.95Z"
                            fill="#1242d5"
                        />
                    </svg>
                </a>
            </div>
            <div class="">
                <template v-for="index in 6" :key="index">
                    <HomeTableBlock />
                </template>
            </div>
        </div>
        <div
            class="w-full border border-[#CCCCCC] bg-white/[0.5] p-4 pb-2 md:w-1/2 md:p-6 md:pb-4"
        >
            <div
                class="flex bg-white p-4 max-md:flex-col max-md:items-center max-md:justify-center"
            >
                <span class="">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="56"
                        height="56"
                        viewBox="0 0 56 56"
                    >
                        <g id="Symbol" transform="translate(-71 -286)">
                            <circle
                                id="Feild"
                                cx="28"
                                cy="28"
                                r="28"
                                transform="translate(71 286)"
                                fill="#1242d5"
                            />
                            <g id="Icon-Server" transform="translate(83 298)">
                                <path
                                    id="Path_21"
                                    data-name="Path 21"
                                    d="M0,0H32V32H0Z"
                                    fill="none"
                                />
                                <path
                                    id="Path_22"
                                    data-name="Path 22"
                                    d="M5.667,13.667H24.333v-8H5.667ZM27,4.333V25.667A1.333,1.333,0,0,1,25.667,27H4.333A1.333,1.333,0,0,1,3,25.667V4.333A1.333,1.333,0,0,1,4.333,3H25.667A1.333,1.333,0,0,1,27,4.333Zm-2.667,12H5.667v8H24.333ZM8.333,19h4v2.667h-4Zm0-10.667h4V11h-4Z"
                                    transform="translate(1 1)"
                                    fill="#fff"
                                />
                            </g>
                        </g>
                    </svg>
                </span>
                <div
                    class="flex max-md:mt-3 max-md:mb-1 max-md:w-full max-md:justify-between md:ml-8"
                >
                    <div class="font-bold">
                        <p class="mb-1 text-xs text-[#1242D5] md:text-sm">
                            TRANSACTIONS
                        </p>
                        <p class="text-base text-[#222222]">
                            1,882.40 M
                            <span class="text-sm font-light text-[#666]"
                                >(11.0TPS)</span
                            >
                        </p>
                    </div>
                    <div class="text-right font-bold md:ml-11">
                        <p class="mb-1 text-xs text-[#1242D5] md:text-sm">
                            MED GAS PRICE
                        </p>
                        <p class="text-base text-[#222222]">
                            29 Gwei
                            <span class="text-sm font-light text-[#666]"
                                >($1.02)</span
                            >
                        </p>
                    </div>
                </div>
            </div>
            <div class="flex items-center justify-between py-5">
                <p class="text-base font-bold">Latest Transactions</p>
                <a
                    href="#"
                    class="flex items-center text-sm font-bold text-[#1242D5]"
                    >View All<svg
                        id="Icon-Arrow-r"
                        xmlns="http://www.w3.org/2000/svg"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                    >
                        <path
                            id="Path_25"
                            data-name="Path 25"
                            d="M0,0H24V24H0Z"
                            fill="none"
                        />
                        <path
                            id="Path_26"
                            data-name="Path 26"
                            d="M13.172,12,8.222,7.05,9.636,5.636,16,12,9.636,18.364,8.222,16.95Z"
                            fill="#1242d5"
                        />
                    </svg>
                </a>
            </div>
            <div class="">
                <template v-for="index in 6" :key="index">
                    <HomeTableTransaction />
                </template>
            </div>
        </div>
    </div>
</template>

<script>
import HomeTableBlock from './HomeTableBlock.vue'
import HomeTableTransaction from './HomeTableTransaction.vue'
export default {
    components: {
        HomeTableBlock,
        HomeTableTransaction,
    },
}
</script>
