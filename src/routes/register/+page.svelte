<script>
    import Swal from "sweetalert2";
    import "../../app.css";

    const trollFunction = () => {
        Swal.fire({
            title: "ajaja, trolleado :V",
            text: "aún no puedes con google",
            icon: "error",
            confirmButtonText: "ok guapo"
        });
    };
</script>

<style>
    @media (max-width: 768px) {
        .flex {
            flex-direction: column;
        }
        .rounded-r-md {
            border-top-left-radius: 0;
            border-bottom-left-radius: 0;
            border-top-right-radius: 0.375rem;
            border-bottom-right-radius: 0.375rem;
        }
        .rounded-l-md {
            border-top-right-radius: 0;
            border-bottom-right-radius: 0;
            border-top-left-radius: 0.375rem;
            border-bottom-left-radius: 0.375rem;
        }
    }
</style>

<!-- Container -->
<div class="flex flex-wrap min-h-screen w-full content-center justify-center bg-gray-200 py-10">

    <!-- Login component -->
    <div class="flex flex-wrap justify-center shadow-mxd">
        <!-- Login form -->
        <div class="flex flex-wrap content-center justify-center rounded-l-md bg-white" style="width: 100%; max-width: 24rem; min-height: 32rem;">
            <div class="w-full px-4">
                <!-- Heading -->
                <h1 class="text-xl font-semibold">Bienvenido estudiante</h1>
                <small class="text-gray-400">Ingresa tus datos correctos y no incorrectos xd</small>

                <!-- Form -->
                <form class="mt-4">
                    <div class="mb-3">
                        <label class="mb-2 block text-xs font-semibold" for="">Nombre</label>
                        <input type="email" placeholder="Enter your email" class="block w-full rounded-md border border-gray-300 focus:border-purple-700 focus:outline-none focus:ring-1 focus:ring-purple-700 py-1 px-1.5 text-gray-500" />
                    </div>

                    <div class="mb-3">
                        <label class="mb-2 block text-xs font-semibold" for="">Email</label>
                        <input type="email" placeholder="dante@gmail.com" class="block w-full rounded-md border border-gray-300 focus:border-purple-700 focus:outline-none focus:ring-1 focus:ring-purple-700 py-1 px-1.5 text-gray-500" />
                    </div>
                    <div class="mb-3">
                        <label class="mb-2 block text-xs font-semibold" for="">Password</label>
                        <input type="email" placeholder="dante@gmail.com" class="block w-full rounded-md border border-gray-300 focus:border-purple-700 focus:outline-none focus:ring-1 focus:ring-purple-700 py-1 px-1.5 text-gray-500" />
                    </div>

                    <div class="mb-3 flex flex-wrap content-center">
                        <a href="/" class="text-xs font-semibold text-purple-700">¿Olvidaste tu contraseña prro?</a>
                    </div>

                    <div class="mb-3">
                        <button class="mb-1.5 block w-full text-center text-white bg-purple-700 hover:bg-purple-900 px-2 py-1.5 rounded-md">Entrar</button>
                        <button class="flex flex-wrap justify-center w-full border border-gray-300 hover:border-gray-500 px-2 py-1.5 rounded-md" on:click={trollFunction}>
                            <img class="w-5 mr-2" src="https://lh3.googleusercontent.com/COxitqgJr1sJnIDe8-jiKhxDx1FrYbtRHKJ9z_hELisAlapwE9LUPh6fcXIfb5vwpbMl4xl9H9TRFPc5NOO8Sb3VSgIBrfRYvW6cUA" alt="">
                            Entrar con Google
                        </button>
                    </div>

                    <!-- Footer -->
                    <div class="text-center">
                        <!-- <span class="text-xs text-gray-400 font-semibold">¿Qué esperas por tener una cuenta?</span> -->
                        <a href="/register" class="text-xs font-semibold text-purple-700">Iniciar sesión</a>
                    </div>
                </form>
            </div>
        </div>

        <!-- Login banner -->
        <div class="flex content-center justify-center rounded-r-md" style="width: 100%; max-width: 24rem; min-height: 32rem;">
            <img class="w-full h-full bg-center bg-no-repeat bg-cover rounded-r-md" src="https://i.imgur.com/9l1A4OS.jpeg" alt="">
        </div>
    </div>

    <!-- Credit -->
    <div class="mt-3 w-full">
        <p class="text-center">Hecho por <a target="_blank" href="https://www.instagram.com/hiram.dev/" class="text-purple-700">Hiram Gabriel</a> el admin</p>
    </div>
</div>
