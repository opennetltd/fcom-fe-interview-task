<template>
  <div class="bg-[#020420] p-8 text-[#e7e7e7]">
    <div class="pb-8">
      <h1
        class="flex flex-col gap-y-4 items-center justify-center"
        data-v-8e92eaa8=""
      >
        <RouterLink
          to="/"
          class="gap-4 inline-flex items-end"
          data-v-8e92eaa8=""
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            aria-label="Nuxt"
            class="h-8 sm:h-12"
            viewBox="0 0 800 200"
            data-v-8e92eaa8=""
          >
            <path
              fill="#00dc82"
              d="M168.303 200h111.522c3.543 0 7.022-.924 10.09-2.679A20.1 20.1 0 0 0 297.3 190a19.86 19.86 0 0 0 2.7-10.001 19.86 19.86 0 0 0-2.709-9.998L222.396 41.429a20.1 20.1 0 0 0-7.384-7.32 20.3 20.3 0 0 0-10.088-2.679c-3.541 0-7.02.925-10.087 2.68a20.1 20.1 0 0 0-7.384 7.32l-19.15 32.896L130.86 9.998a20.1 20.1 0 0 0-7.387-7.32A20.3 20.3 0 0 0 113.384 0c-3.542 0-7.022.924-10.09 2.679a20.1 20.1 0 0 0-7.387 7.319L2.709 170A19.85 19.85 0 0 0 0 179.999c-.002 3.511.93 6.96 2.7 10.001a20.1 20.1 0 0 0 7.385 7.321A20.3 20.3 0 0 0 20.175 200h70.004c27.737 0 48.192-12.075 62.266-35.633l34.171-58.652 18.303-31.389 54.93 94.285h-73.233zm-79.265-31.421-48.854-.011 73.232-125.706 36.541 62.853-24.466 42.01c-9.347 15.285-19.965 20.854-36.453 20.854"
              data-v-8e92eaa8=""
            ></path>
            <path
              fill="currentColor"
              d="M377 200a4 4 0 0 0 4-4v-93s5.244 8.286 15 25l38.707 66.961c1.789 3.119 5.084 5.039 8.649 5.039H470V50h-27a4 4 0 0 0-4 4v94l-17-30-36.588-62.98c-1.792-3.108-5.081-5.02-8.639-5.02H350v150zm299.203-56.143L710.551 92h-25.73a9.97 9.97 0 0 0-8.333 4.522L660.757 120.5l-15.731-23.978A9.97 9.97 0 0 0 636.693 92h-25.527l34.348 51.643L608.524 200h24.966a9.97 9.97 0 0 0 8.29-4.458l19.18-28.756 18.981 28.72a9.97 9.97 0 0 0 8.313 4.494h24.736zM724.598 92h19.714V60.071h28.251V92H800v24.857h-27.437V159.5c0 10.5 5.284 15.429 14.43 15.429H800V200h-16.869c-23.576 0-38.819-14.143-38.819-39.214v-43.929h-19.714zM590 92h-15c-3.489 0-6.218.145-8.5 2.523-2.282 2.246-2.5 3.63-2.5 7.066v52.486c0 8.058-.376 12.962-4 16.925-3.624 3.831-8.619 5-16 5-7.247 0-12.376-1.169-16-5-3.624-3.963-4-8.867-4-16.925v-52.486c0-3.435-.218-4.82-2.5-7.066C519.218 92.145 516.489 92 513 92h-15v62.422q0 21.006 11.676 33.292C517.594 195.905 529.103 200 544 200s26.204-4.095 34.123-12.286Q590 175.428 590 154.422z"
              data-v-8e92eaa8=""
            ></path>
          </svg>
          <span
            class="bg-[#00DC42]/10 border border-[#00DC42]/50 font-mono font-semibold group-hover:bg-[#00DC42]/15 group-hover:border-[#00DC42] inline-block leading-none px-2 py-1 rounded sm:px-2.5 sm:py-1.5 sm:text-[14px] text-[#00DC82] text-[12px]"
            data-v-8e92eaa8=""
          >
            4.0.1</span
          >
        </RouterLink>
      </h1>
    </div>
    <NuxtPage />

    <NuxtWelcome class="hidden!" />
  </div>
</template>

<script lang="ts" setup></script>

<style>
html, body {
  background-color: #020420;
  color: #e7e7e7;
}
</style>
