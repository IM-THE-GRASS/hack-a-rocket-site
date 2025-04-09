<div class="min-h-screen bg-black text-white">
    <div class="section">
        <div class="relative top-[25vh] text-center px-4">
            <h1 class="text-6xl md:text-8xl font-black mb-6 tracking-tighter">
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-red-500 to-yellow-400">HACKAROCKET</span>
            </h1>
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
        </div>
        
        <img src="https://apex.hackclub.com/_astro/orpheusrocket.BcATR92j_ZuAQiV.webp" class ="absolute bottom-[50vh] right-[70vw] rocket-animation" alt="orpheus">
        <img src="https://apex.hackclub.com/_astro/orpheusmoon.zrsJmnRu_Z1TLXVL.webp" alt="orpheus on the mooon" class="absolute bottom-[60vh] left-[80vw]">
        <img src="https://apex.hackclub.com/_astro/orpheusflag.DH1oNYAj_1YzrtM.webp" alt="orpheus on the mooon 2" class="absolute bottom-0 right-[80vw] w-[200px]">

    </div>
</div>

<style>
    .rocket-animation {
        animation: float 6s ease-in-out infinite;
    }
    
    @keyframes float {
        0% { transform: translate(-50%, 0) rotate(0deg); }
        50% { transform: translate(-50%, -20px) rotate(5deg); }
        100% { transform: translate(-50%, 0) rotate(0deg); }
    }
</style>