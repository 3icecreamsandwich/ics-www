<template>
    <div class="mx-auto px-4 py-3 flex items-center justify-between">
        <div class="flex gap-10">
            <NuxtLink to="#contact"
                ><p class="text-[clamp(1rem,2vw,3rem)] mt-5">Contact</p>
            </NuxtLink>
            <NuxtLink to="#about-us">
                <p class="font-def text-[clamp(1rem,2vw,3rem)] mt-5">
                    About Us
                </p>
            </NuxtLink>
        </div>

        <NuxtLink to="/">
            <img
                src="/favicon.svg"
                alt="Ice Cream Sandwich Logo"
                class="absolute left-1/2 -translate-x-1/2 -translate-y-1/4 h-20"
            />
        </NuxtLink>

        <div class="flex gap-10">
            <NuxtLink to="#projects">
                <p class="font-def text-[clamp(1rem,2vw,3rem)] mt-5">
                    Projects
                </p></NuxtLink
            >
            <NuxtLink to="#buymeacoffee">
                <p class="font-def text-[clamp(1rem,2vw,3rem)] mt-5">
                    buymeacoffee
                </p>
            </NuxtLink>
        </div>
    </div>
</template>
