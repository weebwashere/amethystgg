<script lang="ts">
    import '../app.postcss';
    import { AppShell, AppBar } from '@skeletonlabs/skeleton';
    import { LightSwitch, CodeBlock } from '@skeletonlabs/skeleton';
</script>

<!-- App Shell -->
<AppShell>
    <svelte:fragment slot="header">
        <!-- App Bar -->
        <AppBar>
            <LightSwitch />
            <svelte:fragment slot="lead">
                <h1 class="font-abc lowercase">reminder</h1>
            </svelte:fragment>
            <svelte:fragment slot="trail">
                <a
                    class="btn btn-sm variant-ghost-surface font-abc"
                    href="https://www.guilded.gg/i/2VVZR5g2"
                    target="_blank"
                    rel="noreferrer"
                >
                    Support Server
                </a>
                
                <a
                    class="btn btn-sm variant-ghost-surface font-abc"
                    href="https://github.com/weebwashere/skele"
                    target="_blank"
                    rel="noreferrer"
                >
                    GitHub
                </a>
                <a
                    class="btn btn-sm variant-ghost-surface font-abc"
                    href="/commands"
                    target="_blank"
                    rel="noreferrer"
                >
                    About Us
                </a>
            </svelte:fragment>
        </AppBar>
    </svelte:fragment>
    <!-- Page Route Content -->
    <slot />
</AppShell>