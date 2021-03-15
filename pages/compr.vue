<template>
    <div class="bg-gradient-to-r from-gray-100 to-gray-200 h-screen">

        <div class="container mx-auto p-10 lg:p-20">
            <h1
                class="text-4xl tracking-wider uppercase font-bold mt-20"
                >Here are the 
                {{  }} most 
                {{  }} players to 
                {{  }}.
            </h1>

            <!-- Dynamic Table -->
            <Table />
        </div>

    </div>
</template>

<script>
export default {

    data () {

    },

}
</script>