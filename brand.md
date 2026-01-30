---
layout: page
title: Brand Protocols V8.0
description: Design system documentation for the AI Search Lab (V8 Identity).
---

<div class="not-prose space-y-24 bg-slate-50 p-12 pixel-corners border border-slate-900">

    <!-- Header -->
    <header class="border-b-2 border-slate-900 pb-12">
        <span class="font-mono text-xs uppercase tracking-widest bg-slate-900 text-brand-neon px-2 py-1 mb-4 inline-block pixel-corners">
            System_Manifest
        </span>
        <h1 class="font-sans text-6xl font-bold tracking-tighter text-slate-900 mb-6">
            PROTOCOL_V8
        </h1>
        <p class="font-mono text-slate-500 text-lg max-w-2xl">
            A brutalist, high-signal design system for the post-search era. Combining terminal aesthetics with pixel art and neon accents.
        </p>
    </header>

    <!-- Color System -->
    <section>
        <div class="flex items-center gap-4 mb-8 border-b border-slate-200 pb-4">
            <div class="w-3 h-3 bg-slate-900 pixel-corners"></div>
            <h2 class="font-mono text-xl font-bold uppercase tracking-widest text-slate-900">01_Color_Spectrum</h2>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
            <!-- Brand Neon -->
            <div class="group">
                <div class="h-32 bg-brand-neon border border-slate-900 shadow-[4px_4px_0_0_#0f172a] mb-4 pixel-corners"></div>
                <div>
                    <div class="font-sans font-bold text-xl text-slate-900">Signal Green</div>
                    <div class="font-mono text-xs text-slate-500 mt-1">#72e882</div>
                    <div class="font-mono text-xs text-slate-400 mt-2 uppercase tracking-wide">Usage: Primary Action, Highlights</div>
                </div>
            </div>

            <!-- Slate 900 -->
            <div class="group">
                <div class="h-32 bg-slate-900 border border-slate-900 shadow-[4px_4px_0_0_#cbd5e1] mb-4 pixel-corners"></div>
                <div>
                    <div class="font-sans font-bold text-xl text-slate-900">Void Black</div>
                    <div class="font-mono text-xs text-slate-500 mt-1">#0f172a / Slate-900</div>
                    <div class="font-mono text-xs text-slate-400 mt-2 uppercase tracking-wide">Usage: Text, Backgrounds, Borders</div>
                </div>
            </div>

            <!-- Slate 50 (Paper) -->
            <div class="group">
                <div class="h-32 bg-slate-50 border border-slate-200 shadow-[4px_4px_0_0_#cbd5e1] mb-4 pixel-corners"></div>
                <div>
                    <div class="font-sans font-bold text-xl text-slate-900">Paper White</div>
                    <div class="font-mono text-xs text-slate-500 mt-1">#f8fafc / Slate-50</div>
                    <div class="font-mono text-xs text-slate-400 mt-2 uppercase tracking-wide">Usage: Cards, Backgrounds</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Typography -->
    <section>
        <div class="flex items-center gap-4 mb-8 border-b border-slate-200 pb-4">
            <div class="w-3 h-3 bg-slate-900 pixel-corners"></div>
            <h2 class="font-mono text-xl font-bold uppercase tracking-widest text-slate-900">02_Typography</h2>
        </div>

        <div class="space-y-16">
            <!-- Space Grotesk -->
            <div class="border-l-4 border-brand-neon pl-8">
                <div class="font-mono text-xs text-slate-400 mb-2 uppercase">Headlines / Display</div>
                <div class="font-sans text-6xl font-bold text-slate-900 mb-4 tracking-tighter">Space Grotesk</div>
                <div class="font-sans text-2xl text-slate-600 font-medium">
                    ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>
                    abcdefghijklmnopqrstuvwxyz<br>
                    0123456789
                </div>
            </div>

            <!-- JetBrains Mono -->
            <div class="border-l-4 border-slate-900 pl-8">
                <div class="font-mono text-xs text-slate-400 mb-2 uppercase">Code / UI / Accents</div>
                <div class="font-mono text-4xl font-bold text-slate-900 mb-4">JetBrains Mono</div>
                <div class="font-mono text-lg text-slate-600">
                    function init_system() {<br>
                    &nbsp;&nbsp;return "READY";<br>
                    }
                </div>
            </div>

             <!-- Inter -->
             <div class="border-l-4 border-slate-300 pl-8">
                <div class="font-mono text-xs text-slate-400 mb-2 uppercase">Body Text</div>
                <div class="font-body text-4xl font-bold text-slate-900 mb-4">Inter</div>
                <div class="font-body text-lg text-slate-600 max-w-xl leading-relaxed">
                    The quick brown fox jumps over the lazy dog. Used for long-form reading, articles, and density. Optimized for legibility.
                </div>
            </div>
        </div>
    </section>

    <!-- UI Components -->
    <section>
        <div class="flex items-center gap-4 mb-8 border-b border-slate-200 pb-4">
            <div class="w-3 h-3 bg-slate-900 pixel-corners"></div>
            <h2 class="font-mono text-xl font-bold uppercase tracking-widest text-slate-900">03_UI_Primitives</h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
            
            <!-- Buttons -->
            <div class="space-y-8">
                <h3 class="font-sans font-bold text-lg text-slate-900">Action Modules</h3>
                
                <!-- Primary -->
                <button class="w-full bg-slate-900 text-white font-mono text-sm font-bold uppercase tracking-widest py-4 px-6 border border-slate-900 shadow-[4px_4px_0_0_#72e882] hover:translate-y-px hover:shadow-[2px_2px_0_0_#72e882] transition-all pixel-corners text-center">
                    INITIALIZE_PROTOCOL
                </button>

                <!-- Secondary -->
                <button class="w-full bg-white text-slate-900 font-mono text-sm font-bold uppercase tracking-widest py-4 px-6 border border-slate-900 hover:bg-slate-50 transition-all pixel-corners text-center">
                    READ_DOCUMENTATION
                </button>

                 <!-- Tag -->
                 <span class="inline-block bg-slate-100 text-slate-600 font-mono text-xs font-bold uppercase tracking-widest px-3 py-1 border border-slate-300 pixel-corners">
                    v8.0_beta
                </span>
            </div>

            <!-- Cards -->
            <div class="space-y-8">
                <h3 class="font-sans font-bold text-lg text-slate-900">Container Modules</h3>

                <div class="bg-white p-8 border border-slate-200 relative group hover:border-slate-900 transition-colors pixel-corners">
                    <div class="absolute -top-1 -right-1 w-2 h-2 bg-brand-neon"></div>
                    <div class="absolute top-4 right-4 font-mono text-xs text-slate-300 group-hover:text-brand-neon transition-colors">01</div>
                    <h4 class="font-sans font-bold text-xl mb-2">Content Module</h4>
                    <p class="font-mono text-xs text-slate-500">
                        Default container with pixel corners and hover state interactions.
                    </p>
                </div>
            </div>

        </div>
    </section>

</div>
