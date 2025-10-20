<template>
    <header>
        <ul>
            <li><a href="#play">Play</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#rules">Rules</a></li>
            <li><a href="#contacts">Contants</a></li>
        </ul>
    </header>
</template>

<style scoped>
header {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    padding: 24px 0;
}

ul {
    width: 100%;
    list-style: none;
    display: flex;
    justify-content: center;
}

a {
    font-size: 24px;
    color: #ffffff;
    padding: 8px 18px;
    transition: color 0.3s ease;
}
a:hover {
    color: rgb(89, 163, 91);
}

@media (max-width: 768px) {
    a {
        padding: 6px 14px;
        font-size: 18px;
    }
}
</style>

<script></script>
