---
layout: page
title: Brand Protocols
description: Design system documentation for the AI Search Lab.
---

<div class="not-prose space-y-20">

    <!-- Color System -->
    <section>
        <h2 class="text-2xl font-bold text-white mb-8 border-b border-slate-800 pb-2">01 // Color_System</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            <!-- Neon Green -->
            <div class="space-y-3">
                <div class="h-32 bg-neon-green rounded-sm shadow-[0_0_20px_rgba(204,255,0,0.2)]"></div>
                <div>
                    <div class="text-neon-green font-bold text-lg">Neon Green</div>
                    <div class="text-slate-500 font-mono text-xs">#CCFF00</div>
                    <div class="text-slate-600 text-sm mt-1">Primary Action, Success, Growth</div>
                </div>
            </div>
            <!-- Neon Purple -->
            <div class="space-y-3">
                <div class="h-32 bg-neon-purple rounded-sm shadow-[0_0_20px_rgba(217,70,239,0.2)]"></div>
                <div>
                    <div class="text-neon-purple font-bold text-lg">Neon Purple</div>
                    <div class="text-slate-500 font-mono text-xs">#D946EF</div>
                    <div class="text-slate-600 text-sm mt-1">Intelligence, Data, Premium</div>
                </div>
            </div>
            <!-- Neon Cyan -->
            <div class="space-y-3">
                <div class="h-32 bg-neon-cyan rounded-sm shadow-[0_0_20px_rgba(6,182,212,0.2)]"></div>
                <div>
                    <div class="text-neon-cyan font-bold text-lg">Neon Cyan</div>
                    <div class="text-slate-500 font-mono text-xs">#06B6D4</div>
                    <div class="text-slate-600 text-sm mt-1">Community, Network, Flow</div>
                </div>
            </div>
            <!-- Slate 950 -->
            <div class="space-y-3">
                <div class="h-32 bg-slate-950 border border-slate-800 rounded-sm"></div>
                <div>
                    <div class="text-white font-bold text-lg">Void Black</div>
                    <div class="text-slate-500 font-mono text-xs">#020617</div>
                    <div class="text-slate-600 text-sm mt-1">Background, Depth</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Typography -->
    <section>
        <h2 class="text-2xl font-bold text-white mb-8 border-b border-slate-800 pb-2">02 // Typography</h2>
        <div class="space-y-12">
            <div>
                <div class="text-slate-500 text-xs font-mono mb-2">Display / Headings</div>
                <div class="text-5xl font-bold text-white tracking-tighter">Space Grotesk</div>
                <div class="text-2xl text-slate-400 mt-2 font-light">The quick brown fox jumps over the lazy dog.</div>
            </div>
            <div>
                <div class="text-slate-500 text-xs font-mono mb-2">Monospace / Code / UI Elements</div>
                <div class="text-3xl font-mono text-neon-green">JetBrains Mono</div>
                <div class="text-lg font-mono text-slate-400 mt-2">function optimize_search() { return "AI"; }</div>
            </div>
        </div>
    </section>

    <!-- Components -->
    <section>
        <h2 class="text-2xl font-bold text-white mb-8 border-b border-slate-800 pb-2">03 // UI_Components</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
            <!-- Buttons -->
            <div class="space-y-6">
                <h3 class="text-white font-bold">Buttons</h3>
                <div class="flex flex-col items-start gap-4">
                    <!-- Primary -->
                    <button class="px-8 py-4 bg-neon-green text-black font-bold text-lg rounded-sm hover:shadow-[0_0_15px_rgba(204,255,0,0.4)] transition-all">
                        PRIMARY_ACTION
                    </button>
                    <!-- Secondary -->
                    <button class="px-8 py-4 bg-transparent text-white font-bold text-lg rounded-sm border border-slate-700 hover:border-white transition-all hover:bg-white/5">
                        SECONDARY_ACTION
                    </button>
                    <!-- Tag -->
                    <span class="px-3 py-1 text-xs font-bold text-neon-green border border-neon-green/30 hover:bg-neon-green hover:text-black transition-all uppercase tracking-widest rounded-sm cursor-default">
                        [ SYSTEM_TAG ]
                    </span>
                </div>
            </div>

            <!-- Cards -->
            <div class="space-y-6">
                <h3 class="text-white font-bold">Content Cards</h3>
                <div class="bg-slate-900/50 p-8 border border-slate-800 hover:border-neon-purple/50 transition-all duration-300 group relative overflow-hidden">
                    <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-neon-purple to-transparent opacity-0 group-hover:opacity-100 transition-opacity"></div>
                    <div class="font-mono text-xs text-neon-purple mb-4 flex items-center gap-2">[01] :: MODULE</div>
                    <h3 class="text-xl font-bold text-white mb-2">Interactive Card</h3>
                    <p class="text-slate-400 text-sm">Hover to reveal the top border gradient and accent color shift. Used for features and pricing.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Logo Construction -->
    <section>
        <h2 class="text-2xl font-bold text-white mb-8 border-b border-slate-800 pb-2">04 // Identity_Construct</h2>
        <div class="p-12 bg-slate-950 border border-slate-800 flex flex-col items-center justify-center gap-8">
            <!-- Logo Full -->
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-neon-green text-black flex items-center justify-center font-bold text-xl rounded-sm">_</div>
                <span class="text-2xl font-bold tracking-tight text-white">AI_SEARCH_LEADERS</span>
            </div>
            
            <!-- Logo Mark -->
            <div class="w-16 h-16 bg-neon-green text-black flex items-center justify-center font-bold text-4xl rounded-sm">_</div>
            
            <div class="text-slate-500 text-center max-w-md text-sm font-mono">
                The logo represents the "cursor" (_) — the point of interaction between human and machine. <br>Always typeset in bold, uppercase, with underscore separators.
            </div>
        </div>
    </section>

</div>
