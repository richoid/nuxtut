    <template>
        <div clas="layout-container">
            <main class="content">
                <slot />
            </main>
        </div>
    </template>

<style>
    .layout-container {
        height: calc(100vh - 4rem);
        background-color: --ui-bg;
    }
    .main.content {
        height: "100%";
        margin-top: "4rem";
    }
</style>