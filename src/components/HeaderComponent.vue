<template>
    <div class="flex items-center h-20 mx-6 bg-red-200">
        <span class="mr-auto">
            <Icon height="24" icon="logos:netflix" />
        </span>
        <span class="flex items-center justify-center w-16 h-8 mx-1 text-white border-[2px] border-[#767676] rounded-md">

            <Icon width="22" icon="jam:world" class="" />
            <select class="w-1 bg-transparent">
                <option>
                    English
                </option>
            </select>
            <Icon icon="octicon:triangle-down-16" />
        </span>
        <span class="ml-1">
            <button class="bg-[#E50914] text-white font-bold px-4 py-1 rounded-md">Sign In</button>
        </span>
    </div>
</template>

<script setup lang="ts">
import { Icon } from "@iconify/vue";
import { ref } from "vue";


</script>
