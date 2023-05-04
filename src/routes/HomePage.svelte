<script>
	import Hero from "../Components/Hero.svelte";
	import Container from "../Components/Container.svelte";
	import ContainerCol from "../Components/ContainerCol.svelte";
    import Article from "../Components/Article.svelte";
	import ArticleCol from "../Components/ArticleCol.svelte";
	import "../Style/ContentImages.css";
</script>

<Hero/>

<Container>
	<Article>
		<h1>Data Science Academy @ UCR</h1>
		<br/>
		<p>
			Hosted at the University of California, Riverside, the Data Science Academy was started by Professor Paea LePendu. Our aim is to introduce one of
			the most popular and insightful field in Computer Science to <b>K-12 students</b>. Please read more about this program in the
			<a href="/about">About DSA</a> page.
			
			<br/><br/>
			Currently, we are hoping to host a new Data Science Academy cohort during the 2022-23 school year.
		</p>

	</Article>
</Container>

<ContainerCol>

	<ArticleCol>
		<h1> Lessons </h1>
		<br/>
		<p>
			We host a variety of lessons throughout our program. With these lessons, we aim to instill the importance of learning Data Science, privacy,
			as well as many skills needed to manipulate and analyze datasets.
		</p>

		<br/>

		<img class="contentimage" src="/images/content/homepage_lessons1.jpg" loading="lazy" alt="Placeholder">

		<br/><br/>

		<p>
			These lessons are produced both by Professor Paea LePendu, as well as some of our DSA Leaders. These lessons include skillsets such as basic Python
			programming, learning how to analyze datasets, Machine Learning basics, word cloud generation, data visualization, as well as chat bots. With these
			lessons, we aim to not only provide the breadth of knowledge that students need to succeed in a Data Science career, but we also wish to motivate
			students to pursue a Computer Science or Data Science profession.
		</p>

		<br/>

		<img class="contentimage" src="/images/content/homepage_lessons2.jpg" loading="lazy" alt="Placeholder">

	</ArticleCol>


	<ArticleCol>
		<h1> Activities </h1>

		<br/>

		<p>
			While learning is extremely important, we wholeheartedly believe that fun, relaxation, and reflection are equally valuable to absorb new concepts.
			We therefore host a variety of activities for students to do in between the lessons and main Data Science learning. With these activities, we hope 
			that students are able to get away from the seriousness of Data Science and programming, and reflect on how these concepts can be applied in a fun,
			entertaining way.
		</p>

		<br/>

		<img class="contentimage" src="/images/content/homepage_activities1.jpg" loading="lazy" alt="Placeholder">

		<br/><br/>

		<p>
			In the past, these activities have included fun icebreakers, tours of the University of California, Riverside, fun implementations of Data Science
			concepts such as Google's Quickdraw, bingo, and many more. And while these activities do not take up much of our time in the program, they are
			essential to ensure that studens remain interested in the field.
		</p>

		<br/>

		<img class="contentimage" src="/images/content/homepage_activities2.jpg" loading="lazy" alt="Placeholder">

	</ArticleCol>

</ContainerCol>

<Container>
	<Article>
		<h1>Campus Tour</h1>
		<br/>
		<p>
			During our breaks and activities, we often give students a small but quite thorough tour of UC Riverside. Since the program takes place close to the center
			of campus, we have plenty of time to cover the most important spots. The purpose of this activity is to give students an idea of what they will expect if
			they study at UC Riverside. We emphasize the engineering side of campus, highlighting important buildings, facts, and accounts of our engineering experience
			at UC Riverside.

			<br/><br/>
			Our campus tours are led by the DSA Leaders, where they the role of guides who will take you on a journey through the university's history, academic programs,
			research facilities, and cultural landmarks. You'll have the chance to see some of the most iconic locations on campus, including the Bell Tower,
			the Orbach Science Library, and the Arts Building. And although we do not have the chance to cover every side of campus, we give a whollistic view of college life
			at UC Riverside.

			<br/><br/>

			<ContainerCol>
				<ArticleCol>
					<center>
						<img class="contentimage" src="/images/content/homepage_tour1.jpg" loading="lazy" alt="Placeholder">
					</center>
				</ArticleCol>

				<ArticleCol>
					<center>
						<img class="contentimage" src="/images/content/homepage_tour2.jpg" loading="lazy" alt="Placeholder">
					</center>
				</ArticleCol>
			</ContainerCol>

		</p>

		<p>
			Whether you're a prospective student, a current student of the Data Science Academy, or simply curious about the university, our academy tours are a fantastic way to
			experience the vibrant and dynamic community at UCR.
		</p>

	</Article>

	<Article>
		<h1>DSA Leaders</h1>
		<br/>
		<p>
			Please visit the <a href="/people">People</a> page to learn more about the DSA Leaders, as well as the mentors and instructors.
		</p>

	</Article>

</Container>

<Container>
	<Article>
		<h1>Student Testimonials</h1>
		<br/>
		<p>
			Throughout the years of the program's existence, we have collected a plethora of student testimonials that showcase how students feel about the Data Science Academy.
			These testimonials give us some insight into how alumni of the Data Science Academy feel about the program, the lessons, activities, and DSA Leaders.
		</p>
	</Article>
</Container>

<ContainerCol>
	<ArticleCol>
		<center>
			<h2>Testimonial</h2>
			<br/>
			<center>
				<p><b>"</b></p>
				<p>
					I learned a lot about what computers can do to analyze data.
				</p>
				<p><b>"</b></p>
			</center>
		</center>
	</ArticleCol>

	<ArticleCol>
		<center>
			<h2>Testimonial</h2>
			<br/>
			<center>
				<p><b>"</b></p>
				<p>
					Thank you for this amazing opportunity! I've always wanted to learn how to code and analyze and visualize data, but didn't know where to begin. This was the
					perfect experience to step foot in the door of programming with Python and establishing a future career as a computational neuroscientist or a bioinformatic.
				</p>
				<p><b>"</b></p>
			</center>
		</center>
	</ArticleCol>
</ContainerCol>

<ContainerCol>
	<ArticleCol>
		<center>
			<h2>Testimonial</h2>
			<br/>
			<center>
				<p><b>"</b></p>
				<p>
					I would like to thank the founder and sponsors of this program as I think it is a good way to give students
					exposure to the field. I may find a new passion that without this program, may not have been discovered. 
				</p>
				<p><b>"</b></p>
			</center>
		</center>
	</ArticleCol>

	<ArticleCol>
		<center>
			<h2>Testimonial</h2>
			<br/>
			<center>
				<p><b>"</b></p>
				<p>
					Thank you for providing students like me the opportunity to expand our knowledge and learn more about the
					applications of data science.
				</p>
				<p><b>"</b></p>
			</center>
		</center>
	</ArticleCol>
</ContainerCol>