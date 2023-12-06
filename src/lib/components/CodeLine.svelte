<script lang="ts">
    type CodeLineStatus = "added" | "deleted" | "unmodified"

    export let tabs: number = 0
    export let status: CodeLineStatus = "unmodified"
</script>

<div class="w-full h-auto flex justify-center items-center">
    <div class="w-6 h-full flex justify-center items-start shrink-0"></div>
    <div class="w-8 h-full flex justify-center items-start shrink-0">{(status === "added") ? "+" : ""}{(status === "deleted") ? "-" : ""}</div>
    <div class="w-full h-full">
        <slot />
    </div>
</div>
