<script lang="ts">
	import Button from '$lib/components/ui/button/button.svelte';
	import Logo from '../lib/assets/Logo.svg';
	import Home from '../lib/assets/home-01.svg';
	import Explore from '../lib/assets/Explore.svg';
	import Book from '../lib/assets/Book.svg';
	import plus from '../lib/assets/plus-square.svg';
	import * as Avatar from '$lib/components/ui/avatar';
	import Person from '../lib/assets/Person.png';
	import { ChevronDown } from 'lucide-svelte';
</script>

<nav
	class="flex justify-between font-inter py-5 items-center border-b border-dotted xl:w-[1240px] w-full px-4"
>
	<div>
		<img src={Logo} alt="logo" />
	</div>
	<div class="flex gap-5">
		<div class="flex gap-2">
			<Button class="bg-white text-gray-600 hover:bg-slate-100">
				<img src={Home} alt="home" class="text-gray-600 mr-2" />
				Home
			</Button>
			<Button class="bg-white text-gray-600 hover:bg-slate-100">
				<img src={Explore} alt="explore" class="text-gray-600 mr-2" />
				Explore
			</Button>
			<Button class="bg-white text-gray-600 hover:bg-slate-100">
				<img src={Book} alt="home" class="text-gray-600 mr-2" />
				Learn
			</Button>
		</div>
		<div
			class="text-gray-600 text-[14px] font-normal flex items-center border-[#4D4D4D] px-[16px] rounded-[4px] my-shadow border-[0.5px]"
		>
			<img src={plus} alt="home" class="text-gray-600 mr-2" />
			Post
		</div>
		<div class="ml-10 flex items-center font-inter font-medium">
			<Avatar.Root class="border-[0.5px] border-[#4d4d4d] mr-2">
				<Avatar.Image src={Person} alt="person" />
				<Avatar.Fallback>CN</Avatar.Fallback>
			</Avatar.Root>
			Krishna Kiran
			<div class="flex items-center ml-2">
				<ChevronDown class="h-[16px] w-[16px]" />
			</div>
		</div>
	</div>
</nav>

<style>
	.my-shadow {
		box-shadow: 0px 4px 0px 0px rgba(77, 77, 77, 1);
	}
</style>
