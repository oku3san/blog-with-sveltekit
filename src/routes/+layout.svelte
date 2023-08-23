<script>
    import "../app.css";
</script>

<div class="bg-white lg:pb-12">
    <div class="mx-auto max-w-screen-2xl px-4 md:px-8">
        <header class="flex items-center justify-between py-4 md:py-8">
            <!-- logo - start -->
            <a href="/" class="inline-flex items-center gap-2.5 text-2xl font-bold text-black md:text-3xl" aria-label="logo">
                <svg width="95" height="94" viewBox="0 0 95 94" class="h-auto w-6 text-indigo-500" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                    <path d="M96 0V47L48 94H0V47L48 0H96Z" />
                </svg>
                LIGHTS, CAMERA, ACTION!
            </a>
            <!-- logo - end -->
        </header>
    </div>
</div>

<slot />

<div class="bg-gray-900 pt-4 sm:pt-10 lg:pt-12">
    <footer class="mx-auto max-w-screen-2xl px-4 md:px-8">
    </footer>
</div>
