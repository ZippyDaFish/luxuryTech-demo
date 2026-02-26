<script>
    import phone1 from "$lib/assets/phone1.png"
    import phone2 from "$lib/assets/phone2.png";
    import laptop1 from "$lib/assets/laptop1.png"
</script>

<!-- Hero -->
<section class="min-h-screen flex flex-col md:flex-row">
    <!-- Hero Text -->
    <div class="md:w-1/2 w-full flex items-center justify-center bg-[var(--color-bg]">
        <div class="w-full max-w-xl px-6">
            <h1 class="text-6xl mb-8">Curated Tech</h1>
            <p class="text-lg mb-8">Technology, served elegently.</p>
            <a href="#products" class="inline-block btn-primary px-8 py-3 rounded-[var(--radius-md)] 
                font-semibold transition-all duration-200 ease-out hover:bg-[var(--color-primary-hover)] 
                hover:-translate-y-0.5 hover:shadow-md active:translate-y-0 active:shadow-sm">
                See Our Products
            </a>
        </div>
    </div>
    <!-- Hero Media -->
    <div class="md:w-1/2 w-full bg-[var(--color-bg)] h-screen overflow-hidden">
        
    </div>
</section>

<!-- Product 1 -->
<section class="w-full min-h-[66vh] p-16 flex flex-col items-center justify-center bg-[var(--color-surface)] space-y-8">
    <img 
        src={laptop1} 
        alt="Laptop" 
        class="w-2/3 md:w-1/3 max-h-64 object-contain drop-shadow-2xl"
    />

    <div class="max-w-2xl text-center space-y-4">
        <p class="text-xs tracking-[0.2em] uppercase opacity-60">Curated Tech</p>
        <h3 class="text-3xl md:text-4xl font-semibold">Steward Laptop</h3>
        <p class="text-lg md:text-xl opacity-80">
            Sleek and refined. Serving all your needs, elegently.
        </p>
    </div>
    <div class="w-24 h-1 bg-[var(--color-accent)] rounded-full mt-4"></div>
</section>

<!-- Product 2 -->
<section class="min-h-screen py-32 flex flex-col md:flex-row items-center bg-[var(--color-bg)]">
    <div class="md:w-1/2 w-full px-6 py-12 md:py-0 flex flex-col justify-center pl-60 space-y-6">
        <p class="text-xs tracking-[0.2em] uppercase opacity-60">Curated Tech</p>
        <h3 class="text-3xl font-semibold">Valet One</h3>
        <p class="text-lg opacity-80">Built for performance. Designed for those who need to get the job done.</p>
        <ul class="text-sm opacity-70 space-y-1 list-disc list-inside">
            <li>6.5″ adaptive OLED</li>
            <li>Smart battery optimization</li>
            <li>Precision aluminum frame</li>
        </ul>
    </div>

    <div class="md:w-1/2 w-full px-6 py-12 md:py-0 flex items-center justify-center relative">

        <div class="absolute inset-0 flex items-center justify-center pointer-events-none">
            <div class="w-[200%] h-[150%] bg-[radial-gradient(circle,var(--color-accent-light),transparent_70%)] blur-3xl opacity-70"></div>
        </div>

        <img
            src={phone1}
            alt="By Freepik."
            class="relative max-h-[80vh] w-auto object-contain drop-shadow-2xl"
        />
    </div>
</section>

<!-- Product 3 -->
<section class="min-h-screen py-52 flex flex-col md:flex-row items-center bg-[var(--color-bg)]">
    <div class="md:w-1/2 w-full px-6 py-12 md:py-0 flex items-center justify-center relative">
        <div class="absolute inset-0 flex items-center justify-center pointer-events-none">
            <div class="w-[200%] h-[150%] bg-[radial-gradient(circle,var(--color-accent-light),transparent_70%)] blur-3xl opacity-70"></div>
        </div>

        <img
            src={phone2}
            alt="By Rawpixel on Freepik."
            class="relative max-h-[80vh] w-auto object-contain drop-shadow-2xl"
        />
    </div>

    <div class="md:w-1/2 w-full px-6 py-12 md:py-0 flex flex-col justify-center space-y-6">
        <p class="text-xs tracking-[0.2em] uppercase opacity-60">Curated Tech</p>
        <h3 class="text-3xl font-semibold">Concierge Pro</h3>
        <p class="text-lg opacity-80">Compact and fast. Designed for people who prefer precision.</p>
        <ul class="text-sm opacity-70 space-y-1 list-disc list-inside">
            <li>Fast wireless charging</li>
            <li>One-hand comfort</li>
            <li>Stylus-ready surface</li>
        </ul>
    </div>
</section>

<!-- Offer -->
<section class="w-full min-h-[25vh] p-16 flex flex-col items-center justify-center bg-[var(--color-surface)] text-center space-y-6">
    <h2 class="text-4xl md:text-5xl font-bold tracking-tight text-[var(--color-bg)]">
        Limited-Time Offer
    </h2>

    <p class="text-lg md:text-xl opacity-80 max-w-2xl">
        Pre-order any Valet Series device today and receive exclusive access to our premium accessory pack.
    </p>

    <a href="#shop" class="inline-block btn-primary px-8 py-3 rounded-[var(--radius-md)] 
            font-semibold transition-all duration-200 ease-out hover:bg-[var(--color-primary-hover)] 
            hover:-translate-y-0.5 hover:shadow-md active:translate-y-0 active:shadow-sm">
        Pre-Order Now
    </a>
    <div class="w-24 h-1 bg-[var(--color-accent)] rounded-full mt-4"></div>
</section>

<!-- Product Lineup -->
<section class="w-full min-h-screen p-16 flex flex-col items-center bg-[var(--color-bg)]">
    <h2 class="text-3xl md:text-4xl font-semibold mb-10 text-[var(--color-surface)]">See Our Other Products</h2>

    <div class="w-full max-w-6xl mx-auto px-6 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Product Card 1 -->
        <div class="bg-[var(--color-surface)] rounded-2xl shadow-xl overflow-hidden flex flex-col items-center text-center p-6 hover:scale-105 transition-transform duration-300">
            <img src={phone1} alt="Steward Mini" class="w-full h-64 object-contain mb-4 drop-shadow-lg"/>
            <h3 class="text-xl font-semibold mb-2">Steward Mini</h3>
            <p class="text-sm opacity-70 mb-3">Compact and fast.</p>
            <ul class="text-xs opacity-60 space-y-1 list-disc list-inside">
                <li>One-hand comfort</li>
                <li>Fast wireless charging</li>
                <li>Ceramic shield body</li>
            </ul>
        </div>

        <!-- Product Card 2 -->
        <div class="bg-[var(--color-surface)] rounded-2xl shadow-xl overflow-hidden flex flex-col items-center text-center p-6 hover:scale-105 transition-transform duration-300">
            <img src={phone2} alt="Sommelier Pro" class="w-full h-64 object-contain mb-4 drop-shadow-lg"/>
            <h3 class="text-xl font-semibold mb-2">Sommelier Pro</h3>
            <p class="text-sm opacity-70 mb-3">Professional-grade photography.</p>
            <ul class="text-xs opacity-60 space-y-1 list-disc list-inside">
                <li>Triple-lens camera</li>
                <li>Advanced low-light capture</li>
                <li>Pro-grade color calibration</li>
            </ul>
        </div>

        <!-- Product Card 3 -->
        <div class="bg-[var(--color-surface)] rounded-2xl shadow-xl overflow-hidden flex flex-col items-center text-center p-6 hover:scale-105 transition-transform duration-300">
            <img src={phone2} alt="Aurora X1" class="w-full h-64 object-contain mb-4 drop-shadow-lg"/>
            <h3 class="text-xl font-semibold mb-2">Valet 3</h3>
            <p class="text-sm opacity-70 mb-3">Streamlined and minimalist.</p>
            <ul class="text-xs opacity-60 space-y-1 list-disc list-inside">
                <li>6.7″ OLED display</li>
                <li>Smart battery optimization</li>
                <li>Precision aluminum frame</li>
            </ul>
        </div>

        <!-- Product Card 4 -->
        <div class="bg-[var(--color-surface)] rounded-2xl shadow-xl overflow-hidden flex flex-col items-center text-center p-6 hover:scale-105 transition-transform duration-300">
            <img src={phone1} alt="Concierge Fold" class="w-full h-64 object-contain mb-4 drop-shadow-lg"/>
            <h3 class="text-xl font-semibold mb-2">Concierge Fold</h3>
            <p class="text-sm opacity-70 mb-3">Flexible and elegant.</p>
            <ul class="text-xs opacity-60 space-y-1 list-disc list-inside">
                <li>Seamless foldable glass</li>
                <li>Split-screen multitasking</li>
                <li>Stylus-ready surface</li>
            </ul>
        </div>
    </div>
</section>