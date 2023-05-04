<script>
export default{
    name: "HeaderComp",
    data(){
        return{
            vociLista: [
                {
                    nome: 'characters',
                    url: '/characters',
                    current: false
                },
                {
                    nome: 'comics',
                    url: '/comics',
                    current: true
                },
                {
                    nome: 'movies',
                    url: '/movies',
                    current: false
                },
                {
                    nome: 'TV',
                    url: '/TV',
                    current: false
                },
                {
                    nome: 'games',
                    url: '/games',
                    current: false
                },
                {
                    nome: 'collectibles',
                    url: '/collectibles',
                    current: false
                },
                {
                    nome: 'videos',
                    url: '/videos',
                    current: false
                },
                {
                    nome: 'fans',
                    url: '/fans',
                    current: false
                },
                {
                    nome: 'news',
                    url: '/news',
                    current: false
                },
                {
                    nome: 'shop',
                    url: '/shop',
                    current: false
                },
            ]
        }
    }
}
</script>

<template>
    <header>
        <div class="container">
            <div>
                <img src="/img/dc-logo.png" alt="Logo">
            </div>
            <nav>
                <ul>
                    <li v-for="(element, index) in vociLista"
                        :key="index"
                        :class="(element.current == true)? 'active' : '' ">
                        <a :href="element.url">{{ element.nome }}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style scoped lang="scss">
@use '../style/variables' as *;

    header{
        height: 100px;
        .container{
            height: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;

            img{
                height: 80px;
            }
            nav{
                height: 100%;
                display: flex;
                ul{
                    display: flex;
                    height: 100%;
                    align-items: center;
                    li{
                        list-style: none;
                        margin-right: 10px;
                        line-height: 97px;
                        &.active{
                            border-bottom: 3px solid $blue;
                        }
                        &.active a{
                            color: $blue;

                        }

                        a{
                            text-decoration: none;
                            text-transform: uppercase;
                            color: black;
                        }
                    }
                }
            }
        }
    }
</style>