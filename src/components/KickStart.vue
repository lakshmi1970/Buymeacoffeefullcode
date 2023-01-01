<template>
    <section class="kickstart">
        <div class="container-fluid xl:px-14 px-4 grid md:grid-cols-2 grid-cols-1 gap-4">
            <div>
                <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 80 80" fill="none" class="mt-6">
                <g clip-path="url(#clip0_39_6)">
                <rect width="80" height="80" rx="40" fill="#F3F0EA"/>
                <circle cx="60" cy="40" r="28" fill="#66645E"/>
                <circle cx="60" cy="40" r="12" fill="#807E76"/>
                <path d="M53 40L-1 71.1769L-1 8.82308L53 40Z" fill="#71A894"/>
                <path d="M62 40L26 60.7846L26 19.2154L62 40Z" fill="#81BFA8"/>
                </g>
                <defs>
                <clipPath id="clip0_39_6">
                <rect width="80" height="80" rx="40" fill="white"/>
                </clipPath>
                </defs>
                </svg>
                <h2 class="xl:mt-8 xl:text-5xl text-3xl leading-normal">Kickstart an organization with your co-founders</h2>
                <p class="mt-6 md:pr-10">It’s the early days, you just had a long conversation with two friends about a meaningful challenge that you’re all passionate about and have a potential solution for. You’re ready to embark the startup journey.</p>
            </div>
            <div>
                <div class="founder-card bg-white px-8 py-9 border-4 xl:w-4/5 rounded-lg xl:ml-10 w-full">
                    <h4 class="font-bold text-3xl mb-7">Members</h4>
                    <ul class="flex flex-col gap-3">
                        <li class="flex items-center"><img src="../assets/images/founder1.png" class="rounded-full" /><p class="font-bold tracking-widest">Dillon Kydd <span class="block font-normal mt-2">100 SHARES</span></p></li>
                        <li class="flex items-center"><img src="../assets/images/founder2.png" class="rounded-full" /><p class="font-bold tracking-widest">Anna Olsen <span class="block font-normal mt-2">100 SHARES</span></p></li>
                        <li class="flex items-center"><img src="../assets/images/founder3.png" class="rounded-full" /><p class="font-bold tracking-widest">Kas Moss <span class="block font-normal mt-2">100 SHARES</span></p></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<style>
.kickstart .founder-card {
    box-shadow:10px 10px #71a894;
}
.founder-card ul p{
    font-size: 24px;
    line-height: 26px;
    margin-left:14px;
}
.founder-card ul p span {
    font-size: 16px;
    color: #66645E;
}
</style>