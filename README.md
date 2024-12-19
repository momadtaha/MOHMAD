html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Learn Coding for Kids
  </title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&amp;display=swap" rel="stylesheet"/>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="manifest.json" rel="manifest"/>
 </head>
 <body class="bg-gradient-to-r from-blue-100 to-blue-300 text-gray-800 font-poppins">
  <header class="bg-blue-600 text-white text-center py-6 shadow-lg">
   <h1 class="text-4xl font-bold">
    Learn Coding for Kids
   </h1>
   <p class="text-lg mt-2">
    Fun and interactive lessons to start your coding journey!
   </p>
  </header>
  <main class="p-6">
   <section class="mb-12" id="lessons">
    <h2 class="text-3xl font-semibold mb-6">
     Interactive Lessons
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
     <div class="lesson bg-white p-4 rounded-lg shadow-md">
      <img alt="Illustration of a child learning about variables with a computer and code snippets" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/HSMhuQvyqVpsItaYYBphsMcbgNzNFlHA2DtBJEsC5kLXaHfJA.jpg" width="300"/>
      <h3 class="text-xl font-semibold mt-4">
       What are Variables?
      </h3>
      <p class="mt-2">
       Learn about storing information in your code.
      </p>
      <button class="mt-4 bg-blue-500 text-white py-2 px-4 rounded hover:bg-blue-700" onclick="startLesson('variables')">
       Start Lesson
      </button>
     </div>
     <div class="lesson bg-white p-4 rounded-lg shadow-md">
      <img alt="Illustration of a child learning about loops with a computer and code snippets" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/HzCPSf0Cw71NVyxe79ZDX1bVoa44b1TQxeNJ7iGx99QAT74nA.jpg" width="300"/>
      <h3 class="text-xl font-semibold mt-4">
       Understanding Loops
      </h3>
      <p class="mt-2">
       Repeat actions with loops!
      </p>
      <button class="mt-4 bg-blue-500 text-white py-2 px-4 rounded hover:bg-blue-700" onclick="startLesson('loops')">
       Start Lesson
      </button>
     </div>
     <div class="lesson bg-white p-4 rounded-lg shadow-md">
      <img alt="Illustration of a child learning about conditions with a computer and code snippets" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/qJ0bPiqqVRIBPlcTap8uzVXY4dfkiXzSydVFHfyF38e8S74nA.jpg" width="300"/>
      <h3 class="text-xl font-semibold mt-4">
       Conditions
      </h3>
      <p class="mt-2">
       Make decisions in your code.
      </p>
      <button class="mt-4 bg-blue-500 text-white py-2 px-4 rounded hover:bg-blue-700" onclick="startLesson('conditions')">
       Start Lesson
      </button>
     </div>
    </div>
   </section>
   <section class="text-center" id="games">
    <h2 class="text-3xl font-semibold mb-6">
     Coding Games
    </h2>
    <p class="mb-4">
     Practice coding by solving fun challenges!
    </p>
    <button class="bg-green-500 text-white py-2 px-6 rounded hover:bg-green-700" onclick="playGame()">
     Play Now
    </button>
   </section>
  </main>
  <footer class="bg-blue-600 text-white text-center py-4">
   <p>
    © 2024 Learn Coding for Kids
   </p>
  </footer>
  <script src="app.js">
  </script>
 </body>
</html>
