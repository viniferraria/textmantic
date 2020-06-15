<template>
    <div>
        <div>
            <textarea :v-model="text"/>
        </div>
        <div>
            <textarea/>
        </div>
        <button>Send</button>
    </div>
</template>

<script>
export default {
	name: "TextField",
	data() {
		return {
			text: "",
		};
	},
};
</script>

<style>

</style>