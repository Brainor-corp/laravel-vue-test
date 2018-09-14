<template>
    <ul>
        <li><router-link :to="{ name: 'users.index' }">Пользователи</router-link></li>
        <li><router-link :to="{ name: 'contacts.index' }">Контакты</router-link></li>
    </ul>
</template>