<template>
     <div class="fixed top-0 w-full  z-40 navbar border-b border-[#d1d1d1] pb-4 pt-5 px-32" style="background: linear-gradient(311.76deg, #D4E7FE -15.24%, #FFFFFF 78.85%)">
          <div class="navbar_area container mx-auto flex justify-between items-center">
              <div class="navbar_left flex items-center">
                 <img class="cursor-pointer  mr-16" src="../assets/images/logo_one.png">
                 <ul class="cursor-pointer  flex items-center">
                    <li class="cursor-pointer  font-inter font-medium text-sm pr-8">Home</li>
                    <li>
                      <select class="cursor-pointer focus:outline-none bg-[#FAFCFF]">
                         <option class="font-inter font-medium text-sm">Community</option>
                      </select>
                    </li>
                    <li class="cursor-pointer  font-inter font-medium text-sm pl-8 pr-8">Blog</li>
                    <li class="cursor-pointer  font-inter font-medium text-sm pr-8">Events</li>
                 </ul>
              </div>
              <div class="navbar_right flex items-center">
                  <div class="relative">
                        <input  type="text" class="text-xs focus:outline-none w-32 text-[#686868] bg-[#E1EEFE] mr-10 border-b border-[#d1d1d1] pl-5 pb-3" placeholder="Search Here...">
                        &nbsp;
                        <font-awesome-icon icon="fa-solid fa-magnifying-glass" class="absolute top-2 left-0 text-[#2B2B39]" />
                  </div>
                 <button class="bg-btn_bg py-4 px-11 rounded-xl font-inter text-white font-medium">Login</button>
              </div>
          </div>
     </div>
</template>

<script>
export default {
    
}
</script>

