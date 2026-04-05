<template>
    <div class="bg-[#FFECE2] fixed inset-0 flex justify-center overflow-y-auto">
        <div>
            <Navbar />
            <h1
                class="text-[#933500] mt-[clamp(1rem,38vh,8rem)] mb-[clamp(1rem,20vh,3.75rem)] max-w-6xl text-[clamp(3rem,5.5vw,8rem)] font-bold font-quasititle text-center"
            >
                Just 3 guys making software
            </h1>
            <br />
            <section id="about-us">
                <p
                    class="text-center mt-32 mb-[clamp(1rem,8vh,3.75rem)] mx-auto max-w-2xl w-[60vw] text-[clamp(1rem,2.5vw,3rem)] font-def text-[#3E312D]"
                >
                    Hi 👋, we’re three high school students making open source
                    software to help with our and hopefully your annoyances. And
                    this all began with one problem...
                    <br /><br />
                    Our classes often use Quizlet. While it is great for
                    studying, it has so many ads and a lot of useful features
                    are limited in its free plan. So, Xun (founder) had the
                    bright idea to make ourselves an open source flashcard app.
                    <br /><br />
                    Therefore, after some collaboration challenges, we started
                    working on it. Now, Tracer is in alpha and we’re actively
                    maintaining it. We have many more ideas for the future to
                    come.
                </p>
            </section>
            <section id="buymeacoffee" class="flex flex-col">
                <img src="/buymeacoffee.svg" class="mx-auto scale-[0.75]" />
                <p
                    class="text-center text-[clamp(1rem,2.3vw,3rem)] font-def text-[#3E312D]"
                >
                    plz we want money
                </p>
            </section>
            <section id="projects" class="py-20 px-4">
                <h2 class="text-4xl font-def text-center mb-12">
                    Our Projects
                </h2>

                <div
                    class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 max-w-6xl mx-auto"
                >
                    <div
                        class="bg-[#B15018] rounded-3xl shadow-lg flex flex-row items-center justify-between"
                    >
                        <div class="pl-5">
                            <h3 class="text-2xl font-bold mb-3 text-[#FFECE2]">
                                Tracer
                            </h3>
                            <p class="text-[#FFCBAE] mb-4">Flashcards app w/ BYOK and learn modes</p>
                        </div>
                        <img src="/tracer.png" class="scale-[0.6] -mr-3" />
                    </div>

                    <div
                        class="bg-[#B15018] rounded-3xl shadow-lg flex flex-row items-center justify-between"
                    >
                        <div class="pl-5">
                            <h3 class="text-2xl font-bold mb-3 text-[#FFECE2]">
                                Seaport
                            </h3>
                            <p class="text-[#FFCBAE] mb-4">Coming soon!</p>
                        </div>
                        <img src="" class="scale-[0.6] -mr-3" />
                    </div>

                    <div
                        class="bg-[#B15018] rounded-3xl shadow-lg flex flex-row items-center justify-between"
                    >
                        <div class="pl-5">
                            <h3 class="text-2xl font-bold mb-3 text-[#FFECE2]">
                                Fünd
                            </h3>
                            <p class="text-[#FFCBAE] mb-4">Coming soon!</p>
                        </div>
                        <img src="/" class="scale-[0.6] -mr-3" />
                    </div>
                </div>
            </section>

            <section id="contact"></section>
            <div></div>
        </div>
    </div>
</template>
