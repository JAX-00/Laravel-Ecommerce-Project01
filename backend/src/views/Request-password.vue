<template>
    <GuestLayout title="Request New Password">
        <form class="space-y-6" action="#" method="POST">
            <div>
            <label for="email" class="block text-sm/6 font-medium text-gray-100">Email address</label>
            <div class="mt-2">
                <input type="email" name="email" id="email" autocomplete="email" required="" class="block w-full rounded-md bg-white/5 px-3 py-1.5 text-base text-white outline-1 -outline-offset-1 outline-white/10 placeholder:text-gray-500 focus:outline-2 focus:-outline-offset-2 focus:outline-indigo-500 sm:text-sm/6" />
            </div>
            <div class="text-sm">
                <a href="#" class="font-semibold text-indigo-400 hover:text-indigo-300">Remember your password?</a>
                </div>
            </div>


            <div>
            <button type="submit" class="flex w-full justify-center rounded-md bg-indigo-500 px-3 py-1.5 text-sm/6 font-semibold text-white hover:bg-indigo-400 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-500">Submit</button>
            </div>
        </form>
    </GuestLayout>
</template>


<script>
import GuestLayout from '../components/GuestLayout.vue';

export default {
    name: "Request-password",
    components: {
        GuestLayout,
    }
}
</script>

<style scoped>

</style>
