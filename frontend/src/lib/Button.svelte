<script lang="ts">
    let { mode = "primary", children } = $props<{
        mode?: "primary" | "secondary";
        children?: any;
    }>();
</script>

<button
    class={`btn btn-sm border-2 shadow-none
        ${mode === "primary"
            ? "border-[#003F66] bg-[#003F66] text-white"
            : mode === "secondary"
                ? "border-[#003F66] text-[#003F66]"
                : ""}
    `}
>
    {@render children?.()}
</button>
