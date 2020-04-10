<template>
    <div class="modal">
        <div class="modal-wrap" @click="$emit('closeModal')">
            <div class="modal-inner">
                <div class="modal-header">
                    TODO App
                    <div class="close_btn" @click="$emit('closeModal')">✖️</div>
                </div>
                <div class="modal-body">
                    <div class="modal-img">
                        <img src="~/assets/images/Django_ToDo_App.gif" alt="">
                    </div>
                    <div class="modal-text">
                        <p>DjangoとBootstrapで作成したTODOアプリになります。</p>
                        <p>追加、編集、削除が出来ます。</p>
                        <p>ソースコードは→
                            <span><a href="https://github.com/tomioka-miki/portfolio_app/tree/django-app" target="_branck">こちらから</a></span>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>