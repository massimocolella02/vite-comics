<script>
</script>

<template>
    <footer>   
        <div class="container">
            <div class="footer-list">
                <ul>
                    <h5>dc comics</h5>
                    <li>
                        <a href="">
                            <span>characters</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>characters</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>characters</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>characters</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>characters</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>characters</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>characters</span>
                        </a>
                    </li>
                </ul>

                <ul>
                    <h5>dc</h5>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>terms of use</span>
                        </a>
                    </li>
                </ul>

                <ul>
                    <h5>sites</h5>
                    <li>
                        <a href="">
                            <span>dc</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>dc</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>dc</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>dc</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>dc</span>
                        </a>
                    </li>
                </ul>

                <ul>
                    <h5>shop</h5>
                    <li>
                        <a href="">
                            <span>shop dc</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <span>shop dc</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </footer>

    <div id="footer-end">
        <div class="container">
            <button class="btn btn-dark">sign up now!</button>
            <div class="footer-icons">
                <h5>follow us</h5>
                <ul>
                    <li>
                        <a href="">
        
                            <img src="/img/footer-facebook.png" alt="">
                        </a>

                    </li>
                    <li>
                        <a href="">
                            <img src="/img/footer-twitter.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="/img/footer-youtube.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">       
                            <img src="/img/footer-pinterest.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="/img/footer-periscope.png" alt="">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use "../style/variables" as *;

    footer{
        background-image: url("/img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        .container{
            padding: 20px 0;
            background-image: url("/img/dc-logo-bg.png");
            background-repeat: no-repeat;
            background-position: right;
            .footer-list{
                width: 40%;
                display: flex;
                flex-wrap: wrap;
                ul{
                    width: calc(100% / 3);
                    text-transform: capitalize;
                    h5{
                        color: white;
                        text-transform: uppercase;
                    }
                    a{
                        text-decoration: none;
                        color: gray;
                    }
                }
            }
        }
    }
    #footer-end{
        background-color: #303030;
        height: 100px;
        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
            height: 100%;
            button{
                text-transform: uppercase;
                border-color: $blue;
            }
            .footer-icons{
                display: flex;
                height: 100%;
                align-items: center;

                h5{
                    text-transform: uppercase;
                    color: $blue;
                    margin-right: 10px;
                }
                img{
                    margin-right: 10px;
                    vertical-align: middle;
                }
                ul{
                    display: flex;
                    li{
                        list-style-type: none;
                    }
                }
            }
        }
    }
</style>