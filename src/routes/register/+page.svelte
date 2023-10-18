<script>
  import Swal from "sweetalert2"
  import "../../app.css"

  const trollFunction = () => {
      Swal.fire({
          title: "ajaja, trolleado :V",
          text: "aún no puedes con google",
          icon: "error",
          confirmButtonText: "ok guapo"
      })
  }
</script>
<!-- Container -->
<!-- component -->
<body class="">
<!-- Container -->
<div class="container mx-auto">
  <div class="flex justify-center px-6 my-12">
    <!-- Row -->
    <div class="w-full xl:w-3/4 lg:w-11/12 flex">
      <!-- Col -->
      <div
        class="w-full h-auto bg-gray-400 hidden lg:block lg:w-5/12 bg-cover rounded-l-lg"
        style="background-image: url('https://source.unsplash.com/Mv9hjnEUHR4/600x800')"
      ></div>
      <!-- Col -->
      <div class="w-full lg:w-7/12 bg-white p-5 rounded-lg lg:rounded-l-none">
        <h3 class="pt-4 text-2xl text-center">Bievenido estudiante!</h3>
        <form class="px-8 pt-6 pb-8 mb-4 bg-white rounded">
          <div class="mb-4 md:flex md:justify-between">
            <div class="mb-4 md:mr-2 md:mb-0">
              <label class="block mb-2 text-sm font-bold text-gray-700" for="firstName">
                Nombre (s)
              </label>
              <input
                class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline"
                id="firstName"
                type="text"
              />
            </div>
            <div class="md:ml-2">
              <label class="block mb-2 text-sm font-bold text-gray-700" for="lastName">
                Apellido (s)
              </label>
              <input
                class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline"
                id="lastName"
                type="text"
              />
            </div>
          </div>
          <div class="mb-4">
            <label class="block mb-2 text-sm font-bold text-gray-700" for="email">
              Email
            </label>
            <input
              class="w-full px-3 py-2 mb-3 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline"
              id="email"
              type="email"
              placeholder="hiram.dev@gmail.com"
            />
          </div>
          <div class="mb-4 md:flex md:justify-between">
            <div class="mb-4 md:mr-2 md:mb-0">
              <label class="block mb-2 text-sm font-bold text-gray-700" for="password">
                Contraseña
              </label>
              <input
                class="w-full px-3 py-2 mb-3 text-sm leading-tight text-gray-700 border border-red-500 rounded shadow appearance-none focus:outline-none focus:shadow-outline"
                id="password"
                type="password"
                placeholder="******************"
              />
              <p class="text-xs italic text-red-500">Por favor escriba una contraseña.</p>
            </div>
            <div class="md:ml-2">
              <label class="block mb-2 text-sm font-bold text-gray-700" for="c_password">
                Contraseña
              </label>
              <input
                class="w-full px-3 py-2 mb-3 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline"
                id="c_password"
                type="password"
                placeholder="******************"
              />
            </div>
          </div>
          <div class="mb-8">
            <input type="file" name="file" id="file" class="sr-only" />
            <label
              for="file"
              class="relative flex min-h-[200px] items-center justify-center rounded-md border border-dashed border-[#e0e0e0] p-12 text-center"
            >
            <div>
                <span class="mb-2 block text-xl font-semibold text-[#07074D]">
                Arrastra aquí
                </span>
                <span class="mb-2 block text-base font-medium text-[#6B7280]">
                  O
                </span>
                <span
                  class="inline-flex rounded border border-[#e0e0e0] py-2 px-7 text-base font-medium text-[#07074D]"
                >
                  Buscar
                </span>
              </div>
            </label>
          </div>
          <div class="mb-6 text-center">
            <button
              class="w-full px-4 py-2 font-bold text-white bg-blue-500 rounded-full hover:bg-blue-700 focus:outline-none focus:shadow-outline"
              type="button"
              on:click={trollFunction}
              >
               Crear cuenta
            </button>
          </div>
          <hr class="mb-6 border-t" />
          <div class="text-center">
            <a
              class="inline-block text-sm text-blue-500 align-baseline hover:text-blue-800"
              href="/forgot-password"
            >
              ¿Olvidaste tu contraseña?
            </a>
          </div>
          <div class="text-center">
            <a
              class="inline-block text-sm text-blue-500 align-baseline hover:text-blue-800"
              href="/register"
            >
              No tienes una cuenta? Registrate!
            </a>
          </div>
        </form>
      </div>
    </div>
  </div>
</div>
</body>