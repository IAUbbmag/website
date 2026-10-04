---
Title: "نشریه بیت و بایت"
Description: "بیت و بایت؛ از دانشجو، برای دانشجو! نشریه‌ای علمی با تمرکز بر هوش مصنوعی و فناوری، پلی میان دانشجویان و دنیای علم. با ما همراه شوید برای نگاهی نو، مقالات به‌روز و تجربه‌های پژوهشی"
toc: false
layout: wide
Type: home

# HeroSlider (new homepage slider; see themes/hextra/layouts/partials/heroslider.html)
heroslider:
  ariaLabel: "معرفی بیت و بایت"
  slides:
    # 1 — the robotic hand
    - kind: "move"
      seconds: 10
      label: "BIT&BYTE // ISSUE_02 // 1405"
      lines: ["حرکت بعدی را", "هوش مصنوعی", "می‌چیند"]
      lead: "بیت و بایت؛ از دانشجو، برای دانشجو!"
      text: "نشریه‌ای علمی با تمرکز بر هوش مصنوعی و فناوری، پلی میان دانشجویان و دنیای علم. با ما همراه شوید برای نگاهی نو، مقالات به‌روز و تجربه‌های پژوهشی"
      image: "images/home/hero/scene.webp"
      hand: "images/home/hero/hand.webp"
      alt: "دست رباتیک بالای صفحه شطرنج دیجیتال با مهره‌های کلید، نماد پزشکی و ترازوی عدالت"
    # 2 — issue 2 cover with the moving light
    - kind: "cover"
      seconds: 17
      label: "BIT&BYTE // ISSUE_02 // 1405"
      title: "شماره"
      number: "۲"
      lead: "در این شماره:"
      text: "از گفت‌وگو با دکتر محمدامین شایگان تا عدالت دیجیتال در عصر هوش مصنوعی، رایانش عاطفی، چراغ الگوریتم در تاریکی جمجمه، هوش مصنوعی در امنیت شبکه و آینده اینترنت با web3. خواندنی، الهام‌بخش و آینده‌نگر."
      button: "مطالعه و دانلود این شماره"
      issue: "issues/issue-no-2"
      alt: "چهره‌هایی از فناوری، پزشکی و حقوق دور سر یک ذهن مصنوعی ساخته‌شده از ستاره‌ها"
    # 3 — published issues (3D magazine stack)
    - kind: "shelf"
      seconds: 10
      label: "BIT&BYTE // ISSUES // 01-02"
      tag: "مجلات منتشرشده بیت و بایت"
      title: "هنوز شماره ۱ را نخوانده‌اید؟"
      text: "هر شماره بیت و بایت یک بسته کامل است: گفت‌وگو با اساتید و متخصصان، معرفی پروژه‌های دانشجویی، تیپ‌ها و توصیه‌هایی برای زیست دانشجویی و پیدا کردن کار، و کلی مقاله درباره علم هوش مصنوعی. از شماره ۱ شروع کنید و با شماره ۲ ادامه دهید."
      buttonPrefix: "مطالعه و دانلود"
      issues:
        - page: "issues/issue-no-2"
          label: "شماره ۲"
          color: "#9B7CFF"
          ink: "#0B0620"
        - page: "issues/issue-no-1"
          label: "شماره ۱"
          color: "#F2C14E"
          ink: "#1A1405"
    # 4 — call for collaboration (the empty seat under a spotlight)
    - kind: "stage"
      seconds: 9
      label: "BIT&BYTE // JOIN_US"
      lines: ["ساختی؟", "نشونش", "بده"]
      text: "نویسنده، طراح، مترجم، پادکستر یا برنامه‌نویس؛ هر کاری که بلدی، در بیت و بایت جایی برایش هست. پروژه‌ات را نشان بده، ایده‌ات را با ما در میان بگذار یا به تیم ما بپیوند."
      button: "پیوستن به تیم"
      url: "collaboration"
      tag: "RESERVED_FOR: YOU"


# TeamStaff 
teamstaff:
  title: "با تیم ما آشنا شوید"
  members:
    # (Top Row)
    - name: "دکتر محمد علی اسدی"
      role: "استاد مشاور"
      image: "home/staff-drasadi.png"
      url: "fa/staff/asadi"
      row: "top"
      aos_delay: 0
      top_class: ""
    - name: "دکتر زینب شیرکول"
      role: "صاحب امتیاز"
      image: "home/staff-shirkoul.png"
      url: "fa/staff/shirkoul"
      row: "top"
      aos_delay: 300
      top_class: "top-20"
    # (Bottom Row)
    - name: "شیدا ستاری"
      role: "مدیر مسئول"
      image: "home/staff-sattari.png"
      url: "fa/staff/sattari"
      row: "bottom"
      aos_delay: 200
      top_class: "top-10"
    - name: "زهرا صحرانورد"
      role: "سردبیر"
      image: "home/staff-sahranavard.png"
      url: "fa/staff/sahranavard"
      row: "bottom"
      aos_delay: 300
      top_class: "bottom-10"
    - name: "گودرز جعفری"
      role: "وب‌مستر"
      image: "home/staff-jafari.png"
      url: "fa/staff/jafari"
      row: "bottom"
      aos_delay: 400
      top_class: "top-10"
    - name: "علی پروینی"
      role: "سردبیر"
      image: "home/staff-parvini.png"
      url: "fa/staff/parvini"
      row: "bottom"
      aos_delay: 500
      top_class: "bottom-10"


# testimonials Slider
testimonials:
  title: "نشریه در نگاه دانشگاه"
  members:
  - name: "دکتر علی رضا بیابان نورد"
    role: "معاونت فرهنگی-دانشجویی دانشگاه آزاد اسلامی واحد شیراز"
    quote: "یکی از این نهادها، نشریات می‌باشند. نشریات دانشجویی از نهادهایی هستند که امکان مکتوب کردن ایده‌های ذهنی را فراهم می‌کنند. یکی از بخش‌های مهمی که می‌توان این دستاوردها را عرضه کرد، در نوشتن اتفاق می‌افتد و بستر نشریۀ دانشجویی جایی است که دانشجو می‌تواند دستاوردهای علمی، پژوهشی، فرهنگی و اجتماعی خود را در اختیار بقیه بگذارد و از این طریق هم به رشد دیگران کمک می‌کند و هم خودش پرورش پیدا خواهد کرد."
    image: "images/home/mrbiabannavard.jpg"
  - name: "دکتر محمد رضا قائدی"
    role: "ریاست دانشگاه آزاد اسلامی واحد شیراز"
    quote: "نشریات علمی تخصصی و به ویژه نشریه علمی تخصصی کامپیوتر؛ با پژوهش، تحقیق و بازنشر مطالب ارزنده و به روز تخصصی این فناوری نوین جهانی، خصوصا در عرصه‌های مهمی همچون هوش مصنوعی می‌تواند نقش مهم و سازنده‌ای در ارتقای سطح علمی و اندیشه‌ای دانشجویان داشته باشد. از خداوند قادر متعال برای همه دست اندرکاران این مجله وزین آرزوی موفقیت و سربلندی می‌نمایم."
    image: "images/home/mrghaedi.png"
  - name: "دکتر علی رضا بیابان نورد"
    role: "معاونت فرهنگی-دانشجویی دانشگاه آزاد اسلامی واحد شیراز"
    quote: "یکی از این نهادها، نشریات می‌باشند. نشریات دانشجویی از نهادهایی هستند که امکان مکتوب کردن ایده‌های ذهنی را فراهم می‌کنند. یکی از بخش‌های مهمی که می‌توان این دستاوردها را عرضه کرد، در نوشتن اتفاق می‌افتد و بستر نشریۀ دانشجویی جایی است که دانشجو می‌تواند دستاوردهای علمی، پژوهشی، فرهنگی و اجتماعی خود را در اختیار بقیه بگذارد و از این طریق هم به رشد دیگران کمک می‌کند و هم خودش پرورش پیدا خواهد کرد."
    image: "images/home/mrbiabannavard.jpg"
  - name: "دکتر محمد رضا قائدی"
    role: "ریاست دانشگاه آزاد اسلامی واحد شیراز"
    quote: "نشریات علمی تخصصی و به ویژه نشریه علمی تخصصی کامپیوتر؛ با پژوهش، تحقیق و بازنشر مطالب ارزنده و به روز تخصصی این فناوری نوین جهانی، خصوصا در عرصه‌های مهمی همچون هوش مصنوعی می‌تواند نقش مهم و سازنده‌ای در ارتقای سطح علمی و اندیشه‌ای دانشجویان داشته باشد. از خداوند قادر متعال برای همه دست اندرکاران این مجله وزین آرزوی موفقیت و سربلندی می‌نمایم."
    image: "images/home/mrghaedi.png"

# Social 
linkedin:
  - image: "images/home/linkedin-preview.png"
    text: "ما را در لینکدین دنبال کنید تا از آخرین دستاوردها و فعالیت‌های علمی و تخصصی‌مان باخبر شوید."
    button: "مشاهده صفحه لینکدین"
    url: "https://www.linkedin.com/company/bbmag/"
---