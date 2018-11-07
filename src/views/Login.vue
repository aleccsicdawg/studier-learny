<template v-if="loginType === 'username'">
  <label>Имя пользователя</label>
  <input placeholder="Введите имя пользователя">
</template>
<template v-else>
  <label>Email</label>
  <input placeholder="Введите адрес email">
</template>