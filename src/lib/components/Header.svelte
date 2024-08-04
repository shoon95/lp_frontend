<script>
    import { goto } from '$app/navigation';
</script>

<!-- component -->
	<!-- Navigaiton Bar -->
    <div class="bg-white py-4 shadow-lg">
        <div class="container mx-auto flex items-center justify-between">
          <!-- 로고 -->
          <div class="flex items-center bg-red-600 text-white px-4 py-2 rounded-lg">
            <span class="text-lg font-bold">Couples</span>
          </div>
          
          <!-- 네비게이션 메뉴 -->
          <div class="flex items-center space-x-4">
            <button on:click={() => goto("/")} class="text-gray-800 px-3 py-2 rounded-lg hover:bg-red-600 hover:text-white transition duration-300 cursor-pointer" >홈</button>
            <button class="text-gray-800 px-3 py-2 rounded-lg hover:bg-red-600 hover:text-white transition duration-300">사진첩</button>
            <button class="text-gray-800 px-3 py-2 rounded-lg hover:bg-red-600 hover:text-white transition duration-300">맛집</button>
            <button class="text-gray-800 px-3 py-2 rounded-lg hover:bg-red-600 hover:text-white transition duration-300">기록</button>
            <button class="text-gray-800 px-3 py-2 rounded-lg hover:bg-red-600 hover:text-white transition duration-300">캘린더</button>
          </div>
          
          <!-- 로그인 및 회원가입 버튼 -->
          <div class="flex items-center space-x-3">
            <button on:click={() => goto("/login")} class="border border-indigo-600 bg-white text-indigo-600 rounded-lg px-4 py-2 transition duration-300 hover:bg-indigo-600 hover:text-white">
              Login
            </button>
          </div>
        </div>
      </div>
	<!-- End Navigation Bar -->
