<template>
  <q-layout view="lHh Lpr lFf">
    <!-- aqui -->
    <q-header elevated>
      <q-toolbar>

        <q-toolbar-title>
          <template>

            <div class="row justify-center">
              <div class="col-auto">
                <ul class="list-menu">
                  <img src="~assets/monday-logo.png" style="width:154px">
                    <li class="q-ml-lg"><a href = "#">Produto</a> </li>
                    <li  class="q-ml-lg"><a href = "#"> Histórias de uso</a></li>
                    <li  class="q-ml-lg"><a href = "#">Trabalho remoto</a></li>
                    <li class="q-ml-lg"><a href = "#">Corporativo</a></li>
                    <li class="q-ml-lg"><a href = "#">Preços</a></li>
                      <li class="q-ml-xl">
                        <a class="q-ml-xl" href="#"> Contate a equipe de vendas</a>
                      </li>
                      <li class="q-ml-xl">
                         <a  href="#"> Login</a>
                      </li>
                    <q-btn  class="q-ml-lg" no-caps rounded color="pink-12" size="md" label="Comece já >"/>
                </ul>

              </div>

            </div>
           </template>
        </q-toolbar-title>

      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: 'MainLayout',
  components: {
    // EssentialLink
  }
}
</script>
<style lang="css" scoped>
.list-menu {
  color: black;
  list-style-type:none;
  display: flex;
  align-items: center;
  font-size: 17px;
  font-weight: 400;

}
.list-menu a {
  text-decoration: none;
  }

 a {
  text-decoration: none;
  color: rgb(66, 67, 69);

}

.list-menu a:hover {
  color:#4d7fed;
}
</style>
