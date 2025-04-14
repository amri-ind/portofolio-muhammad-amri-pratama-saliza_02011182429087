<script>
    document.getElementById("lawForm").addEventListener("submit", function (e) {
      e.preventDefault();
      const event = document.getElementById("eventInput").value.toLowerCase();
      const responseArea = document.getElementById("responseArea");

      let response = "";

      // Simulasi AI memberikan jawaban hukum
      if (event.includes("tanah") && event.includes("notaris")) {
        response = "⚖️ Menurut hukum pertanahan, transaksi jual beli tanah wajib dilakukan dengan akta notaris (PPAT). Tanpa akta, jual beli tidak memiliki kekuatan hukum penuh.";
      } else if (event.includes("cerai") || event.includes("perceraian")) {
        response = "⚖️ Untuk proses perceraian, Anda harus mengajukan gugatan ke Pengadilan Agama (untuk Muslim) atau Pengadilan Negeri (untuk Non-Muslim).";
      } else if (event.includes("utang") || event.includes("pinjam")) {
        response = "⚖️ Perjanjian utang-piutang sebaiknya dibuat secara tertulis dan ditandatangani kedua pihak. Jika terjadi sengketa, Anda dapat mengajukan gugatan perdata.";
      } else {
        response = "⚖️ Terima kasih atas pertanyaannya. AI Advokat kami sedang mengembangkan pemahaman untuk topik ini. Silakan konsultasi lebih lanjut dengan advokat manusia.";
      }

      responseArea.innerText = response;
    });
  </script>
