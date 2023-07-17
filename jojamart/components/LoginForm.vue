<template>
  <div class="flex flex-col items-center justify-center px-6 py-8 mx-auto md:h-screen lg:py-0">
      <a href="#" class="flex items-center mb-6 text-3xl font-semibold text-sky-600">J<div class="border-inherit smile">oJa</div>-Mart</a>
      <div class="w-full bg-white rounded-lg shadow-lg md:mt-0 sm:max-w-md xl:p-0">
          <div class="p-6 space-y-4 md:space-y-6 sm:p-8">
              <h1 class="text-xl font-bold leading-tight tracking-tight text-sky-600 md:text-2xl">
                  Sign in to your account
              </h1>
              <form class="space-y-4 md:space-y-6" action="#">
                  <div>
                        <label for="email" class="block mb-2 text-sm font-medium text-sky-600">Email</label>
                        <input type="email" name="email" id="email" @keyup="CheckEmail" class="bg-gray-50 border border-gray-300 text-gray-600 sm:text-sm rounded-lg block w-full p-2.5" placeholder="name@joja.com" required>
                        <div id="email-alert" class="pt-1" style="display: none;">
                            <span class="text-red-500">Invalid email address</span>
                        </div>
                  </div>
                  <div>
                      <label for="password" class="block mb-2 text-sm font-medium text-sky-600">Password</label>
                      <input type="password" name="password" id="password" placeholder="***********" class="bg-gray-50 border border-gray-300 text-gray-600 sm:text-sm rounded-lg block w-full p-2.5" required>
                  </div>
                  <button type="submit" class="w-full text-white bg-sky-600 hover:bg-sky-700 focus:ring-4 focus:outline-none focus:ring-sky-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center">Sign in</button>
              </form>
          </div>
      </div>
  </div>
</template>

<script>
    export default {
        
    }
    
</script>

<style scoped>
    .smile{
        border-bottom: 3px solid; 
        border-bottom-left-radius: 50px 20px; 
        border-bottom-right-radius: 50px 20px;
    }
</style>