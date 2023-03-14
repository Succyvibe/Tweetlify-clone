<template>
  <footer>
    <div class="lg:max-w-[1216px] mx-auto px-4 py-24 lg:py-24">
      <div class="w-full grid lg:grid-cols-3 xl:grid-cols-4">
        <div>
          <svg
            width="50"
            height="50"
            viewBox="0 0 50 50"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M24.6377 50C38.2447 50 49.2754 38.8071 49.2754 25C49.2754 11.1929 38.2447 0 24.6377 0C11.0307 0 0 11.1929 0 25C0 38.8071 11.0307 50 24.6377 50ZM27.1106 13.0662C26.9383 12.8279 26.6956 12.6516 26.4177 12.563V12.5643C26.1401 12.4755 25.8417 12.4787 25.566 12.5736C25.2904 12.6685 25.0517 12.8502 24.8847 13.0921L15.3034 26.981C15.1599 27.1892 15.0755 27.4334 15.0592 27.6869C15.043 27.9404 15.0957 28.1936 15.2114 28.4189C15.3271 28.6441 15.5015 28.8329 15.7156 28.9646C15.9298 29.0963 16.1754 29.1658 16.4257 29.1657H21.9008V36.1102C21.9006 36.4058 21.9934 36.6938 22.1656 36.9322C22.3379 37.1706 22.5806 37.3471 22.8585 37.4358C23.1364 37.5246 23.435 37.5211 23.7107 37.4258C23.9865 37.3305 24.2252 37.1484 24.3919 36.906L33.9732 23.0171C34.1167 22.8089 34.2011 22.5648 34.2174 22.3112C34.2336 22.0577 34.1809 21.8045 34.0652 21.5793C33.9495 21.354 33.7751 21.1652 33.5609 21.0335C33.3468 20.9019 33.1012 20.8323 32.8509 20.8324H27.3758V13.888C27.3758 13.5924 27.2829 13.3045 27.1106 13.0662Z"
              fill="url(#paint0_linear_38_2)"
            ></path>
            <defs>
              <linearGradient
                id="paint0_linear_38_2"
                x1="25"
                y1="-14"
                x2="25"
                y2="63"
                gradientUnits="userSpaceOnUse"
              >
                <stop stop-color="#4F46E5"></stop>
                <stop
                  offset="0.520833"
                  stop-color="#6F46E5"
                  stop-opacity="0.943125"
                ></stop>
                <stop
                  offset="1"
                  stop-color="#C546E5"
                  stop-opacity="0.92"
                ></stop>
              </linearGradient>
            </defs>
          </svg>
          <p class="text-[#F4F4F5] text-sm text-[100] mt-3">
            Tweetlify.co <br />
            Millions, and millions of viral tweets
          </p>
        </div>

        <div class="flex flex-col items-center gap-4">
          <p class="uppercase text-[#84868A] font-[700]">Features</p>
          <ul class="flex flex-col gap-4">
            <li class="cursor-pointer text-sm text-[#F4F4F5] text-[100]">
              <NuxtLink to="/">Viral tweets</NuxtLink>
            </li>
            <li class="cursor-pointer text-sm text-[#F4F4F5] text-[100]">
              <NuxtLink to="/">Scheduling</NuxtLink>
            </li>
            <li class="cursor-pointer text-sm text-[#F4F4F5] text-[100]">
              <NuxtLink to="/">Engagement</NuxtLink>
            </li>
            <li class="cursor-pointer text-sm text-[#F4F4F5] text-[100]">
              <NuxtLink to="/">Threads</NuxtLink>
            </li>
          </ul>
        </div>
        <div class="flex flex-col gap-4">
          <p class="uppercase text-[#84868A] font-[700]">Services</p>
          <ul class="flex flex-col gap-4">
            <li class="cursor-pointer text-sm text-[#F4F4F5] text-[100]">
              <NuxtLink to="/">Ghoatwritting</NuxtLink>
            </li>
          </ul>
        </div>
        <div class="flex flex-col gap-4">
          <p class="uppercase text-[#84868A] font-[700]">Company</p>
          <ul class="flex flex-col gap-4">
            <li class="cursor-pointer text-sm text-[#F4F4F5] text-[100]">
              <NuxtLink to="/">Join Our Affilliate Program</NuxtLink>
            </li>
            <li class="cursor-pointer text-sm text-[#F4F4F5] text-[100]">
              <NuxtLink to="/">Private Policy</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style></style>
