<template>
  <div>
    <header>
        <nav>
            <NuxtLink to="/">Nuxt App</NuxtLink>
            <ul>
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                    <NuxtLink to="/about">About</NuxtLink>
                    <NuxtLink to="products">Products</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>

    <h2>Home</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum ea beatae pariatur non nulla voluptatibus tenetur consequuntur, aliquid repellat consequatur ipsam reiciendis. Magni recusandae mollitia quibusdam earum quos, quasi amet.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum ea beatae pariatur non nulla voluptatibus tenetur consequuntur, aliquid repellat consequatur ipsam reiciendis. Magni recusandae mollitia quibusdam earum quos, quasi amet.</p>
  </div>
</template>

<script setup>

</script>

<style>
h2{
    margin-bottom: 20px;
    font-size: 36px;
}
p{
    margin: 20px 0;
}
</style>