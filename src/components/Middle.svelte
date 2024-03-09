<script lang="ts">
	import * as Avatar from '$lib/components/ui/avatar';
	import { ArrowUpRightFromSquare, MoreHorizontal } from 'lucide-svelte';
	import Person from '../lib/assets/Person.png';
	import social from '../lib/assets/Social Icons.svg';
</script>

<div class="flex xl:w-[1000px] w-[80%] mt-16">
	<div class="flex flex-col items-center mr-8">
		<Avatar.Root class="border-[0.5px] border-[#eaeff5] mr-2 h-[120px] w-[120px]">
			<Avatar.Image src={Person} alt="person" />
			<Avatar.Fallback>CN</Avatar.Fallback>
		</Avatar.Root>
		<h1 class="font-inter font-bold text-[24px] text-[#4b5c6d]">Krishna</h1>
		<h1 class="font-inter font-bold text-[24px] text-[#4b5c6d]">Kiran</h1>
	</div>
	<div class="flex justify-between font-inter mt-8">
		<div class="flex flex-col">
			<div class="flex justify-between">
				<p class="text-[14px] leading-[24px] w-[60%]">
					Co-Founder and CEO at Duggup - Social network for people in tech. Ex-Amazon Head of
					Engineering. I write hot-takes on building a business, shipping delightful products and
					accelerating product and career growth.
				</p>
				<div class="flex flex-col text-right items-end font-inter gap-2">
					<img src={social} alt="social" class="h-[36px] w-[36px]" />
					<h1 class="font-bold text-[17px]">Duggup</h1>
					<h3 class="text-[#7a9299] text-[12px]">Co-Founder and CEO</h3>
				</div>
			</div>
			<div class="mt-7 flex justify-between">
				<div
					class="text-gray-600 text-[14px] font-normal flex items-center border-[#4D4D4D] px-6 py-1 rounded-[4px] my-shadow border-[0.5px] w-min"
				>
					Followed
				</div>
				<div class="flex items-center">
					<div class="flex items-center mr-2 cursor-pointer">
						<h3 class="font-inter text-[#4d4d4d] mr-1">My website</h3>
						<ArrowUpRightFromSquare class="text-[#4d4d4d] h-[16px] w-[16px] " />
					</div>
					<MoreHorizontal class="text-[#a5b9d3]" />
				</div>
			</div>
		</div>
	</div>
</div>

<style>
	.my-shadow {
		box-shadow: 0px 4px 0px 0px rgba(77, 77, 77, 1);
	}
</style>
