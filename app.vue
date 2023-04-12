<template>
  <div>
    <NuxtLayout>
      <header>
        <ul>
          <li><NuxtLink to="/">home</NuxtLink></li>
          <li><NuxtLink to="/events">events</NuxtLink></li>
          <li><NuxtLink to="/events/itsme">itsme event</NuxtLink></li>
        </ul>
      </header>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
