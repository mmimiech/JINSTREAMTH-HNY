    </style>
</head>
<body>
    <div class="card">
        <h1>🎉 New year with JinstreamTH🎉 </h1>
        <p>Happy new year to our Team JinstreamTH💜</p>
        <p>ขอให้ลูกบ้านของจสต.มีความสุขกับมีรอยยิ้มเยอะๆมีวันที่ดีทุกวันเลย ขอให้สิ่งที่ตั้งใจอยู่สำเร็จแล้วก็ผ่านไปได้ด้วยดี(ซพเเล้วก็เป็นกลจให้นะคะ)ได้เติบโตอย่างที่ตั้งใจยามเหนื่อยก็ขอให้ได้รับอ้อมกอดอยู่เสมอ ขอให้ได้รับการปลอบใจที่อบอุ่น ได้เจอผู้ฟังที่ดี มีรอยยิ้มที่สดใส พบเจอแต่เรื่องราวที่ดีต่อหัวใจ cause you deserve all the best things 💐💐 ห่างไกลจากความสัมพันธ์ทึ่เป็นพิษ ได้พบคนที่อยู่เคียงข้างอย่างเสมอต้นเสมอปลายอย่างบังทัน กลุ่มคนที่เป็นเหมือนบ้านของเหล่าอาร์มี่เป็นพื้นที่ปลอดภัยให้กัน ขอให้ได้เจอบังทันครบทั้ง7คน อยู่ซัพพอร์ตพี่จินและเมมเบอร์อีก6คนไปด้วยกันนานๆนะคะ

✿ สุดท้ายนี้อย่าลืมยิ้มให้กับตัวเองเยอะๆ จงรักและภูมิใจกับการเป็นอยู่ของตัวเองให้มากๆ โอบกอดตัวเองไว้อย่างดีเสมอเมื่อต้องเจอเรื่องที่หนักอึ้งหัวใจ มอบสิ่งน่ารักเหล่านั้นให้กับตัวเธอเองในทุกวันนะคะ Happy new year ค่ะคนเก่งของจสต.</p>
        <input type="text" id="userMessage" placeholder="อยากบอกอะไรกับจสต.?">
        <button onclick="showMessage()">ส่งข้อความ</button>
        <div class="message" id="displayMessage"></div>
    </div>

    <script>
        function showMessage() {
            const input = document.getElementById('userMessage').value;
            const messageDiv = document.getElementById('displayMessage');
            if (input.trim() === "") {
                messageDiv.textContent = "กรุณาพิมพ์ข้อความก่อนนะ!";
                messageDiv.style.color = "Purple";
            } else {
                messageDiv.textContent = `ขอบคุณสำหรับข้อความ Have a nice day naka ARMY💜: "${input}" 🎉`;
                messageDiv.style.color = "#2e7d32";
            }
        }
    </script>
</body>
</html>
