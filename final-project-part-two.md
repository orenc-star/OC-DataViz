
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project Part II - Oren's Portfolio</title>
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
                <li><a href="final-project-part-two.html" class="text-blue-600 font-bold border-b-2 border-blue-600 pb-1">Final Project II</a></li>
                <li><a href="final-project-part-three.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project III</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">
        <div class="max-w-6xl mx-auto bg-white p-8 rounded-lg shadow-lg">

            <!-- Page Title -->
            <section class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Final Project Part II</h1>
            </section>
            
            <!-- Wireframes / storyboards -->
            <section>
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Wireframes / Storyboards</h2>
                <p class="text-gray-700 leading-relaxed">My initial storyboard, which lays out the narrative flow and includes the draft visualizations, can be viewed on Shorthand here: <a href="https://preview.shorthand.com/FRXxRxaWOMqIt3v2" class="text-blue-600 hover:underline" target="_blank">https://preview.shorthand.com/FRXxRxaWOMqIt3v2</a></p>
            </section>

            <!-- User research -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">User Research</h2>
                
                <h3 class="text-2xl font-bold text-gray-900 mt-8 mb-4">Target Audience</h3>
                <p class="text-gray-700 leading-relaxed">My target audience for this project is composed of three primary groups, all of whom are at a key transition point in their housing journey in Pittsburgh:</p>
                <ul class="list-disc list-inside text-gray-700 leading-relaxed mt-4 space-y-2">
                    <li><strong>Newcomer Students:</strong> Individuals who are new to Pittsburgh and need initial guidance on where to live.</li>
                    <li><strong>Second-Year Students:</strong> Students who have completed their first year, whose housing contracts may be ending, and are looking to move to a new neighborhood that better suits their established routines and preferences.</li>
                    <li><strong>Recent Graduates:</strong> Individuals who have finished their studies and have accepted jobs in Pittsburgh. Their needs are shifting from a student-centric lifestyle to that of a working professional, and they are looking for a neighborhood that reflects this change.</li>
                </ul>

                <h3 class="text-2xl font-bold text-gray-900 mt-8 mb-4">Interview Script</h3>
                <p class="text-gray-700 leading-relaxed mb-4">The following interview script is designed to validate the core assumptions of my project. The goals are to ensure the chosen preferences are comprehensive, the data visualizations are clear and insightful, and the overall story is effective and impactful for the target audience.</p>
                <div class="overflow-x-auto my-6">
                    <table class="min-w-full bg-white border border-gray-300">
                        <thead class="bg-gray-100">
                            <tr>
                                <th class="py-2 px-4 border-b text-left">Goal</th>
                                <th class="py-2 px-4 border-b text-left">Questions to Ask</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="py-2 px-4 border-b align-top font-semibold">Understand if the project addresses all key needs.</td>
                                <td class="py-2 px-4 border-b align-top">"When you think about choosing a neighborhood, what are the top three things you look for? I've focused on safety, restaurants/entertainment, and transportation to CMU. Is there anything significant I might be missing?"</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b align-top font-semibold">Evaluate if the visualizations are clear and insightful.</td>
                                <td class="py-2 px-4 border-b align-top">"Looking at these charts, do they give you a clear and useful comparison between the neighborhoods? For example, does the crime chart make you feel more or less safe about a certain area? Do the restaurant and entertainment charts give you a good sense of the neighborhood's vibe?"</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b align-top font-semibold">Assess if the storyboard flow is effective and impactful.</td>
                                <td class="py-2 px-4 border-b align-top">"As you go through this story, does the flow make sense? Does it help you think differently about how you'd choose a neighborhood? What's the main takeaway for you after seeing this?"</td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <h3 class="text-2xl font-bold text-gray-900 mt-8 mb-4">Interview Findings</h3>
                 <div class="overflow-x-auto my-6">
                    <table class="min-w-full bg-white border border-gray-300 text-sm">
                        <thead class="bg-gray-100">
                            <tr>
                                <th class="py-3 px-4 border-b text-left font-bold">Question</th>
                                <th class="py-3 px-4 border-b text-left font-bold">Interview 1 (Recent Graduate)</th>
                                <th class="py-3 px-4 border-b text-left font-bold">Interview 2 (2nd Year Student)</th>
                                <th class="py-3 px-4 border-b text-left font-bold">Interview 3 (Newcomer Student)</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="py-2 px-4 border-b align-top font-semibold">What is missing from the preference in this storyboard?</td>
                                <td class="py-2 px-4 border-b align-top">I’m expecting to see the rental cost per neighborhood.</td>
                                <td class="py-2 px-4 border-b align-top">I think safety and transportation are in my top three, but also a grocery store and how close it is to my apartment are very important to me.</td>
                                <td class="py-2 px-4 border-b align-top">I would love to see what type of food exists in the area. For example, if there are 20 restaurants, what types of restaurants are they?</td>
                            </tr>
                             <tr>
                                <td class="py-2 px-4 border-b align-top font-semibold">In the visuals, what works for you and what not so much?</td>
                                <td class="py-2 px-4 border-b align-top">I love the categories on safety, restaurants and bars, and art and entertainment. The transportation to campus is not clear — maybe use a side-by-side bar chart for frequency and distance.</td>
                                <td class="py-2 px-4 border-b align-top">I think the radar chart at the end is very good because it gives me the option to choose based on multiple preferences, not just one.</td>
                                <td class="py-2 px-4 border-b align-top">I’m not sure I understand the meaning of “two restaurants per 100 people” or “two and a half.” Does it mean too many people per restaurant? Maybe just showing the total number of restaurants would be clearer.</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b align-top font-semibold">How does the storyboard work for you? Did you love the flow of it?</td>
                                <td class="py-2 px-4 border-b align-top">The placement of personas is not very insightful. It feels like you’re telling me who I am before showing preferences. It would be better if personas came at the end, after seeing preferences.</td>
                                <td class="py-2 px-4 border-b align-top">I would love to see images for each chart. I think they would guide me in understanding what we are focusing on in terms of preferences.</td>
                                <td class="py-2 px-4 border-b align-top">You mentioned the correlation between being successful in studies and having a neighborhood that fits your needs, but it felt a little out of nowhere. I can see how it might encourage people, but maybe we could find data to support that so it’s more persuasive.</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>

            <!-- Identified changes for Part III -->
            <section class="mt-8">
                 <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Identified Changes for Part III</h2>
                <div class="overflow-x-auto my-6">
                    <table class="min-w-full bg-white border border-gray-300">
                        <thead class="bg-gray-100">
                            <tr>
                                <th class="py-2 px-4 border-b">Research Synthesis</th>
                                <th class="py-2 px-4 border-b">Anticipated Changes for Part III</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="py-2 px-4 border-b">Findings or observations from interviews</td>
                                <td class="py-2 px-4 border-b">Describe what, if any changes I anticipate making to address the observation.</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                            </tr>
                             <tr>
                                <td class="py-2 px-4 border-b">...add more rows as necessary</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <p class="text-gray-700 leading-relaxed">Text here!</p>
            </section>

             <!-- Personas Section -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Personas</h2>
                <div class="grid md:grid-cols-3 gap-8 mt-6">
                    <!-- Maya -->
                    <div class="border border-gray-200 rounded-lg p-6 shadow-md bg-gray-50 flex flex-col items-center">
                        <img src="images/maya 2.png" alt="Persona for Maya" class="w-36 h-64 rounded-lg mb-4 border-2 border-blue-500 object-cover">
                        <h4 class="text-xl font-bold text-center mb-1">Maya (Newcomer)</h4>
                        <p class="text-center text-sm text-gray-500 mb-4 flex-grow">Business student at Tepper, proud of her school. Loves bars and social campus events. Very athletic and enjoys group sports like running and pickleball.</p>
                        <div class="text-sm w-full">
                            <p class="mb-2"><strong class="font-semibold text-gray-800">Top Preferences:</strong> Social Events on Campus, Restaurants & Bars</p>
                            <p><strong class="font-semibold text-gray-800">Second Preferences:</strong> Sports & Group Activities (running, pickleball)</p>
                        </div>
                    </div>
                    <!-- Li -->
                    <div class="border border-gray-200 rounded-lg p-6 shadow-md bg-gray-50 flex flex-col items-center">
                        <img src="images/li 2.png" alt="Persona for Li" class="w-36 h-64 rounded-lg mb-4 border-2 border-green-500 object-cover">
                        <h4 class="text-xl font-bold text-center mb-1">Li (First-Year → Second Year)</h4>
                        <p class="text-center text-sm text-gray-500 mb-4 flex-grow">International student, very focused on studies. Loves swimming at the campus pool and enjoys eating out occasionally. Staying close to campus is very important to her.</p>
                        <div class="text-sm w-full">
                            <p class="mb-2"><strong class="font-semibold text-gray-800">Top Preferences:</strong> Safety & Security, Proximity to Campus</p>
                            <p><strong class="font-semibold text-gray-800">Second Preferences:</strong> Dining out once or twice a month</p>
                        </div>
                    </div>
                    <!-- Alex -->
                    <div class="border border-gray-200 rounded-lg p-6 shadow-md bg-gray-50 flex flex-col items-center">
                        <img src="images/Alex 2.png" alt="Persona for Alex" class="w-36 h-64 rounded-lg mb-4 border-2 border-purple-500 object-cover">
                        <h4 class="text-xl font-bold text-center mb-1">Alex (Graduate Student)</h4>
                        <p class="text-center text-sm text-gray-500 mb-4 flex-grow">Arts Management student. Loves live music, bars, and the coffee culture. Active in a campus dance club and enjoys the city’s cultural scene.</p>
                        <div class="text-sm w-full">
                            <p class="mb-2"><strong class="font-semibold text-gray-800">Top Preferences:</strong> Arts & Entertainment, Live Music & Bars</p>
                            <p><strong class="font-semibold text-gray-800">Second Preferences:</strong> Coffee Shops, Restaurants & Cafés</p>
                        </div>
                    </div>
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
                         <p class="text-gray-400 text-sm"><em>List any references I used here.</em></p>
                    </div>
                     <div>
                        <h3 class="font-bold text-lg mb-2">AI Acknowledgements</h3>
                        <p class="text-gray-400 text-sm"><em>If I used AI to help me complete this assignment (within the parameters of the instruction and course guidelines), I will detail my use of AI for this assignment here.</em></p>
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



