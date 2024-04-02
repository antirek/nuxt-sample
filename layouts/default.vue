<template>
  <div>
    <header>
    <nav>
      <ul>
        <li><NuxtLink to="/">home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>        
      </ul>
    </nav>
  </header>
    <!-- AppHeader /-->
    <slot />
    <!-- AppFooter /-->
    <p>footer</p>
  </div>
</template>