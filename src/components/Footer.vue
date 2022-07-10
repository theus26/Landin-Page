<template>

<footer class="footer">
<p>
    Acme Web Solutions 
</p>

<p>
    Project By <a href="#">Traversy Media</a>
</p>
</footer>
</template>


<script>
export default{
    name:'Footer'
}
</script>


<style scoped>
.footer{
    margin-top: 25rem;
    width: 100%;
    height: 100px;
    background-color: #222;
    color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
p > a{
    text-decoration: none;
    color:#2690D4;
}
</style>