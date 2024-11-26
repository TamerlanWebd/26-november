<script setup>

</script>

<template>
<div class="container ">
<div class="row">
<div class="col ">
        <h1 class="text-center my-3">Зароботная плата</h1> 
<div class="mb-3">
  <label for="name" class="name" :class="{'is-invalid': !name}">ФИО</label>
  <input type="text" v-model="name" class="form-control" id="name">
</div>
<div class="mb-3">
  <label for="date" class="date" :class="{'is-invalid': !date}">Дата выдачи зарплаты</label>
  <input type="date" v-model="date" class="form-control" id="date">

</div>
<div class="mb-3">
  <label for="count" class="count" :class="{'is-invalid': !count}">Количество отработанных дней</label>
  <input type="number" v-model="count" class="form-control" id="count">

</div>
<div class="mb-3">
  <label for="amountWithoutTax" class="amountWithoutTax" :class="{'is-invalid': !amountWithoutTax}">Сумма заработной платы сотрудника без налоговых отчислений</label>
  <input type="number" v-model="amountWithoutTax" class="form-control" id="amountWithoutTax">

</div>
<div class="mb-3">
  <label for="taxАmount" class="taxАmount" :class="{'is-invalid': !taxАmount}">Сумма заработной платы сотрудника с налоговыми отчислениями (-15%)</label>
  <input type="number" v-model="count" class="form-control" id="taxАmount">

</div>
<button type="button" class="btn btn-outline-success">Добавить</button>

</div>
</div>
</div>
</template>

