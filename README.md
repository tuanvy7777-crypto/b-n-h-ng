<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Cafe túi Tuấn Vỹ — Cafe túi lọc nguyên chất, chuẩn vị quán</title>
  <meta name="description" content="Cafe túi lọc nguyên chất Tuấn Vỹ — rang mới mỗi tuần, pha nhanh 30 giây. Hương đậm, hậu ngọt, 100% hạt thật. Mua combo tiết kiệm, freeship hôm nay.">
  <meta name="keywords" content="cafe túi, cafe túi lọc, cafe rang mới, cafe nguyên chất, cafe tiện lợi">
  <meta name="author" content="Tuấn Vỹ">

  <!-- OpenGraph -->
  <meta property="og:title" content="Cafe túi Tuấn Vỹ — Pha 30 giây, chuẩn vị quán">
  <meta property="og:description" content="Rang mới mỗi tuần, 100% hạt nguyên chất. Ly cafe ngon trong 30 giây.">
  <meta property="og:type" content="website">
  <meta property="og:locale" content="vi_VN">

  <!-- Basic styling (mobile-first) -->
  <style>
    :root{
      --bg:#fffaf6; /* warm beige */
      --accent:#d35400; /* CTA orange */
      --accent-dark:#b24400;
      --brown:#6b3f26;
      --muted:#6f6f6f;
      --card:#fff;
      --container:1100px;
      --max-width:1200px;
      --radius:12px;
      --shadow:0 6px 24px rgba(27,24,22,0.08);
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    html,body{height:100%;margin:0;background:var(--bg);color:var(--brown);}
    .container{max-width:var(--container);margin:0 auto;padding:24px;}
    header{padding:20px 0;display:flex;align-items:center;justify-content:space-between}
    .brand{display:flex;gap:12px;align-items:center}
    .brand img{height:48px;width:48px;border-radius:8px;object-fit:cover}
    .brand h1{font-size:18px;margin:0}
    nav a{margin-left:18px;color:var(--brown);text-decoration:none;font-weight:600}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr;gap:20px;align-items:center;padding:28px 0}
    .hero-inner{background:linear-gradient(180deg, rgba(255,255,255,0.6), rgba(255,255,255,0.6));padding:24px;border-radius:14px;box-shadow:var(--shadow)}
    .hero h2{font-size:28px;margin:0 0 12px;line-height:1.05}
    .hero p{margin:0 0 18px;color:var(--muted)}
    .cta-row{display:flex;gap:12px;flex-wrap:wrap}
    .btn{background:var(--accent);color:#fff;padding:12px 18px;border-radius:10px;border:0;font-weight:700;cursor:pointer}
    .btn.secondary{background:transparent;color:var(--brown);border:2px solid rgba(107,63,38,0.08)}

    /* Layout columns for larger screens */
    @media(min-width:900px){
      .hero{grid-template-columns:1fr 460px}
      .hero h2{font-size:36px}
    }

    /* Benefits */
    .grid-3{display:grid;grid-template-columns:1fr;gap:12px;margin:20px 0}
    .benefit{background:var(--card);padding:18px;border-radius:12px;box-shadow:var(--shadow)}
    .benefit h3{margin:0 0 8px}
    .benefit p{margin:0;color:var(--muted)}
    @media(min-width:900px){.grid-3{grid-template-columns:repeat(3,1fr)}}

    /* Testimonials */
    .testimonials{margin:28px 0}
    .test-slider{display:flex;gap:12px;overflow:hidden}
    .testimonial{min-width:260px;background:var(--card);padding:16px;border-radius:10px;box-shadow:var(--shadow)}
    .testimonial p{margin:0 0 10px;color:var(--muted)}
    .testimonial .who{font-weight:700;font-size:14px}

    /* Pricing */
    .pricing{display:grid;grid-template-columns:1fr;gap:12px;margin:18px 0}
    .price-card{background:linear-gradient(180deg,#fff,#fff);padding:18px;border-radius:12px;box-shadow:var(--shadow);display:flex;flex-direction:column;gap:8px}
    .price-row{display:flex;justify-content:space-between;align-items:center}
    @media(min-width:900px){.pricing{grid-template-columns:repeat(3,1fr)}}

    .guarantee{background:var(--card);padding:16px;border-radius:12px;box-shadow:var(--shadow);margin:18px 0}

    footer{padding:24px 0;color:var(--muted);font-size:14px}

    /* Small helpers */
    .muted{color:var(--muted)}
    .center{text-align:center}
    .pill{display:inline-block;background:#fff;padding:6px 10px;border-radius:999px;border:1px solid rgba(107,63,38,0.06);font-weight:700}

    /* Accessibility focus */
    .btn:focus{outline:3px solid rgba(211,84,0,0.18)}

    /* Order form */
    .order{display:flex;flex-direction:column;gap:8px}
    .order input[type=number]{width:100px;padding:10px;border-radius:8px;border:1px solid #eee}

    /* Tiny responsive image */
    .hero-image{border-radius:12px;overflow:hidden;border:8px solid rgba(255,255,255,0.02);box-shadow:0 20px 40px rgba(27,24,22,0.08)}

    /* Subtle animation */
    .fade-in{animation:fadeIn 800ms ease both}
    @keyframes fadeIn{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}

    /* Small screen tweaks */
    @media(max-width:480px){.hero h2{font-size:20px}}
  </style>

  <!-- Structured data (basic) -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"Store",
    "name":"Cafe túi Tuấn Vỹ",
    "description":"Cafe túi lọc nguyên chất Tuấn Vỹ — rang mới mỗi tuần, pha nhanh 30 giây.",
    "url":"https://example.com",
    "telephone":"",
    "image":"https://via.placeholder.com/800x600?text=Tu%C3%A1n+V%C4%B3"
  }
  </script>
</head>
<body>
  <header class="container">
    <div class="brand">
      <img src="https://via.placeholder.com/80x80?text=TV" alt="Logo Tuấn Vỹ">
      <div>
        <div class="pill">Tuấn Vỹ</div>
        <h1 style="font-size:14px;margin-top:6px">Cafe túi lọc nguyên chất</h1>
      </div>
    </div>
    <nav aria-label="Main navigation">
      <a href="#benefits">Lợi ích</a>
      <a href="#feedback">Feedback</a>
      <a href="#pricing">Giá</a>
      <a href="#order" class="btn" style="padding:10px 14px">Đặt hàng</a>
    </nav>
  </header>

  <main class="container">

    <!-- HERO: includes 5 A/B/E variants (data-variant attribute) -->
    <section class="hero" aria-labelledby="hero-title">
      <div class="hero-inner fade-in">
        <!-- Variant selector (for A/B testing simulation) -->
        <div style="display:flex;gap:8px;align-items:center;margin-bottom:8px">
          <small class="muted">Phiên bản:</small>
          <select id="heroVariant" aria-label="Chọn phiên bản hero">
            <option value="default">A (Vị mạnh)</option>
            <option value="B">B (Tiện lợi)</option>
            <option value="C">C (Rang mới)</option>
            <option value="D">D (Nguyên chất)</option>
            <option value="E">E (Dân văn phòng)</option>
          </select>
        </div>

        <h2 id="hero-title">Cafe túi nguyên chất – chuẩn vị quán trong 30 giây</h2>
        <p id="hero-sub">Rang mới mỗi tuần, hương đậm – hậu ngọt – tiện lợi cho mọi buổi sáng.</p>

        <div class="cta-row">
          <button class="btn" onclick="scrollToOrder()">Mua ngay hôm nay</button>
          <button class="btn secondary" onclick="scrollToSection('benefits')">Tìm hiểu lợi ích</button>
        </div>

        <div style="margin-top:16px;color:var(--muted);font-size:14px">
          <strong>FreeShip</strong> cho đơn hàng combo trong hôm nay • <span id="salesCount">Hơn 10.000 gói đã bán</span>
        </div>

      </div>

      <aside class="hero-image center">
        <picture>
          <source media="(min-width:900px)" srcset="https://via.placeholder.com/800x600?text=Cafe+T%C3%BAi+Tu%C3%A1n+V%C4%B3+%7C+Hero">
          <img src="https://via.placeholder.com/600x420?text=Cafe+Tu%C3%A1n+V%C4%B3" alt="Túi cafe Tuấn Vỹ và ly cafe" style="width:100%;height:100%;object-fit:cover">
        </picture>
      </aside>
    </section>

    <!-- BENEFITS -->
    <section id="benefits">
      <h2 style="margin-top:6px">Lợi ích nổi bật</h2>
      <div class="grid-3">
        <div class="benefit">
          <h3>Hương vị đậm – thơm lâu</h3>
          <p>Hạt Arabica & Robusta tuyển chọn, rang mới mỗi tuần để giữ độ tươi và hương.</p>
        </div>
        <div class="benefit">
          <h3>Tiện lợi tuyệt đối</h3>
          <p>Pha 30 giây, không cần máy pha. Phù hợp văn phòng, du lịch, tại nhà.</p>
        </div>
        <div class="benefit">
          <h3>100% nguyên chất</h3>
          <p>Không hương liệu, không độn. Mỗi túi đảm bảo trọng lượng và vị giống nhau.</p>
        </div>
      </div>

      <div style="display:flex;gap:12px;align-items:center;margin-top:10px;flex-wrap:wrap">
        <div class="pill">Pha 30s</div>
        <div class="pill">Rang mới mỗi tuần</div>
        <div class="pill">Đổi trả 7 ngày</div>
      </div>
    </section>

    <!-- PRODUCT DESCRIPTION - PAS formula -->
    <section id="product-desc" style="margin-top:24px">
      <h2>Mô tả sản phẩm</h2>
      <div style="background:var(--card);padding:18px;border-radius:12px;box-shadow:var(--shadow)">
        <strong>Problem</strong>
        <p class="muted">Bạn muốn một ly cafe đậm, nguyên chất nhưng không có thời gian, hoặc máy pha. Hòa tan thì nhạt, phin thì mất thời gian.</p>

        <strong>Agitate</strong>
        <p class="muted">Uống cafe không ngon mỗi sáng làm giảm trải nghiệm, dễ chuyển sang đồ uống khác và tốn tiền cho lựa chọn không ổn định.</p>

        <strong>Solution</strong>
        <p class="muted">Cafe túi Tuấn Vỹ – gói tiện lợi, pha 30s, rang mới mỗi tuần, 100% hạt nguyên chất để bạn có ly cafe chuẩn vị mọi lúc.</p>

        <ul>
          <li>Hương đậm, hậu ngọt</li>
          <li>Pha nhanh, phù hợp mọi nơi</li>
          <li>100% hạt rang mới, không phụ gia</li>
          <li>Gói tiện, bảo quản dễ</li>
        </ul>

        <div style="margin-top:12px" class="center">
          <a class="btn" href="#order">Đặt hàng ngay</a>
        </div>
      </div>
    </section>

    <!-- TESTIMONIALS -->
    <section id="feedback" class="testimonials">
      <h2>Phản hồi khách hàng</h2>
      <div class="test-slider" id="testSlider" aria-live="polite">
        <div class="testimonial">
          <p>"Vị đậm như uống ở quán, thơm lâu, rất đã."</p>
          <div class="who">— Long N.</div>
        </div>
        <div class="testimonial">
          <p>"Đi làm pha 30 giây là có ngay ly ngon."</p>
          <div class="who">— Hương T.</div>
        </div>
        <div class="testimonial">
          <p>"Mua combo 3 gói tiết kiệm, uống mỗi sáng không chán."</p>
          <div class="who">— Tài V.</div>
        </div>
      </div>
    </section>

    <!-- GUARANTEE / COMMITMENT -->
    <section class="guarantee">
      <h3>Cam kết từ Tuấn Vỹ</h3>
      <ul>
        <li>100% nguyên chất — không phụ gia</li>
        <li>Rang & đóng gói trong tuần — bảo đảm tươi</li>
        <li>Đổi trả nếu không đúng hương vị</li>
      </ul>
    </section>

    <!-- PRICING -->
    <section id="pricing">
      <h2>Giá & Gói</h2>
      <div class="pricing">
        <div class="price-card">
          <div class="price-row"><strong>Gói 10 túi</strong><span>89.000₫</span></div>
          <div class="muted">Pha 30s — phù hợp dùng cá nhân</div>
          <div style="margin-top:12px"><button class="btn" onclick="addToCart('10')">Chọn gói</button></div>
        </div>

        <div class="price-card">
          <div class="price-row"><strong>Combo 3 gói</strong><span>239.000₫</span></div>
          <div class="muted">Tiết kiệm 28.000₫ — freeship tối ưu</div>
          <div style="margin-top:12px"><button class="btn" onclick="addToCart('3')">Chọn combo 3</button></div>
        </div>

        <div class="price-card">
          <div class="price-row"><strong>Combo 5 gói</strong><span>389.000₫</span></div>
          <div class="muted">Tiết kiệm 56.000₫ — freeship</div>
          <div style="margin-top:12px"><button class="btn" onclick="addToCart('5')">Chọn combo 5</button></div>
        </div>
      </div>
    </section>

    <!-- ORDER FORM / CTA -->
    <section id="order" style="margin-top:22px">
      <h2>Đặt hàng</h2>
      <div style="display:grid;grid-template-columns:1fr;gap:12px">
        <form id="orderForm" class="order" onsubmit="handleOrder(event)">
          <label for="product">Chọn gói</label>
          <select id="product" required>
            <option value="10">Gói 10 túi — 89.000₫</option>
            <option value="3">Combo 3 gói — 239.000₫</option>
            <option value="5">Combo 5 gói — 389.000₫</option>
          </select>

          <label for="qty">Số lượng</label>
          <input type="number" id="qty" value="1" min="1" required>

          <label for="name">Họ tên</label>
          <input id="name" type="text" required placeholder="Nguyễn Văn A">

          <label for="phone">Số điện thoại</label>
          <input id="phone" type="tel" required placeholder="0xxxxxxxxx">

          <label for="address">Địa chỉ</label>
          <input id="address" type="text" required placeholder="Địa chỉ giao hàng">

          <div style="display:flex;gap:8px;align-items:center">
            <button class="btn" type="submit">Đặt hàng ngay</button>
            <button type="button" class="btn secondary" onclick="applyVoucher()">Áp voucher 10%</button>
          </div>
        </form>

        <aside style="background:var(--card);padding:12px;border-radius:10px;box-shadow:var(--shadow)">
          <h4>Tóm tắt đơn hàng</h4>
          <div id="cartSummary" class="muted">Chưa có sản phẩm.</div>
        </aside>
      </div>
    </section>

  </main>

  <footer class="container">
    <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
      <div>
        <strong>Tuấn Vỹ</strong>
        <div class="muted">Cafe túi lọc nguyên chất • Rang mới mỗi tuần</div>
      </div>
      <div class="muted">© "Tuấn Vỹ" — All rights reserved</div>
    </div>
  </footer>

  <!-- Scripts: hero variants, testimonials slider, minimal cart/order logic -->
  <script>
    // Hero variants content map (A-E). This allows testing different headlines/subs/cta.
    const heroVariants = {
      'default': {
        title: 'Ly cafe đánh thức mọi giác quan',
        sub: 'Vị đậm – thơm sâu – pha 30 giây từ cafe túi nguyên chất.',
        cta: 'Trải nghiệm ngay'
      },
      'B': {
        title: 'Buổi sáng bận? Pha ly cafe chuẩn vị chỉ 30 giây',
        sub: 'Không máy pha. Không rườm rà. Chỉ cần rót nước nóng.',
        cta: 'Mua liền 1 gói'
      },
      'C': {
        title: 'Hương cafe mới rang – thơm đến ngỡ ngàng',
        sub: 'Rang – đóng gói trong tuần, giữ trọn sự tươi mới.',
        cta: 'Thử ngay hôm nay'
      },
      'D': {
        title: 'Cafe túi sạch – nguyên chất từ hạt thật',
        sub: 'Không phụ gia, không tẩm ướp, không độn. Vị thật của cafe thật.',
        cta: 'Đặt mua ngay'
      },
      'E': {
        title: 'Ly cafe đúng gu cho ngày làm việc hiệu quả',
        sub: 'Tiện lợi mang theo – pha nhanh – tỉnh táo lâu.',
        cta: 'Chọn gói phù hợp'
      }
    }

    // Switch hero on select
    const sel = document.getElementById('heroVariant');
    sel.addEventListener('change', (e)=>{
      const key = e.target.value;
      const v = heroVariants[key] || heroVariants['default'];
      document.getElementById('hero-title').textContent = v.title;
      document.getElementById('hero-sub').textContent = v.sub;
      // update primary CTA text
      document.querySelector('.cta-row .btn').textContent = v.cta;
    });

    // Simple testimonial carousel auto-advance
    const slider = document.getElementById('testSlider');
    let offset = 0;
    function slideTestimonials(){
      offset -= 280; // approx card width + gap
      if(Math.abs(offset) > (slider.scrollWidth - slider.clientWidth)) offset = 0;
      slider.style.transform = `translateX(${offset}px)`;
    }
    setInterval(slideTestimonials,4000);

    // Minimal cart and order handling (client-side demo)
    const cartSummary = document.getElementById('cartSummary');
    function addToCart(type){
      let label = 'Gói 10 túi — 89.000₫';
      if(type==='3') label = 'Combo 3 gói — 239.000₫';
      if(type==='5') label = 'Combo 5 gói — 389.000₫';
      cartSummary.textContent = label + ' • Số lượng 1';
      // highlight order form
      document.getElementById('product').value = type==='10'? '10': type;
      window.scrollTo({top:document.getElementById('order').offsetTop - 20, behavior:'smooth'});
    }

    function handleOrder(e){
      e.preventDefault();
      const product = document.getElementById('product').value;
      const qty = Number(document.getElementById('qty').value);
      const name = document.getElementById('name').value.trim();
      const phone = document.getElementById('phone').value.trim();
      const address = document.getElementById('address').value.trim();
      if(!name||!phone||!address){alert('Vui lòng điền đầy đủ thông tin');return}
      // Simulate order success
      alert(`Cảm ơn ${name}! Đơn hàng (${product} - số lượng ${qty}) đã được ghi nhận. Nhân viên sẽ liên hệ ${phone} để xác nhận.`);
      document.getElementById('orderForm').reset();
      cartSummary.textContent = 'Chưa có sản phẩm.';
    }

    function applyVoucher(){
      alert('Voucher 10% đã áp dụng khi thanh toán (demo).');
    }

    function scrollToOrder(){
      document.getElementById('order').scrollIntoView({behavior:'smooth',block:'start'});
    }
    function scrollToSection(id){
      document.getElementById(id).scrollIntoView({behavior:'smooth',block:'start'});
    }

    // Accessibility: enable keyboard switching for hero variants (1-5)
    window.addEventListener('keydown',(e)=>{
      if(['1','2','3','4','5'].includes(e.key)){
        const map={'1':'default','2':'B','3':'C','4':'D','5':'E'};
        sel.value = map[e.key];
        sel.dispatchEvent(new Event('change'));
      }
    });
  </script>
</body>
</html>
