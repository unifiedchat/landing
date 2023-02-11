<template>
  <div class="flex justify-between">
    <div class="max-w-xl">
      <h1 class="text-6xl">You don’t have to</h1>
      <h1 class="text-6xl font-bold mt-4">Fight them Alone.</h1>

      <div class="mt-9">
        <p class="text-[#818296]">
          Lorem ipsum dolor sit amet consectetur adipiscing elit blandit,
          curabitur sodales conubia ut inceptos faucibus himenaeos tortor eget,
          hac massa gravida arcu interdum proin curae.
        </p>
      </div>

      <div class="mt-10 space-x-6">
        <button
          class="w-[150px] h-[50px] bg-[#3B82F6] text-white rounded-full font-bold text-sm hover:bg-[#2563EB] duration-200 transition-all ease-in-out"
        >
          Get Started
        </button>

        <button
          class="w-[150px] h-[50px] border-2 duration-200 hover:bg-[#fff] hover:text-black text-white rounded-full font-bold text-sm hover:bg-[#2563EB] duration-200 transition-all ease-in-out"
        >
          Discord
        </button>
      </div>
    </div>

    <div>
      <img
        class="w-[600px] h-[400px] object-cover rounded-full shadow-2xl -mt-10 -mr-20"
        src="https://cdn.discordapp.com/attachments/881468109188370432/1033339808757596211/unknown.png"
        alt="hero"
      />
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Hero",
};
</script>

<style scoped></style>
