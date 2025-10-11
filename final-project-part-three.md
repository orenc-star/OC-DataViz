
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project Part III - Oren's Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        blockquote {
            border-left: 4px solid #d1d5db;
            padding-left: 1rem;
            margin-left: 0;
            color: #4b5563;
            font-style: italic;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Header and Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-10">
        <nav class="container mx-auto px-6 py-4">
            <ul class="flex justify-center space-x-4 md:space-x-8 text-sm md:text-base">
                <li><a href="index.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Home</a></li>
                <li><a href="dataviz-examples.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Data Viz Examples</a></li>
                <li><a href="my folder/critique-by-design.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Critique by Design</a></li>
                <li><a href="final-project-part-one.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project I</a></li>
                <li><a href="final-project-part-two.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project II</a></li>
                <li><a href="final-project-part-three.html" class="text-blue-600 font-bold border-b-2 border-blue-600 pb-1">Final Project III</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">
        <div class="max-w-6xl mx-auto bg-white p-8 rounded-lg shadow-lg">

            <!-- Page Title -->
            <section class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Final Project Part III</h1>
            </section>
            
            <!-- The final data story -->
            <section>
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">The Final Data Story</h2>
                <p class="text-gray-700 leading-relaxed">My final interactive data story, "Finding Your Perfect Pittsburgh Neighborhood!", can be viewed on Shorthand at the following link:</p>
                <p class="mt-4"><a href="https://carnegiemellon.shorthandstories.com/which-student-profile-are-you/index.html" class="text-blue-600 hover:underline break-words" target="_blank">https://carnegiemellon.shorthandstories.com/which-student-profile-are-you/index.html</a></p>
            </section>

            <!-- Changes made since Part II -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Changes Made Since Part II</h2>
                <div class="text-gray-700 leading-relaxed space-y-6">
                    <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Narrative and Story Flow</h3>
                        <ul class="list-disc list-inside space-y-2">
                            <li><strong>Shifted Narrative Goal:</strong> Based on professor feedback, the story's focus shifted from asking "Which is the perfect Pittsburgh neighborhood?" to a more personal "Finding *your* perfect neighborhood." This clarified the purpose and changed the goal from simple information delivery to a persuasive journey designed to guide a user towards signing up for a newsletter.</li>
                            <li><strong>Strategic Repositioning of Personas:</strong> Contrary to initial feedback, I left the personas on the *start* of the story. They now serve as a crucial "checkpoint," helping users understand the concept of preferences and how they define a profile *before* they analyze the data.</li>
                             <li><strong>Refined Project Scope:</strong> I removed the original claim linking neighborhood choice to academic success. This felt like it was expanding the scope beyond what I could realistically back up with data and kept the project focused on its core goal.</li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Data and Visualization</h3>
                        <ul class="list-disc list-inside space-y-2">
                             <li><strong>Prioritized Essential Amenities:</strong> Based on feedback, I switched the focus from "Restaurants" to "Grocery Stores," as this is a more universal and frequent need for the target student audience.</li>
                            <li><strong>Redesigned Transportation Chart:</strong> The initial transportation visual was unclear. It was redesigned into a back-to-back bar chart comparing commute time and bus frequency, which allows for easier sorting and comparison.</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- The audience -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">The Audience</h2>
                <p class="text-gray-700 leading-relaxed mb-6">
                    While developing this project, my understanding of the target audience evolved. Initially, I received feedback that rental rates should be a key preference. However, after creating personas and considering the student journey, I realized that rental costs are often comparable across the main student neighborhoods; the real difference lies in the lifestyle and value each area offers. This insight led me to focus on preferences that are more critical to students, many of whom may not have a car, such as proximity to grocery stores, coffee shops, and reliable public transportation. This shift allowed me to tailor the story to the practical, day-to-day needs of my audience.
                </p>
                <p class="text-gray-700 leading-relaxed font-bold mb-2">My target audience for this project is composed of three primary groups, all of whom are at a key transition point in their housing journey in Pittsburgh:</p>
                 <ul class="list-disc list-inside text-gray-700 leading-relaxed space-y-2">
                    <li><strong>Newcomer Students:</strong> Individuals who are new to Pittsburgh and need initial guidance on where to live.</li>
                    <li><strong>Second-Year Students:</strong> Students who have completed their first year, whose housing contracts may be ending, and are looking to move to a new neighborhood that better suits their established routines and preferences.</li>
                    <li><strong>Recent Graduates:</strong> Individuals who have finished their studies and have accepted jobs in Pittsburgh. Their needs are shifting from a student-centric lifestyle to that of a working professional, and they are looking for a neighborhood that reflects this change.</li>
                </ul>
            </section>

             <!-- Final design decisions -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Final Design Decisions</h2>
                 <div class="text-gray-700 leading-relaxed space-y-6 mt-6">
                    <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Charts & Visual Design</h3>
                        <ul class="list-disc list-inside space-y-2">
                            <li><strong>Introduced "Podium" Charts:</strong> To support the new persuasive narrative, I developed "podium" style charts for each preference. This design clearly and quickly communicates the "winning" neighborhood for each category. For clarity, I used a unique color for each neighborhood rather than confusing medal colors.</li>
                            <li><strong>Implemented Interactive Radar Chart:</strong> Based on professor feedback, the final summary radar chart was transformed from a static image into an interactive tool. Users can now select and compare a custom set of 3-5 preferences, making the final recommendations feel highly personalized and actionable.</li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Shorthand Flow</h3>
                        <p> I structured the Shorthand story to create a balanced rhythm for the reader. The flow intentionally alternates between text and imagery to keep the narrative engaging. For the data sections, I adopted a two-step approach: first, presenting the data visualization with a neutral explanation of what it shows, and then immediately following up with a "conclusion" in the form of a podium chart that interprets the data for the user. This "data-then-conclusion" and "image-then-text" pattern was designed to make the story easy to follow while ensuring the key takeaways were clear and impactful.</p>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Imagery</h3>
                         <ul class="list-disc list-inside space-y-2">
                            <li><strong>Context-Specific Imagery:</strong> I strategically divided the images into two categories: "Neighborhood" images were paired with data to provide visual context for the analysis, while "inside the house" images were used to create a more personal, relatable tone for the reader. 'I used AI image generation to create visuals that specifically matched the environment and stage of my story. This allowed me to produce unique, highly relevant images that were more effective than generic stock photos.</li>
                            <li><strong>Persona & Narrative Imagery:</strong> AI was particularly powerful for creating the persona images. I was able to generate portraits where background elements and objects reflected the specific characteristics and preferences of each persona, making them more relatable and instantly understandable. This use of AI-generated imagery extended to the story's climax, where the final section has a background video depicting all three personas interacting. This served as a powerful visual conclusion that reinforced the idea of a shared student experience while expressing the call to action.</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- Project References -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Project References</h2>
                <div class="overflow-x-auto">
                    <table class="min-w-full bg-white border border-gray-300 text-sm">
                        <thead class="bg-gray-100">
                            <tr>
                                <th class="py-2 px-4 border-b text-left">Name (Chicago Citation)</th>
                                <th class="py-2 px-4 border-b text-left">Link</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr class="bg-gray-50">
                                <td colspan="2" class="py-2 px-4 border-b font-bold text-gray-600">Data Sources</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">"File:Pittsburgh Pennsylvania neighborhoods.svg." Wikipedia. Accessed October 10, 2025.</td>
                                <td class="py-2 px-4 border-b"><a href="https://en.wikipedia.org/wiki/File:Pittsburgh_Pennsylvania_neighborhoods.svg" class="text-blue-600 hover:underline" target="_blank">Link</a></td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">Oren C. "Data for Telling Data - Final." Google Sheets. [Data cleaning and analysis worksheet]. Accessed October 10, 2025.</td>
                                <td class="py-2 px-4 border-b"><a href="https://docs.google.com/spreadsheets/d/1-gQkKBfqiGtIRLT4hxewYCGvmuBwon9c9KapOCa7oLM/edit?usp=sharing" class="text-blue-600 hover:underline" target="_blank">Link</a></td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">Google Maps. "Grocery store [Squirrel Hill, Shadyside, etc.]." Search results. [Sample link for searches performed on all target neighborhoods]. Accessed October 10, 2025.</td>
                                <td class="py-2 px-4 border-b"><a href="https://www.google.com/maps/search/grocery+store+squirrel+hill/@40.4348393,-79.9296764,15.69z/data=!4m2!2m1!6e6?entry=ttu" class="text-blue-600 hover:underline" target="_blank">Link</a></td>
                            </tr>
                             <tr>
                                <td class="py-2 px-4 border-b">Western Pennsylvania Regional Data Center. "Monthly Criminal Activity Dashboard." Accessed October 10, 2025.</td>
                                <td class="py-2 px-4 border-b"><a href="https://data.wprdc.org/dataset/monthly-criminal-activity-dashboard/resource/bd41992a-987a-4cca-8798-fbe1cd946b07" class="text-blue-600 hover:underline" target="_blank">Link</a></td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">Western Pennsylvania Regional Data Center. "2020 Census Redistricting Data Extracts." Accessed October 10, 2025.</td>
                                <td class="py-2 px-4 border-b"><a href="https://data.wprdc.org/dataset/2020-census-redistricting-data-extracts/resource/a8414ed5-c50f-417e-bb67-82b734660da6" class="text-blue-600 hover:underline" target="_blank">Link</a></td>
                            </tr>
                             <tr>
                                <td class="py-2 px-4 border-b">Pittsburgh Regional Transit. "All Schedules." Accessed October 10, 2025.</td>
                                <td class="py-2 px-4 border-b"><a href="https://www.rideprt.org/all-schedules/" class="text-blue-600 hover:underline" target="_blank">Link</a></td>
                            </tr>
                            <tr class="bg-gray-50">
                                <td colspan="2" class="py-2 px-4 border-b font-bold text-gray-600">AI Tools</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">Google. "Gemini 2.5 Pro." Large language model. Accessed October 10, 2025.</td>
                                <td class="py-2 px-4 border-b">N/A</td>
                            </tr>
                             <tr>
                                <td class="py-2 px-4 border-b">Perplexity AI. "Perplexity Comet." AI search engine. Accessed October 10, 2025.</td>
                                <td class="py-2 px-4 border-b">N/A</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>

            <!-- Project AI Acknowledgements -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Project AI Acknowledgements</h2>
                <div class="text-gray-700 leading-relaxed space-y-6">
                    <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Text</h3>
                        <p>I used a suite of AI tools, including Gemini 2.5 Pro (in Chrome), Perplexity Comet Assistant, and ChatGPT, as writing assistants. My process involved writing the initial content myself and then using these tools to refine the text for spelling, grammar, and clarity.</p>
                    </div>
                     <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Imagery</h3>
                        <p>I used Gemini 2.5 Pro (Nano Banana) to generate and edit images to fit the specific messaging and context of my story. With the exception of the Pittsburgh neighborhoods map, which was adapted from Wikipedia, all other images—including the personas, the view of downtown Pittsburgh, and various thematic visuals—were generated by AI. The final video in the story was generated using Google's Veo model.</p>
                    </div>
                     <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Charts</h3>
                        <p>I used Gemini 2.5 Pro in Canvas mode to create and edit the data visualizations based on the data I supplied. I also utilized the build feature in Google AI Studio to generate the underlying code for the charts, which I then embedded as HTML sections within my Shorthand story.</p>
                    </div>
                </div>
            </section>

            <!-- Final thoughts -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Final Thoughts</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 text-gray-700 leading-relaxed">
                    <ul class="list-disc list-inside space-y-2">
                        <li>Felt empowered by the constructive process of integrating story, critique, charts, and purpose.</li>
                        <li>Wished for more critique sessions during the development of a large-scale project.</li>
                        <li>Realized the power of focusing on personas and a target audience to sharpen the story's message.</li>
                    </ul>
                    <ul class="list-disc list-inside space-y-2">
                         <li>Discovered the radar chart is a powerful framework for visualizing complex, multi-factor decisions.</li>
                        <li>This project was a valuable learning experience for my technical and storytelling skills.</li>
                        <li>Valued using the Shorthand storytelling platform.</li>
                    </ul>
                </div>

                <div class="mt-8 text-gray-700 leading-relaxed">
                    <p><strong>Presentation Reflection:</strong> It was an incredible and challenging experience to distill this entire project into a one-minute presentation. I enjoyed the process of using Google Vids as a new presentation tool, and although it felt risky, I believe it's a powerful and modern way to communicate ideas. I have attached the video with the voiceover below for review, as I feel it demonstrates the power of this concise storytelling format.</p>
                    <p class="mt-4"><a href="https://drive.google.com/file/d/1wOS2SSUSkgEkwLC1sHtMRKqZzrumJNfl/view?usp=sharing" class="text-blue-600 hover:underline" target="_blank">View Presentation Video</a></p>
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
                        <h3 class="font-bold text-lg mb-2">Page-Specific References</h3>
                         <ul class="list-disc list-inside text-gray-400 text-sm space-y-2">
                            <li>Google. "Gemini 2.5 Pro." Large language model. Accessed October 11, 2025.</li>
                            <li>Shorthand. "Shorthand." Digital storytelling platform. Accessed October 11, 2025. https://shorthand.com/.</li>
                             <li>Google. "Google Vids." AI-powered video creation tool. Accessed October 11, 2025.</li>
                        </ul>
                    </div>
                     <div>
                        <h3 class="font-bold text-lg mb-2">Page-Specific AI Acknowledgements</h3>
                        <p class="text-gray-400 text-sm">For the text on this portfolio page, I wrote the initial content and then used Gemini to correct spelling errors and improve grammar and clarity. The presentation video was created with Google Vids, which utilizes AI to generate video, images, and slide designs. I provided the original content and concepts as a baseline for the models to generate.</p>
                    </div>
                </div>
                <div class="mt-8 border-t border-gray-700 pt-6">
                    <p class="text-gray-500 text-sm">&copy; 2024 Oren C. All Rights Reserved.</p>
                </div>
            </div>
        </div>
    </footer>

</body>
</html>

