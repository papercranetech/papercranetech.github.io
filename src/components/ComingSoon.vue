<template>
  <div class="w-full h-screen-90 flex justify-center items-center border-box">
    <div>
      <div class="px-8 py-8 flex flex-wrap">
        <div class="flex justify-center items-center">
          <img class="h-64" src="../assets/logo.png">
        </div>
        <div class="md:ml-10 py-8 flex flex-grow flex-col justify-center items-center">
          <p class="text-4xl font-mono"><span class="text-pri">p</span>aper cra<span class="text-sec">n</span>e tech</p>
          <p class="text-2xl font-mono text-gray-60">coming soon...</p>
          <div class="mt-12">
            <p class="text-lg text-gray-400">📮 hello@papercranetech.co</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ComingSoon',
  props: {
    text: String
  }
}
</script>
