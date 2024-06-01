<script setup>

</script>

<template>
    <div class="">
        <header class="block base-color w-full h-20 pt-7 pl-5 align-middle items-center content-center">
            <img src="@/assets/logos/Zephyr.svg" class="w-24 inline" alt="">
            <ul class="flex float-right">
                <li>Конструктор</li>
                <li>Войти</li>
                <li>Зарегистрироваться</li>
            </ul>
        </header>
        <main class="flex justify-center">
            <div class="main-container p-8 ">
                <div class="text-5xl font-bold mb-10">ВАШЕ ПУТЕШЕСТВИЕ</div>

                <div class="flex align-middle items-center content-center">
                    <p class=" font-bold text-3xl mr-5">ПУНКТ НАЗНАЧЕНИЯ</p>
                    <div class="line bg-black mr-5"></div>
                    <p class=" text-blue-700">СБРОСИТЬ</p>
                </div>
                <p class="text-2xl">Уверяю все будет хорошо!</p>
               
                <div class="flex">
                    <v-text-field label="Начальная точка" class="h-14" variant="underlined" prepend-inner-icon="mdi-magnify"></v-text-field>
                    <div>
                        <v-icon size="x-large" icon="mdi-magnify"></v-icon>
                    </div>
                    <v-text-field label="Конечная точка" class="h-14" variant="underlined" prepend-inner-icon="mdi-magnify"></v-text-field>
                </div>
            </div>
        </main>
    </div>
</template>

<style>
  li{
    color: white;
    text-transform: uppercase;
    margin-right: 20px;
  }
  .line{
    height: 2px;
    width: 400px;
  }
  .main-container{
    width:963px;
  }
</style>