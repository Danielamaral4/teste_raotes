<template>
  <q-page class="flex flex-center">
    <div class="container1">
    <div class="container2">
      <h3>Exemplo 1</h3>

      <ul>
      <li><input  class="pesquisa" type="text" placeholder="Pesquisar" /></li>
      <li><select class="select" name="select">
        <option value="valor1">Coluna 1</option>
      </select></li>
      <li><h2>Novo Exemplo</h2></li>
  </ul>
  <p>Dashboard</p>
  </div>
    <div class="container3">
      <div class="filtro">
        <p>Filtro</p>
      </div>
      <table>
        <tr>
          <th>Situação</th>
          <th>Cod Exemplo</th>
          <th>Nome</th>
          <th>Descrição</th>
          <th>Tipo</th>
          <th>Origem</th>
          <th>Contato</th>
          <th>Email</th>
          <th>Tel 1</th>
          <th>Tel 2</th>
        </tr>
        <tr>
          <td></td>
          <td>122</td>
          <td>nome 15</td>
          <td>descrição 15</td>
          <td>tipo 15</td>
          <td>origem 15</td>
          <td>contato 15</td>
          <td>email 15</td>
          <td>tel 15</td>
          <td>tel 15</td>
        </tr>
        <tr>
          <td></td>
          <td>121</td>
          <td>nome 14</td>
          <td>descrição 14</td>
          <td>tipo 14</td>
          <td>origem 14</td>
          <td>contato 14</td>
          <td>email 14</td>
          <td>tel 14</td>
          <td>tel 14</td>
        </tr>
        <tr>
          <td></td>
          <td>120</td>
          <td>nome 13</td>
          <td>descrição 13</td>
          <td>tipo 13</td>
          <td>origem 13</td>
          <td>contato 13</td>
          <td>email 13</td>
          <td>tel 13</td>
          <td>tel 13</td>
        </tr>
        <tr>
          <td></td>
          <td>120</td>
          <td>nome 38</td>
          <td>descrição 38</td>
          <td>tipo 38</td>
          <td>origem 38</td>
          <td>contato 38</td>
          <td>email 38</td>
          <td>tel 38</td>
          <td>tel 38</td>
        </tr>
        <tr>
          <td></td>
          <td>922</td>
          <td>nome 45</td>
          <td>descrição 45</td>
          <td>tipo 45</td>
          <td>origem 45</td>
          <td>contato 45</td>
          <td>email 45</td>
          <td>tel 45</td>
          <td>tel 45</td>
        </tr>
        <tr>
          <td></td>
          <td>154</td>
          <td>nome 15</td>
          <td>descrição 15</td>
          <td>tipo 15</td>
          <td>origem 15</td>
          <td>contato 15</td>
          <td>email 15</td>
          <td>tel 15</td>
          <td>tel 15</td>
        </tr>
      </table>
    </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'PageIndex'
})

const linkColor = document.querySelectorAll('.nav__link')
function colorLink () {
  linkColor.forEach((l) => l.classList.remove('active'))
  this.classList.add('active')
}

linkColor.forEach((l) => l.addEventListener('click', colorLink))
</script>
