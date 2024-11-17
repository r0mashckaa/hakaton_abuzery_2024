<script>
    import Mainpage from "$lib/comp/mainpage.svelte";
</script>

<div class="all">
    <a href="https://www.surgu.ru/index"><img src="\surgulogo.png" alt="" class="surlog" /></a>
    <a href="https://t.me/s/profsouzSurGU"><img src="\prophsoyuse.png" alt="" class="soyuselog" /></a>
    <a href="https://web.telegram.org/a/"><img src="\support.png" alt="" class="support" /></a>
    <img src="/tgbot.jpg" alt="" class="tgbot" />
    <div class="page">
        <Mainpage />
    </div>
</div>

<style>
    .page {
        padding-top: 35px;
        display: grid;
        justify-content: center;
        align-content: center;
    }
    .surlog {
        display: block;
        position: fixed;
        width: 230px;
        margin-top: 320px;
        margin-left: 75px;
        rotate: 345deg;
        transition: all 0.6s;
    }
    .surlog:hover {
        transform: scale(1.4);
        filter: drop-shadow(0 0 20px #0d5ab3);
    }
    .soyuselog {
        display: block;
        position: fixed;
        width: 230px;
        margin-top: 100px;
        margin-left: 1175px;
        rotate: 15deg;
        transition: all 0.6s;
    }
    .soyuselog:hover {
        transform: scale(1.4);
        filter: drop-shadow(0 0 20px #1a92b7);
    }
    .support {
        display: block;
        position: fixed;
        width: 140px;
        margin-top: 79px;
        margin-left: 58px;
        rotate: 349deg;
        transition: all 0.6s;
    }
    .support:hover {
        transform: scale(1.4);
        filter: drop-shadow(0 0 20px #049bcd);
    }
    .tgbot {
        display: block;
        position: fixed;
        width: 200px;
        margin-top: 440px;
        margin-left: 1200px;
        transition: all 0.6s;
    }
    .tgbot:hover {
        transform: scale(1.3);
    }
    .all {
        background: linear-gradient(45deg, white, rgb(222, 214, 214));
    }
</style>
