<script lang="ts">
	export let src: string;
	export let text: string;
</script>

<div
	class="flex h-max w-[344px] flex-col rounded-md font-inter border-[0.5px] border-[#d0d5dd] m-6"
>
	<img {src} alt="my-img" class="object-cover h-[150px] rounded-t-md" />
	<div class="px-7 py-9">
		<p class="line-clamp-2">{text}</p>
	</div>
</div>
