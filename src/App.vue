<script setup>
import { RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
</script>

<script>
import Game from "@/Game";

const games = [
  new Game("Blackjack", "/blackjack.jpg", "Beat the dealer and win!"),
];
export default {
  data() {
    return {
      games: games,
    };
  },
  methods: {},
};
</script>

<template>
  <NavBar :points="points" />
  <RouterView class="h-full pb-10 pt-28" :games="games" />
</template>
