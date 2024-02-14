<script setup>
import GroupItem from "@/Components/app/GroupItem.vue"
import TextInput from "@/Components/TextInput.vue"
import { ref } from "vue";

const searchKeyword = ref('')
</script>

<template>
    <div class="bg-white px-3 rounded border py-3 h-full overflow-hidden flex flex-col ">
        <h2 class="text-xl font-bold mb-4">My Groups</h2>
        <TextInput :model-value="searchKeyword" placeholder="Search for groups" class="w-full" />
        <div class="mt-3 flex-1 overflow-auto">
            <div v-if="false" class="text-gray-400 text-center p-3">
                You are not joined to any groups
            </div>
            <div v-else>
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="Laravel Developer"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
                <GroupItem image="https://picsum.photos/100" title="VueJs Developers"
                    description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. " />
            </div>
        </div>
    </div>
</template>

<style></style>

