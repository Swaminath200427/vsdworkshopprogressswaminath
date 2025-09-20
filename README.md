<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swaminath-VSD Toolkit Installation</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Custom styles for details/summary dropdown arrow */
        details > summary {
            list-style: none;
        }
        details > summary::-webkit-details-marker {
            display: none;
        }
        details > summary::before {
            content: '▶';
            margin-right: 0.75rem;
            font-size: 0.8em;
            display: inline-block;
            transition: transform 0.2s ease-in-out;
        }
        details[open] > summary::before {
            transform: rotate(90deg);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 p-4 sm:p-8">

    <div class="max-w-4xl mx-auto bg-white rounded-xl shadow-lg overflow-hidden">
        <div class="p-6 sm:p-8">
            <h1 class="text-4xl font-bold text-gray-900 mb-6 border-b border-gray-200 pb-4">swaminath-vsd</h1>

            <details class="border-2 border-gray-200 rounded-lg bg-white transition-shadow hover:shadow-md">
                <summary class="cursor-pointer bg-gray-50 hover:bg-gray-100 p-5 text-xl font-bold text-gray-700 select-none">
                    Day 0 - Tools Installation
                </summary>
                <div class="p-6 border-t border-gray-200">

                    <!-- Yosys Section -->
                    <div class="mb-10">
                        <h2 class="text-2xl font-semibold text-gray-800 mb-3">Yosys</h2>
                        <p class="mb-4 text-gray-600">Installation from source for the latest version. This method ensures you have the most up-to-date features.</p>
                        <pre class="bg-gray-900 text-white rounded-lg p-4 text-sm font-mono overflow-x-auto"><code>$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make
$ sudo make install</code></pre>
                        <img class="mt-4 rounded-lg shadow-md border border-gray-200 w-full max-w-xl mx-auto" alt="Yosys output" src="yosys version and installation.png" onerror="this.onerror=null;this.src='https://placehold.co/600x150?text=Yosys+Output';">
                    </div>

                    <!-- Icarus Verilog Section -->
                    <div class="mb-10">
                        <h2 class="text-2xl font-semibold text-gray-800 mb-3">Icarus Verilog</h2>
                        <p class="mb-4 text-gray-600">Simple installation using the standard package manager.</p>
                        <pre class="bg-gray-900 text-white rounded-lg p-4 text-sm font-mono overflow-x-auto"><code>$ sudo apt-get install iverilog</code></pre>
                        <img class="mt-4 rounded-lg shadow-md border border-gray-200 w-full max-w-2xl mx-auto" alt="Icarus Verilog installation command line output" src="iverilog installation.png" onerror="this.onerror=null;this.src='https://placehold.co/700x100?text=iverilog+Output';">
                    </div>

                    <!-- GTKWave Section -->
                    <div>
                        <h2 class="text-2xl font-semibold text-gray-800 mb-3">GTKWave</h2>
                        <p class="mb-4 text-gray-600">Installation using the standard package manager.</p>
                        <pre class="bg-gray-900 text-white rounded-lg p-4 text-sm font-mono overflow-x-auto"><code>$ sudo apt update
$ sudo apt install gtkwave</code></pre>
                        <img class="mt-4 rounded-lg shadow-md border border-gray-200 w-full max-w-xl mx-auto" alt="GTKWave installation command line output" src="gtkwaveformsinstallation.png" onerror="this.onerror=null;this.src='https://placehold.co/600x100?text=GTKWave+Output';">
                    </div>

                </div>
            </details>
        </div>
    </div>

</body>
</html>


