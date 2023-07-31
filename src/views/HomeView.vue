<template>
    <div style=" background-image:
        url('https://assets.nflxext.com/ffe/siteui/vlv3/5eab1b22-c5ea-48b0-8ef4-862b3fa6df2c/3805d282-3a68-4c43-9395-d7a81bbd6980/MX-en-20230724-popsignuptwoweeks-perspective_alpha_website_small.jpg');"
        class="w-full h-screen bg-center bg-no-repeat bg-cover">
        <div
            class="flex-col items-center justify-center w-full h-screen bg-gradient-to-b from-black via-transparent to-black">
            <div class="absolute px-3 text-center text-white top-32">
                <h1 class="text-3xl font-bold">Unlimited movies, TV shows, and more</h1>
                <p class="mt-8 text-lg">Watch anywhere. Cancel anytime.</p>
                <div class="h-48 px-12 mt-6">
                    <form class="flex flex-col items-center justify-around">
                        <h1 class="text-lg">Ready to watch? Enter your email to create or restart your membership.</h1>
                        <input class="w-full mt-4 bg-[rgba(48,46,46,60%)] border-[2px] border-[#767676] p-2 text-gray-900"
                            type="email" name="" placeholder="Email address" id="">

                        <button
                            class="mt-4 bg-[rgb(229,9,20)] font-medium w-34 justify-center items-center text-xl text-white font-bold px-4 shrink-0 grow-0 py-2 flex rounded-md">
                            Get Started
                            <div>
                                <Icon width="32" icon="iconamoon:arrow-right-2-light" />
                            </div>
                        </button>
                    </form>
                </div>
            </div>

        </div>

    </div>

    <div class="w-screen h-auto bg-black">

        <!-- radial-gradient(
            248.35% 220% at 49.86% -6.29%,
            #E50916 0%,
            #0e1b4f 46.15%,
            #0d1121 100%
        ) -->
        <div
            class="bg-gradient-to-b from-0% from-[#e50914] via-46% via-[#0e1b4f] to-[#0d1121] relative px-8 pt-12 pb-4 mx-4 text-white bg-yellow-800 rounded-md">
            <div class="absolute -top-14 left-12">
                <pop-corns></pop-corns>
            </div>
            <p class="text-xl font-bold">The Netflix you love for just MXN99.</p>
            <p class="mt-1 text-md">Get the Standard with ads plan.</p>
            <button>Learn More </button>
        </div>
    </div>
</template>

<script setup lang="ts">
import { Icon } from "@iconify/vue";
import PopCorns from "@/components/icons/PopCorns.vue";
</script>