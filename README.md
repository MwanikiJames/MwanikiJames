<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>James Mwaniki | Finance & Data Professional</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fafafa;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        .emoji {
            font-size: 1.2em;
            margin-right: 5px;
        }
        .profile-pic {
            border: 5px solid white;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body class="gradient-bg min-h-screen">
    <div class="container mx-auto px-4 py-8 max-w-4xl">
        <!-- Header Section -->
        <header class="text-center mb-12" data-aos="fade-down">
            <div class="flex justify-center mb-6">
                <img src="http://static.photos/people/200x200/42" alt="James Mwaniki" class="profile-pic rounded-full w-32 h-32 object-cover">
            </div>
            <h1 class="text-4xl font-bold text-gray-800 mb-2">👋 Hi, I'm James Mwaniki</h1>
            <p class="text-xl text-gray-600 mb-4">
                <span class="emoji">🎓</span> <span class="font-medium">Economics & Finance Graduate</span> | 
                <span class="emoji">💼</span> <span class="font-medium">Aspiring Finance & Data Professional</span> | 
                <span class="emoji">📊</span> <span class="font-medium">Passionate about Data Analysis & Financial Modeling</span>
            </p>
            <div class="flex justify-center space-x-4">
                <a href="#about" class="px-4 py-2 bg-blue-500 text-white rounded-full hover:bg-blue-600 transition">About Me</a>
                <a href="#projects" class="px-4 py-2 bg-purple-500 text-white rounded-full hover:bg-purple-600 transition">Projects</a>
                <a href="#contact" class="px-4 py-2 bg-pink-500 text-white rounded-full hover:bg-pink-600 transition">Contact</a>
            </div>
        </header>

        <!-- About Section -->
        <section id="about" class="mb-12 bg-white rounded-xl p-6 shadow-md" data-aos="fade-up">
            <h2 class="text-2xl font-bold text-gray-800 mb-4 flex items-center">
                <span class="emoji">🔹</span> About Me
            </h2>
            <div class="grid md:grid-cols-2 gap-6">
                <div>
                    <p class="text-gray-700 mb-4">
                        I am an Economics and Finance graduate with hands-on experience at <span class="font-semibold text-blue-600">NSSF Kenya</span> and the <span class="font-semibold text-blue-600">National Treasury – Nyeri Central</span>.
                    </p>
                    <p class="text-gray-700">
                        I'm passionate about <span class="font-semibold">financial analysis, data-driven decision making, and leveraging technology</span> to solve economic and business challenges.
                    </p>
                </div>
                <div class="flex justify-center">
                    <img src="http://static.photos/office/320x240/10" alt="Office workspace" class="rounded-lg object-cover h-full">
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section class="mb-12 bg-white rounded-xl p-6 shadow-md" data-aos="fade-up">
            <h2 class="text-2xl font-bold text-gray-800 mb-4 flex items-center">
                <span class="emoji">🔹</span> Skills
            </h2>
            <div class="grid md:grid-cols-2 gap-6">
                <div>
                    <h3 class="text-lg font-semibold text-gray-700 mb-2 flex items-center">
                        <i data-feather="code" class="mr-2"></i> Programming & Data
                    </h3>
                    <ul class="list-disc pl-5 text-gray-700 space-y-1">
                        <li>Computer Packages Certificate (MS Word, Excel, PowerPoint, Access)</li>
                        <li>Microsoft Excel (data entry, pivot tables, basic analysis)</li>
                        <li>Basic data presentation and reporting</li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-lg font-semibold text-gray-700 mb-2 flex items-center">
                        <i data-feather="dollar-sign" class="mr-2"></i> Finance Tools
                    </h3>
                    <ul class="list-disc pl-5 text-gray-700 space-y-1">
                        <li>Investment analysis</li>
                        <li>Financial modeling & forecasting</li>
                        <li>Budgeting & expenditure analysis</li>
                        <li>Economic research & policy evaluation</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="mb-12" data-aos="fade-up">
            <h2 class="text-2xl font-bold text-gray-800 mb-6 flex items-center">
                <span class="emoji">🔹</span> Projects
            </h2>
            <div class="grid md:grid-cols-2 gap-6">
                <!-- Project 1 -->
                <div class="bg-white rounded-xl p-6 shadow-md card-hover transition duration-300">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-100 p-3 rounded-full mr-4">
                            <i data-feather="file-text" class="text-blue-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800">Housing Program Critique Report</h3>
                    </div>
                    <p class="text-gray-700 mb-4">Policy and economic evaluation of housing programs</p>
                    <a href="https://github.com/MwanikiJames/Housing-Program-Critique" class="text-blue-500 hover:text-blue-700 flex items-center">
                        <i data-feather="github" class="mr-2"></i> View on GitHub
                    </a>
                </div>
                
                <!-- Project 2 -->
                <div class="bg-white rounded-xl p-6 shadow-md card-hover transition duration-300">
                    <div class="flex items-center mb-4">
                        <div class="bg-purple-100 p-3 rounded-full mr-4">
                            <i data-feather="calculator" class="text-purple-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800">NSSF Benefits Calculator</h3>
                    </div>
                    <p class="text-gray-700 mb-4">Pension/benefits simulation in Python or Excel (coming soon)</p>
                    <span class="text-gray-500 flex items-center">
                        <i data-feather="clock" class="mr-2"></i> Coming soon
                    </span>
                </div>
            </div>
        </section>

        <!-- Experience Section -->
        <section class="mb-12 bg-white rounded-xl p-6 shadow-md" data-aos="fade-up">
            <h2 class="text-2xl font-bold text-gray-800 mb-4 flex items-center">
                <span class="emoji">🔹</span> Experience
            </h2>
            <div class="space-y-6">
                <div>
                    <h3 class="text-lg font-semibold text-gray-800">NSSF Kenya</h3>
                    <ul class="list-disc pl-5 text-gray-700 space-y-1 mt-2">
                        <li>Assisted in benefits processing, financial reporting, and client support</li>
                        <li>Gained exposure in social security fund management</li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-lg font-semibold text-gray-800">National Treasury – Nyeri Central (Attachment)</h3>
                    <ul class="list-disc pl-5 text-gray-700 space-y-1 mt-2">
                        <li>Worked on budget preparation and expenditure reports</li>
                        <li>Supported financial planning and compliance processes</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Education Section -->
        <section class="mb-12 bg-white rounded-xl p-6 shadow-md" data-aos="fade-up">
            <h2 class="text-2xl font-bold text-gray-800 mb-4 flex items-center">
                <span class="emoji">🔹</span> Education
            </h2>
            <div class="space-y-4">
                <div>
                    <h3 class="text-lg font-semibold text-gray-800">Kirinyaga University</h3>
                    <p class="text-gray-700">BSc. Economics & Finance</p>
                </div>
                <div>
                    <h3 class="text-lg font-semibold text-gray-800">Kenyatta High School</h3>
                    <p class="text-gray-700">B- (KCSE)</p>
                </div>
                <div>
                    <h3 class="text-lg font-semibold text-gray-800">Kirini Primary School</h3>
                    <p class="text-gray-700">361 Marks (KCPE)</p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="mb-12 bg-white rounded-xl p-6 shadow-md text-center" data-aos="fade-up">
            <h2 class="text-2xl font-bold text-gray-800 mb-4 flex items-center justify-center">
                <span class="emoji">🔹</span> Let's Connect
            </h2>
            <div class="flex flex-col items-center space-y-4">
                <a href="mailto:jamesnderitu947@gmail.com" class="flex items-center text-blue-600 hover:text-blue-800">
                    <i data-feather="mail" class="mr-2"></i> jamesnderitu947@gmail.com
                </a>
                <a href="https://www.linkedin.com/in/james-mwaniki-11a550379" target="_blank" class="flex items-center text-blue-600 hover:text-blue-800">
                    <i data-feather="linkedin" class="mr-2"></i> LinkedIn Profile
                </a>
                <a href="https://github.com/MwanikiJames" target="_blank" class="flex items-center text-blue-600 hover:text-blue-800">
                    <i data-feather="github" class="mr-2"></i> GitHub Projects
                </a>
            </div>
        </section>

        <!-- Quote Section -->
        <footer class="text-center py-6" data-aos="fade-up">
            <p class="text-gray-700 italic">⭐️ "Always learning, always building – with data, finance, and impact in mind."</p>
        </footer>
    </div>

    <script>
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });
        feather.replace();
    </script>
</body>
</html>
