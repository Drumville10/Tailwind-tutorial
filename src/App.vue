<template>
  <div class="bg-blue-400 h-96">
    <div class="text-5xl font-extrabold">
      <span class="bg-clip-text text-transparent bg-gradient-to-r from-yellow-300 via-lime-200 to-lime-400">
        Formulario
      </span>
    </div>
    <form action="" class=" bg-white w-80 mx-auto rounded-lg p-6 sm:bg-amber-200">
      <label for="">Nombre</label>
      <input class="border border-gray-300 w-full px-3 py-2 mb-4 rounded-md disabled:bg-red-200" type="text"
        placeholder="Jhon Doe" disabled>

      <label for="">Correo</label>
      <input
        class="border border-gray-300 w-full px-3 py-2 mb-4 rounded-md focus:outline-none focus:ring-1 focus:ring-purple-600 invalid:focus:ring-red-400 peer"
        type="email">
      <p class="text-red-400 hidden peer-invalid:block">El correo es invalido</p>

      <label for="">Contraseña</label>
      <input class="border border-gray-300 w-full px-3 py-2 mb-4 rounded-md " type="password">

      <button class="bg-blue-500 w-full py-2 text-white rounded-md cursor-pointer hover:bg-blue-400">Ingresar</button>
    </form>
  </div>
</template>

<script setup>

</script>

<style scoped></style>
