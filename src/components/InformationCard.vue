<template>
  <div class="flex flex-col justify-center items-center mt-24">
    <h1 class="text-3xl font-bold">Why Unified Chat?</h1>

    <div class="text-center max-w-lg mt-4">
      <span class="text-center text-lg">
        We do not sell any products. We are platform owner and we are
        responsible of checking products safety. We are here if you have a
        problem with any sellers. We are here to help you.
      </span>
    </div>

    <div class="flex justify-center items-center gap-32 mt-20">
      <div
        v-for="card in cards"
        :key="card.title"
        class="flex flex-col justify-center items-center w-[300px] space-y-4"
      >
        <img
          class="w-[80px] h-[80px] object-cover rounded-full shadow-2xl"
          :src="card.image"
          alt="hero"
        />

        <span class="text-2xl font-bold">
          {{ card.title }}
        </span>

        <span class="text-[#818296] text-center">
          {{ card.description }}
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InformationCard",
  data() {
    return {
      cards: [
        {
          title: "Always Safe",
          description:
            "We always safe, We always safe We always safeWe always safe We always safe We always safe",
          image:
            "https://cdn.discordapp.com/attachments/881468109188370432/1033339808757596211/unknown.png",
        },
        {
          title: "Always Safe",
          description:
            "We always safe, We always safe We always safeWe always safe We always safe We always safe",
          image:
            "https://cdn.discordapp.com/attachments/881468109188370432/1033339808757596211/unknown.png",
        },
        {
          title: "Always Safe",
          description:
            "We always safe, We always safe We always safeWe always safe We always safe We always safe",
          image:
            "https://cdn.discordapp.com/attachments/881468109188370432/1033339808757596211/unknown.png",
        },
      ],
    };
  },
};
</script>

<style scoped></style>
