
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
                            <li><strong>Strategic Repositioning of Personas:</strong> Contrary to initial feedback, I moved the personas to the *start* of the story. They now serve as a crucial "checkpoint," helping users understand the concept of preferences and how they define a profile *before* they analyze the data.</li>
                             <li><strong>Refined Project Scope:</strong> I removed the original claim linking neighborhood choice to academic success. This felt like it was expanding the scope beyond what I could realistically back up with data and kept the project focused on its core goal.</li>
                             <li><strong>Added Interactive Survey:</strong> The story now opens with an interactive survey to immediately engage the user and provide a clear justification for the subsequent analysis.</li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Data and Visualization</h3>
                        <ul class="list-disc list-inside space-y-2">
                             <li><strong>Prioritized Essential Amenities:</strong> Based on feedback, I switched the focus from "Restaurants" to "Grocery Stores," as this is a more universal and frequent need for the target student audience.</li>
                            <li><strong>Redesigned Transportation Chart:</strong> The initial transportation visual was unclear. It was redesigned into a back-to-back bar chart comparing commute time and bus frequency, which allows for easier sorting and comparison.</li>
                            <li><strong>Introduced "Podium" Charts:</strong> To support the new persuasive narrative, I developed "podium" style charts for each preference. This design clearly and quickly communicates the "winning" neighborhood for each category. For clarity, I used a unique color for each neighborhood rather than confusing medal colors.</li>
                            <li><strong>Implemented Interactive Radar Chart:</strong> Based on professor feedback, the final summary radar chart was transformed from a static image into an interactive tool. Users can now select and compare a custom set of 3-5 preferences, making the final recommendations feel highly personalized and actionable.</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- The audience -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">The Audience</h2>
                 <blockquote class="my-4">
                    Talk about who you identified as the audience for your final data story. Include any other information you've used that helped you narrow the focus (e.g. insights from your interviews, personas, etc.). Note any specific adjustments you made to your final project to make it work for your audience.
                </blockquote>
                <p class="text-gray-700 leading-relaxed">Text here!</p>
            </section>

             <!-- Final design decisions -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Final Design Decisions</h2>
                 <blockquote class="my-4">
                    You can specifically break out your design decisions here, or include it under *Changes made since Part II* and delete this section. Talk about the design decisions you had to make along the way, and reflect on anything in particular that stands out to you that you learned working through the process. Include any other information that helps round out your data story.
                </blockquote>
                <p class="text-gray-700 leading-relaxed">Text here!</p>
            </section>

            <!-- Project References -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Project References</h2>
                <p class="text-gray-700 leading-relaxed"><!-- Your text for overall project references goes here --></p>
            </section>

            <!-- Project AI Acknowledgements -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Project AI Acknowledgements</h2>
                <p class="text-gray-700 leading-relaxed"><!-- Your text for overall project AI acknowledgements goes here --></p>
            </section>

            <!-- Final thoughts -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Final Thoughts</h2>
                 <blockquote class="my-4">
                    You can summarize any final thoughts / reflections that don't fit well in the previous sections here. How did it go? What did you run out of time for, or wish you had a chance to revisit? What were you most excited about? Include any final reflections as you think they might help us understand your process. If you already included such reflections elsewhere, you can delete this section.
                </blockquote>
                <p class="text-gray-700 leading-relaxed">Text here!</p>
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
                         <p class="text-gray-400 text-sm"><em>You should have already included detailed references on your Shorthand story - if so, you do not need to list them twice, unless you used additional references for specific to your writeup.</em></p>
                    </div>
                     <div>
                        <h3 class="font-bold text-lg mb-2">Page-Specific AI Acknowledgements</h3>
                        <p class="text-gray-400 text-sm"><em>If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here.</em></p>
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

