<template>
    <div class="">
        <!-- Search Bar -->
        <div class="lg:w-2/3 lg:mx-auto relative flex flex-col m-20 bg-white shadow-lg">
            <div class="p-20 mx-auto container text-center">
                <form>
                    <div class="mb-10">
                        <label
                            class="font-bold"
                            >Search baseball player:
                        </label>
                        <input 
                            
                            id="baseballPrim"
                            type="text"
                            class=" border border-gray-300 shadow-md hover:shadow-lg rounded-lg"
                        >
                        <h2> {{  }} </h2>
                    </div>
                </form>
                <div class="">
                    <h2
                        class="mb-10"
                        >Show me the
                            <!-- Number of Comparers Selected -->
                            <div class="relative inline-flex mb-5">
                                <select 
                                    class="border border-gray-300 rounded-xl text-gray-600 h-10 pl-5 pr-10 bg-white hover:border-gray-400 focus:outline-none appearance-none"
                                    >
                                    <option>3</option>
                                    <option>4</option>
                                    <option>5</option>
                                    <option>6</option>
                                    <option>7</option>
                                    <option>8</option>
                                </select>
                            </div>
                        players, that are most
                            <!-- Similar/Unsimilar -->
                            <div class="relative inline-flex mb-5">
                                <select 
                                    class="border border-gray-300 rounded-xl text-gray-600 h-10 pl-5 pr-10 bg-white hover:border-gray-400 focus:outline-none appearance-none">
                                    <option>similar</option>
                                    <option>dissimilar</option>
                                </select>
                            </div>
                        to the current selected player.
                    </h2>
                    <div class="w-max mx-auto">
                        <NuxtLink
                            to="/compr"
                            class="hover:text-white transition duration-500 ease-in-out transform rounded-lg bg-gradient-to-r from-blue-300 hover:from-blue-400 to-blue-200 hover:to-blue-30 focus:ring-blue-200 focus:text-blue-100 text-gray-600 active:bg-gray-700 text-sm font-bold uppercase px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1"
                            type="button"
                            style="transition: all 0.15s ease 0s;"
                            >Statistics Available Here
                        </NuxtLink>
                    </div>

                    <div class="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
    data() {
        return {
            
        }
    },

    methods: {

        
    }

}
</script>