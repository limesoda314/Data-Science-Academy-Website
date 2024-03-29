<script>
	import Hero from "../Components/Hero.svelte";
	import Container from "../Components/Container.svelte";
	import ContainerCol from "../Components/ContainerCol.svelte";
    import Article from "../Components/Article.svelte";
	import ArticleCol from "../Components/ArticleCol.svelte";
	import "../Style/ContentImages.css";
    import CenteredImageArticle from "../Components/CenteredImageArticle.svelte";
    import "../Style/GalleryImages.css";

</script>

<Container>
    <Article>
        <h1>Overview</h1>
        <br/>
        <p>
            The University of California, Riverside, has many opportunities to all types of students. We host several clubs and organizations that are open to anyone
            willing to participate. In view of the fast-growing Data Science major at UC Riverside, the Data Science Academy stands at the forefront of change, giving
            students a window into many aspects of Data Science.
        </p>
        <br/>
        <p>
            Hosted at the University of California, Riverside, the Data Science Academy was started by Professor Paea LePendu. Our aim is to introduce one of the most
            popular and insightful field in Computer Science to <b>K-12 students</b>. 
        </p>
        <br/>
        <p>
            At the Data Science Academy students meet current Computer Science university students and professors. Each day students get a combination of interactive
            lessons and activities about different topics in computer science. Some topics that we go over include cryptography and data anaylsis. By the end of the
            program, students will have a project that they can present in the showcase. These projects range from chatbots to wordclouds or ascii art. 
        </p>
        <br/>
        <ContainerCol>
            <ArticleCol>
                <centering>
                    <img class="contentimage" src="/images/content/about_overview.jpg" loading="lazy" alt="Placeholder">
                </centering>
            </ArticleCol>
            <ArticleCol>
                <p>
                    In previous cohorts, the Data Science Academy took place at the school hosting it. Professor LePendu and volunteers traveled to the school, and gave
                    students lessons on Data Science.
                </p>
                <br/>
                <p>
                    Since we provide Data Science instruction to <b>K-12</b> students, we visited several High Schools, such as Ramona High. In 2020, amid the pandemic,
                    we hosted a cohort online. In this cohort, more than 100 students participated, from several different high schools and middle schools.
                </p>
                <br/>
                <p>
                    We utilize the <b>Google Colab</b> platform to program in Python. We have found that students extremely enjoy this platform, because it is not only
                    intuitive, but it is also easy to access. Colab also provides several built-in tools that allow us to teach students about Data Science without
                    having to install many programs and packages.
                </p>
                <br/>
                <p>
                    Finally, throughout the program, students are encouraged to fill out surveys about their thoughts on the program. We incorporate these surveys in 
                    several different ways, such as performing data analysis on them, using the data to teach students, as well as for our own insight to improve the
                    program.
                </p>
            </ArticleCol>
        </ContainerCol>

    </Article>

    <Article>
        <h1>Mission Statement</h1>
        <br/>

        <h2>Our Vision</h2>
        <br/>
        <p>The Data Science Academy focuses on a variety of issues. First and foremost, <u>we aim to give prospective college students a view into how Data Science is "done"
            in the real world.</u></p>
        <br/>

        <h2>Our Mission</h2>
        <br/>
        <p>In order to give these K-12 students a view into the Data Science profession, we implement a variety of strategies. <b>(1)</b> We host lessons in Data Science topics
            (view the lessons header to learn more). <b>(2)</b> We host activities for fun. These activities are meant to not only motivate students about Computer Science and
            Data Science, since some of these activities are implementations of the concepts we are learning. They are also meant to give students a break from the high intensity
            learning we do in our main sessions. <b>(3)</b> We host a showcase for students to demonstrate what they have learned throughout the cohort. The purpose of these is
            tri-fold. First, it helps students get motivated about Data Science and Computer Science. It also enables students to demonstrate what they have learned throughout
            the cohort, since they are presenting their projects in front of everyone. Finally, it allows students to practice their public speaking, as well as presentation
            skills.
        </p>

        <Container>
            <CenteredImageArticle>
                <centering>
                    <img class="contentimage" src="/images/content/about_mission.jpg" loading="lazy" alt="Placeholder">
                </centering>
            </CenteredImageArticle>
        </Container>

    </Article>

    <Article>
        <h1>Lessons</h1>
        <br/>
        <p>
            Throughout the years, our lessons have changed and adapted to the times and context of society. In 2020, our Data Science Academy had an emphasis on <b>homelessness</b>, in view
            of the growing homeless populations in Riverside, CA. In our current cohort, we want to emphasize underrepresented populations in the Data Science and Computer Science
            student population. Further, we are also implementing a new <b>ethics</b> module to instruct students in how ethics plays an enormous part in Data Science.
        </p>
        <br/>
        
        <p>
            Our current lesson modules include the following:
        </p>

        <li>Lesson 1: Intro to Python and Encryption</li>
        <li>Lesson 2: Data Science, Visualization, and Ethics</li>
        <li>Lesson 3: Visualizing Textual Data Using Word Clouds</li>

        <ContainerCol>
            <ArticleCol>
                <h3>Intro to Python and Encryption</h3>
                <br/>
                <img class="contentimage" src="/images/content/about_lesson1.jpg" loading="lazy" alt="Placeholder" style="width: 150px;">
                <br/>
                <p>
                    This lesson aims to teach students about <b>conditionals</b>, <b>variables</b>, <b>loops</b>, and <b>functions</b>. <b>Python</b> is one of the most famous
                    programming languages that Data Scientists use to analyze and visualize data. This is why we use Python as the programming language. Additionally, this
                    lesson uses encryption to strengthen some of these concepts for students. Since basic encryption methods use some of the same concepts (conditionals, variables,
                    loops, functions), it is useful for students to have an understanding of Python before jumping into Data Science.
                </p>
            </ArticleCol>
            <ArticleCol>
                <h3>Data Science, Visualization, and Ethics</h3>
                <br/>
                <img class="contentimage" src="/images/content/about_lesson2.jpg" loading="lazy" alt="Placeholder" style="width: 150px;">
                <br/>
                <p>
                    In this module, we focus on the main Data Science topics that students must know coming out of the program. First, we touch on the <b>Pandas</b> package, which
                    is a table-handling package for <b>Python</b>. Using the same library, we cover the topics of <b>matrices</b> and <b>vectors</b>. <b>Data Cleaning</b>, which
                    plays an incredibly important role in proper Data Science operations, is also taught in this module. Finally, we also cover <b>ethics</b> in Data Science
                    (and Computer Science at large).
                </p>
            </ArticleCol>
        </ContainerCol>

        <Container>
            <Article>
                <h3>Visualizing Textual Data Using Word Clouds</h3>
                <br/>
                <img class="contentimage" src="/images/content/about_lesson3.jpg" loading="lazy" alt="Placeholder" style="width: 150px;">
                <br/>
                <p>
                    A common method of analyzing textual data (for example, books or articles), is to create <b>word clouds</b>. Examples of word clouds can be found
                    <a href="https://www.google.com/search?q=word+clouds&source=lnms&tbm=isch&sa=X&ved=2ahUKEwi36oqP99n-AhWMADQIHd1GBtsQ0pQJegQIBhAC&cshid=1683143768283707">here</a>.
                    Because we aim to give students several ways to visualize data, we do not want to merely focus on numerical data. Therefore, word clouds are an important
                    concept to know. In presenting data, word clouds play a critical role.
                </p>
                <br/>
                <p>
                    We first introduce the concept of <b>word clouds</b>, and why they are important. Further, we show students several Python packages they will need when
                    creating basic word clouds. Finally, to give students some time to create their projects and have fun, we ask them to improve their word clouds with colors,
                    different shapes, and different silhouettes images.
                </p>
            </Article>
        </Container>

    </Article>

    <Article>
        <h1>Activities</h1>
        <br/>
        <p>
            We host a variety of activities in the Data Science Academy. The purpose of these activities is to entertain students before and after each lesson. We have found
            that these activities help students ease into the program. For instance, the tour of the campus gives students a well-deserved break from the intensity of the main
            lesson, while also introducing them to life at UC Riverside.
        </p>
    </Article>
</Container>

<ContainerCol>
    <ArticleCol>
        <img class="galleryimage" src="/images/content/about_activities1.jpg" loading="lazy" alt="Placeholder">
    </ArticleCol>
    <ArticleCol>
        <img class="galleryimage" src="/images/content/about_activities3.jpg" loading="lazy" alt="Placeholder">
    </ArticleCol>
</ContainerCol>

<ContainerCol>
    <ArticleCol>
        <img class="galleryimage" src="/images/content/about_activities4.jpg" loading="lazy" alt="Placeholder">
    </ArticleCol>
    <ArticleCol>
        <img class="galleryimage" src="/images/content/about_activities2.jpg" loading="lazy" alt="Placeholder">
    </ArticleCol>
</ContainerCol>