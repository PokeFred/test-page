<script lang="ts">
    import CodeLine from "./CodeLine.svelte";

</script>

<div class="mx-4 my-2 border border-gray-600 rounded-xl overflow-hidden">
    <div class="bg-gray-700 px-4 py-2">package.json</div>
    <div>
        <CodeLine tabs=1>&#123;</CodeLine>
        <CodeLine>"name": "demo-project",</CodeLine>
        <CodeLine>"version": "0.0.1",</CodeLine>
        <CodeLine>"private": "true",</CodeLine>
        <CodeLine>"scripts": &#123;</CodeLine>
        <CodeLine status="added">"start": "node server.js",</CodeLine>
        <CodeLine>"dev": "vite dev",</CodeLine>
        <CodeLine>"build": "vite build",</CodeLine>
        <CodeLine status="deleted">"preview": "vite preview",</CodeLine>
        <CodeLine status="deleted">"check": "svelte-kit sync && svelte-check --tsconfig ./tsconfig.json",</CodeLine>
        <CodeLine status="deleted">"check:watch": "svelte-kit sync && svelte-check --tsconfig ./tsconfig.json --watch"</CodeLine>
        <CodeLine>&#125;,</CodeLine>
        <CodeLine status="added">"dependencies": &#123;</CodeLine>
        <CodeLine status="added">"express": "^4.18.2"</CodeLine>
        <CodeLine status="added">&#125;,</CodeLine>
        <CodeLine>"devDependencies": &#123;</CodeLine>
        <CodeLine status="deleted">"@sveltejs/adapter-auto": "^2.0.0",</CodeLine>
        <CodeLine status="added">"@sveltejs/adapter-node": "^1.3.1"</CodeLine>
        <CodeLine>"@sveltejs/kit": "^1.27.4",</CodeLine>
        <CodeLine>"svelte": "^4.2.7",</CodeLine>
        <CodeLine>"svelte-check": "^3.6.0",</CodeLine>
        <CodeLine>"tslib": "^2.4.1",</CodeLine>
        <CodeLine>"typescript": "^5.0.0",</CodeLine>
        <CodeLine>"vite": "^4.4.2"</CodeLine>
        <CodeLine>&#125;</CodeLine>
        <CodeLine>&#125;</CodeLine>
    </div>
</div>
