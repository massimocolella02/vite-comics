<script></script>

<template>
    <div class="utilities">
        <div class="container">
            <ul class="d-flex justify-content-around">
                <li>
                    <a href="#">
                        <img src="/img/buy-comics-digital-comics.png" alt="">
                        <span>digital comics</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="/img/buy-comics-merchandise.png" alt="">
                        <span>dc merchandise</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="/img/buy-comics-subscriptions.png" alt="">
                        <span>subscription</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="/img/buy-comics-shop-locator.png" alt="">
                        <span>comic shop locator</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="/img/buy-dc-power-visa.svg" alt="">
                        <span>dc power visa</span>
                    </a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
    @use "../style/variables" as *;

    .utilities{
        background-color: $blue;
        padding: 20px 0;
        ul{
            li{
                list-style-type: none;
                img{
                    height: 80px;
                    margin-right: 10px;
                }
                a{
                    text-decoration: none;
                    color: white;
                    display: flex;
                    align-items: center;
                    margin-right: 20px;
                    text-transform: uppercase;
                }
            }
        }
    }


</style>