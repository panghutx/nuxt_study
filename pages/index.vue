<template>
  <div class="flex flex-col items-center justify-center min-h-screen bg-black/90 text-white bg-[url('./back.jpg')] bg-cover bg-center bg-fixed">
    <div class="absolute top-4 left-1/2 -translate-x-1/2 flex items-center bg-black/30 backdrop-blur-sm px-4 py-2 rounded-lg">
      <UIcon name="i-heroicons-wallet" class="w-6 h-6" />
      <span class="ml-2">Wallet</span>
    </div>
    
    <div class="flex flex-col items-center space-y-6 max-w-md mx-auto px-6">
      <h1 class="text-5xl font-bold tracking-wider">Coming soon!</h1>
      
      <div class="w-full bg-black/60 backdrop-blur-sm rounded-2xl p-8">
        <h2 class="text-2xl font-semibold mb-3">Join our waitlist!</h2>
        <p class="text-gray-300 mb-6">Sign up for our newsletter to receive the latest updates and insights straight to your inbox.</p>
        
        <div class="flex gap-2">
          <UInput
            placeholder="Enter email"
            class="flex-1"
            size="lg"
          />
          <UButton
            color="white"
            variant="solid"
            size="lg"
          >
            Join Waitlist
          </UButton>
        </div>
      </div>

      <div class="flex gap-4 mt-8">
        <UButton
          icon="i-simple-icons-x"
          variant="ghost"
          color="white"
          class="hover:bg-white/10"
        />
        <UButton
          icon="i-simple-icons-facebook"
          variant="ghost" 
          color="white"
          class="hover:bg-white/10"
        />
        <UButton
          icon="i-simple-icons-instagram"
          variant="ghost"
          color="white"
          class="hover:bg-white/10"
        />
      </div>
    </div>
  </div>
</template>