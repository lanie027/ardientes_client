<template>
    <NuxtLayout name="default">

        <div class="resources">
            <h3>Uploaded files</h3>
        </div>
        <div>
            <h2 class="my-2 font-medium">Index</h2>
            <form>
                <button class="bg-gray-300 hover:bg-gray-400 text-black font-bold py-2 px-4 rounded inline-flex items-center">
                    <img class="h-5 w-5" src="../images/remove.png" alt="">
                    <span class="ml-2">Remove</span>
                </button>
                <button class="ml-5 bg-gray-300 hover:bg-gray-400 text-black font-bold py-2 px-4 rounded inline-flex items-center">
                    <img class="h-5 w-5" src="../images/export.png" alt="">
                    <span class="ml-2">Export</span>
                </button>
            </form>
        </div>
        
    </NuxtLayout>
</template>

<script>
</script>

<style scoped>
</style>