<template>
    <main>
        <div class="container-title">
            <h2 class="content-title">Web & Aplication Development</h2>
        </div>
        <div class="left">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe sint eligendi possimus? Unde officiis magnam
            laborum ipsa distinctio odio, vero dolores
        </div>
        <div class="rigth">
            dicta aliquam aperiam repellendus. Perferendis officiis deserunt
            velit voluptas nobis sequi animi totam, accusantium, ex eius quia, natus quo?
        </div>
    </main>
</template>

<script>
export default {
    name: 'Main'
}
</script>

<style scoped>
main {
    margin-top: 170px;
    height: 200px;
    background-color: #EAEAEA;
    text-align: center;
    width: 100%;
    
}

.container-title {
    padding-top: 1rem;
}

.left {
    width: 300px;
    height: 300px;
    float: left;
    margin-left: 300px;
    margin-right: 100px;
    text-align: justify;

}

.rigth {
    width: 300px;
    height: 400px;
    float: left;
    text-align: justify;
}
</style>