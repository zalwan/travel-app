<template>
  <section
    class="bg-hero relative flex h-screen flex-col items-center justify-center bg-cover bg-center"
  >
    <!-- Overlay -->
    <div class="absolute inset-0 bg-black/70" />

    <!-- Main Content -->
    <div class="relative z-10 flex h-full items-center text-center">
      <div class="container mx-auto px-6 lg:px-12">
        <div class="max-w-4xl">
          <h1
            class="mb-6 text-4xl leading-tight font-bold text-white md:text-5xl lg:text-6xl"
          >
            <span class="text-amber-300">Perjalanan Spiritual</span><br />
            Menuju Baitullah
          </h1>

          <p class="mb-8 text-lg leading-relaxed text-amber-100">
            Nikmati pengalaman ibadah haji & umrah yang penuh makna dengan
            fasilitas premium dan bimbingan ulama berpengalaman. Perjalanan suci
            Anda adalah prioritas kami.
          </p>

          <div class="flex items-center justify-center gap-4">
            <NuxtLink to="/" class="btn rounded-full px-8 btn-primary">
              Mulai Perjalanan
            </NuxtLink>
            <NuxtLink
              to="/"
              class="btn rounded-full px-8 btn-outline btn-primary"
            >
              Konsultasi gratis
            </NuxtLink>
          </div>

          <div
            class="mt-10 flex flex-wrap items-center justify-center gap-4 text-sm text-amber-200"
          >
            <div class="flex items-center gap-2">
              <Icon name="ph:check-circle-bold" class="h-5 w-5" />
              <span>Bersertifikat Kemenag</span>
            </div>
            <div class="flex items-center gap-2">
              <Icon name="ph:check-circle-bold" class="h-5 w-5" />
              <span>Hotel Bintang 5</span>
            </div>
            <div class="flex items-center gap-2">
              <Icon name="ph:check-circle-bold" class="h-5 w-5" />
              <span>Pembimbing Berpengalaman</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.bg-hero {
  background-image: url('/assets/img/hero.jpg');
}
</style>
