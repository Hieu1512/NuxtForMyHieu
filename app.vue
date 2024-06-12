<template>
  <NuxtLayout>
    <Header />
    <!-- Cách tạo liên kết đến trang sau -->
    <header>
      <ul>
        <li>
          <NuxtLink to="/"> Home </NuxtLink>
          <NuxtLink to="/events">Events</NuxtLink>
        </li>
      </ul>
    </header>
    <NuxtPage />
  </NuxtLayout>
</template>
