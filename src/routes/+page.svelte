<script>
	import github_logo from '$lib/images/github-mark.svg';
	import linkedin_logo from '$lib/images/LI-In-Bug.png';
	import instagram_logo from '$lib/images/instagram.png';
</script>

<section class="pt-16">
	<div class="w-full lg:w-4/12 px-4 mx-auto">
		<div
			class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-xl rounded-lg mt-16"
		>
			<div class="px-6">
				<div class="flex flex-wrap justify-center">
					<div class="w-full px-4 py-4 flex justify-center">
						<div class="relative">
							<img
								alt="..."
								src="https://storage.cloud.google.com/fortyfour-bucketlab/DSC00152%20edit%20kotak.jpg?authuser=1"
								class="shadow-xl rounded-full align-middle border-none object-contain max-w-xs"
							/>
						</div>
					</div>
				</div>
				<div class="text-center mt-12">
					<h3 class="text-2xl font-semibold leading-normal mb-2">I Komang Surya Adinandika</h3>
					<div class="text-sm leading-normal font-bold uppercase">
						<i class="mr-2 text-lg" />
						Bali, Indonesia
					</div>
					<div class="mt-5">
						<i class="mr-2 text-lg" />
						Undergraduate Computer Science Student
					</div>
					<div>
						<i class="mr-2 text-lg" />
						Udayana University
					</div>
				</div>
				<div class="mt-5 py-5 border-t text-center">
					<div class="flex flex-wrap justify-center">
						<div class="w-full lg:w-9/12 px-4">
							<p class="mb-4 text-lg leading-relaxed">
								A passionate and dedicated 3rd year Computer Science student at Udayana University,
								I have found my true calling in the world of backend programming. With a strong
								foundation in computer science principles and a keen eye for detail, I thrive in
								creating robust and efficient solutions
							</p>
						</div>
					</div>
				</div>
				<div class="py-5 border-t text-center">
                    <!-- find me on -->
                    <h3 class="text-sm leading-normal font-bold uppercase">Find me on</h3>
					<div class="flex flex-wrap justify-center">
						<div class="w-full lg:w-9/12 px-10">
							<div class="flex flex-row justify-center">
								<div class="w-full lg:w-4/12 px-4 text-center">
									<a href="https://github.com/suryaadi44" target="_blank">
										<div
											class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
										>
											<img src={github_logo} alt="" />
										</div>
									</a>
								</div>
                                <div class="w-full lg:w-4/12 px-4 text-center">
									<a href="https://www.linkedin.com/in/suryaadi44" target="_blank">
										<div
											class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
										>
											<img src={linkedin_logo} alt="" />
										</div>
									</a>
								</div>
                                <div class="w-full lg:w-4/12 px-4 text-center">
									<a href="https://www.instagram.com/surya.adi44/" target="_blank">
										<div
											class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
										>
											<img src={instagram_logo} alt="" />
										</div>
									</a>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}
</style>
