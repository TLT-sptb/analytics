<template>
    <header class="p-3 bg-dark bg-gradient text-white header-controll">
        <div class="container header-controll-1">
            <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
                <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
                    <img src="../assets/img/logo.png" alt="">
                </a>
                <ul class="spinner nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
                    <li class="nav-link px-2 text-secondary"><span><a href="/">Inicio</a></span></li>
                    <li class="nav-link px-2 text-white"><span><a href="/dashboard">Analytics
                    <!-- <li class="nav-link px-2 text-white"><span><a href="itens/analytics">Vendas</a></span></li> -->
                    <li class="nav-link px-2 text-white"><span><a href="#">Fretes</a></span></li>
                        
                    </a></span></li>
                    <li class="nav-link px-2 text-white"><span><a href="#">Sobre</a></span></li>
                </ul>
                <!-- <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3">
                    <input type="search" class="form-control form-control-dark" placeholder="Search..."
                        aria-label="Search" />
                </form> -->
                <div class="text-end">
                    <a href="/login" type="button" class="btn btn-warning me-2">Login</a>
                    <a href="/register" type="button" class="btn btn-success">Sign-up</a>
                </div>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    name: 'Home-bar'
}
</script>
<style>
a {
    list-style: none;
    color: white;
    text-decoration: none;
}

a:hover {
    color: rgb(211, 211, 202);
}

.spinner {
    margin-left: 1%;
    text-align: center;
    height: 50px;
    width: max-content;
    font-size: 14px;
    font-weight: 600;
    font-family: monospace;
    letter-spacing: .2em;
    filter: drop-shadow(0 0 4px);
    display: flex;
    justify-content: center;
    align-items: center;
    animation: loading6454 1.75s ease;
}

.spinner span:nth-child(2) {
    animation-delay: 0.25s;
}

.spinner span:nth-child(3) {
    animation-delay: 0.5s;
}

.spinner span:nth-child(4) {
    animation-delay: 0.75s;
}

.spinner span:nth-child(5) {
    animation-delay: 1s;
}

.spinner span:nth-child(6) {
    animation-delay: 1.25s;
}

.spinner span:nth-child(7) {
    animation-delay: 1.5s;
}

@keyframes loading6454 {

    0%,
    100% {
        transform: translateY(0);
    }

    50% {
        transform: translateY(-10px);
    }
}
</style>