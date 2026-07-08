<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<title>Vediko | Transparency & Lab Reports</title>

<!-- Tailwind -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<!-- Lucide -->
<script src="https://unpkg.com/lucide@latest"></script>

<script>
tailwind.config = {
theme:{
extend:{
colors:{
forest:"#1E4D3A",
sage:"#DCE7DD",
cream:"#FAF8F4",
border:"#ECEAE5",
text:"#3E3E3E"
},
fontFamily:{
heading:["Cormorant Garamond","serif"],
body:["Inter","sans-serif"]
},
boxShadow:{
soft:"0 20px 60px rgba(0,0,0,.06)",
card:"0 8px 30px rgba(0,0,0,.05)"
}
}
}
}
</script>

<style>

html{
scroll-behavior:smooth;
}

body{
background:#FAF8F4;
font-family:'Inter',sans-serif;
color:#3E3E3E;
overflow-x:hidden;
}

h1,h2,h3{
font-family:'Cormorant Garamond',serif;
}

.glass{
backdrop-filter:blur(18px);
background:rgba(255,255,255,.65);
border:1px solid rgba(255,255,255,.5);
}

.fade-up{
opacity:0;
transform:translateY(30px);
transition:1s ease;
}

.fade-up.show{
opacity:1;
transform:none;
}

.hero-gradient{
background:
radial-gradient(circle at top right,#E9F3EA 0%,transparent 40%),
radial-gradient(circle at bottom left,#F8F3E8 0%,transparent 35%);
}

.grid-bg{
background-image:
linear-gradient(rgba(30,77,58,.04) 1px,transparent 1px),
linear-gradient(90deg,rgba(30,77,58,.04) 1px,transparent 1px);

background-size:70px 70px;
}

.primary-btn{

transition:.35s;
}

.primary-btn:hover{

transform:translateY(-3px);

box-shadow:0 16px 40px rgba(30,77,58,.25);

}

.card-hover{

transition:.35s;

}

.card-hover:hover{

transform:translateY(-8px);

box-shadow:0 25px 60px rgba(0,0,0,.08);

}

.batch-pill{

background:#E8F4EA;

color:#1E4D3A;

padding:8px 16px;

border-radius:999px;

font-weight:600;

display:inline-flex;

align-items:center;

gap:8px;

}

.hero-ring{

position:absolute;

width:550px;

height:550px;

border-radius:999px;

background:radial-gradient(circle,rgba(30,77,58,.08),transparent);

filter:blur(10px);

right:-150px;

top:-120px;

z-index:0;

}

</style>

</head>

<body>

<!-- Background -->

<div class="fixed inset-0 hero-gradient grid-bg -z-10"></div>

<!-- NAVBAR -->

<header class="sticky top-0 z-50">

<nav class="glass border-b border-white/50">

<div class="max-w-7xl mx-auto px-6 lg:px-10">

<div class="h-20 flex items-center justify-between">

<div class="flex items-center gap-3">

<div class="w-11 h-11 rounded-full bg-forest text-white flex items-center justify-center font-bold">
V
</div>

<div>

<h3 class="text-2xl font-heading text-forest leading-none">
Vediko
</h3>

<p class="text-xs text-gray-500">
Transparency & Lab Reports
</p>

</div>

</div>

<div class="hidden md:flex items-center gap-8 text-sm">

<a href="#verify" class="hover:text-forest transition">
Verify Batch
</a>

<a href="#report" class="hover:text-forest transition">
Lab Report
</a>

<a href="#faq" class="hover:text-forest transition">
FAQ
</a>

</div>

<a href="#verify"
class="primary-btn bg-forest text-white px-6 py-3 rounded-full text-sm font-medium">

View Lab Report

</a>

</div>

</div>

</nav>

</header>

<!-- ========================= -->
<!-- HERO -->
<!-- ========================= -->

<section class="relative overflow-hidden">

<div class="hero-ring"></div>

<div class="max-w-7xl mx-auto px-6 lg:px-10 py-20 lg:py-32">

<div class="grid lg:grid-cols-2 gap-20 items-center">

<!-- LEFT -->

<div class="fade-up">

<div class="batch-pill mb-8">

🔬 Transparency You Can Verify

</div>

<h1 class="text-5xl lg:text-7xl text-forest leading-tight">

See the Proof Behind Every Vediko Product.

</h1>

<p class="mt-8 text-lg leading-8 text-gray-600 max-w-xl">

At Vediko, transparency is at the heart of everything we do. Every product is backed by batch-wise laboratory testing, giving you complete confidence in the quality, purity, and safety of what you bring home.

</p>

<div class="mt-10 flex flex-wrap gap-4">

<a href="#verify"
class="primary-btn bg-forest text-white px-8 py-4 rounded-full font-medium">

View Lab Report

</a>

</div>

</div>

<!-- RIGHT -->

<div class="fade-up relative">

<div class="bg-white rounded-[36px] shadow-soft p-8 border border-border">

<div class="aspect-[4/5] rounded-3xl bg-gradient-to-br from-white to-sage flex items-center justify-center">

<div class="w-72 h-[420px] rounded-[34px] bg-white shadow-card border border-gray-200 p-6 flex flex-col justify-between">

<div>

<div class="h-7 w-32 rounded bg-sage"></div>

<div class="mt-5 h-56 rounded-2xl bg-gradient-to-br from-green-100 to-white flex items-center justify-center text-7xl">

🌿

</div>

</div>

<div>

<div class="text-xs uppercase tracking-widest text-gray-500">

Product Label

</div>

<div class="mt-3 border rounded-xl p-4">

<div class="text-xs text-gray-500">

Batch Number

</div>

<div class="mt-2 inline-flex bg-green-100 text-forest font-semibold px-3 py-2 rounded-lg">

VG240615A

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</div>

</section>

<!-- ========= BATCH 2 STARTS BELOW ========= -->
<!-- ===================================== -->
<!-- Decorative Floating Background -->
<!-- ===================================== -->

<div class="pointer-events-none absolute inset-0 overflow-hidden">

  <div class="absolute top-20 left-10 w-56 h-56 bg-green-100/40 rounded-full blur-3xl"></div>

  <div class="absolute bottom-20 right-10 w-72 h-72 bg-emerald-100/30 rounded-full blur-3xl"></div>

  <div class="absolute top-1/2 left-1/2 w-80 h-80 bg-white/30 rounded-full blur-3xl -translate-x-1/2"></div>

</div>

<!-- Scroll Indicator -->

<div class="flex justify-center pb-12">

<div class="animate-bounce">

<div class="w-8 h-14 rounded-full border border-gray-300 flex justify-center">

<div class="w-1 h-3 bg-forest rounded-full mt-3 animate-pulse"></div>

</div>

</div>

</div>

<!-- Elegant Divider -->

<section class="relative py-20">

<div class="max-w-7xl mx-auto px-6">

<div class="flex items-center gap-6">

<div class="flex-1 h-px bg-gradient-to-r from-transparent via-gray-300 to-transparent"></div>

<div class="text-xs uppercase tracking-[0.3em] text-gray-400">

Verified Quality

</div>

<div class="flex-1 h-px bg-gradient-to-r from-transparent via-gray-300 to-transparent"></div>

</div>

</div>

</section>

<!-- ===================================== -->
<!-- SECTION 2 -->
<!-- TRUST CARDS -->
<!-- ===================================== -->

<section class="pb-28">

<div class="max-w-7xl mx-auto px-6 lg:px-10">

<div class="grid md:grid-cols-2 xl:grid-cols-4 gap-8">

<!-- CARD 1 -->

<div class="card-hover bg-white rounded-3xl p-8 shadow-card border border-border fade-up">

<div class="w-16 h-16 rounded-2xl bg-green-50 flex items-center justify-center mb-8">

<i data-lucide="flask-conical" class="w-8 h-8 text-forest"></i>

</div>

<h3 class="text-3xl font-heading text-forest">

Batch-wise Tested

</h3>

<p class="mt-5 text-gray-600 leading-7">

Every batch is independently tested.

</p>

</div>

<!-- CARD 2 -->

<div class="card-hover bg-white rounded-3xl p-8 shadow-card border border-border fade-up">

<div class="w-16 h-16 rounded-2xl bg-green-50 flex items-center justify-center mb-8">

<i data-lucide="file-text" class="w-8 h-8 text-forest"></i>

</div>

<h3 class="text-3xl font-heading text-forest">

Transparent Reports

</h3>

<p class="mt-5 text-gray-600 leading-7">

View reports for the exact batch you purchased.

</p>

</div>

<!-- CARD 3 -->

<div class="card-hover bg-white rounded-3xl p-8 shadow-card border border-border fade-up">

<div class="w-16 h-16 rounded-2xl bg-green-50 flex items-center justify-center mb-8">

<i data-lucide="building-2" class="w-8 h-8 text-forest"></i>

</div>

<h3 class="text-3xl font-heading text-forest">

Independent Lab Testing

</h3>

<p class="mt-5 text-gray-600 leading-7">

Every batch is tested by an independent laboratory.

</p>

</div>

<!-- CARD 4 -->

<div class="card-hover bg-white rounded-3xl p-8 shadow-card border border-border fade-up">

<div class="w-16 h-16 rounded-2xl bg-green-50 flex items-center justify-center mb-8">

<i data-lucide="leaf" class="w-8 h-8 text-forest"></i>

</div>

<h3 class="text-3xl font-heading text-forest">

Quality Verified

</h3>

<p class="mt-5 text-gray-600 leading-7">

Committed to quality, authenticity & transparency.

</p>

</div>

</div>

</div>

</section>

<!-- ===================================== -->
<!-- SECTION 3 -->
<!-- Process Timeline -->
<!-- ===================================== -->

<section class="py-28 bg-white border-y border-border">

<div class="max-w-7xl mx-auto px-6 lg:px-10">

<div class="text-center max-w-3xl mx-auto">

<h2 class="text-5xl lg:text-6xl text-forest font-heading">

Every Batch Is Verified Before It Reaches You.

</h2>

<p class="mt-8 text-lg text-gray-600 leading-8">

Every Vediko batch is independently tested based on its product category before it reaches you. Every report reflects our commitment to quality, authenticity, and transparency.

</p>

</div>

<!-- Timeline -->

<div class="mt-24 grid grid-cols-1 md:grid-cols-4 gap-10 relative">

<!-- Step 1 -->

<div class="text-center fade-up">

<div class="w-20 h-20 rounded-full bg-green-50 flex items-center justify-center mx-auto shadow-card">

<i data-lucide="leaf" class="w-9 h-9 text-forest"></i>

</div>

<h4 class="mt-6 text-2xl font-heading text-forest">

🌿 Product

</h4>

</div>

<!-- Step 2 -->

<div class="text-center fade-up">

<div class="w-20 h-20 rounded-full bg-green-50 flex items-center justify-center mx-auto shadow-card">

<i data-lucide="flask-conical" class="w-9 h-9 text-forest"></i>

</div>

<h4 class="mt-6 text-2xl font-heading text-forest">

🧪 Laboratory Testing

</h4>

</div>

<!-- Step 3 -->

<div class="text-center fade-up">

<div class="w-20 h-20 rounded-full bg-green-50 flex items-center justify-center mx-auto shadow-card">

<i data-lucide="clipboard-list" class="w-9 h-9 text-forest"></i>

</div>

<h4 class="mt-6 text-2xl font-heading text-forest">

📋 Report Generated

</h4>

</div>

<!-- Step 4 -->

<div class="text-center fade-up">

<div class="w-20 h-20 rounded-full bg-green-50 flex items-center justify-center mx-auto shadow-card">

<i data-lucide="house" class="w-9 h-9 text-forest"></i>

</div>

<h4 class="mt-6 text-2xl font-heading text-forest">

🏡 Delivered To You

</h4>

</div>

</div>

</div>

</section>

<!-- ========================= -->
<!-- BATCH 3 STARTS BELOW -->
<!-- ========================= -->
<!-- ===================================== -->
<!-- SECTION 4 -->
<!-- FIND YOUR PRODUCT'S LAB REPORT -->
<!-- ===================================== -->

<section id="verify" class="py-32">

  <div class="max-w-7xl mx-auto px-6 lg:px-10">

    <div class="grid lg:grid-cols-2 gap-16 items-center">

      <!-- LEFT -->

      <div class="fade-up">

        <h2 class="text-5xl lg:text-6xl font-heading text-forest leading-tight">
          Find Your Product's Lab Report
        </h2>

        <p class="mt-8 text-lg leading-8 text-gray-600 max-w-xl">
          Every Vediko product has a unique batch number. Use it to access the laboratory report for the exact batch you purchased.
        </p>

        <!-- Search Card -->

        <div class="mt-12 bg-white rounded-[30px] border border-border shadow-soft p-8">

          <label class="block text-sm font-medium text-gray-500 mb-4">
            Batch Number
          </label>

          <div class="flex flex-col sm:flex-row gap-4">

            <input
              id="batchInput"
              type="text"
              placeholder="Enter your batch number (e.g. VG240615A)"
              class="flex-1 rounded-2xl border border-gray-200 px-6 py-4 outline-none focus:ring-2 focus:ring-forest/20 focus:border-forest transition"
            />

            <button
              id="viewReportBtn"
              class="primary-btn bg-forest text-white rounded-2xl px-8 py-4 font-medium whitespace-nowrap">
              View Lab Report
            </button>

          </div>

          <!-- Search Result -->

          <div
            id="searchResult"
            class="hidden mt-8 rounded-2xl bg-green-50 border border-green-100 p-6">

            <div class="flex items-center gap-3">

              <div class="w-12 h-12 rounded-full bg-white flex items-center justify-center shadow">

                <i data-lucide="badge-check" class="w-6 h-6 text-green-700"></i>

              </div>

              <div>

                <p class="font-semibold text-forest">
                  Batch Verified
                </p>

                <p class="text-sm text-gray-600">
                  Click below to view the laboratory report.
                </p>

              </div>

            </div>

            <button
              class="mt-6 bg-forest text-white rounded-xl px-6 py-3 font-medium">
              Open Report
            </button>

          </div>

        </div>

      </div>

      <!-- RIGHT -->

      <div class="fade-up">

        <div class="bg-white rounded-[34px] border border-border shadow-soft p-8">

          <h3 class="text-4xl font-heading text-forest">
            Need help finding your batch number?
          </h3>

          <!-- Product Label -->

          <div class="mt-10 rounded-[28px] border border-border bg-gradient-to-br from-white to-sage p-8">

            <div class="mx-auto w-72 rounded-[28px] bg-white border border-gray-200 shadow-card p-6">

              <div class="h-8 w-32 rounded bg-sage"></div>

              <div class="mt-5 h-56 rounded-2xl bg-gradient-to-br from-green-100 to-white flex items-center justify-center text-7xl">
                🌿
              </div>

              <div class="mt-6 space-y-3">

                <div class="flex justify-between text-sm">
                  <span class="text-gray-500">MRP</span>
                  <span>₹499</span>
                </div>

                <div class="flex justify-between text-sm">
                  <span class="text-gray-500">MFG</span>
                  <span>15 Jun 2024</span>
                </div>

                <div class="flex justify-between text-sm">
                  <span class="text-gray-500">Best Before</span>
                  <span>12 Months</span>
                </div>

                <!-- Batch Highlight -->

                <div class="mt-6 rounded-xl border-2 border-dashed border-forest bg-green-50 p-4">

                  <div class="text-xs uppercase tracking-wide text-gray-500">
                    Batch Number
                  </div>

                  <div class="mt-2 text-xl font-bold text-forest">
                    VG240615A
                  </div>

                </div>

              </div>

            </div>

          </div>

          <p class="mt-8 text-gray-600 leading-7">
            You'll find it on your product label, usually near the MRP, Manufacturing Date, or Best Before Date.
          </p>

        </div>

      </div>

    </div>

  </div>

</section>

<!-- ============================ -->
<!-- BATCH 4 STARTS BELOW -->
<!-- ============================ -->
<!-- ===================================== -->
<!-- SECTION 5 -->
<!-- WHAT'S INSIDE YOUR LAB REPORT -->
<!-- ===================================== -->

<section id="report" class="py-32 bg-white border-y border-border">

    <div class="max-w-7xl mx-auto px-6 lg:px-10">

        <div class="text-center max-w-3xl mx-auto fade-up">

            <h2 class="text-5xl lg:text-6xl font-heading text-forest">
                What's Inside Your Lab Report
            </h2>

            <p class="mt-8 text-lg leading-8 text-gray-600">
                Your lab report contains everything you need to verify the quality of your Vediko product.
            </p>

        </div>

        <div class="grid lg:grid-cols-2 gap-20 mt-24">

            <!-- LEFT -->

            <div class="grid sm:grid-cols-2 gap-6">

                <!-- Card 1 -->

                <div class="card-hover bg-cream rounded-3xl border border-border p-8 fade-up">

                    <div class="w-14 h-14 rounded-2xl bg-green-50 flex items-center justify-center mb-6">

                        <i data-lucide="package" class="w-7 h-7 text-forest"></i>

                    </div>

                    <h3 class="text-2xl font-heading text-forest">

                        Product Details

                    </h3>

                    <p class="mt-4 text-gray-600 leading-7">

                        Confirms the product and batch you purchased.

                    </p>

                </div>

                <!-- Card 2 -->

                <div class="card-hover bg-cream rounded-3xl border border-border p-8 fade-up">

                    <div class="w-14 h-14 rounded-2xl bg-green-50 flex items-center justify-center mb-6">

                        <i data-lucide="flask-conical" class="w-7 h-7 text-forest"></i>

                    </div>

                    <h3 class="text-2xl font-heading text-forest">

                        Tests Performed

                    </h3>

                    <p class="mt-4 text-gray-600 leading-7">

                        Shows the quality checks carried out for that batch.

                    </p>

                </div>

                <!-- Card 3 -->

                <div class="card-hover bg-cream rounded-3xl border border-border p-8 fade-up">

                    <div class="w-14 h-14 rounded-2xl bg-green-50 flex items-center justify-center mb-6">

                        <i data-lucide="clipboard-list" class="w-7 h-7 text-forest"></i>

                    </div>

                    <h3 class="text-2xl font-heading text-forest">

                        Test Results

                    </h3>

                    <p class="mt-4 text-gray-600 leading-7">

                        Displays the results of each quality check.

                    </p>

                </div>

                <!-- Card 4 -->

                <div class="card-hover bg-cream rounded-3xl border border-border p-8 fade-up">

                    <div class="w-14 h-14 rounded-2xl bg-green-50 flex items-center justify-center mb-6">

                        <i data-lucide="building-2" class="w-7 h-7 text-forest"></i>

                    </div>

                    <h3 class="text-2xl font-heading text-forest">

                        Laboratory Details

                    </h3>

                    <p class="mt-4 text-gray-600 leading-7">

                        Shows which independent laboratory tested your product.

                    </p>

                </div>

                <!-- Card 5 -->

                <div class="card-hover sm:col-span-2 bg-cream rounded-3xl border border-border p-8 fade-up">

                    <div class="w-14 h-14 rounded-2xl bg-green-50 flex items-center justify-center mb-6">

                        <i data-lucide="badge-check" class="w-7 h-7 text-forest"></i>

                    </div>

                    <h3 class="text-2xl font-heading text-forest">

                        Batch Verification

                    </h3>

                    <p class="mt-4 text-gray-600 leading-7">

                        Confirms the report belongs to your product's batch.

                    </p>

                </div>

            </div>

            <!-- RIGHT -->

            <div class="fade-up">

                <div class="relative bg-gradient-to-br from-white to-sage rounded-[36px] border border-border shadow-soft p-10">

                    <!-- Report -->

                    <div class="bg-white rounded-3xl shadow-card border border-border overflow-hidden">

                        <!-- Header -->

                        <div class="bg-green-50 border-b border-border px-8 py-5">

                            <div class="h-5 w-44 rounded bg-green-200"></div>

                        </div>

                        <!-- Body -->

                        <div class="p-8 space-y-5">

                            <div class="h-5 rounded bg-gray-100 blur-[1px]"></div>

                            <div class="h-5 rounded bg-gray-100 blur-[1px] w-5/6"></div>

                            <div class="h-5 rounded bg-gray-100 blur-[1px] w-4/6"></div>

                            <div class="border-t my-6"></div>

                            <div class="h-24 rounded bg-gray-100 blur-[1px]"></div>

                            <div class="h-5 rounded bg-gray-100 blur-[1px] w-2/3"></div>

                            <div class="h-5 rounded bg-gray-100 blur-[1px] w-1/2"></div>

                        </div>

                    </div>

                    <!-- Callouts -->

                    <div class="absolute -left-5 top-16 bg-white rounded-xl shadow-card px-4 py-2 text-sm font-medium border">

                        Product Name

                    </div>

                    <div class="absolute right-0 top-40 bg-white rounded-xl shadow-card px-4 py-2 text-sm font-medium border">

                        Batch Number

                    </div>

                    <div class="absolute -left-4 bottom-40 bg-white rounded-xl shadow-card px-4 py-2 text-sm font-medium border">

                        Test Parameter

                    </div>

                    <div class="absolute right-6 bottom-24 bg-white rounded-xl shadow-card px-4 py-2 text-sm font-medium border">

                        Result

                    </div>

                    <div class="absolute left-16 -bottom-4 bg-white rounded-xl shadow-card px-4 py-2 text-sm font-medium border">

                        Laboratory

                    </div>

                </div>

            </div>

        </div>

    </div>

</section>

<!-- ========================== -->
<!-- BATCH 5 STARTS BELOW -->
<!-- ========================== -->
<!-- ===================================== -->
<!-- SECTION 6 -->
<!-- NATURE MAKES EVERY BATCH UNIQUE -->
<!-- ===================================== -->

<section class="relative py-32 overflow-hidden">

    <!-- Background Blobs -->

    <div class="absolute top-0 left-0 w-72 h-72 bg-green-100/30 rounded-full blur-3xl"></div>
    <div class="absolute bottom-0 right-0 w-80 h-80 bg-emerald-100/20 rounded-full blur-3xl"></div>

    <div class="relative max-w-7xl mx-auto px-6 lg:px-10">

        <div class="grid lg:grid-cols-2 gap-20 items-center">

            <!-- LEFT -->

            <div class="fade-up">

                <span class="inline-flex items-center px-5 py-2 rounded-full bg-green-50 text-forest font-medium text-sm mb-8">
                    Natural Variations
                </span>

                <h2 class="text-5xl lg:text-6xl font-heading text-forest leading-tight">
                    Nature Makes Every Batch Unique.
                </h2>

                <p class="mt-8 text-lg leading-8 text-gray-600 max-w-xl">
                    Vediko products are made from real ingredients, so slight variations between batches are completely natural. Factors like season, harvest conditions, and sourcing can influence each batch while maintaining our commitment to quality, authenticity, and safety.
                </p>

            </div>

            <!-- RIGHT -->

            <div class="fade-up">

                <div class="relative rounded-[36px] bg-white border border-border shadow-soft p-10">

                    <!-- Circle -->

                    <div class="mx-auto relative w-[340px] h-[340px] rounded-full bg-gradient-to-br from-green-50 to-white flex items-center justify-center">

                        <!-- Center -->

                        <div class="w-36 h-36 rounded-full bg-forest text-white flex items-center justify-center shadow-xl">

                            <i data-lucide="leaf" class="w-14 h-14"></i>

                        </div>

                        <!-- Leaves -->

                        <div class="absolute top-2 left-1/2 -translate-x-1/2 bg-white shadow-card rounded-2xl p-4 border">
                            <i data-lucide="sprout" class="w-8 h-8 text-forest"></i>
                        </div>

                        <!-- Farm -->

                        <div class="absolute right-2 top-1/2 -translate-y-1/2 bg-white shadow-card rounded-2xl p-4 border">
                            <i data-lucide="trees" class="w-8 h-8 text-forest"></i>
                        </div>

                        <!-- Ingredients -->

                        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 bg-white shadow-card rounded-2xl p-4 border">
                            <i data-lucide="flower-2" class="w-8 h-8 text-forest"></i>
                        </div>

                        <!-- Quality -->

                        <div class="absolute left-2 top-1/2 -translate-y-1/2 bg-white shadow-card rounded-2xl p-4 border">
                            <i data-lucide="badge-check" class="w-8 h-8 text-forest"></i>
                        </div>

                    </div>

                    <!-- Bottom Stats -->

                    <div class="grid grid-cols-3 gap-5 mt-12">

                        <div class="rounded-2xl bg-green-50 p-5 text-center border border-green-100">

                            <i data-lucide="leaf" class="mx-auto w-7 h-7 text-forest mb-3"></i>

                            <p class="text-sm font-medium text-gray-700">
                                Natural Ingredients
                            </p>

                        </div>

                        <div class="rounded-2xl bg-green-50 p-5 text-center border border-green-100">

                            <i data-lucide="shield-check" class="mx-auto w-7 h-7 text-forest mb-3"></i>

                            <p class="text-sm font-medium text-gray-700">
                                Quality Checked
                            </p>

                        </div>

                        <div class="rounded-2xl bg-green-50 p-5 text-center border border-green-100">

                            <i data-lucide="flask-conical" class="mx-auto w-7 h-7 text-forest mb-3"></i>

                            <p class="text-sm font-medium text-gray-700">
                                Batch Tested
                            </p>

                        </div>

                    </div>

                </div>

            </div>

        </div>

    </div>

</section>

<!-- ===================================== -->
<!-- BATCH 6 STARTS BELOW -->
<!-- ===================================== -->
<!-- ===================================== -->
<!-- SECTION 7 -->
<!-- FAQ -->
<!-- ===================================== -->

<section id="faq" class="py-32 bg-white border-y border-border">

  <div class="max-w-5xl mx-auto px-6">

    <div class="text-center mb-20 fade-up">

      <h2 class="text-5xl lg:text-6xl font-heading text-forest">
        Frequently Asked Questions
      </h2>

    </div>

    <div class="space-y-5">

      <!-- FAQ 1 -->

      <div class="faq-item bg-cream rounded-3xl border border-border overflow-hidden shadow-card">

        <button
          class="faq-btn w-full flex justify-between items-center p-8 text-left">

          <span class="text-xl font-semibold text-forest">
            What will I find in my lab report?
          </span>

          <i data-lucide="plus" class="faq-icon w-6 h-6"></i>

        </button>

        <div class="faq-content hidden px-8 pb-8 text-gray-600 leading-8">

          Product details, batch number, tests performed, laboratory details, and test results for your batch.

        </div>

      </div>

      <!-- FAQ 2 -->

      <div class="faq-item bg-cream rounded-3xl border border-border overflow-hidden shadow-card">

        <button
          class="faq-btn w-full flex justify-between items-center p-8 text-left">

          <span class="text-xl font-semibold text-forest">

            Which Vediko products have lab reports?

          </span>

          <i data-lucide="plus" class="faq-icon w-6 h-6"></i>

        </button>

        <div class="faq-content hidden px-8 pb-8 text-gray-600 leading-8">

          All Vediko products are batch-tested, and lab reports are available for every batch.

        </div>

      </div>

      <!-- FAQ 3 -->

      <div class="faq-item bg-cream rounded-3xl border border-border overflow-hidden shadow-card">

        <button
          class="faq-btn w-full flex justify-between items-center p-8 text-left">

          <span class="text-xl font-semibold text-forest">

            Are Vediko products tested by an independent laboratory?

          </span>

          <i data-lucide="plus" class="faq-icon w-6 h-6"></i>

        </button>

        <div class="faq-content hidden px-8 pb-8 text-gray-600 leading-8">

          Yes. Every batch is independently tested before it is approved for sale.

        </div>

      </div>

      <!-- FAQ 4 -->

      <div class="faq-item bg-cream rounded-3xl border border-border overflow-hidden shadow-card">

        <button
          class="faq-btn w-full flex justify-between items-center p-8 text-left">

          <span class="text-xl font-semibold text-forest">

            I can't find my batch number or lab report. What should I do?

          </span>

          <i data-lucide="plus" class="faq-icon w-6 h-6"></i>

        </button>

        <div class="faq-content hidden px-8 pb-8 text-gray-600 leading-8">

          Check that you've entered the correct batch number. If you still need help, contact our support team.

        </div>

      </div>

    </div>

  </div>

</section>

<!-- ===================================== -->
<!-- FOOTER CTA -->
<!-- ===================================== -->

<section class="py-28">

<div class="max-w-5xl mx-auto px-6">

<div class="bg-gradient-to-br from-forest to-green-900 rounded-[42px] text-white text-center p-16 shadow-soft">

<h2 class="text-5xl font-heading">

Still Need Help?

</h2>

<p class="mt-6 text-lg text-green-100">

Can't find your report?

Contact our team and we'll help you verify your batch.

</p>

<a
href="#"
class="inline-flex mt-10 bg-white text-forest px-10 py-4 rounded-full font-semibold hover:scale-105 transition">

Contact Support

</a>

</div>

</div>

</section>

<!-- ===================================== -->
<!-- SIMPLE FOOTER -->
<!-- ===================================== -->

<footer class="border-t border-border py-10">

<div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center gap-5">

<div>

<h3 class="font-heading text-3xl text-forest">

Vediko

</h3>

<p class="text-gray-500 mt-1">

Transparency & Lab Reports

</p>

</div>

<p class="text-gray-500 text-sm">

© 2026 Vediko. All rights reserved.

</p>

</div>

</footer>

<!-- ===================================== -->
<!-- BATCH 7 STARTS BELOW -->
<!-- ===================================== -->
<!-- ===================================== -->
<!-- JAVASCRIPT -->
<!-- ===================================== -->

<script>

document.addEventListener("DOMContentLoaded",()=>{

    // ============================
    // Lucide Icons
    // ============================

    lucide.createIcons();

    // ============================
    // Fade Up Animation
    // ============================

    const observer=new IntersectionObserver((entries)=>{

        entries.forEach(entry=>{

            if(entry.isIntersecting){

                entry.target.classList.add("show");

            }

        });

    },{

        threshold:.15

    });

    document.querySelectorAll(".fade-up").forEach(el=>{

        observer.observe(el);

    });

    // ============================
    // FAQ Accordion
    // ============================

    const faqButtons=document.querySelectorAll(".faq-btn");

    faqButtons.forEach(btn=>{

        btn.addEventListener("click",()=>{

            const content=btn.nextElementSibling;
            const icon=btn.querySelector(".faq-icon");

            const isOpen=!content.classList.contains("hidden");

            document.querySelectorAll(".faq-content").forEach(item=>{
                item.classList.add("hidden");
            });

            document.querySelectorAll(".faq-icon").forEach(ic=>{
                ic.setAttribute("data-lucide","plus");
            });

            lucide.createIcons();

            if(!isOpen){

                content.classList.remove("hidden");

                icon.setAttribute("data-lucide","minus");

                lucide.createIcons();

            }

        });

    });

    // ============================
    // Batch Search Demo
    // ============================

    const input=document.getElementById("batchInput");
    const button=document.getElementById("viewReportBtn");
    const result=document.getElementById("searchResult");

    if(button){

        button.addEventListener("click",()=>{

            if(input.value.trim()===""){

                input.focus();

                input.classList.add("ring-2","ring-red-300");

                setTimeout(()=>{

                    input.classList.remove("ring-2","ring-red-300");

                },1200);

                return;

            }

            result.classList.remove("hidden");

            result.scrollIntoView({

                behavior:"smooth",
                block:"center"

            });

        });

    }

    // ============================
    // Card Hover Glow
    // ============================

    document.querySelectorAll(".card-hover").forEach(card=>{

        card.addEventListener("mouseenter",()=>{

            card.style.boxShadow="0 25px 60px rgba(30,77,58,.10)";

        });

        card.addEventListener("mouseleave",()=>{

            card.style.boxShadow="";

        });

    });

});

</script>

</body>
</html>
<!-- ===================================== -->
<!-- BACK TO TOP BUTTON -->
<!-- ===================================== -->

<button
id="backToTop"
class="fixed bottom-8 right-8 z-50 w-14 h-14 rounded-full bg-forest text-white shadow-xl opacity-0 invisible transition-all duration-300 hover:scale-110 hover:shadow-2xl">

<i data-lucide="arrow-up" class="w-6 h-6 mx-auto"></i>

</button>

<style>

/* Premium Scrollbar */

::-webkit-scrollbar{
width:10px;
}

::-webkit-scrollbar-track{
background:#FAF8F4;
}

::-webkit-scrollbar-thumb{
background:#1E4D3A;
border-radius:999px;
border:2px solid #FAF8F4;
}

::-webkit-scrollbar-thumb:hover{
background:#2b6951;
}

/* Better Focus */

button:focus,
input:focus,
a:focus{
outline:3px solid rgba(30,77,58,.15);
outline-offset:3px;
}

/* Reduce Motion */

@media(prefers-reduced-motion:reduce){

*{
scroll-behavior:auto!important;
animation:none!important;
transition:none!important;
}

}

/* Better Mobile */

@media(max-width:768px){

h1{
font-size:3rem!important;
}

h2{
font-size:2.3rem!important;
}

section{
padding-top:5rem!important;
padding-bottom:5rem!important;
}

}

</style>

<script>

// =========================
// Back To Top
// =========================

const topBtn=document.getElementById("backToTop");

window.addEventListener("scroll",()=>{

if(window.scrollY>500){

topBtn.classList.remove("opacity-0","invisible");

}else{

topBtn.classList.add("opacity-0","invisible");

}

});

topBtn.addEventListener("click",()=>{

window.scrollTo({

top:0,

behavior:"smooth"

});

});

// Refresh icons

lucide.createIcons();

</script>

</body>
</html>
