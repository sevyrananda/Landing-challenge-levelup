<section
	class="text-white bg-[#1B353D]"
	style="background-image: url('/images/hero.png'); background-size: cover; margin-top:140px;"
	id="home"
>
	<div class="bg-black bg-opacity-50">
		<div class="max-w-screen-xl mx-auto p-4">
			<div class="flex flex-col lg:flex-row items-center lg:space-x-24">
				<div class="flex flex-col lg:w-1/2">
					<div class="flex flex-col space-y-4">
						<h1 class="text-5xl font-bold font-heading">Take your career to the next level.</h1>
						<p>With indispensable courses</p>
					</div>
					<div class="flex mt-12 space-x-3">
						<button class="w-full lg:w-1/3 outline rounded-lg p-4">Exams</button>
						<button class="w-full lg:w-1/3 rounded-lg bg-white p-4 text-black">Our Courses</button>
					</div>
				</div>
				<div class=" mt-8 lg:mt-0">
					<img src="/images/hero-1.png" class="w-full h-full" alt="Hero" />
				</div>
			</div>
		</div>
	</div>
</section>

<section id="course" class="py-10 lg:py-20 text-black bg-white">
	<div class="flex flex-col max-w-screen-xl mx-auto space-y-10 px-4">
		<div class="flex flex-col justify-center text-center">
			<h2 class="text-3xl lg:text-5xl font-bold font-heading">Enrol for a course now</h2>
		</div>

		<div class="flex flex-col lg:flex-row space-y-6 lg:space-y-0 lg:space-x-12">
			<div class="flex flex-col justify-center w-full lg:w-1/2 space-y-3">
				<h2 class="text-3xl lg:text-5xl font-semibold">Take your career to the next level.</h2>
				<h4 class="text-2xl font-regular">With indispensable courses</h4>
				<p>
					Lorem ipsum dolor sit at, consectetur adipielit. Facilisi fermentum, dignissim pharetra.
					Aliquam Lorem ipsum dolor sit at, consectetur adipielit. Facilisi fermentum, dignissim
					pharetra. Aliquam Lorem ipsum dolor sit at, consectetur adipielit. Facilisi fermentum,
					dignissim pharetra. Aliquam
				</p>
			</div>
			<div class="flex flex-col w-full lg:w-1/2">
				<div class="bg-white p-4 lg:p-8 border-2 border-gray-100 rounded-lg hover:shadow-lg">
					<h1 class="text-2xl font-semibold">Registration for enrolment</h1>
					<form class="flex flex-col space-y-4 mt-6 lg:mt-12">
						<input
							type="text"
							id="full-name"
							placeholder="Enter your full name"
							class="border-2 border-gray-50 py-3 px-4 focus:border-primary transition duration-300 rounded-lg shadow-md"
						/>

						<input
							type="email"
							id="email"
							placeholder="Enter your email"
							class="border-2 border-gray-50 py-3 px-4 focus:border-primary transition duration-300 rounded-lg shadow-md"
						/>

						<input
							type="tel"
							id="phone-number"
							placeholder="Enter your phone number"
							class="border-2 border-gray-50 py-3 px-4 focus:border-primary transition duration-300 rounded-lg shadow-md"
						/>

						<select
							id="course-select"
							class="border-2 border-gray-50 py-3 px-4 focus:border-primary transition duration-300 rounded-lg shadow-md"
						>
							<option value="course-1">❆ List of courses goes here</option>
						</select>
						<div class="text-center lg:text-right">
							<button
								type="submit"
								class="bg-[#1B353D] mt-6 lg:mt-10 text-white py-3 px-16 lg:px-20 rounded-lg hover:bg-primary transition duration-300"
								>Apply Now</button
							>
						</div>
					</form>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="py-10 lg:py-20 text-black bg-white">
	<div class="flex flex-col max-w-screen-xl mx-auto space-y-10 p-4">
		<div class="flex flex-col space-y-3 text-center">
			<h2 class="text-3xl lg:text-5xl font-bold font-heading">What we offer</h2>
		</div>
		<div class="flex flex-col lg:flex-row space-y-6 lg:space-y-0 lg:space-x-24">
			<div class="flex lg:w-1/2">
				<img src="/images/person.png" class="w-full h-full rounded" alt="Optimized for growth" />
			</div>
			<div class="flex flex-col w-full lg:w-1/2 space-y-6">
				<h5 class="text-4xl font-semibold text-[#0F756B]">Online Courses</h5>
				<h4 class="text-4xl font-regular text-[#404040CC]">
					Our Courses are the best among others
				</h4>
				<p>
					Lorem ipsum dolor sit at, consectetur adipielit. Facilisi fermentum, dignissim pharetra.
					Aliquam Lorem ipsum dolor sit at, consectetur adipielit. Facilisi fermentum, dignissim
					pharetra. Aliquam
				</p>
				<div class="flex space-x-3 cursor-pointer group">
					<button class="w-full lg:w-1/3 outline-black rounded-lg p-4">Explore our courses</button>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="pt-20 pb-32">
    <div class="flex flex-col justify-center space-y-3 text-center">
        <h2 class="text-3xl lg:text-5xl font-bold font-heading">Trending Courses</h2>
    </div>

    <div class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-4 xl:grid-cols-4 gap-8 mt-24 p-4">
        <!-- Card 1 -->
        <div class="relative">
            <img src="/images/img1.png" alt="Showcase 1" class="w-full h-auto rounded" />
            <div class="absolute inset-0 flex flex-col items-start justify-end text-white text-left p-4">
                <h3 class="text-3xl font-normal">Game Development</h3>
            </div>
        </div>

        <!-- Card 2 -->
        <div class="relative">
            <img src="/images/img2.png" alt="Showcase 2" class="w-full h-auto rounded" />
            <div class="absolute inset-0 flex flex-col items-start justify-end text-white text-left p-4">
                <h3 class="text-3xl font-normal">Marketing Strategy</h3>
            </div>
        </div>

        <!-- Card 3 -->
        <div class="relative">
            <img src="/images/img3.png" alt="Showcase 3" class="w-full h-auto rounded" />
            <div class="absolute inset-0 flex flex-col items-start justify-end text-white text-left p-4">
                <h3 class="text-3xl font-normal">Data Analysis With Python</h3>
            </div>
        </div>

        <!-- Card 4 -->
        <div class="relative">
            <img src="/images/img4.png" alt="Showcase 4" class="w-full h-auto rounded" />
            <div class="absolute inset-0 flex flex-col items-start justify-end text-white text-left p-4">
                <h3 class="text-3xl font-normal">Advanced UX Designs</h3>
            </div>
        </div>
    </div>
</section>




<section id="instructor" class="py-10 lg:py-20 text-black bg-white">
    <div class="flex flex-col max-w-screen-xl mx-auto space-y-10 lg:space-y-20 px-4">
        <div class="flex flex-col justify-center space-y-3 text-center">
            <h2 class="text-3xl lg:text-4xl xl:text-5xl font-bold font-heading">Notable Intructors</h2>
        </div>

        <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-2 xl:grid-cols-4 mt-24 justify-center">
            <!-- Card 1 -->
            <div class="bg-white rounded-lg hover:shadow-lg px-4 py-6 text-center w-[311.37px] h-[311.37px] mx-auto flex flex-col justify-center items-center">
                <img src="/images/c1.png" alt="Instructor 1" class="w-18 h-18 rounded-full mx-auto mb-4" />
                <p class="text-xl text-gray-600">DATA ANALYST</p>
                <h3 class="text-xl font-semibold">Prof. W.J Khatam</h3>
            </div>

            <!-- Card 2 -->
            <div class="bg-white rounded-lg hover:shadow-lg px-4 py-6 text-center w-[311.37px] h-[311.37px] mx-auto flex flex-col justify-center items-center">
                <img src="/images/c2.png" alt="Instructor 2" class="w-18 h-18 rounded-full mx-auto mb-4" />
                <p class="text-xl text-gray-600">UX DESIGNER</p>
                <h3 class="text-xl font-semibold">Prof. Kaif Kofi O</h3>
            </div>

            <!-- Card 3 -->
            <div class="bg-white rounded-lg hover:shadow-lg px-4 py-6 text-center w-[311.37px] h-[311.37px] mx-auto flex flex-col justify-center items-center">
                <img src="/images/c3.png" alt="Instructor 3" class="w-18 h-18 rounded-full mx-auto mb-4" />
                <p class="text-xl text-gray-600">SOFTWARE DEV.</p>
                <h3 class="text-xl font-semibold">Prof. Maryam J</h3>
            </div>

            <!-- Card 4 -->
            <div class="bg-white rounded-lg hover:shadow-lg px-4 py-6 text-center w-[311.37px] h-[311.37px] mx-auto flex flex-col justify-center items-center">
                <img src="/images/c4.png" alt="Instructor 4" class="w-18 h-18 rounded-full mx-auto mb-4" />
                <p class="text-xl text-gray-600">PSYCHOLOGIST</p>
                <h3 class="text-xl font-semibold">Mr. Oluwole B.O</h3>
            </div>
        </div>
    </div>
</section>


<section id="contact" class="py-10 lg:py-20 text-black bg-[#F4F9FA]">
	<div class="flex flex-col max-w-screen-xl mx-auto space-y-10 lg:space-y-20 px-4">
		<div class="flex flex-col justify-center space-y-3 text-center">
			<h2 class="text-3xl lg:text-4xl xl:text-5xl font-bold font-heading">Get In Touch</h2>
			<p>
				Lorem ipsum dolor sit at, consectetur adipielit. Facilisi fermentum, dignissim pharetra.
				Aliquam Lorem ipsum dolor sit at, consectetur adipielit. Facilisi fermentum, dignissim
				pharetra. Aliquam
			</p>
		</div>

		<div class="flex flex-col lg:flex-row space-y-6 lg:space-y-0 lg:space-x-12">
			<div
				class="flex flex-col justify-center lg:w-1/2 space-y-3 border-2 border-gray-105 rounded-lg hover:shadow-lg p-6 mx-auto"
				style="width: 317px; height:428px; margin-left:30px;"
			>
				<div class="flex flex-col space-y-1">
					<div class="flex items-baseline">
						<img src="/icons/mail-fill.png" alt="Email" />
						<h2 class="text-2xl font-bold ml-2">Email</h2>
					</div>
					<p class="ml-8">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

					<div class="flex items-baseline">
						<img src="/icons/phone-fill.png" alt="Phone" />
						<h2 class="text-2xl font-bold ml-2">Phone</h2>
					</div>
					<p class="ml-8">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

					<div class="flex items-baseline">
						<img src="/icons/support.png" alt="Support" />
						<h2 class="text-2xl font-bold ml-2">Support Center</h2>
					</div>
					<p class="ml-8">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
				</div>

				<div class="flex items-center space-x-8 mx-auto" style="margin-top: 30px;">
					<a href="/" class="text-primary hover:text-primary">
						<img src="/icons/facebook-circle-fill.png" alt="Facebook" class="w-6 h-6" />
					</a>
					<a href="/" class="text-primary hover:text-primary">
						<img src="/icons/twitter-fill.png" alt="Twitter" class="w-6 h-6" />
					</a>
					<a href="/" class="text-primary hover:text-primary">
						<img src="/icons/instagram-fill.png" alt="Instagram" class="w-6 h-6" />
					</a>
					<a href="/" class="text-primary hover:text-primary">
						<img src="/icons/linkedin-box-fill.png" alt="LinkedIn" class="w-6 h-6" />
					</a>
				</div>
			</div>

			<div class="flex flex-col lg:w-1/2">
				<form class="flex flex-col space-y-4">
					<input
						type="text"
						id="full-name"
						placeholder="Name"
						class="border-2 border-gray-50 py-3 px-4 focus:border-primary transition duration-300 rounded-lg shadow-md"
					/>

					<input
						type="email"
						id="email"
						placeholder="Email"
						class="border-2 border-gray-50 py-3 px-4 focus:border-primary transition duration-300 rounded-lg shadow-md"
					/>

					<input
						type="text"
						id="subject"
						placeholder="Subject"
						class="border-2 border-gray-50 py-3 px-4 focus:border-primary transition duration-300 rounded-lg shadow-md"
					/>

					<textarea
						id="message"
						placeholder="Message"
						class="border-2 border-gray-50 py-3 px-4 focus:border-primary transition duration-300 rounded-lg shadow-md"
						rows="6"
					/>

					<div class="text-right">
						<button
							type="submit"
							class="bg-[#1B353D] mt-6 lg:mt-10 text-white py-3 px-16 lg:px-20 xl:px-24 rounded-lg hover:bg-primary transition duration-300"
							>Send</button
						>
					</div>
				</form>
			</div>
		</div>
	</div>
</section>
