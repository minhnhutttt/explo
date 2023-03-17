<template>
    <li>
        <a
            href="{{ link }}"
            class="group flex items-center text-sm font-bold text-white/[0.7] duration-300 hover:text-white max-lg:p-1 max-lg:text-xl"
            ><span class="mr-0.5">{{ text }}</span>
            <svg
                v-if="arrow"
                id="Icon-Arrowdown"
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
            >
                <path
                    id="Path_1"
                    data-name="Path 1"
                    d="M0,0H24V24H0Z"
                    fill="none"
                />
                <path
                    id="Path_2"
                    data-name="Path 2"
                    d="M12,13.172l4.95-4.95,1.414,1.414L12,16,5.636,9.636,7.05,8.222Z"
                    class="fill-white/[0.7] group-hover:fill-white"
                />
            </svg>
        </a>
    </li>
</template>
<script>
export default {
    props: {
        link: {
            type: String,
            required: true,
        },
        text: {
            type: String,
            required: true,
        },
        arrow: {
            type: Boolean,
            required: false,
            default: false,
        },
    },
}
</script>
