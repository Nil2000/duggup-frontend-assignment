<script lang="ts">
	import Card from './Card.svelte';
	import BigCard from './BigCard.svelte';
	import { ChevronUp } from 'svelte-radix';
</script>

<div class="flex flex-col xl:w-[1240px] w-[100%] mt-10 xl:ml-[-140px]">
	<div class="flex xl:w-[100%] w-[80%]">
		<div class="xl:w-[20%] w-[20%] flex items-center justify-end pr-10">
			<h1 class="text-sm text-[#7a9299] font-inter">Dec 2023</h1>
		</div>
		<div class="flex items-center">
			<div class="border-[2.5px] border-dotted border-r-0 border-[#778fb1] h-[100%]" />
			<div
				class="h-[15px] w-[15px] bg-[#0066ff] ml-[-8px] rounded-full flex items-center justify-center"
			>
				<div class="h-[10px] w-[10px] bg-white rounded-full"></div>
			</div>
		</div>
		<div class="flex items-center w-[79%]">
			<Card
				src="https://s3-alpha-sig.figma.com/img/ccdc/bd9b/5b2f7dca180260dd9a121e21e4ccb158?Expires=1710720000&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=dOWBi6OHLSab0NnAaNUUXQkXB5~7u0al1jfpXxNgA0tlnAiMVIOqESi-PMhBkg8XTcM3Avu-~kmWy9R46SPhcRdaDFIUnCnnTw-Oi~LymMYl4APflb5NEEJnEIch5ZUw2mtvpnsXPg0AJtbR3wGRzECIOzQVAluoDWOxQDzqiDZPZBgbXQ0iWXyR9ecwlUY4LHEkdZ-ZeDkU3bU39Pw87Vt2Q7QsE9wY2baFiD7KLkYWCuoNm2DF6KoN5KkW6eKcM8C102~UPvSom0~4dxklFMeV6S4ZI3glmKDZVMJXXAcYsGQRYv-z8QtklRtpuE7ZuNM4CeF85M4OW5L8Ob848A__"
				text="No amount of technology can convert a bad story into a good story."
			/>
			<Card
				src="https://s3-alpha-sig.figma.com/img/25ac/166c/37888417ccf24a1991743ef364aea246?Expires=1710720000&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=RA144wBULxFqs3giTkSpv~K-Ks6LwHcjUK5-FvbiNwtV-jHgMdfBBDDeiqT0I-MqARSKmHtjVNYI0SsWQ6X~K586jbuM0UpnxJUxtYZRph6lw6DyuPg0OBa83a6gwA5lV54r~CQjUZIBPb1-PZoK4HTJlF5uo2gIFS1DpexjsC~nawjwHDM8V-ybDPDDY14Px2Rdjh72JI1CuXt~uzPH20OQacifogxJng97IXMLbxRrcbF2vdn7vf9pCkFPunH5RTC7fstELVNbz1iS1BugX1XXwL4vF6uDVP-X1vNA~ZT69xQH~qufUMg8u2nM7NFRVy~9tsILziSyhi-HLFJpNA__"
				text="Most people don't have original ideas. Here is how Sam Altman pushes himself to have unpopular ideas."
			/>
		</div>
	</div>
	<div class="flex xl:w-[100%] w-[80%]">
		<div class="w-[20%] flex flex-col items-end px-10">
			<img
				src="https://s3-alpha-sig.figma.com/img/f1bc/3eca/3db6ec41cda31968010a7f56f3c3658a?Expires=1710720000&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=FT4oZFOFyVS5aS~O~42xm38C0rnk~5fKs4MDSsflPi3Zxlf~4iKBbwUOtYMGPRLGF5jLph723jRvd5p1sJ2nZ7UAfNt2cRfal~5Vot0EDZFR5vHxpzDPqBAk5I3nCXqorDNl1-nvLQw8J~bThtOy4km1ADWoGFr3ufCrHP7NakEPdDAFfh0f6b7K8sjaK3-G2BB0yTFOvFYCsCHvyXOBOfOh~fqEZQxyObR2trfFgLR2cabLauALtH6e6srK393GL9Cf7UHQ17IbXQdP18iQfif1a7vrosu4Xmf4bVGi-27Ic8YghSJWXJ71nXX54CtGvhPSTY-di5B8zIWBrxvEmw__"
				alt="logo"
				class="h-[48px] w-[48px] rounded-full"
			/>
			<h1 class="font-inter font-bold mt-1">Duggup</h1>
			<p class="text-sm text-[#7a9299] font-inter text-right">San Francisco Bay Area</p>
			<p class="text-sm text-[#7a9299] font-inter">Joined</p>
			<p class="text-sm text-[#7a9299] font-inter text-right">Nov 2023</p>
		</div>
		<div class="flex flex-col mt-[-5px] xl:ml-0 ml-[-0.5px]">
			<ChevronUp class="ml-[-10px] mb-[-10px]" />
			<div class="flex items-center h-full ml-[0.5px]">
				<div class="border-[2.5px] border-dotted border-r-0 border-[#778fb1] h-[100%]" />
				<div
					class="h-[20px] w-[20px] bg-[#0066ff] ml-[-10px] rounded-full flex items-center justify-center"
				>
					<div class="h-[8px] w-[8px] bg-white rounded-full"></div>
				</div>
			</div>
		</div>
		<div class="flex p-5 w-[79%]">
			<BigCard title="Co-Founder and CEO" subtitle="Full-time · Remote" />
		</div>
	</div>
	<div class="flex xl:w-[100%] w-[80%] mt-[1px]">
		<div class="w-[20%] flex items-center justify-end px-10">
			<h1 class="text-sm text-[#7a9299] font-inter">Dec 2023</h1>
		</div>
		<div class="flex items-center">
			<div class="border-[2.5px] border-dotted border-r-0 border-[#778fb1] h-[100%]" />
			<div
				class="h-[15px] w-[15px] bg-[#0066ff] ml-[-8px] rounded-full flex items-center justify-center mt-[1px]"
			>
				<div class="h-[10px] w-[10px] bg-white rounded-full"></div>
			</div>
		</div>
		<div class="flex items-center w-[79%]">
			<Card
				src="https://s3-alpha-sig.figma.com/img/19af/a12d/f27e595212d7ad397a130cdeb8ac6c5e?Expires=1710720000&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=Htfr2nBE~tyspuVPCUnQaeCtZxiW2uOmS5dLkY8q3JtCmWtEKmq5jFts4iKnN1~FeEqDG-2HVx1QwDPnTOWrUwsZHY64xhJ6xnLV2h9RO46NhASPNYIQxbyjqqOVPhSSDLYo2zxcrSdfNS4~Cx17EBN~LQ89EQ2AFBQa9roumb7QbAwUA8JwtnPXe73hc2XhxDwIfyoAujuQvj-AOxBvGcXiUY-IARz4DjfD5A3-2SQ2bJSntkXXrdW6486UpfOkA1IeZ08Y~5G9po2lupn5E0a2b2Kh9so~j7cKrJIMeUF~vQD0OycxC2q4CXqI8G2p-zSRj2DZwgFYTeeE7DZ66w__"
				text="Startup Lesson I am reflecting. Don't build for the &quot;average person&quot;."
			/>
			<Card
				src="https://s3-alpha-sig.figma.com/img/fcaf/84e6/4461b5caa81a8f3d2afecfa15491ed1f?Expires=1710720000&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=fXQtZaSXvasp~3zTGMyiXjNZqwtA~hn-UiXIAZ~RftGmKw6ikeCBnHMQ2jnwa~-KUQpuwOTg1tn7rCX0beYea-rACbqAKvYYfg5adtbiyBs6L7DMwYcq9VwUDt60Uej~XnFgLKG2AIhlTqj76qehPJ1hyGV2UBkUr6Puu9NWXCN6ze3mxNNutcK-gsdC60w5o~jpfejvnLG3mxOvWmOLq9HYQKxUjt~9DB0u7tilC4GyfIlmbOYcRSBDLJUFJ0KrmxPT3oOAacVh6K~QH3JU9N94VQqdgysKs0g-T5IqVBYn0TAVVaE6pS4bs6zoQvNkb1KJDfQzuT2~-wOKRkiisg__"
				text="Your biggest regrets at 80 will be acts of omission."
			/>
		</div>
	</div>
	<div class="flex xl:w-[100%] w-[80%]">
		<div class="w-[20%] flex flex-col items-end px-10">
			<img
				src="https://s3-alpha-sig.figma.com/img/1b23/f02f/60bc556cd22a575549ce43ad307ec0ee?Expires=1710720000&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=XmlN~3FGwC3Eiofaiw2YRoSilaWLnmZbaz6AJ8ZSghKKIrxdpbwyo8DbmfqII9iJCL5u4Qtb4ssMaMo1owhn7V6f0vsv3yLSbO8YgEPtwxlwwVEwbeVCXMMvyfSjT-3G20lXcqSXNkS5s5pZ8waU-oYL9e7KJ3Jg1QkR1R5KzLrk~pRCSBDSLMes4gfPUB9x-0~z2O8bdCaHJfIJnZd~E7ib1MYrKIya6vLwtmCWgaVnIAItzAeQiILyqUVNL9QvDQvoNeoISDDgLyM1D6zhql6HVe6k3soojKRXQ~mby04ys4EnmtUd2wNYkhQE~nnr9U6WY1tGxt7CmM05hiP47w__"
				alt="logo"
				class="h-[48px] w-[48px] rounded-full"
			/>
			<h1 class="font-inter font-bold mt-1">BetterUp</h1>
			<p class="text-sm text-[#7a9299] font-inter text-right">San Francisco Bay Area</p>
			<p class="text-sm text-[#7a9299] font-inter">Joined</p>
			<p class="text-sm text-[#7a9299] font-inter text-right">Sep 2022</p>
		</div>
		<div class="flex flex-col mt-[-5px] xl:ml-0 ml-[-0.5px]">
			<ChevronUp class="ml-[-10px] mb-[-10px]" />
			<div class="flex items-center h-full ml-[0.5px]">
				<div class="border-[2.5px] border-dotted border-r-0 border-[#778fb1] h-[100%]" />
				<div
					class="h-[20px] w-[20px] bg-[#0066ff] ml-[-10px] rounded-full flex items-center justify-center"
				>
					<div class="h-[8px] w-[8px] bg-white rounded-full"></div>
				</div>
			</div>
		</div>
		<div class="flex p-5 w-[79%]">
			<BigCard title="VP Engineering" subtitle="Full-time" />
		</div>
	</div>
</div>
