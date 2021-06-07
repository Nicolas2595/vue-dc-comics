<template>
    <div class="container">
        <div class="container_first">
            <div class="image">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
        <div class="link">
             <ul>
                <li v-for="link, index in headerLinks" :key="index">
                    <a href="link.url" :class="{'active' : link.active}">{{ link.text }}</a>
                </li>
            </ul>
        </div>
        </div>
        
        <div class="container_second">
            <h3>Content Goes Here</h3>
        </div>
    </div>

</template>

<script>
export default {
    name: "Header",
    data: function() {
        return {
            headerLinks: [
                {
                    text : 'Characters',
                    url : '#characters',
                    active : false
                },
                {
                    text : 'Comics',
                    url : '#comics',
                    active : true
                },
                {
                    text : 'Movies',
                    url : '#movies',
                    active : false
                },
                {
                    text : 'TV',
                    url : '#tv',
                    active : false
                },
                {
                    text : 'Games',
                    url : '#games',
                    active : false
                },
                {
                    text : 'Collectibles',
                    url : '#collectibles',
                    active : false
                },
                {
                    text : 'Videos',
                    url : '#videos',
                    active : false
                },
                {
                    text : 'Fans',
                    url : '#fans',
                    active : false
                },
                {
                    text : 'News',
                    url : '#news',
                    active : false
                },
                {
                    text : 'Shop',
                    url : '#shop',
                    active : false
                }
            ]
        }
    }
}
</script>

<style scoped>

    .container_first{
        height: 90px;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    img {
        height: 50px;
    }

    ul {
        display: flex;
        list-style: none;
        justify-content: center;
    }

     li a  {
        text-decoration: none;
        color: black;
        padding: 10px;
        font-size: 12px;
        font-weight: bold;
    } 

    li a.active {
        color: #0282f9;
        border-bottom: 3px solid;
    }

    li a:hover {
        color: #0282f9;
        border-bottom: 3px solid;
    }

    .container_second {
        background-color: #1c1c1c;
        height: 100px;
    }

    h3 {
        color: white;
        line-height: 100px;
        padding-left: 250px;
    }

</style>