<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.16/dist/tailwind.min.css" rel="stylesheet">
 <title>Hostel Management System</title>
 <style>
    /* Custom CSS */
    .card:hover {
      transform: scale(1.05);
      transition: transform 0.3s ease-in-out;
    }

    @keyframes pulse {
      0% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.05);
      }
      100% {
        transform: scale(1);
      }
    }

    .card:hover .icon {
      animation: pulse 1.5s infinite;
    }
 </style>
</head>
<body class="bg-gray-100">
 <div class="container mx-auto px-4 py-8">
    <header class="text-center mb-8">
      <h1 class="text-4xl font-bold text-blue-600">Hostel Management System</h1>
    </header>

    <main class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
      <a href="/students" class="card bg-white shadow-md rounded-md p-5 transition duration-300 ease-in-out">
        <div class="icon text-4xl text-blue-600">
          <i class="fas fa-user-graduate"></i>
        </div>
        <h2 class="text-xl font-bold mb-5 mt-4">Students</h2>
        <p>Manage student information and their stay in the hostel.</p>
      </a>

      <a href="/rooms" class="card bg-white shadow-md rounded-md p-5 transition duration-300 ease-in-out">
        <div class="icon text-4xl text-blue-600">
          <i class="fas fa-bed"></i>
        </div>
        <h2 class="text-xl font-bold mb-5 mt-4">Rooms</h2>
        <p>Record, manage, and assign rooms to students.</p>
      </a>

      <a href="/fees" class="card bg-white shadow-md rounded-md p-5 transition duration-300 ease-in-out">
        <div class="icon text-4xl text-blue-600">
          <i class="fas fa-money-bill-wave"></i>
        </div>
        <h2 class="text-xl font-bold mb-5 mt-4">Fees</h2>
        <p>Record, manage, and generate fee reports.</p>
      </a>
    </main>

    <footer class="mt-8 text-center">
      <p>&copy; Hostel Management System 2023</p>
    </footer>
 </div>
</body>
</html>