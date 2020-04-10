<template>
    <div class="modal">
        <div class="modal-wrap" @click="$emit('closeModal')">
            <div class="modal-inner">
                <div class="modal-header">
                    Portfolio Site
                    <div class="close_btn" @click="$emit('closeModal')">✖️</div>
                </div>
                <div class="modal-body">
                    <div class="modal-img">
                        <img src="~/assets/images/Meow.png" alt="">
                    </div>
                    <div class="modal-text">
                        <p>Nuxt.js/Vue.jsで作成したポートフォリオサイトです。</p>
                        <p>シンプルで見やすいデザインにし、可愛いにゃんこの画像で癒されるサイトにしました。</p>
                        <p>ソースコードは→
                            <span><a href="https://github.com/tomioka-miki/tomioka-miki.github.io" target="_branck">こちらから</a></span>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>