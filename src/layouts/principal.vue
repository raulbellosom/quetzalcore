<template>
    <q-layout view="hHh lpR fFf">
        <q-header elevated style="background-color:#B6143A ">
            <q-toolbar>
                <div class="col-md-8 col-xs-6 q-pl-xl ">
                    <img src="../assets/logos/negativo.png" alt="logo-quetzalcore" height="50px" srcset="">
                </div>
                <div class="col-md-4 col-xs-5">
                    <div class="my-font text-h6 text-right">
                        <label for="" class="q-pr-md">Inicio</label>
                        <label for="" class="q-pr-md">Proyectos</label>
                        <label for="" class="q-pr-md">Nosotros</label>
                        <label for="" class="q-pr-xl">Contacto</label>
                    </div>
                </div>
                <div class="lt-md">
                    <q-btn flat round dense icon="menu" aria-label="Menu" @click="leftDrawerOpen = !leftDrawerOpen">

                    </q-btn>
                </div>
            </q-toolbar>
        </q-header>
    </q-layout>
</template>