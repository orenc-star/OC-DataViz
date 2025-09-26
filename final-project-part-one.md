
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project Part I - Oren's Portfolio</title>
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
                <li><a href="final-project-part-one.html" class="text-blue-600 font-bold border-b-2 border-blue-600 pb-1">Final Project I</a></li>
                <li><a href="final-project-part-two.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project II</a></li>
                <li><a href="final-project-part-three.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project III</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">
        <div class="max-w-6xl mx-auto bg-white p-8 rounded-lg shadow-lg">

            <!-- Page Title -->
            <section class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Final Project Part I</h1>
            </section>
            
            <!-- Outline Section -->
            <section>
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Outline</h2>
                <p class="text-gray-700 leading-relaxed mb-6">My project aims to be a practical guide for students trying to decide where to live in Pittsburgh. Whether they are new to the city, looking to move after their first year, or planning to stay after graduation, this guide will help them find a neighborhood that aligns with their personal preferences and lifestyle needs. The goal is to support their academic and professional success by helping them find a living situation where they can thrive.</p>
                <p class="text-gray-700 leading-relaxed mb-6">The project will focus on three key aspects that are often important to students: neighborhood safety, access to entertainment (like restaurants and bars), and the quality of public transportation, particularly its proximity to the Carnegie Mellon University campus. By presenting data on these factors, the guide will offer clear, preference-based recommendations. For example, if a student prioritizes safety, the guide will point them to the safest neighborhoods; if they value a vibrant social scene, it will highlight areas with the best entertainment options. The ultimate call to action is to empower students to make an informed decision based on what matters most to them.</p>

                <h3 class="text-2xl font-bold text-gray-900 mt-8 mb-4">Project Structure & Story Arc</h3>
                <p class="text-gray-700 leading-relaxed mb-6">My story will follow a clear narrative structure designed to guide students from a common, relatable problem to a specific, actionable solution.</p>
                <ol class="list-decimal list-inside text-gray-700 leading-relaxed space-y-4">
                    <li>
                        <strong>The Hook: A Universal Question.</strong> The story begins by posing a question familiar to every student in Pittsburgh: "Where is the best place for me to live?" This section will acknowledge that this question is relevant for new arrivals, students moving between academic years, and recent graduates deciding whether to stay in the city.
                    </li>
                    <li>
                        <strong>The Premise: Popularity Isn't Everything.</strong> I will introduce the four most popular student neighborhoods, establishing them as common choices. However, the narrative will quickly pivot to the central idea: while popular, these neighborhoods have distinct characteristics, and the "best" choice depends entirely on individual priorities.
                    </li>
                    <li>
                        <strong>The Analysis: Exploring Key Preferences.</strong> This is the core of the project, where data visualizations will be used to compare the four neighborhoods across three key categories:
                        <ul class="list-disc list-inside ml-6 mt-2 space-y-2">
                            <li><strong>Safety & Security:</strong> How do the neighborhoods compare in terms of crime rates, type of crime, and frequency?</li>
                            <li><strong>Entertainment & Amenities:</strong> Which areas offer the most options for restaurants, grocery shopping, and leisure activities like bars, museums, or shows?</li>
                            <li><strong>Transportation & Proximity:</strong> How efficient is the commute to the CMU campus? This will be measured by bus frequency and average travel time.</li>
                        </ul>
                    </li>
                    <li>
                        <strong>Call to Action: Direct Recommendations.</strong> After presenting the data for each category, this section will synthesize the findings into clear, direct recommendations. It will follow an "if-then" format, such as: "If your top priority is safety, Neighborhood X is your best choice." or "If you value a short commute above all else, consider Neighborhood Y."
                    </li>
                    <li>
                        <strong>The Resolution: An Empowered Decision.</strong> The story concludes by reiterating the project's main goal: to empower students with the data they need to make a smart, personalized decision about where to live, ultimately contributing to their success and well-being in Pittsburgh.
                    </li>
                </ol>
            </section>

            <!-- Initial Sketches Section -->
            <section class="mt-8">
                <h3 class="text-2xl font-bold text-gray-900 mb-4">Initial sketches</h3>
                <p class="text-gray-700 leading-relaxed mb-4">My first visualization will set the stage by showing where students currently live, based on preliminary data. This simple bar chart will highlight the most popular neighborhoods, such as Oakland North and Shadyside, providing a baseline before diving into the specific characteristics of each area. This chart directly addresses "The Premise" in my story arc, establishing the common choices before I analyze them in more detail.</p>
                <div class="my-6 p-6 border rounded-lg bg-gray-50 shadow-inner">
                    <h4 class="text-lg font-bold text-center mb-12 text-gray-800">Current Neighborhood Distribution for Students</h4>
                    <div class="flex justify-around items-end h-80 border-b-2 border-gray-200 pb-12">
                        <!-- Oakland North -->
                        <div class="w-12 bg-blue-500 rounded-t relative" style="height: 33.33%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">33.3%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Oakland North</div>
                        </div>
                        <!-- Shadyside -->
                        <div class="w-12 bg-blue-500 rounded-t relative" style="height: 25%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">25%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Shadyside</div>
                        </div>
                        <!-- Bloomfield -->
                        <div class="w-12 bg-blue-500 rounded-t relative" style="height: 16.67%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">16.7%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Bloomfield</div>
                        </div>
                        <!-- Downtown -->
                        <div class="w-12 bg-blue-500 rounded-t relative" style="height: 12.5%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">12.5%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Downtown</div>
                        </div>
                        <!-- Squirrel Hill South -->
                        <div class="w-12 bg-blue-500 rounded-t relative" style="height: 12.5%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">12.5%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Squirrel Hill South</div>
                        </div>
                    </div>
                </div>

                <p class="text-gray-700 leading-relaxed my-8">My second visualization will address the "Safety & Security" aspect of my analysis. This chart compares the percentage of reported criminal cases relative to the population in each neighborhood. The data reveals a dramatic difference, particularly for Downtown, which will be a key talking point in my story. This visual is designed to give students a clear, comparative look at how safe each area is considered to be.</p>

                <div class="my-6 p-6 border rounded-lg bg-gray-50 shadow-inner">
                    <h4 class="text-lg font-bold text-center mb-12 text-gray-800">Neighborhood Crime Comparison (% of cases per population)</h4>
                    <div class="flex justify-around items-end h-80 border-b-2 border-gray-200 pb-12">
                        <!-- North Oakland -->
                        <div class="w-12 bg-red-500 rounded-t relative" style="height: 5.0%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">0.06%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">North Oakland</div>
                        </div>
                        <!-- Squirrel Hill South -->
                        <div class="w-12 bg-red-500 rounded-t relative" style="height: 6.7%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">0.08%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Squirrel Hill South</div>
                        </div>
                         <!-- Shadyside -->
                        <div class="w-12 bg-red-500 rounded-t relative" style="height: 10.1%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">0.12%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Shadyside</div>
                        </div>
                        <!-- Bloomfield -->
                        <div class="w-12 bg-red-500 rounded-t relative" style="height: 13.4%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">0.16%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Bloomfield</div>
                        </div>
                        <!-- Downtown -->
                        <div class="w-12 bg-red-500 rounded-t relative" style="height: 100%;">
                            <div class="absolute -top-6 left-1/2 -translate-x-1/2 text-sm font-bold text-gray-600">1.19%</div>
                            <div class="absolute -bottom-8 w-auto text-center left-1/2 -translate-x-1/2 text-sm font-bold text-gray-700 whitespace-nowrap">Downtown</div>
                        </div>
                    </div>
                </div>

                <p class="text-gray-700 leading-relaxed my-8">The third sketch focuses on the "Entertainment & Amenities" preference, specifically the number of restaurants per 100 residents. This metric helps normalize for population differences and highlights areas with a high concentration of dining options. For students who value social dining, this chart clearly shows that Downtown, despite a lower residential population, offers the most options per capita.</p>
                <div class="my-6 p-6 border rounded-lg bg-gray-50 shadow-inner">
                    <h4 class="text-lg font-bold text-center mb-8 text-gray-800">Restaurants per 100 People</h4>
                    <div class="space-y-4">
                        <!-- Downtown -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">Downtown</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-green-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 100%;">2.5</div>
                            </div>
                        </div>
                        <!-- Squirrel Hill South -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">Squirrel Hill South</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-green-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 40%;">1.0</div>
                            </div>
                        </div>
                        <!-- Shadyside -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">Shadyside</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-green-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 40%;">1.0</div>
                            </div>
                        </div>
                        <!-- Bloomfield -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">Bloomfield</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-green-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 30%;">0.75</div>
                            </div>
                        </div>
                        <!-- North Oakland -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">North Oakland</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-green-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 20%;">0.5</div>
                            </div>
                        </div>
                    </div>
                </div>

                <p class="text-gray-700 leading-relaxed my-8">Continuing with amenities, this fourth visualization uses a simple bar chart to show the total number of entertainment venues (museums, galleries, theaters, etc.). This gives a straightforward look at which neighborhoods are cultural hubs. The data highlights Downtown as the clear leader for students who prioritize access to arts and nightlife.</p>
                <div class="my-6 p-6 border rounded-lg bg-gray-50 shadow-inner">
                    <h4 class="text-lg font-bold text-center mb-8 text-gray-800">Total Number of Entertainment Venues</h4>
                    <div class="space-y-4">
                        <!-- Downtown -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">Downtown</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-purple-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 100%;">100</div>
                            </div>
                        </div>
                        <!-- Shadyside -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">Shadyside</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-purple-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 45%;">45</div>
                            </div>
                        </div>
                         <!-- North Oakland -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">North Oakland</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-purple-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 30%;">30</div>
                            </div>
                        </div>
                        <!-- Squirrel Hill South -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">Squirrel Hill South</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-purple-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 20%;">20</div>
                            </div>
                        </div>
                        <!-- Bloomfield -->
                        <div class="flex items-center">
                            <div class="w-32 text-sm font-bold text-gray-700 text-right pr-4">Bloomfield</div>
                            <div class="flex-1 bg-gray-200 rounded-full h-6">
                                <div class="bg-purple-500 h-6 rounded-full text-right pr-2 text-white text-sm flex items-center justify-end" style="width: 15%;">15</div>
                            </div>
                        </div>
                    </div>
                </div>

                <p class="text-gray-700 leading-relaxed my-8">Finally, for the "Transportation & Proximity" analysis, this quadrant chart provides a more nuanced view by plotting commute time against bus frequency. This allows students to see the trade-offs between different neighborhoods. The top-left quadrant represents the ideal scenario: a short commute combined with high bus frequency. Neighborhoods like North Oakland and Bloomfield fall into this category, making them strong choices for students who prioritize an easy and reliable commute to campus.</p>
                 <div class="my-6 p-6 border rounded-lg bg-gray-50 shadow-inner">
                    <h4 class="text-lg font-bold text-center mb-8 text-gray-800">Transportation Analysis: Commute vs. Frequency</h4>
                     <div class="relative w-full h-96 pl-10 pr-4 pt-4 pb-10">
                        <!-- Y-Axis Labels -->
                        <div class="absolute left-0 top-0 bottom-10 flex flex-col justify-between">
                            <span class="text-xs text-gray-500">4</span>
                            <span class="text-xs text-gray-500">3</span>
                            <span class="text-xs text-gray-500">2</span>
                            <span class="text-xs text-gray-500">1</span>
                            <span class="text-xs text-gray-500">0</span>
                        </div>
                        <div class="absolute -left-4 top-1/2 -translate-y-1/2 -rotate-90 font-bold text-gray-600 text-sm">Bus Frequency (per 30 min)</div>

                        <!-- X-Axis Labels -->
                        <div class="absolute bottom-0 left-10 right-4 flex justify-between">
                            <span class="text-xs text-gray-500">0</span>
                            <span class="text-xs text-gray-500">5</span>
                            <span class="text-xs text-gray-500">10</span>
                            <span class="text-xs text-gray-500">15</span>
                            <span class="text-xs text-gray-500">20</span>
                            <span class="text-xs text-gray-500">25</span>
                            <span class="text-xs text-gray-500">30</span>
                        </div>
                        <div class="absolute -bottom-4 left-1/2 -translate-x-1/2 font-bold text-gray-600 text-sm">Commute Time to CMU (minutes)</div>
                        
                        <!-- Chart Area -->
                        <div class="relative w-full h-full border-l-2 border-b-2 border-gray-400">
                             <!-- Quadrant Labels -->
                            <div class="absolute top-2 left-2 text-gray-500 text-sm font-semibold">Ideal Commute</div>
                            <div class="absolute top-2 right-2 text-gray-500 text-sm font-semibold">Frequent but Far</div>
                            <div class="absolute bottom-2 left-2 text-gray-500 text-sm font-semibold">Close but Infrequent</div>
                            <div class="absolute bottom-2 right-2 text-gray-500 text-sm font-semibold">Challenging Commute</div>

                            <!-- Data Points -->
                            <!-- N. Oakland: 5min, 2 buses/30min -->
                            <div class="absolute w-4 h-4 bg-orange-500 rounded-full -m-2" style="bottom: 40%; left: 16.6%;"><span class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs font-bold whitespace-nowrap">N. Oakland</span></div>
                            <!-- Bloomfield: 10min, 3 buses/30min -->
                            <div class="absolute w-4 h-4 bg-orange-500 rounded-full -m-2" style="bottom: 60%; left: 33.3%;"><span class="absolute top-4 left-1/2 -translate-x-1/2 text-xs font-bold whitespace-nowrap">Bloomfield</span></div>
                            <!-- Shadyside: 15min, 1 bus/30min -->
                            <div class="absolute w-4 h-4 bg-orange-500 rounded-full -m-2" style="bottom: 20%; left: 50%;"><span class="absolute -bottom-6 left-1/2 -translate-x-1/2 text-xs font-bold whitespace-nowrap">Shadyside</span></div>
                            <!-- S. Hill South: 20min, 2 buses/30min -->
                            <div class="absolute w-4 h-4 bg-orange-500 rounded-full -m-2" style="bottom: 40%; left: 66.6%;"><span class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs font-bold whitespace-nowrap">S. Hill South</span></div>
                            <!-- Downtown: 30min, 4 buses/30min -->
                            <div class="absolute w-4 h-4 bg-orange-500 rounded-full -m-2" style="bottom: 80%; left: 100%;"><span class="absolute top-4 left-1/2 -translate-x-1/2 text-xs font-bold whitespace-nowrap">Downtown</span></div>
                        </div>
                    </div>
                </div>


            </section>

            <!-- The Data Section -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">The Data</h2>
                <blockquote class="my-4">
                    A couple of paragraphs that document my data source(s), and an explanation of how I plan on using my data.
                </blockquote>
                <p class="text-gray-700 leading-relaxed mb-6">Text here...</p>

                <blockquote class="my-4">
                     A link to the publicly-accessible datasets I plan on using, or a link to a copy of the data I've uploaded to my Github repository, Box account or other publicly-accessible location. Using a datasource that is already accessible is highly encouraged. If I anticipate using a data source other than something that would be publicly available I will talk to my instructor first.
                </blockquote>
                <div class="overflow-x-auto">
                    <table class="min-w-full bg-white border border-gray-300">
                        <thead class="bg-gray-100">
                            <tr>
                                <th class="py-2 px-4 border-b">Name</th>
                                <th class="py-2 px-4 border-b">URL</th>
                                <th class="py-2 px-4 border-b">Description</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                            </tr>
                            <tr>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                                <td class="py-2 px-4 border-b">&nbsp;</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>
            
            <!-- Method and Medium Section -->
            <section class="mt-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 border-b pb-2">Method and Medium</h2>
                <blockquote class="my-4">
                    In a few sentences, I should document how I plan on completing my final project.
                </blockquote>
                <p class="text-gray-700 leading-relaxed mb-4">Text here...</p>
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

