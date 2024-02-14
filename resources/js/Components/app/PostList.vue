<script setup>
import PostItem from './PostItem.vue';

const post1 = {
    user: {
        id: 1,
        avatar: 'https://randomuser.me/api/portraits/men/59.jpg',
        name: 'John Smith'
    },
    group: null,
    body: `
    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias, reprehenderit fuga dolor incidunt consequatur harum? Recusandae velit exercitationem necessitatibus accusamus, eligendi autem quod sapiente voluptas quibusdam! Blanditiis sed voluptate ullam.</p>
    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias, reprehenderit fuga dolor incidunt consequatur harum? Recusandae velit exercitationem necessitatibus accusamus, eligendi autem quod sapiente voluptas quibusdam! Blanditiis sed voluptate ullam.</p>
    `,
    created_at: '2023-11-19 15:12'
}
const post2 = {
    user: {
        id: 2,
        avatar: 'https://randomuser.me/api/portraits/men/53.jpg',
        name: 'Elon Musk'
    },
    group: {
        id: 1,
        name: 'Laravel Developers'
    },
    attachments: [
        {
            id: 1,
            name: 'test.png',
            url: 'https://picsum.photos/1000',
            mime: 'image/png',
        },
        {
            id: 2,
            name: 'test2.png',
            url: 'https://picsum.photos/1000',
            mime: 'image/png',
        },
        {
            id: 3,
            name: 'myDoc.docx',
            url: '#',
            mime: 'application/msword',
        }
    ],
    body: `
    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias, reprehenderit fuga dolor incidunt consequatur harum? Recusandae velit exercitationem necessitatibus accusamus, eligendi autem quod sapiente voluptas quibusdam! Blanditiis sed voluptate ullam.</p>
    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias, reprehenderit fuga dolor incidunt consequatur harum? Recusandae velit exercitationem necessitatibus accusamus, eligendi autem quod sapiente voluptas quibusdam! Blanditiis sed voluptate ullam.</p>
    `,
    created_at: '2024-01-19 10:12'
}
</script>
<template>
    <div class="overflow-auto">
        <PostItem :post="post1" />
        <PostItem :post="post2" />
    </div>
</template>

<style scoped></style>