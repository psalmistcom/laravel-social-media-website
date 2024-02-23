<script setup>
import FollowingItem from "@/Components/app/FollowingItem.vue"
import TextInput from "@/Components/TextInput.vue"
import { ref } from "vue";

const searchKeyword = ref('')
</script>

<template>
    <div class="bg-white px-3 rounded border py-3 h-[300px] lg:h-full overflow-hidden flex flex-col ">

        <h2 class="text-xl font-bold mb-4">My Followings</h2>
        <TextInput :model-value="searchKeyword" placeholder="Search followers" class="w-full" />
        <div class="mt-3 flex-1 overflow-auto">
            <div v-if="false" class="text-gray-400 text-center p-3">
                You don't have freinds yet
            </div>
            <div v-else>
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="John Doe"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <FollowingItem image="https://picsum.photos/100" title="Elon Musk"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
            </div>
        </div>
    </div>
</template>

<style></style>

