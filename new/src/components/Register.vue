<template>
    <div class="flex h-screen">
        <div class="w-4/6 bg-blue-600 text-white"></div>
        <div class="w-5/6 bg-white">
            <div class="my-28 px-11 md:28 lg:px-64 ">
                <div class="flex items-center justify-center">
                    <div>
                        <img :src="companyLogo" class="w-10 rounded-full" alt="">
                    </div>
                    <div class="mx-2 font-bold text-gray-800">
                        {{ companyName }}
                    </div>
                </div>
                <div class="font-bold text-black text-3xl text-center">
                    Hi, let's get familiar.
                </div>
                <div class="text-black text-center">
                    Create your free account, No credit card required.
                </div>
                <button class="text-black px-2 py-2 border border-gray rounded hover:bg-gray-200 w-full">Continue with Google</button>
                <div>
                    <label for="fullname">Full name</label><br>
                    <input type="text" class="w-full rounded bg-gray-100 border border-gray-200">
                </div>
                <div>
                    <label for="email">Email address</label><br>
                    <input type="text" class="w-full rounded bg-gray-100 border border-gray-200">
                </div>
                <div>
                    <label for="phone">Phone Number</label><br>
                    <input type="text" class="w-full rounded bg-gray-100 border border-gray-200">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'RegisterPage',
    data() {
        return {
            companyLogo: './assets/logo.jpeg',
            companyName: 'Kavisoftek',
        }
    }
}
</script>

<style lang="scss" scoped></style>