<!-- component -->
<script 
    defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js">

</script>

<main class="relative min-h-screen w-full bg-white">
    <div class="p-6" x-data="app">
        <!-- header -->
        <header class="flex w-full justify-between">
            <svg class="h-7 w-7 cursor-pointer text-gray-400 hover:text-gray-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" stroke="currentColor">
                <path stroke-width="1" fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path>
            </svg>


        </header>

        <div class="absolute left-1/2 top-1/2 mx-auto max-w-sm -translate-x-1/2 -translate-y-1/2 transform space-y-4 text-center">
            <!-- register content -->
            <div x-show="isLoginPage" class="space-y-4">
                <header class="mb-3 text-2xl font-bold">Create your profile</header>
                <div class="w-full rounded-2xl bg-gray-50 px-4 ring-2 ring-gray-200 focus-within:ring-blue-400">
                    <input type="text" placeholder="Age" class="my-3 w-full border-none bg-transparent outline-none focus:outline-none" />
                </div>
                <div class="w-full rounded-2xl bg-gray-50 px-4 ring-2 ring-gray-200 focus-within:ring-blue-400">
                    <input type="text" placeholder="Name (optional)" class="my-3 w-full border-none bg-transparent outline-none focus:outline-none" />
                </div>
                <div class="w-full rounded-2xl bg-gray-50 px-4 ring-2 ring-gray-200 focus-within:ring-blue-400">
                    <input type="text" placeholder="Email" class="my-3 w-full border-none bg-transparent outline-none focus:outline-none" />
                </div>
                <div class="w-full rounded-2xl bg-gray-50 px-4 ring-2 ring-gray-200 focus-within:ring-blue-400">
                    <input type="password" placeholder="Password" class="my-3 w-full border-none bg-transparent outline-none focus:outline-none" />
                </div>
                <button class="w-full rounded-2xl border-b-4 border-b-blue-600 bg-blue-500 py-3 font-bold text-white hover:bg-blue-400 active:translate-y-[0.125rem] active:border-b-blue-400">CREATE ACCOUNT</button>
            </div>

            <footer>
                <div class="grid grid-cols-2 gap-4">
                    <a href="#" class="rounded-2xl border-b-2 border-b-gray-300 bg-white px-4 py-2.5 font-bold text-blue-700 ring-2 ring-gray-300 hover:bg-gray-200 active:translate-y-[0.125rem] active:border-b-gray-200">FACEBOOK</a>
                    <a href="#" class="rounded-2xl border-b-2 border-b-gray-300 bg-white px-4 py-2.5 font-bold text-blue-500 ring-2 ring-gray-300 hover:bg-gray-200 active:translate-y-[0.125rem] active:border-b-gray-200">GOOGLE</a>
                </div>

                <div class="mt-8 text-sm text-gray-400">
                    By signing in to ********, you agree to our
                    <a href="#" class="font-medium text-gray-500">Terms</a> and <a href="#" class="font-medium text-gray-500">Privacy Policy</a>.
                </div>
            </footer>
        </div>
    </div>
</main>
