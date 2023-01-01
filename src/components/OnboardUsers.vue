<template>
    <section>
        <section>
        <div class="container-fluid xl:px-14 px-4 grid md:grid-cols-2 grid-cols-1 gap-4">
            <div>
                <div class="founder-card bg-white px-8 py-9 border-4 xl:w-4/6 xl:ml-6 rounded-lg w-full">
                    <ul class="flex flex-col gap-3">
                        <li class="flex items-center tracking-widest"><img src="../assets/images/onboard.png" class="rounded-full" /><p class="font-bold  tracking-widest">Jassir Jonis <span class="block font-normal">Pre-seed angel investor</span></p></li>
                    </ul>
                    <p class="text-lg my-4 tracking-widest">Hey guys, love what you’re doing and I’m convinced that together we’ll achieve amazing things.</p>
                    <ul class="count flex">
                        <li><p class="tracking-widest">COMMIT <span class="block">10,000 DAI</span></p></li>
                        <li class="ml-12 tracking-widest"><p class="tracking-widest">SHARES <span class="block">20</span></p></li>
                    </ul>
                    <div class="pointer-events-auto text-white rounded-md text-center font-normal shadow-sm ring-1 ring-slate-700/10 hover:opacity-70 mt-10 bg-primary w-full px-6 py-4 tracking-widest">Go to vote</div>

                </div>
            </div>
            <div>
                <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 80 80" fill="none" class="mt-6">
                <rect width="80" height="80" rx="40" fill="#F3F0EA"/>
                <circle opacity="0.2" cx="40" cy="40" r="32" fill="#71A894"/>
                <circle opacity="0.4" cx="40" cy="40" r="24" fill="#71A894"/>
                <circle opacity="0.6" cx="40" cy="40" r="17" fill="#71A894"/>
                <circle cx="40" cy="40" r="9" fill="#71A894"/>
                </svg>
                <h2 class="xl:mt-8 xl:text-5xl text-3xl leading-normal">Onboard users, investors and advisors as you grow</h2>
                <p class="mt-6 md:pr-10">You’ve bootstrapped and delivered an MVP, and some investors and advisors are interested in having a chat with you. As an Open Enterprise, you can onboard them seamlessly into your digital organization and align them with your success.</p>
            </div>
        </div>
    </section>
    </section>
</template>

<style>
.founder-card .count p {
    margin:0;
    font-size:16px;
}
.founder-card .count p span {
    font-size:24px;
    letter-spacing: -0.02em;
}
</style>