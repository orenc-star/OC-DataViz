<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Created by Design - A Data Visualization Project</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f1f5f9;
        }
        .nav-link-active {
            color: #0ea5e9;
            border-bottom: 2px solid #0ea5e9;
        }
    </style>
</head>
<body class="text-slate-800">

    <!-- Navigation Bar -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex-shrink-0">
                    <span class="text-xl font-bold text-slate-700">My Portfolio</span>
                </div>
                <div class="hidden sm:ml-6 sm:flex sm:space-x-8">
                    <a href="#" class="inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-sm font-medium text-slate-500 hover:border-slate-300 hover:text-slate-700">Home</a>
                    <a href="#" class="nav-link-active inline-flex items-center px-1 pt-1 text-sm font-medium">Created by Design</a>
                    <a href="#" class="inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-sm font-medium text-slate-500 hover:border-slate-300 hover:text-slate-700">About</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <!-- Hero Section -->
            <div class="text-center mb-12">
                <h1 class="text-4xl font-extrabold tracking-tight text-slate-900 sm:text-5xl md:text-6xl">Data Visualization Showcase</h1>
                <p class="mt-3 max-w-md mx-auto text-base text-slate-500 sm:text-lg md:mt-5 md:text-xl md:max-w-3xl">
                    Exploring compelling narratives through thoughtful and appealing data design.
                </p>
            </div>

            <!-- Project Section -->
            <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
                <div class="p-6 sm:p-8">
                    <h2 class="text-2xl font-bold text-slate-800">Project: What Are People Drinking on Dates?</h2>
                    <p class="mt-2 text-slate-600">This project is a redesign of an existing chart, focusing on creating a clearer and more engaging narrative about drink preferences on dates. The goal was to move beyond simple bar charts to a more direct and visually appealing comparison between genders, highlighting key differences and similarities in a clean, modern format.</p>
                </div>
                
                <!-- Embedded Chart using an iFrame -->
                <div class="w-full bg-slate-50 p-2 sm:p-4">
                     <iframe src="index.html" class="w-full h-[850px] border-0 rounded-lg" title="Drinks on a Date Visualization"></iframe>
                </div>
            </div>

        </div>
    </main>

    <!-- Footer -->
    <footer class="bg-slate-800 mt-16">
        <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-sm text-slate-400">&copy; 2025 My Portfolio. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
