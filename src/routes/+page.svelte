<script>
	// import Navbar from '../lib/components/nav.svelte';
	import { enhance } from '$app/forms';
	import Icon from '@iconify/svelte';
	var systemName = 'Form Builder and sharing service';
	let theme = 'light';
	const toggleTheme = () => {
		theme = theme === 'light' ? 'dark' : 'light';
	};
</script>

<svelte:head>
	<title>{systemName}</title>
	<meta name="description" content="Form Service" />
</svelte:head>

<div class="">
	<section class=" bg-[url('/bg-1.png')] bg-center bg-cover">
		<div class=" py-32 h-screen flex items-center">
			<div class="max-w-3xl px-6 ltr:sm:text-left rtl:sm:text-right">
				<p class="p-2 font-serif text-4xl font-bold text-slate-700">
					<span> Powerful and intuitive data collection tools to make an impact</span>
				</p>
				<p class="mt-6 p-2 font-sans text-xl sm:text-2xl">
					We provide the best solution on your problems with our powerful and user friendly toolset.
					Our team of experts is always ready to assist you.
				</p>
				<a href="./users">
					<button
						class="mt-6 rounded-md border px-8 py-2 text-lg font-semibold hover:shadow-md hover:shadow-purple-900 duration-150"
					>
						Start creating New Form
					</button></a
				>
			</div>
			<div class="h-full w-[350px] ml-24 items-center">
				<img src="/sticker-1.png" class=" h-96" alt="" srcset="" />
			</div>
		</div>
	</section>

	<div class=" bg-gradient-to-bl from-gray-50 to-purple-100">
		<section class="container mx-auto flex py-20 h-fit flex flex-col gap-3" id="service">
			<div
				class="mx-auto flex w-[68%] h-64 items-center justify-center text-center bg-white rounded-t-[400px]"
			>
				<div class="text-center">
					<h1
						class="text-gradient-to-b mb-4 from-violet-600 to-purple-900 font-serif text-4xl font-semibold"
					>
						Welcome to A-Forms
					</h1>
					<p class="text-gray-600">Collect and organize information with our easy-to-use forms.</p>
					<a href="./users">
						<button
							class="mt-6 rounded-md border border-black px-8 py-2 text-lg font-semibold hover:shadow-md hover:shadow-purple-200 duration-150"
						>
							Create a New Form
						</button></a
					>
				</div>
			</div>
			<div class="mx-auto flex w-[68%] items-center justify-center h-72 bg-white rounded-b-[400px]">
				<div class="text-center w-2/3">
					<h1
						class="text-gradient-to-r mb-4 from-violet-600 to-purple-900 font-serif text-4xl font-semibold"
					>
						Get insights quickly, with A-Forms
					</h1>
					<p class="text-gray-600">
						Create an online form as easily as creating a document Select from multiple question
						types, drag-and-drop to reorder questions, and customize values as easily as pasting a
						list.
					</p>
				</div>
			</div>
		</section>

		<!-- Solutions Section -->
		<section
			class="container mx-auto flex flex-col px-6 py-36 mb-20 bg-[url('/solution-img.webp')] bg-cover bg-center bg-fixed bg-opacity-40"
			id="solutions"
		>
			
				<div class="mx-auto flex w-[50%] flex-col items-center justify-center text-justify">
					<div class="px-2 text-center">
						<h2 class="mb-4 font-serif text-4xl font-bold text-slate-800">Our Solutions</h2>
						<h3 class="font-serif font-black text-xl">
							Create an online form as easily as creating a document
						</h3>
						<p class="text-gray-600 text-lg">
							Select from multiple question types, drag-and-drop to reorder questions, and customize
							values as easily as pasting a list.
						</p>
					</div>
				</div>
		</section>
		<section class="container mx-auto flex flex-col gap-2 py-20 px-10 md:flex-row" id="about">
			<div
				class="mx-auto flex flex-1 flex-col items-center justify-center rounded-bl-3xl rounded-tr-3xl bg-white p-5"
			>
				<Icon icon="flat-color-icons:collaboration" width="36" height="36" class="mb-8" />
				<h1 class="font-serif text-xl font-bold">Build forms and analyze results together</h1>
				<p class="text-justify text-gray-600">
					Add collaborators—just like with Google Docs, Sheets, and Slides—to build questions
					together in real-time. Then analyze results together without having to share multiple
					versions of the file.
				</p>
			</div>
			<div
				class="mx-auto flex flex-1 flex-col items-center justify-center rounded-bl-3xl rounded-tr-3xl bg-white p-2 text-justify"
			>
				<Icon
					icon="fluent-mdl2:responses-menu"
					width="36"
					height="36"
					style="color: #2314F5"
					class="mb-8"
				/>
				<div class="px-6 text-center">
					<h1 class="font-serif text-xl font-bold">Work with clean response data</h1>
					<p class="text-justify text-gray-600">
						Use built-in intelligence to set response validation rules. For example, ensure that
						email addresses are properly formatted or that numbers fall within a specified range.
					</p>
				</div>
			</div>
			<div
				class="mx-auto flex flex-1 flex-col items-center justify-center rounded-bl-3xl rounded-tr-3xl bg-white p-4 text-justify"
			>
				<Icon
					icon="heroicons-solid:share"
					width="36"
					height="36"
					style="color: #2314F5"
					class="mb-8"
				/>
				<h1 class="font-serif text-xl font-bold">Share forms via email, link, or website</h1>
				<p class="mb-12 text-justify text-gray-600">
					It's easy to share forms with specific people or with a broad audience by embedding forms
					on your website or sharing the links on social media.
				</p>
			</div>
		</section>
	</div>

	<!-- Contact Us Section -->
	<section
		class="container mx-auto flex h-screen flex-col rounded-md bg-[url('/contact-us.jpg')] bg-cover bg-center bg-no-repeat px-6 py-5 md:flex-row"
		id="contact"
	>
		<div
			class="w-full h-full p-5 bg-gray-400 text-white bg-clip-padding backdrop-filter backdrop-blur-md bg-opacity-10 flex"
		>
			<div class="mx-auto flex w-[50%] flex-col items-center justify-center p-4 text-justify">
				<div class="px-6 text-center font-serif">
					<h2 class="mb-4 font-serif text-4xl font-semibold">Contact Us</h2>
					<p class="">Email: contact@googleforms.com</p>
					<p class="">Phone: +1 (123) 456-7890</p>
				</div>
			</div>
			<div class="mx-auto w-[50%]">
				<div class="flex w-full flex-col">
					<div class="mx-auto flex flex-col items-center justify-center">
						<form
							method="post"
							action="?/NewUser"
							use:enhance
							class="my-auto w-[500px] space-y-6 rounded-lg p-8 pt-5 shadow-lg shadow-white"
						>
							<div>
								<label for="firstName" class="block text-sm font-medium">First Name</label>
								<input
									type="text"
									id="firstName"
									name="firstName"
									class="w-full rounded-md border border-gray-300 px-3 py-2 focus:outline-none focus:ring-1 focus:ring-indigo-500"
								/>
							</div>
							<div>
								<label for="lastName" class="block text-sm font-medium">Last Name</label>
								<input
									type="text"
									id="lastName"
									name="lastName"
									class="w-full rounded-md border border-gray-300 px-3 py-2 focus:outline-none focus:ring-1 focus:ring-indigo-500"
								/>
							</div>
							<div>
								<label for="email" class="block text-sm font-medium">Email</label>
								<input
									type="email"
									id="email"
									name="email"
									class="w-full rounded-md border border-gray-300 px-3 py-2 focus:outline-none focus:ring-1 focus:ring-indigo-500"
								/>
							</div>
							<div>
								<label for="username" class="block text-sm font-medium">Username</label>
								<input
									type="text"
									id="username"
									name="username"
									class="w-full rounded-md border border-gray-300 px-3 py-2 focus:outline-none focus:ring-1 focus:ring-indigo-500"
								/>
							</div>
							<div>
								<label for="password" class="block text-sm font-medium">Password</label>
								<input
									type="password"
									id="password"
									name="password"
									class="w-full rounded-md border border-gray-300 px-3 py-2 focus:outline-none focus:ring-1 focus:ring-indigo-500"
								/>
							</div>
							<button type="submit" class=" btn mb-6 mt-8 w-full rounded-md bg-sky-600 p-2">
								Submit
							</button>
						</form>
					</div>
				</div>
			</div>
		</div>
	</section>
</div>
