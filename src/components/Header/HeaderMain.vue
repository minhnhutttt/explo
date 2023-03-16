
<template>
    <div class="bg-[#0031C4] flex items-center justify-between h-[72px] px-8 fixed top-0 left-0 right-0">
        <a href="/">
            <img :src="require('@/assets/images/logo.png')" alt="">
        </a>
        <div class="flex items-center h-full space-x-6">
            <ul class="flex items-center space-x-6 max-lg:flex-col max-lg:justify-center max-lg:fixed max-lg:inset-0 max-lg:bg-[#0031C4]/[0.9]" :class="{ 'max-lg:hidden ': !isOpen, 'flex': isOpen }">
                <div class="flex items-center absolute top-4 right-8 lg:hidden">
                    <button @click="isOpen = !isOpen" class="inline-flex items-center justify-center p-2 bg-white/[0.1] rounded-full">
                        <span :class="{ 'hidden': !isOpen, 'inline-flex': isOpen }">
                            <svg class="h-6 w-6" stroke="white" fill="none" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                            </svg>
                        </span>
                    </button>
                </div>
                <HeaderNavLink link="#" text="Home"></HeaderNavLink>
                <HeaderNavLink link="#" text="Blockchain" arrow></HeaderNavLink>
                <HeaderNavLink link="#" text="Tokens" arrow></HeaderNavLink>
                <HeaderNavLink link="#" text="NFTs" arrow></HeaderNavLink>
                <HeaderNavLink link="#" text="Resources" arrow></HeaderNavLink>
                <HeaderNavLink link="#" text="Developers" arrow></HeaderNavLink>
                <HeaderNavLink link="#" text="More" arrow></HeaderNavLink>
            </ul>
            <a href="#" class="flex items-center justify-center bg-white/[0.1] rounded-lg py-2 px-3">
                <svg id="Icon-User" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
                    <path id="Path_9" data-name="Path 9" d="M0,0H24V24H0Z" fill="none"/>
                    <path id="Path_10" data-name="Path 10" d="M20,22H18V20a3,3,0,0,0-3-3H9a3,3,0,0,0-3,3v2H4V20a5,5,0,0,1,5-5h6a5,5,0,0,1,5,5Zm-8-9a6,6,0,1,1,6-6A6,6,0,0,1,12,13Zm0-2A4,4,0,1,0,8,7,4,4,0,0,0,12,11Z" fill="#fff"/>
                </svg>
                <span class="ml-2 text-sm font-bold text-white">Sign in</span>
            </a>
            <button type="button" class="p-2 bg-white/[0.1] rounded-full">
                <svg id="Icon-Light" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
                    <path id="Path_11" data-name="Path 11" d="M0,0H24V24H0Z" fill="none"/>
                    <path id="Path_12" data-name="Path 12" d="M12,18a6,6,0,1,1,6-6A6,6,0,0,1,12,18Zm0-2a4,4,0,1,0-4-4A4,4,0,0,0,12,16ZM11,1h2V4H11Zm0,19h2v3H11ZM3.515,4.929,4.929,3.515,7.05,5.636,5.636,7.05,3.515,4.93ZM16.95,18.364l1.414-1.414,2.121,2.121-1.414,1.414Zm2.121-14.85,1.414,1.415L18.364,7.05,16.95,5.636l2.121-2.121ZM5.636,16.95,7.05,18.364,4.929,20.485,3.515,19.071,5.636,16.95ZM23,11v2H20V11ZM4,11v2H1V11Z" transform="translate(0 0)" fill="#fff"/>
                </svg>
            </button>
            <div class="flex items-center lg:hidden">
                <button @click="isOpen = !isOpen" class="inline-flex items-center justify-center p-2 bg-white/[0.1] rounded-full">
                <span :class="{ 'hidden': isOpen, 'inline-flex': !isOpen }">
                    <svg id="Icon-Menu" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
                        <path id="Path_31" data-name="Path 31" d="M0,0H24V24H0Z" fill="none"/>
                        <path id="Path_32" data-name="Path 32" d="M3,4H21V6H3Zm0,7H21v2H3Zm0,7H21v2H3Z" fill="#fff"/>
                    </svg>
                </span>
                </button>
            </div>
        </div>
    </div>
</template>
<script>
import HeaderNavLink from './HeaderNavLink.vue';

export default {
    components: {
        HeaderNavLink
    },
    data() {
        return {
            isOpen: false
        }
    }
}
</script>