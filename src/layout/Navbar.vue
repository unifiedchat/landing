<template>
  <div class="flex justify-between items-center">
    <h1 class="text-2xl font-bold cursor-pointer">Unified Chat</h1>

    <div class="flex items-center justify-center space-x-10 text-white">
      <div
        v-for="router in routers"
        :key="router.name"
        class="cursor-pointer text-base font-semibold"
      >
        <a
          v-if="router.href"
          :href="router.href"
          target="_blank"
          class="hover:text-[#7289da] duration-200"
        >
          {{ router.name }}
        </a>

        <span class="hover:text-[#7289da] duration-200" v-else>
          {{ router.name }}
        </span>
      </div>
    </div>

    <div class="flex items-center justify-end">
      <button
        class="px-8 py-2 border-2 border-white text-white font-bold text-sm hover:bg-white duration-200 hover:text-black"
      >
        Get Started
      </button>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Navbar",
  data() {
    return {
      routers: [
        {
          name: "Home",
          path: "/",
        },
        {
          name: "Github",
          href: "https://github.com/unifiedchat",
        },
        {
          name: "Discord",
          href: "https://discord.gg/UANQ6MksGu",
        },
      ],
    };
  },
};
</script>
