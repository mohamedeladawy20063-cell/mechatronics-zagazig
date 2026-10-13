<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>دليل قسم الميكاترونكس | هندسة الزقازيق الحكومية</title>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <!-- Google Font: Cairo -->
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Cairo', sans-serif; }
  </style>
</head>
<body class="bg-slate-900 text-slate-100 min-h-screen flex flex-col">

  <!-- Navigation Bar -->
  <nav class="bg-slate-800/80 backdrop-blur border-b border-slate-700 sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-4 py-3 flex justify-between items-center">
      <div class="flex items-center gap-3">
        <div class="bg-blue-600 text-white p-2 rounded-xl text-xl font-bold">
          <i class="fa-solid fa-gear"></i>
        </div>
        <div>
          <h1 class="font-bold text-lg leading-tight">ميكاترونكس الزقازيق</h1>
          <p class="text-xs text-slate-400">جامعة الزقازيق - هندسة حكومي</p>
        </div>
      </div>
      <div class="flex gap-4 text-sm font-semibold">
        <a href="#levels" class="hover:text-blue-400 transition">المستويات</a>
        <a href="#gpa" class="hover:text-blue-400 transition">حاسبة GPA</a>
        <a href="#about" class="hover:text-blue-400 transition">عن المنصة</a>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="max-w-6xl mx-auto px-4 py-12 text-center">
    <span class="bg-blue-500/10 text-blue-400 border border-blue-500/20 px-4 py-1.5 rounded-full text-sm font-semibold inline-block mb-4">
      <i class="fa-solid fa-graduation-cap ml-1"></i> المرجع الموحد لطلاب الميكاترونكس
    </span>
    <h2 class="text-3xl md:text-5xl font-extrabold mb-4 leading-tight">
      كل ما تحتاجه لرحلتك الدراسية في مكان واحد
    </h2>
    <p class="text-slate-400 max-w-2xl mx-auto mb-8 text-sm md:text-base">
      محاضرات، سكاشن، شيتات، ومراجعات الفاينل والميدتيرم لقسم هندسة الميكاترونكس بجميع الفرق الدراسية.
    </p>
  </header>

  <!-- Levels Section -->
  <section id="levels" class="max-w-6xl mx-auto px-4 py-8">
    <h3 class="text-2xl font-bold mb-6 flex items-center gap-2 border-r-4 border-blue-500 pr-3">
      اختر المستوى الدراسي
    </h3>
    
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
      
      <!-- Prep Level -->
      <div class="bg-slate-800 rounded-2xl p-6 border border-slate-700 hover:border-blue-500 transition shadow-lg flex flex-col justify-between">
        <div>
          <div class="text-3xl text-blue-400 mb-3"><i class="fa-solid fa-building-columns"></i></div>
          <h4 class="text-xl font-bold mb-1">السنة الإعدادية</h4>
          <p class="text-xs text-blue-400 font-semibold mb-2">Level 000</p>
          <p class="text-slate-400 text-sm mb-4">المواد الأساسية قبل التخصص والالتحاق بالأقسام.</p>
        </div>
        <div class="mt-4">
          <a href="https://drive.google.com" target="_blank" class="block text-center bg-blue-600 hover:bg-blue-700 text-white font-semibold py-2 rounded-xl transition">
            عرض المواد <i class="fa-solid fa-arrow-left mr-1"></i>
          </a>
        </div>
      </div>

      <!-- Level 100 -->
      <div class="bg-slate-800 rounded-2xl p-6 border border-slate-700 hover:border-blue-500 transition shadow-lg flex flex-col justify-between">
        <div>
          <div class="text-3xl text-blue-400 mb-3"><i class="fa-solid fa-microchip"></i></div>
          <h4 class="text-xl font-bold mb-1">الفرقة الأولى</h4>
          <p class="text-xs text-blue-400 font-semibold mb-2">Level 100</p>
          <p class="text-slate-400 text-sm mb-4">أساسيات الهندسة الكهربية، البرمجة، والرسم الميكانيكي.</p>
        </div>
        <div class="grid grid-cols-2 gap-2 mt-4">
          <a href="https://drive.google.com/drive/folders/1NX8W32Fzv9yvjSMKHgit6m8uMs5q3ug3?usp=drive_link" target="_blank" class="text-center bg-slate-700 hover:bg-blue-600 text-white text-sm font-semibold py-2 rounded-xl transition">
            📘 الترم الأول
          </a>
          <a href="https://drive.google.com/drive/folders/1Uhxspunek3ti3xlPtF7jZbKtS02cteQW?usp=drive_link" target="_blank" class="text-center bg-slate-700 hover:bg-blue-600 text-white text-sm font-semibold py-2 rounded-xl transition">
            📗 الترم الثاني
          </a>
        </div>
      </div>

      <!-- Level 200 -->
      <div class="bg-slate-800 rounded-2xl p-6 border border-slate-700 hover:border-blue-500 transition shadow-lg flex flex-col justify-between">
        <div>
          <div class="text-3xl text-blue-400 mb-3"><i class="fa-solid fa-cogs"></i></div>
          <h4 class="text-xl font-bold mb-1">الفرقة الثانية</h4>
          <p class="text-xs text-blue-400 font-semibold mb-2">Level 200</p>
          <p class="text-slate-400 text-sm mb-4">ديناميكا، إلكترونيات، وتصميم الأجزاء الميكانيكية.</p>
        </div>
        <div class="grid grid-cols-2 gap-2 mt-4">
          <a href="https://drive.google.com/drive/folders/1Dqks9hnUKobDluD_vSTXC_EGGqJGnWBF?usp=drive_link" target="_blank" class="text-center bg-slate-700 hover:bg-blue-600 text-white text-sm font-semibold py-2 rounded-xl transition">
            📘 الترم الأول
          </a>
          <a href="https://drive.google.com/drive/folders/1GdWb1TO3zvX2HAzUW5H19rT56_8iuZFA?usp=drive_link" target="_blank" class="text-center bg-slate-700 hover:bg-blue-600 text-white text-sm font-semibold py-2 rounded-xl transition">
            📗 الترم الثاني
          </a>
        </div>
      </div>

      <!-- Level 300 -->
      <div class="bg-slate-800 rounded-2xl p-6 border border-slate-700 hover:border-blue-500 transition shadow-lg flex flex-col justify-between">
        <div>
          <div class="text-3xl text-blue-400 mb-3"><i class="fa-solid fa-robot"></i></div>
          <h4 class="text-xl font-bold mb-1">الفرقة الثالثة</h4>
          <p class="text-xs text-blue-400 font-semibold mb-2">Level 300</p>
          <p class="text-slate-400 text-sm mb-4">أنظمة التحكم، الحساسات، والمشغلات الهيدروليكية.</p>
        </div>
        <div class="grid grid-cols-2 gap-2 mt-4">
          <a href="https://drive.google.com/drive/folders/1pivKU9SLuXPUAZep45akZtkAon5cqU4Q?usp=drive_link" target="_blank" class="text-center bg-slate-700 hover:bg-blue-600 text-white text-sm font-semibold py-2 rounded-xl transition">
            📘 الترم الأول
          </a>
          <a href="https://drive.google.com/drive/folders/1GlO5MPS8IgE6HkoROxHE81eHvEmiz9Ro?usp=drive_link" target="_blank" class="text-center bg-slate-700 hover:bg-blue-600 text-white text-sm font-semibold py-2 rounded-xl transition">
            📗 الترم الثاني
          </a>
        </div>
      </div>

      <!-- Level 400 -->
      <div class="bg-slate-800 rounded-2xl p-6 border border-slate-700 hover:border-blue-500 transition shadow-lg flex flex-col justify-between">
        <div>
          <div class="text-3xl text-blue-400 mb-3"><i class="fa-solid fa-rocket"></i></div>
          <h4 class="text-xl font-bold mb-1">الفرقة الرابعة</h4>
          <p class="text-xs text-blue-400 font-semibold mb-2">Level 400</p>
          <p class="text-slate-400 text-sm mb-4">الروبوتات، الأتمتة الصناعية، ومشاريع التخرج.</p>
        </div>
        <div class="grid grid-cols-2 gap-2 mt-4">
          <a href="https://drive.google.com/drive/folders/1OZmzyStjbk9Nip6LjNNzsbDG9glXCKqw?usp=drive_link" target="_blank" class="text-center bg-slate-700 hover:bg-blue-600 text-white text-sm font-semibold py-2 rounded-xl transition">
            📘 الترم الأول
          </a>
          <a href="https://drive.google.com/drive/folders/1v_sgsbmjzy3In8vd3qm-hH56v6oO8vdV?usp=drive_link" target="_blank" class="text-center bg-slate-700 hover:bg-blue-600 text-white text-sm font-semibold py-2 rounded-xl transition">
            📗 الترم الثاني
          </a>
        </div>
      </div>

    </div>
  </section>

  <!-- GPA Calculator Section -->
  <section id="gpa" class="max-w-4xl mx-auto px-4 py-12 w-full">
    <div class="bg-slate-800 border border-slate-700 rounded-2xl p-6 md:p-8">
      <h3 class="text-2xl font-bold mb-4 text-center">حاسبة المعدل التراكمي (GPA)</h3>
      <p class="text-slate-400 text-sm text-center mb-6">أدخل درجاتك وساعات المواد لحساب معدلك التراكمي</p>

      <div id="subjects-container" class="space-y-4 mb-6">
        <div class="flex gap-2 items-center">
          <input type="text" placeholder="اسم المادة" class="bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm w-1/2 focus:outline-none focus:border-blue-500">
          <select class="grade-select bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm w-1/4 focus:outline-none focus:border-blue-500">
            <option value="4.0">A+ / A</option>
            <option value="3.5">B+</option>
            <option value="3.0">B</option>
            <option value="2.5">C+</option>
            <option value="2.0">C</option>
            <option value="1.5">D+</option>
            <option value="1.0">D</option>
            <option value="0.0">F</option>
          </select>
          <input type="number" min="1" max="6" value="3" class="hours-input bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm w-1/4 focus:outline-none focus:border-blue-500" placeholder="الساعات">
        </div>
      </div>

      <div class="flex gap-3 mb-6">
        <button onclick="addSubject()" class="bg-slate-700 hover:bg-slate-600 text-white font-semibold px-4 py-2 rounded-xl text-sm transition">
          + إضافة مادة
        </button>
        <button onclick="calculateGPA()" class="bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-2 rounded-xl text-sm transition flex-grow">
          احسب المعدل
        </button>
      </div>

      <div class="bg-slate-900/80 rounded-xl p-4 text-center border border-slate-700">
        <span class="text-slate-400 text-sm">المعدل التراكمي:</span>
        <span id="gpa-result" class="text-3xl font-extrabold text-blue-400 block mt-1">--</span>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer id="about" class="bg-slate-800/50 border-t border-slate-800 mt-auto py-6 text-center text-slate-500 text-sm">
    <p>مبادرة طلابية غير رسمية - هندسة الزقازيق الحكومية</p>
    <p class="mt-1">صُنع بكل <i class="fa-solid fa-heart text-red-500"></i> لخدمة طلاب قسم الميكاترونكس</p>
  </footer>

  <!-- JavaScript Code -->
  <script>
    function addSubject() {
      const container = document.getElementById('subjects-container');
      const div = document.createElement('div');
      div.className = 'flex gap-2 items-center';
      div.innerHTML = `
        <input type="text" placeholder="اسم المادة" class="bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm w-1/2 focus:outline-none focus:border-blue-500">
        <select class="grade-select bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm w-1/4 focus:outline-none focus:border-blue-500">
          <option value="4.0">A+ / A</option>
          <option value="3.5">B+</option>
          <option value="3.0">B</option>
          <option value="2.5">C+</option>
          <option value="2.0">C</option>
          <option value="1.5">D+</option>
          <option value="1.0">D</option>
          <option value="0.0">F</option>
        </select>
        <input type="number" min="1" max="6" value="3" class="hours-input bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm w-1/4 focus:outline-none focus:border-blue-500" placeholder="الساعات">
      `;
      container.appendChild(div);
    }

    function calculateGPA() {
      const grades = document.querySelectorAll('.grade-select');
      const hours = document.querySelectorAll('.hours-input');

      let totalPoints = 0;
      let totalHours = 0;

      for (let i = 0; i < grades.length; i++) {
        const gradeVal = parseFloat(grades[i].value);
        const hourVal = parseFloat(hours[i].value) || 0;

        totalPoints += gradeVal * hourVal;
        totalHours += hourVal;
      }

      if (totalHours === 0) {
        document.getElementById('gpa-result').innerText = '0.00';
        return;
      }

      const gpa = (totalPoints / totalHours).toFixed(2);
      document.getElementById('gpa-result').innerText = gpa;
    }
  </script>
</body>
</html>