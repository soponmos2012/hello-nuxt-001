<template>
    <div class="">
        <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet" />
        <div class="body_content">
            <div class="row group_menu content-center">
                <div class="col-14 col-lg-7 cursor_pointer active">
                    <img class="large_img" src="/image/allgame.jpg" alt="">
                </div>
                <div class="col-6 col-lg-7 cursor_pointer select casino">
                    <img src="/image/casino.jpg" alt="">
                </div>
                <div class="col-6 col-lg-7 cursor_pointer select slot">
                    <img src="/image/slot.jpg" alt="">
                </div>
            </div>
            <div class="margin-32px large"></div>
            <div class="margin-16px mobile"></div>
            <div class="row_content_games">
                <div class="list_game">
                    <div class="bg_title_outer casino">
                        <div class="bg_title_inside">
                            <div class="text-gold pentor-bold text-center">คาสิโนออนไลน์</div>
                        </div>
                    </div>
                    <div class="margin_casino margin-16px"></div>
                    <div class="sort_casino">
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/casino_0.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/casino_1.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/casino_2.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/casino_3.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/casino_4.png" alt="">
                        </div>
                    </div>
                    <div class="margin-32px large"></div>
                    <div class="bg_title_outer slot">
                        <div class="bg_title_inside">
                            <div class="text-gold pentor-bold text-center">สล็อตออนไลน์</div>
                        </div>
                    </div>
                    <div class="margin_slot margin-16px"></div>
                    <div class="sort_slot">
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_0.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_1.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_2.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_3.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_4.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_5.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_6.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_7.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_8.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_9.png" alt="">
                        </div>
                        <div class="cob_ cursor_pointer example">
                            <img src="/image/playgame/slot_10.png" alt="">
                        </div>
                    </div>
                    <div class="margin_slot margin-16px"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'NuxtPlaygame',
}
</script>

<style>
.body_content {
    padding: 0.5rem 20rem 0rem 20rem;
}

.content-center {
    justify-content: center !important;
}

.row {
    --bs-gutter-x: 1.5rem;
    --bs-gutter-y: 0;
    display: flex;
    flex-wrap: wrap;
    margin-top: calc(-1 * var(--bs-gutter-y));
    margin-right: calc(-0.5 * var(--bs-gutter-x));
    margin-left: calc(-0.5 * var(--bs-gutter-x));
}

.active {
    filter: unset;
}

.select {
    filter: saturate(0);
}

.margin-32px {
    margin-top: 2rem;
}

.sort_casino {
    display: flex;
    flex-wrap: wrap;
    margin-right: -0.5rem;
    margin-left: -0.5rem;
    margin-top: -1rem;
}

div.cob_ {
    flex: 0 0 auto;
    max-width: 100%;
    margin-top: 0.625rem;
    padding-right: 0.3125rem;
    padding-left: 0.3125rem;
    width: 13.3rem;
}

img {
    max-width: 100%;
}

.sort_slot {
    display: flex;
    flex-wrap: wrap;
    margin-right: -0.5rem;
    margin-left: -0.5rem;
    margin-top: -1rem;
}

.text-center {
    background: linear-gradient(90deg, #AE8625 0%, #F7EF8A 36.46%, #D2AC47 79.69%, #EDC967 100%);
    -webkit-background-clip: text;
    background-clip: text;
    font-size: 1.5rem;
}

.col-lg-7 {
    flex: 0 0 auto;
    width: 25%;
    margin-right: 1.25rem;
}
</style>