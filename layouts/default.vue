<template>
  <main>
    <Suspense>
      <slot />
      <template #fallback>
        <div>Your fallback content here</div>
      </template>
    </Suspense>
  </main>
</template>
