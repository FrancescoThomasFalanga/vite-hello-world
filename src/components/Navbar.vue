<script></script>

<template>
    <nav>
        <div>
            <h2>App Hero Section</h2>
            <span>agagagagaga</span>
        </div>
        <div class="links">
            <a href="" class="like">&#9829;</a>
            <a href="" class="change-img">Change Img</a>
            <a href="" class="sign-up">Sign Up</a>
            <a href="" class="log-in">Log In</a>
        </div>
    </nav>
</template>

<style scoped>
nav {
    position: fixed;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    padding: 10px 30px;
    background-color: #1e1f23;
    box-shadow: 2px 10px 10px #1e1f239c;
}

.links {
    display: flex;
    gap: 10px;
}

a {
    text-decoration: none;
    color: white;
    padding: 10px;
    border: 2px solid rgb(77, 77, 77);
    border-radius: 10px;
}

.like {
    padding-left: 15px;
    padding-right: 15px;
    font-size: 16px;
}

.sign-up {
    color: black;
    background-color: #70cd7b;
}

.log-in, .change-img {
    background-color: #464859;
}

</style>