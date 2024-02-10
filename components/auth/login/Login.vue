<template>
  <div
    class="flex flex-col gap-6 justify-center bg-white rounded-md p-5 py-10 w-[25%]"
  >
    <div class="flex items-center justify-center">
      <h1 class="text-2xl font-bold">Login</h1>
    </div>
    <div class="flex flex-col gap-10">
      <div class="flex flex-col gap-2">
        <label for="email">Email</label>
        <input
          type="text"
          id="email"
          class="flex h-12 w-full rounded-md border border-gray-300 px-3 py-2 text-sm text-zinc-950 file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-zinc-500 focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-zinc-900 focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50"
        />
      </div>
      <div class="flex flex-col gap-2">
        <label for="password">Password</label>
        <input
          type="password"
          id="password"
          class="flex h-12 w-full rounded-md border border-gray-300 px-3 py-2 text-sm text-zinc-950 file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-zinc-500 focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-zinc-900 focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50"
        />
        <div class="flex items-center justify-between">
          <div class="flex gap-4">
            <input id="remember_me" type="checkbox" />
            <label for="remember_me" class="cursor-pointer">Remember me</label>
          </div>
          <div>
            <NuxtLink to="/auth/register" class="text-blue-500">
              Forgot Password?
            </NuxtLink>
          </div>
        </div>
      </div>
      <div class="flex">
        <button
          class="inline-flex items-center justify-center rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 bg-blue-700 w-full p-3 text-blue-50 hover:bg-blue-700/90"
        >
          Sign in
        </button>
      </div>
    </div>
  </div>
</template>
