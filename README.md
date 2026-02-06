<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Price Tracker - Live</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">
    <nav class="bg-blue-600 p-4 text-white flex justify-between items-center shadow-lg">
        <span class="font-bold">PriceTracker SaaS</span>
        <a href="admin.html" class="bg-white text-blue-600 px-3 py-1 rounded-full text-sm font-bold shadow">
            + Add Product
        </a>
    </nav>
    <div class="container mx-auto p-4 text-center">
        <h1 class="text-xl font-bold my-4">आज की बेहतरीन डील्स</h1>
        <div id="product-list" class="grid grid-cols-1 gap-4">
             <div class="bg-white p-4 shadow rounded flex justify-between items-center border-l-4 border-blue-500">
                <div class="text-left">
                    <h2 class="font-bold text-lg text-gray-800">Yamaha Crux (Used)</h2>
                    <p class="text-green-600 font-bold text-xl">₹12,000</p>
                </div>
                <button class="bg-orange-500 text-white px-4 py-2 rounded font-bold shadow-md">Check Deal</button>
             </div>
        </div>
    </div>
</body>
</html>
