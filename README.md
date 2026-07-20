<!-- แนะนำให้ลิงก์ฟอนต์ Google Fonts ไว้ใน ส่วน <head> ของโปรเจกต์เพื่อให้แสดงผลได้สมบูรณ์แบบ -->
<!-- <link rel="preconnect" href="https://fonts.googleapis.com"> -->
<!-- <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> -->
<!-- <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@400;700;900&family=Orbitron:wght@700;900&display=swap" rel="stylesheet"> -->

<header class="w-full max-w-4xl mx-auto p-1 mt-6 select-none font-['Kanit']">
  <!-- กล่องด้านนอกสุดทำหน้าที่สร้างขอบเรืองแสงแบบ Pulse (Neon Glow Layer) -->
  <div class="relative rounded-3xl p-[2px] bg-gradient-to-r from-cyan-500 via-amber-500 to-fuchsia-500 animate-pulse shadow-[0_0_25px_rgba(245,158,11,0.2)]">
    
    <!-- กล่องหลักสไตล์ Glassmorphism -->
    <div class="relative bg-slate-950/85 backdrop-blur-xl rounded-[22px] px-6 py-8 md:py-10 flex flex-col items-center justify-center border border-white/5 overflow-hidden">
      
      <!-- เอฟเฟกต์แสง Background Grid/Beam อารมณ์ Sci-Fi Arcade -->
      <div class="absolute inset-0 bg-[linear-gradient(to_right,#0f172a_1px,transparent_1px),linear-gradient(to_bottom,#0f172a_1px,transparent_1px)] bg-[size:4rem_4rem] [mask-image:radial-gradient(ellipse_60%_50%_at_50%_50%,#000_70%,transparent_100%)] opacity-30"></div>
      
      <!-- 1. Badge ด้านบน (Mini Glowing Tag) -->
      <div class="relative z-10 mb-4 flex items-center gap-1.5 px-3 py-1 rounded-full bg-cyan-950/60 border border-cyan-500/30 shadow-[0_0_10px_rgba(6,182,212,0.15)]">
        <span class="inline-block w-2 h-2 rounded-full bg-cyan-400 animate-ping"></span>
        <span class="text-[10px] md:text-xs font-['Orbitron'] font-bold tracking-widest text-cyan-400">
          👾 AI &amp; AR EDUCATIONAL GAME
        </span>
      </div>

      <!-- 2. หัวข้อใหญ่ (Gaming Gradient & Glow Text Effect) -->
      <h1 class="relative z-10 flex items-center justify-center flex-wrap gap-2 text-center text-3xl md:text-5xl lg:text-6xl font-['Orbitron'] font-black tracking-wider uppercase">
        <!-- ไอคอนซ้าย -->
        <span class="text-amber-400 drop-shadow-[0_0_8px_rgba(245,158,11,0.6)] animate-bounce text-2xl md:text-4xl">⚡</span>
        
        <!-- ข้อความหลัก ไล่เฉดสีทอง-ส้ม -->
        <span class="bg-gradient-to-r from-yellow-400 via-amber-300 to-orange-500 bg-clip-text text-transparent drop-shadow-[0_2px_8px_rgba(249,115,22,0.4)]">
          GAME-AI-ROUTINE-ENG
        </span>
        
        <!-- ไอคอนขวา -->
        <span class="text-amber-400 drop-shadow-[0_0_8px_rgba(245,158,11,0.6)] animate-bounce text-2xl md:text-4xl" style="animation-delay: 0.2s;">⚡</span>
      </h1>

      <!-- เส้นแบ่ง Neon Divider เพิ่มมิติ -->
      <div class="relative z-10 w-24 h-[3px] my-4 rounded-full bg-gradient-to-r from-transparent via-cyan-400 to-transparent shadow-[0_0_8px_rgba(34,211,238,0.8)]"></div>

      <!-- 3. คำอธิบายภาษาไทย (อ่านง่าย วรรณยุกต์ไม่จมด้วย leading-relaxed) -->
      <p class="relative z-10 text-center text-base md:text-xl font-bold text-cyan-300/90 tracking-wide drop-shadow-[0_1px_4px_rgba(0,0,0,0.8)] leading-relaxed max-w-md md:max-w-xl">
        เพื่อการศึกษาและเรียนรู้ปัญญาประดิษฐ์
      </p>
      
      <!-- ตกแต่งมุมกล่องสไตล์ UI เกม (Tech Corners) -->
      <div class="absolute top-3 left-3 w-3 h-3 border-t-2 border-l-2 border-cyan-500/40"></div>
      <div class="absolute top-3 right-3 w-3 h-3 border-t-2 border-r-2 border-cyan-500/40"></div>
      <div class="absolute bottom-3 left-3 w-3 h-3 border-b-2 border-l-2 border-cyan-500/40"></div>
      <div class="absolute bottom-3 right-3 w-3 h-3 border-b-2 border-r-2 border-cyan-500/40"></div>

    </div>
  </div>
</header>
