<template>
<div >
    <header class="header">
        <nav class="navbar navbar-expand-md navbar-light col-md-10 col-12">
            <div class="navbar-brand iconBackground logo-header" ></div>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ml-auto ">
                    <li class="nav-item mr-3 ">
                        <a class="nav-link text-primary" href="#">Việc làm</a>
                    </li>
                    <li class="nav-item mr-3">
                        <a class="nav-link text-primary" href="#">Quản Lý CV</a>
                    </li>
                    <li class="nav-item mr-3">
                        <a class="nav-link text-primary" href="#">Hỗ trợ</a>
                    </li>
                    <li class="nav-item mr-3">
                        <a class="nav-link text-primary" href="#"><i class="far fa-bell"></i></a>
                    </li>
                    <li class="nav-item mr-3">
                        <div class="avt"></div>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</div>
</template>

<script>
export default {
    name: 'header',

}
</script>

<style scoped>
    .avt{
        width: 32px;
        height: 32px;
        background-size: cover;
        border-radius: 50%;
        background-image: url(/img/avt.56a4af13.jpg);
        background-repeat: no-repeat;
        margin-top: 4px;
        
    }
    .header{
        height: 60px;
    }
   .logo-header{
       width: 140px;
       height: 32px;
       background-repeat: no-repeat;
       cursor: pointer;
       background-position: -396px  -78px;
   }
    h4.title {
        display: block !important;
        clear: both;
    }
   

    header li.nav-item a:hover {
        color: #FF5969 !important;
    }

    header li.nav-item a {
        color: #212121 !important;
        font-size: 16px;
    }

</style>
