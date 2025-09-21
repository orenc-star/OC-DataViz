
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Critique by Design - Oren's Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        blockquote {
            border-left: 4px solid #e5e7eb;
            padding-left: 1rem;
            margin-left: 1rem;
            font-style: italic;
            color: #4b5563;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Header and Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-10">
        <nav class="container mx-auto px-6 py-4">
            <ul class="flex justify-center space-x-4 md:space-x-8 text-sm md:text-base">
                <li><a href="../index.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Home</a></li>
                <li><a href="../dataviz-examples.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Data Viz Examples</a></li>
                <li><a href="myFolder/critique-by-design.html" class="text-blue-600 font-bold border-b-2 border-blue-600 pb-1">Critique by Design</a></li>
                <li><a href="../final-project-part-one.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project I</a></li>
                <li><a href="../final-project-part-two.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project II</a></li>
                <li><a href="../final-project-part-three.html" class="text-gray-600 hover:text-blue-600 transition duration-300">Final Project III</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">
        <div class="max-w-4xl mx-auto bg-white p-8 rounded-lg shadow-lg">

            <!-- Page Title and Intro -->
            <section class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">My Critique Journey</h1>
                <p class="text-gray-700 leading-relaxed max-w-2xl mx-auto">In this page, I will take you through the process of how I explored, critiqued, and redesigned a data visualization.</p>
            </section>

            <!-- Divider -->
            <hr class="my-8 border-gray-200">

            <!-- Step 1 -->
            <section class="mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Step 1: Finding the Chart</h2>
                <p class="mb-4 text-gray-700 leading-relaxed">I started by looking at <a href="https://makeovermonday.co.uk/" class="text-blue-600 hover:underline">makeovermonday.co.uk</a>, which collects different data visualizations. One title in particular caught my eye: <a href="https://dribbble.com/shots/10539609-Drink-and-Dating-Infographics" class="text-blue-600 hover:underline">Drinking & Dating</a>, and I felt curious about the theme.</p>
            </section>

            <!-- Step 2 -->
            <section class="mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Step 2: Looking at the Visualization</h2>
                <p class="mb-4 text-gray-700 leading-relaxed">Here is the chart I found:</p>
                <img src="Chart 1.webp" alt="The original chart: Drinking & Dating Infographics" class="w-full rounded-lg shadow-md border border-gray-200 mb-4" onerror="this.onerror=null;this.src='https://placehold.co/800x500?text=Chart+1+Image';">
                <p class="text-gray-700 leading-relaxed">At first glance, I thought the designer did a good job. The chart looked engaging, colorful, and well-structured. But as I continued to review it, I felt that something was confusing me. I decided to read the article the designer mentioned as inspiration: <a href="https://www.zoosk.com/date-mix/dating-data/dating-data-study-drinks-dating/" class="text-blue-600 hover:underline">Data Study: Drinking & Dating</a>. While the design was visually appealing, I felt that the chart only picked a very narrow piece of the article’s data and didn’t serve the audience as well as it could. The article had more layers about drinking culture and dating behavior that the visualization didn’t capture.</p>
            </section>
            
            <!-- Writing the Critique -->
            <section class="mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Writing the Critique</h2>
                <p class="mb-4 text-gray-700 leading-relaxed">This is the critique I wrote after analyzing the visualization across usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement:</p>
                
                <blockquote class="mb-6">
                    <p class="font-semibold">Describe your overall observations about the data visualization here. What stood out to you? What did you find worked really well? What didn't work well?</p>
                    <p>What stood out to me first was how strong the design feels at a first glance. The visualization works well in terms of aesthetics, intuitiveness, and engagement. It uses three complementary colors, clean icons that aren’t overwhelming, and a clear structure that flows from the title to highlights to the chart. I especially loved the wine glass filling up the heart to represent percentage; it was a smart, visually pleasing touch. These details make the chart look approachable and attractive right away.</p>
                    <p class="mt-2">At the same time, there were several things that didn’t work well. I didn’t like the heart icon showing 65% as completely full, since that’s misleading. I also didn’t love the bar chart setup. It gives the impression that men’s and women’s percentages are complementary and should add up to 100, when they are actually independent. The colors for men and women are also similar, making it harder to separate between them. Finally, the subtitle felt off, since it included data source information (number of surveys and messages) rather than giving useful framing for the chart.</p>
                </blockquote>
                 <blockquote class="mb-6">
                    <p class="font-semibold">Who is the primary audience for this tool? Do you think this visualization is effective for reaching that audience? Why or why not?</p>
                    <p>While the visualization clearly targets a general lifestyle or dating-curious audience, it ultimately fails to commit to serving any particular segment within that group in a meaningful way. It tries to do too much without a clear narrative: blending behavioral insights about alcohol with patterns of drink preferences during dates, without distinguishing between the two. As a result, it doesn’t offer enough depth or clarity for viewers who might be interested in either topic. Those looking to understand how normalized drinking is within dating culture get surface-level data without meaningful framing, while those hoping to find out what people typically order on dates receive only fragmented, hard-to-interpret comparisons. That said, the graphic still performs well on the surface. Its visual style and structure are accessible and attention-grabbing, which does align with the casual tone of the article. It may pull in readers, but once someone tries to make sense of the message or apply the insights to their own dating experience, the lack of thematic focus becomes a barrier.</p>
                </blockquote>
                 <blockquote class="mb-6">
                    <p class="font-semibold">Based on your critique, what do you think you'll try to focus on in your redesign? Any ideas or inspiration for how you can make a better data visualization? What are you excited to try next?</p>
                    <p>First, I want to focus on the theme. I want to highlight the types of drinks people order most often on dates and build the visualization around that. My goal is to make the discussion about drinks more clear and connected to the different aspects mentioned in the article. To do that, I will get rid of the material about alcoholic behavior in general and instead focus on showing what people actually drink on their dates, so the audience has a clear and direct takeaway.</p>
                    <p class="mt-2">What I think I will do better is move away from the two horizontal bar charts and instead show the differences more directly. This will make it clear where there are big gender differences and where men and women are actually similar. I am very excited to try this because I have not used this type of chart before, and I think it will be a strong way to visualize comparisons between two measures. I also want to make men and women stand out with different colors, add images for the drinks themselves, and separate alcoholic from non-alcoholic. That way, the alcoholic aspect is still present but in the background, while the main focus stays on the drinks people order during dates.</p>
                </blockquote>
                <p class="text-gray-700 leading-relaxed">As you can see in my critique, my main conclusion was that the chart lacked focus. It tried to mix two themes: alcohol behavior in dating and the specific drinks people order, but didn’t give enough to either.</p>
            </section>

            <!-- Step 3 -->
            <section class="mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Step 3: Sketching a Solution</h2>
                <p class="text-gray-700 leading-relaxed mb-4">I decided to concentrate on one topic and one dataset that I believed would be more engaging: which drinks people choose to order on their dates. My first redesign sketch focused on showing differences between men and women in drink preferences. I also separated alcoholic and non-alcoholic drinks to make the message clearer:</p>
                <img src="Chart 2.png" alt="First redesign sketch focusing on drink preference differences" class="w-full rounded-lg shadow-md border border-gray-200" onerror="this.onerror=null;this.src='https://placehold.co/800x500?text=Chart+2+Image';">
            </section>

            <!-- Step 4 -->
            <section class="mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Step 4: Testing and Iterating the Design</h2>
                <h3 class="text-2xl font-bold text-gray-900 mb-4">Rethinking the Audience</h3>
                <p class="text-gray-700 leading-relaxed mb-4">Once I built this version, I quickly saw that something was missing. It's useful to know that men prefer beer more than women, but emphasizing only the difference ignores the general popularity of each drink, which could also be valuable. This became clearer when I showed the graph to my father. He asked, "Who is the audience for this?" I initially said singles, but he suggested that bar owners and bartenders would be a better audience, since the insights would be more valuable to them. That feedback led me to switch to the side-by-side version.</p>
                <img src="Chart 3.png" alt="Side-by-side bar chart version" class="w-full rounded-lg shadow-md border border-gray-200 mb-8" onerror="this.onerror=null;this.src='https://placehold.co/800x500?text=Chart+3+Image';">
                
                <h3 class="text-2xl font-bold text-gray-900 mb-4">Refining the Palette</h3>
                <p class="text-gray-700 leading-relaxed mb-4">At this stage, I had not yet chosen colors. I asked my wife for feedback on the color palette. She said the use of blue for men and red for women felt too obvious and stereotypical, almost childish. She also expected something cleaner and softer. Based on her input, I switched to a more neutral and balanced palette:</p>
                <img src="Chart 4.png" alt="Version with a neutral and balanced color palette" class="w-full rounded-lg shadow-md border border-gray-200 mb-8" onerror="this.onerror=null;this.src='https://placehold.co/800x500?text=Chart+4+Image';">
                
                <p class="text-gray-700 leading-relaxed mb-4">But then she also said that this version lacked the playful, colorful feeling of the original. To balance this, I eliminated the gray tones and the heavy axis lines, and I added an image above the chart to bring back some character. This is the result:</p>
                <img src="Chart 5.jpg" alt="Final color version with added character image" class="w-full rounded-lg shadow-md border border-gray-200 mb-8" onerror="this.onerror=null;this.src='httpshttps://placehold.co/800x500?text=Chart+5+Image';">
                
                <h3 class="text-2xl font-bold text-gray-900 mb-4">Getting Feedback from Classmates</h3>
                <p class="text-gray-700 leading-relaxed mb-4">I showed the design to friends in class. Their first reaction was positive: they said they could quickly see the trend between men and women, especially with beer and wine. They also liked that I chose to separate alcoholic from non-alcoholic drinks. After a while, my classmates gave me three critical points that I knew I needed to address. The first was the unavoidable confusion around summing the numbers to 100%. This was fascinating to hear, because I had actually pointed out the same issue when critiquing the original designer’s chart. I thought I had avoided it in my own version, but I ended up falling into the same trap. That moment showed me how self-critique is not always enough, even when you know what to look out for.</p>
                <p class="text-gray-700 leading-relaxed mb-4">The second piece of feedback was about clarity of scope. They weren’t sure if the chart represented only first-date choices or drinks people typically order on dates in general. The last point concerned the icons I used as labels at the bottom of the chart. While some were clear, others were less recognizable, which forced them to rely on the text instead. They suggested that using real images might work better and make the visualization more immediately intuitive.</p>
                
                <h3 class="text-2xl font-bold text-gray-900 mb-4">Live Editing</h3>
                <p class="text-gray-700 leading-relaxed mb-4">Before responding to their other feedback, I tried on the fly to see if a different type of bar chart would solve the problem of people wanting to sum the percentages to 100. Since I was working with Gemini to create these charts, I had the valuable opportunity to edit the chart in just a minute and show them a new version of it immediately. This allowed me to capture their reactions to the updated chart right after they had given me their initial feedback (which I see as a useful use-case of AI):</p>
                <img src="Chart 6.png" alt="Live edited version with a different bar chart style" class="w-full rounded-lg shadow-md border border-gray-200 mb-4" onerror="this.onerror=null;this.src='https://placehold.co/800x500?text=Chart+6+Image';">
                <p class="text-gray-700 leading-relaxed">Still, when I showed them this new version, they preferred the first sketch. I asked if adding a multiple-choice survey style to the description under the title would make the numbers clearer, and they agreed it would help, which led me to a new way of thinking about how to address the first two pieces of feedback.</p>
            </section>
            
            <!-- Step 5 -->
            <section class="mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">Step 5: Building the Final Solution</h2>
                <p class="text-gray-700 leading-relaxed mb-4">While their advice was very simple, not to redesign the chart or change the type but just to add a short explanation, it led me to a deeper realization. A few well-chosen words in the description can completely shift how people interpret the numbers. In this case, the confusion came from not understanding the scope of the data. I appreciated that the original designer used the word “most popular” to frame the drink types, which already gives a helpful signal about preferences. Another helpful word is “typically,” which makes it clear that we’re talking about general dating behavior, not just first dates. And finally, the word “choices” reflects that the data comes from a selection of multiple options, not a single pick.</p>
                <p class="text-gray-700 leading-relaxed font-semibold">That’s why I chose to revise the title to: “Most popular types of drinks men and women order on dates, typically.”</p>
                <p class="text-gray-700 leading-relaxed font-semibold mt-2">And in the description below it, I added a clarifying line: “Based on a multiple-choice survey, showing the proportion of people who would order each drink versus those who would not.”</p>
                <p class="text-gray-700 leading-relaxed my-4">This small change helps eliminate the expectation that the numbers should sum to 100 and anchors the viewer in the right context from the beginning:</p>
<iframe src="Chart 7.html" class="w-full h-[700px] rounded-lg shadow-md border border-gray-200 mb-4" title="Final Chart Design"></iframe>                <p class="text-gray-700 leading-relaxed mt-4">The third piece of feedback I received was to use real images instead of the drink icons, since not all of the icons were immediately recognizable. While I didn’t fully adopt this suggestion, I responded by increasing the font size of the drink names. I felt that this change would make the labels more eye-catching and improve readability without requiring a complete shift in visual style.</p>
            </section>
            
            <!-- New Direction -->
             <section class="mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Exploring a New Direction</h2>
                <p class="text-gray-700 leading-relaxed mb-4">After completing my final result, I started exploring a new direction. I wanted to see how the chart might look with realistic drink elements instead of abstract bars. My idea was to place the drink types in two horizontal rows and use actual containers, like mugs or wine glasses, filled based on the percentage for men and women. Here is the beginning of it:</p>
                <img src="Image 8.png" alt="Exploration with realistic drink elements, attempt 1" class="w-full rounded-lg shadow-md border border-gray-200 mb-4" onerror="this.onerror=null;this.src='https://placehold.co/800x500?text=Chart+8+Image';">
                <img src="Image 9.png" alt="Exploration with realistic drink elements, attempt 2" class="w-full rounded-lg shadow-md border border-gray-200 mb-4" onerror="this.onerror=null;this.src='https://placehold.co/800x500?text=Chart+9+Image';">
                <p class="text-gray-700 leading-relaxed">I made these two initial attempts using AI, but it was challenging to generate accurate images. The model struggled to apply the correct fill levels, possibly due to how I described the concept.</p>
            </section>
            
            <!-- Reflection -->
            <section>
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Reflection</h2>
                <p class="text-gray-700 leading-relaxed mb-4">I enjoyed this process because I got to experience firsthand how easy it is to fall into the same design traps as the one you critique. Even when you're aware of certain problems, recreating a solution yourself often reveals how challenging they really are. It gave me a respect for designers and the compromises they have to make.</p>
                <p class="text-gray-700 leading-relaxed">This project also showed me how important it is to understand the context of the data and define your target audience from the start. It made me think more deeply about how design choices can shape interpretation, and how things like percentage could be confusing: especially when viewers instinctively try to sum values to 100%. I’m looking forward to trying new chart types in the future and finding creative ways to solve these problems.</p>
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
                        <ul class="text-gray-400 text-sm list-disc list-inside">
                            <li><a href="https://makeovermonday.co.uk/" class="hover:underline">Makeover Monday</a>. (n.d.). Retrieved September 19, 2025.</li>
                            <li>Zoosk. (n.d.). <a href="https://www.zoosk.com/date-mix/dating-data/dating-data-study-drinks-dating/" class="hover:underline">Data Study: Drinking & Dating</a>. The Date Mix.</li>
                            <li>Yur, A. (2020). <a href="https://dribbble.com/shots/10539609-Drink-and-Dating-Infographics" class="hover:underline">Drink and Dating Infographics</a>. Dribbble.</li>
                            <li>OpenAI. (2025). <a href="https://chat.openai.com/" class="hover:underline">ChatGPT</a>.</li>
                             <li>Google. (2025). <a href="https://gemini.google.com/" class="hover:underline">Gemini</a>.</li>
                        </ul>
                    </div>
                     <div>
                        <h3 class="font-bold text-lg mb-2">AI Acknowledgements</h3>
                        <p class="text-gray-400 text-sm">I used Gemini to design the graphs and to iterate on them after receiving feedback. I also used Gemini to generate the visual concepts shown in the exploration of a new direction for further research. I used ChatGPT to help record my thoughts, clean up my writing, and revise some of the paragraphs. Most of the content was based on my own input, with ChatGPT used primarily for clarity and polish.</p>
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


