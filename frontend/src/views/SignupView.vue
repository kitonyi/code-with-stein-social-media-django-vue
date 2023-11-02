<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-4">
    <div class="main-left">
      <div class="p-12 bg-white border border-gray-200 rounded-lg">
        <h1 class="mb-6 text-2xl">Sign up</h1>
        <p class="mb-6 text-gray-500">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus
          deleniti architecto omnis hic, officia enim! Earum velit omnis ea
          ipsa!
        </p>
        <p class="font-bold">
          Already have an account?
          <RouterLink to="/login" class="underline">Click here</RouterLink> to
          login!
        </p>
      </div>
    </div>
    <div class="main-right">
      <div class="p-12 bg-white border border-gray-200 rounded-lg">
        <form class="space-y-6">
          <div>
            <label for="name">Name</label> <br />
            <input
              type="text"
              name="name"
              placeholder="Your Full Name"
              class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg"
            />
          </div>
          <div>
            <label for="email">E-mail</label> <br />
            <input
              type="email"
              name="email"
              placeholder="Your Email address"
              class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg"
            />
          </div>
          <div>
            <label for="password">Password</label> <br />
            <input
              type="password"
              name="password"
              placeholder="Your  Password"
              class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg"
            />
          </div>
          <div>
            <label for="confirmPassword">Confirm Password</label> <br />
            <input
              type="password"
              name="confirmPassword"
              placeholder="Confirm Your Password"
              class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg"
            />
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
