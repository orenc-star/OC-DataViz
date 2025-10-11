
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TSWD Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header and Navigation -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4">
            <ul class="flex flex-wrap justify-center items-center space-x-4 md:space-x-6">
                <li><a href="index.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Home</a></li>
                <li><a href="dataviz-examples.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Data Viz Examples</a></li>
                <li><a href="myFolder/critique-by-design.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Critique by Design</a></li>
                <li><a href="final-project-part-one.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project I</a></li>
                <li><a href="final-project-part-two.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project II</a></li>
                <li><a href="final-project-part-three.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project III</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">
        <div class="max-w-4xl mx-auto">

            <!-- Introduction Section -->
            <section id="home" class="mb-16 text-center">
                <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">What Story will the Data Telling you?</h1>
                <p class="text-lg text-gray-600 mb-6">This is my public portfolio showing how to tell stories with Data. Hope you will enjoy!</p>
                <div class="bg-blue-100 border-l-4 border-blue-500 text-blue-700 p-4 rounded-md text-left text-sm">
                    <p class="font-semibold">Quick Links:</p>
                    <ul class="list-disc list-inside mt-2">
                        <li><strong>Web page URL:</strong> <a href="https://orenc-star.github.io/OC-DataViz/index.html" class="underline hover:text-blue-800">https://orenc-star.github.io/OC-DataViz/index.html</a></li>
                        <li><strong>Repository:</strong> <a href="https://github.com/cmustudent/tswd-portfolio-templates/" class="underline hover:text-blue-800">https://github.com/cmustudent/tswd-portfolio-templates/</a></li>
                    </ul>
                </div>
            </section>

            <!-- About Me Section -->
            <section id="about" class="mb-16 bg-white p-8 rounded-lg shadow-md">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">About Me</h2>
                <p class="text-gray-700 leading-relaxed">Hello. I am Oren. I live in Pittsburgh during my program. I study arts management and work on creative tech projects. I love data stories that help people decide, especially when the story connects culture, community, and operations. I play piano, guitar, and clarinet.</p>
            </section>
            
            <!-- What I Hope to Learn Section -->
            <section id="learning" class="mb-16 bg-white p-8 rounded-lg shadow-md">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">What I Hope to Learn</h2>
                <ul class="list-disc list-inside space-y-2 text-gray-600">
                    <li>I'm hoping to learn how to assess my charts and how to make them part of my performance when I present ideas.</li>
                    <li>I want to learn how to validate my data in a way that convinces people and allows me to be creative with it.</li>
                </ul>
            </section>

            <!-- Portfolio Examples Section -->
            <section id="portfolio" class="mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-6 text-center">Portfolio Examples</h2>
                <p class="text-center text-gray-700 mb-8">This portfolio contains some charts and explanations I created during my studies. You can travel through the different examples from here or from the main menu.</p>
                <div class="space-y-8">
                    <!-- Assignment Card 1 -->
                    <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300">
                        <h3 class="text-2xl font-semibold mb-2">Assignment: Visualizing Government Debt</h3>
                        <p class="text-gray-600 mb-4">For this assignment, I set up and linked to a new page to explore government debt data.</p>
                        <a href="visualizing-government-debt.html" class="inline-block bg-blue-600 text-white font-semibold px-6 py-2 rounded-lg hover:bg-blue-700 transition-colors">View Project &rarr;</a>
                    </div>
                    <!-- Assignment Card 2 -->
                    <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300">
                        <h3 class="text-2xl font-semibold mb-2">Assignment 3 & 4: Critique by Design</h3>
                        <p class="text-gray-600 mb-4">For this assignment, I analyzed and redesigned an existing visualization.</p>
                        <a href="critique-by-design.html" class="inline-block bg-blue-600 text-white font-semibold px-6 py-2 rounded-lg hover:bg-blue-700 transition-colors">View Project &rarr;</a>
                    </div>
                </div>
            </section>
            
            <!-- Final Project Section -->
            <section id="final-project" class="mb-16 bg-white p-8 rounded-lg shadow-md">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Final Project</h2>
                <p class="text-gray-700 leading-relaxed mb-6">Here is a high-level description of my final project, broken down into its three parts.</p>
                <div class="flex flex-col sm:flex-row sm:justify-around text-center gap-4">
                    <a href="final-project-part-one.html" class="bg-gray-200 text-gray-800 font-semibold py-3 px-6 rounded-lg hover:bg-gray-300 transition-colors">Part I</a>
                    <a href="final-project-part-two.html" class="bg-gray-200 text-gray-800 font-semibold py-3 px-6 rounded-lg hover:bg-gray-300 transition-colors">Part II</a>
                    <a href="final-project-part-three.html" class="bg-gray-200 text-gray-800 font-semibold py-3 px-6 rounded-lg hover:bg-gray-300 transition-colors">Part III</a>
                </div>
            </section>

             <!-- Image Example Section -->
            <section id="image-example" class="mb-16 bg-white p-8 rounded-lg shadow-md">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Adding Images</h2>
                <p class="text-gray-700 leading-relaxed mb-6">Here's an example of how to add an image to my portfolio.</p>
                <div class="text-center">
                    <img src="images/funny-dog-unsplash.jpg" 
                         alt="A funny dog wearing glasses" 
                         class="rounded-lg shadow-lg mx-auto w-full max-w-md"
                         onerror="this.onerror=null;this.src='https://placehold.co/600x400?text=Image+Not+Found';">
                    <p class="text-xs text-gray-500 mt-2">
                        Original photo by <a href="https://unsplash.com/pt-br/@charlesdeluvio" class="underline">charlesdeluvio</a> on <a href="https://unsplash.com" class="underline">Unsplash</a>
                    </p>
                </div>
            </section>
        </div>
    </main>

        <!-- Footer -->
    <footer class="bg-gray-800 text-white mt-16">
        <div class="container mx-auto px-6 py-8">
            <div class="max-w-3xl mx-auto text-center">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 text-left">
                    <div>
                        <h3 class="font-bold text-lg mb-2">References</h3>
                         <ul class="text-gray-400 text-sm list-disc list-inside space-y-2">
                            <li>Google. "Gemini 2.5 Pro." Large language model. Accessed October 11, 2025.</li>
                         </ul>
                    </div>
                     <div>
                        <h3 class="font-bold text-lg mb-2">AI Acknowledgements</h3>
                        <p class="text-gray-400 text-sm">
                            I used Gemini 2.5 Pro to generate the HTML for this website.
                        </p>
                    </div>
                </div>
                <div class="mt-8 border-t border-gray-700 pt-6">
                    <p class="text-gray-500 text-sm">&copy; 2025 Oren C. All Rights Reserved.</p>
                </div>
            </div>
        </div>
    </footer>

</body>
</html>
