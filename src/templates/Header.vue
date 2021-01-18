<template>
    <div class="flex flex-row justify-between py-6 border-b-1 border-gray-300">
        <div class="flex-initial">

        </div>
        <div class="flex-initial">
            <div class="flex flex-row space-x-4">
                <div class="flex-initial">
                    <Button
                        :class="[
                            'px-6',
                            'py-2',
                            'text-white',
                            'text-base',
                            'font-semibold',
                            'rounded',
                            'bg-blue-400',
                            'hover:bg-blue-500',
                            'focus:bg-blue-600',
                        ]"
                        tag="button"
                        href="#">
                        Cart
                    </Button>
                </div>
                <div class="flex-initial">
                    <button
                        :class="[
                            'px-6',
                            'py-2',
                            'ring-1',
                            'ring-gray-300',
                            'rounded',
                            'text-base',
                            'font-semibold',
                            'text-gray-600',
                        ]"
                        tag="button"
                        href="#">
                        Account
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>
<style></style>
<script>
import Button from "@/components/Button.vue";

export default {
    components: { Button }
}
</script>
