<script setup lang="ts">
</script>

<template>
  <main>
    <!-- Home -->
    <section class="bg-blue-500 text-white py-20 px-6">
      <div class="flex justify-around items-center">

        <div>
          <h1 class="text-4xl md:text-5xl font-extrabold">
            Estética canina
          </h1>

          <p class="mt-4 text-lg text-white/90">
            Consentimos a tu mejor amigo como se merece
          </p>

          <a class="inline-block mt-6 bg-white text-blue-500 font-bold px-6 py-3 rounded-2xl shadow-lg cursor-pointer" href="https://t.me/Puppy_Clean_Bot" target="_blank">
            Reservar cita
          </a>
        </div>

        <div class="flex justify-center">
          <img
            src="/src/assets/Dog1.png"
            alt="Perrito baño"
            class="w-80 md:w-96 drop-shadow-2xl"
          />
        </div>
      </div>
    </section>
    <!-- Servicios -->
    <section>
        <div class="text-center mx-auto">
            <h2 class="text-3xl font-bold text-blue-500">Nuestros servicios</h2>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-3">
                <div class="rounded-2xl shadow-md p-6">
                    <h3 class="font-bold text-lg">Baño</h3>
                    <p>Productos de calidad para la piel de tu mascota</p>
                </div>

                <div class="rounded-2xl shadow-md p-6">
                    <h3 class="font-bold text-lg">Corte</h3>
                    <p>Estilos profesional según la raza</p>
                </div>

                <div class="rounded-2xl shadow-md p-6">
                    <h3 class="font-bold text-lg">Spa</h3>
                    <p>Relajación total para tu perrito</p>
                </div>
            </div>

        </div>
    </section>
    <!-- Horarios -->
    <section>
        <div class="text-center p-2">
            <h2 class="text-blue-500 text-3xl font-bold">Horarios de atención</h2>
            <div>
                <p class="text-lg font-semibold">Lunes a Viernes</p>
                <p class="text- mb-4">9:00 AM - 6:00 PM</p>

                <p class="text-lg font-semibold">Sábados</p>
                <p class="mb-4">9:00 AM - 2:00 PM</p>

                <p class="text-lg font-semibold text-red-500">Domingos</p>
                <p class="mb-4">Cerrado</p>
            </div>
        </div>
    </section>
    <!-- Agendar QR -->
    <section>
        <div class="bg-blue-500 text-center text-white">
            
            <h2 class="text-3xl font-bold">Agenda facil y rápido</h2>
            <p class="mt-4 font-semibold">Escanea el QR y reserva tu cita en minutos</p>

            <div class="flex items-center justify-center mt-6">
                <div>
                    <img
                        src="/src/assets/Dog2.png"
                        alt="Perrito baño"
                        class="w-30 md:w-35 drop-shadow-2xl"
                    />
                </div>
                <div>
                    <img
                        src="/src/assets/qrcode.png"
                        alt="Codigo QR"
                        class="w-70 md:w-90 drop-shadow-2xl"
                    />
                </div>
                <div>
                    <img
                        src="/src/assets/Dog2.png"
                        alt="Perrito baño"
                        class="w-30 md:w-35 drop-shadow-2xl transform scale-x-[-1]"
                    />
                </div>
            </div>
        </div>
    </section>

  </main>
</template>
