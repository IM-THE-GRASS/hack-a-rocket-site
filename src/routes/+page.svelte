<div class="min-h-screen bg-black text-white snap-y snap-mandatory overflow-y-scroll">
    <div class="section snap-center">
        <div class="h-full w-[100vw] text-center px-4 fixed mt-[10vh]">
            <div class="flex flex-col items-center justify-center">
                <img src="./logo.svg" alt="orpheus logo" class="w-[500px] mb-6">
            </div>
            <h2 class="text-2xl font-bold mb-2 tracking-tighter">
                The <span class="text-transparent font-black bg-clip-text bg-gradient-to-r from-red-500 to-yellow-400">high school hackathon</span> where you send your</h2>
            <h2 class="text-2xl font-bold mb-6 tracking-tighter">
                homemade rocket <span class="text-transparent font-black bg-clip-text bg-gradient-to-r from-red-500 to-yellow-400">400ft in the air</span>
            </h2>
            <div class="flex gap-4 justify-center">
                <a href="#register" class="bg-red-600 hover:bg-red-700 px-8 py-3 rounded-full font-black text-xl transition">
                    Register
                </a>
                <a href="#about" class="border-2 border-white hover:bg-white hover:text-black px-8 py-3 rounded-full font-black text-xl transition">
                    Learn More
                </a>
            </div>
            <div>
                <img src="./star1.svg" class="fixed bottom-[20%] left-[75%] scale-20 rotate-6" alt="orpheus">
                <img src="./star2.svg" class="fixed bottom-[30%] left-[15%] scale-15 rotate-1" alt="orpheus">
                <img src="./star3.svg" class="fixed bottom-[70%] left-[65%] scale-17 rotate-[-12deg]" alt="orpheus">
                
            </div>
            <img src="https://apex.hackclub.com/_astro/orpheusrocket.BcATR92j_ZuAQiV.webp" class="fixed bottom-[60%] left-[85%] rocket-animation" alt="orpheus">
            <img src="https://apex.hackclub.com/_astro/orpheusmoon.zrsJmnRu_Z1TLXVL.webp" alt="orpheus on the mooon" class="fixed moon-animation  bottom-[60vh] left-[5%]">
            <img src="https://apex.hackclub.com/_astro/orpheusflag.DH1oNYAj_1YzrtM.webp" alt="orpheus on the mooon 2" class=" fixed bottom-0 right-[80vw] w-[200px]">

        </div>
        
    </div>
    <div class="section snap-center">
        <div class="fixed">
        </div>
    </div>
    <div class="section snap-center">
        <div class="">
        </div>
    </div>
    <div class="section snap-center">
        <div class="">
        </div>
    </div>
</div>

<style>
    .rocket-animation {
        animation: float 6s ease-in-out infinite;
    }
    .moon-animation {
        animation: float2 6s ease-in-out infinite;
    }
    @keyframes float {
        0% { transform: translate(-50%, 0) rotate(0deg); }
        50% { transform: translate(-50%, -20px) rotate(5deg); }
        100% { transform: translate(-50%, 0) rotate(0deg); }
    }
    @keyframes float2 {
        0% { transform: translate(-15%, 5) rotate(0deg); }
        50% { transform: translate(-15%, 0) rotate(5deg); }
        100% { transform: translate(-15%, -5) rotate(0deg); }
    }
</style>
