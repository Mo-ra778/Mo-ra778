# كتالوج عرض مشاريع Mohammed Rashad Al-Edrisi

هذا الكتالوج هو أساس إعادة كتابة أوصاف مستودعات GitHub. الهدف ليس وصف كل تجربة بالحجم نفسه، بل جعل الشركة تفهم بسرعة: المشكلة، الحل، دورك، التقنية، الحالة، والدليل القابل للمشاهدة.

## مشاريع العرض الرئيسية

### 1. AuditFlow — `auditflow-audit-platform`

**الفكرة:** منصة عربية RTL لإدارة أعمال مكاتب التدقيق الخارجي من تأسيس المكتب والعميل والارتباط إلى التخطيط والمخاطر وميزان المراجعة وسجل القرارات.

**القيمة:** تحويل إجراءات التدقيق المتفرقة إلى سير عمل موثق، مع صلاحيات واضحة وأثر تدقيق يمكن تتبعه.

**ما يبرز مهارتك:** تصميم domain معقد، multi-tenancy، RBAC، حواجز انتقال الحالات، التحقق من الاستقلالية والموارد، استيراد الجداول، validation، واختبارات Vitest واسعة.

**الحالة التي يجب إظهارها:** المراحل الأولى والثانية منفذة، والمرحلة الثالثة قيد الاختبار؛ لا تعرض المراحل غير المنفذة على أنها جاهزة.

### 2. Commerce Platform — `commerce-platform-v5`

**الفكرة:** أساس SaaS متعدد المستأجرين يمكّن التاجر من إدارة متجر أو عدة متاجر، والمنتجات، الأسعار، المخزون، العملاء، السلة، الدفع، الشحن، العروض، المحتوى، القوالب، والتحليلات.

**القيمة:** بناء قاعدة قابلة للتوسع بدل تطبيق متجر واحد مغلق.

**ما يبرز مهارتك:** monorepo، فصل storefront/admin/backend، حزم مشتركة، theme engine، PostgreSQL/Drizzle، Redis/BullMQ، search، object storage، observability، وCI.

**الحالة التي يجب إظهارها:** Foundation/architecture stage. اشرح ما تم بناؤه وما هو roadmap حتى تزيد الثقة ولا يبدو المشروع مبالغًا فيه.

### 3. Baybayin OCR — `Baybayin-OCR`

**الفكرة:** pipeline للتعرف على خط Baybayin التاريخي من الصور والمخطوطات ثم تحويله إلى transliteration Tagalog مع معالجة لغوية.

**القيمة:** تطبيق computer vision على مادة تاريخية صعبة ومنخفضة التباين.

**ما يبرز مهارتك:** YOLOv8، PyTorch، OpenCV، CLAHE، tiling، evaluation، Gradio، قاموس لغوي، وتحضير بيانات وتجارب تدريب.

**ما يجب إضافته قبل العرض:** روابط dataset أو بيان ترخيصه، split واضح، metrics قابلة لإعادة الإنتاج، model card، وأمثلة قبل/بعد.

### 4. Baybayin Mobile — `baybayin_mobile_app`

**الفكرة:** تطبيق Flutter يعمل على الجهاز للتعرف على Baybayin، الترجمة الصوتية، المعجم، النطق، والتصفح دون اعتماد أساسي على السيرفر.

**القيمة:** نقل نموذج ML من التجربة البحثية إلى تجربة مستخدم قابلة للاستخدام على الهاتف.

**ما يبرز مهارتك:** Flutter، ONNX Runtime، isolates، معالجة الصور، NMS، spatial clustering، lexicon search، TTS، ودعم RTL.

### 5. E-Wallet Core — `ewallet-core-platform`

**الفكرة:** نظام محفظة رقمية يتضمن المستخدمين والوكلاء والإدارة والإيداع والسحب والتحويل والحوالات والعملات المتعددة وأسعار الصرف والإشعارات.

**القيمة:** يوضح فهمك للعمليات المالية، الصلاحيات، المعاملات، ومنع race conditions.

**ما يبرز مهارتك:** Laravel، PHP، JWT، Hash، CSRF، `DB::transaction()`، `lockForUpdate()`، migrations، Blade، وواجهات API.

**شرط العرض:** أصلح أولًا `admin123` و`agent123` و`demo_otp`، ثم اذكر بوضوح أنه portfolio project وليس نظامًا مصرفيًا إنتاجيًا.

### 6. AI-AGET — `ai-aget-platform`

**الفكرة:** أساس Python لوكيل برمجي يعمل ضمن حدود زمنية وعددية ومالية واضحة.

**القيمة:** إظهار أنك لا تبني chatbot فقط، بل تفكر في safety، budgets، observability، وproduct boundaries.

**ما يبرز مهارتك:** FastAPI، LangGraph، typing، pytest، Ruff، mypy، request IDs، cost estimation، usage reconciliation، وتصميم حدود الأدوات.

## مشاريع داعمة

### Wafi Pay Mobile — `-wafi-pay-mobile`
تطبيق FinTech موبايل مبني بـ React Native وExpo وTypeScript، مصمم للتكامل مع Laravel API ويعرض مهارات mobile UI، authentication flows، وإدارة تجربة المستخدم المالية.

### PIXOLR — `PIXOLR`
أساس محرر صور ويب باستخدام TypeScript وVite وserver layer. يعرض بناء أدوات تفاعلية للصور وتقسيم الواجهة عن الخادم. يجب إضافة README وصورة demo وبيان واضح لما هو منفذ فعليًا.

### GlassPOS — `GlassPOS`
واجهة Point-of-Sale متعددة اللغات لإدارة المنتجات والمبيعات والعملاء والمصروفات والتقارير، مع mock API محلي للتجربة السريعة. مناسب لعرض React/TypeScript وتصميم لوحات الأعمال.

### LectureMind AI — `lectureMind-ai-`
فكرة منتج تعليمي يحول الصوت أو transcript إلى نقاط أساسية وملاحظات منظمة وflashcards وملخصات. يجب توضيح هل المعالجة منفذة فعليًا أم أنها product prototype.

### Hand Drawing in Air — `hand-drawing-airhand-drawing-air`
تجربة computer vision للتفاعل والرسم عبر حركة اليد. مناسبة لإظهار Python، image processing، وتجارب human-computer interaction.

### UNet Novel View Synthesis — `UNet-Novel-View-Synth`
تجربة deep learning لتوليد زوايا جديدة لمشهد انطلاقًا من صورة واحدة. يجب إضافة dataset، طريقة التقييم، أمثلة النتائج، وحدود النموذج.

### Voice-to-Notion Assistant — `voice-to-notion-assistant`
Workflow مبني على n8n يحول الإدخال الصوتي إلى محتوى منظم داخل Notion. مناسب لعرض automation، API integration، وتصميم workflows.

### Loqmat Jadati — `loqmat-jadati`
موقع لمشروع أطعمة يمنية تراثية يعرض المنتجات ويستقبل الطلبات ويوفر إدارة تشغيلية. مناسب لعرض PHP الأساسي، UX، قواعد البيانات، وربط احتياج تجاري بمنتج رقمي.

### VIBE-TECH — `VIBE-TECH`
واجهة/موقع لعلامة تقنية مبني بـ TypeScript. يجب إبقاؤه خاصًا أو إضافة README ولقطات شاشة إذا كان سيُستخدم كدراسة تصميم.

### Portfolio v0 — `portfolio-v0`
نسخة سابقة من الموقع الشخصي. الأفضل اعتبارها archive أو تحويلها إلى نسخة canonical بدل إبقائها كمشروع عرض مستقل.

## مشاريع تعليمية أو أرشيفية

### Mini Compiler — `mini-compiler-`
واجهة compiler صغيرة بـ C# تشمل lexer، symbol table، parser، AST، والتحليل الدلالي. مشروع ممتاز لإظهار أساسيات علوم الحاسوب، لكن يحتاج README بأمثلة input/output.

### CLAINET Server — `CLAINET-SERVER-`
تطبيق محادثة TCP/IP client-server باستخدام C# Windows Forms. يوضح الشبكات، sockets، desktop UI، وفصل العميل عن الخادم.

### Finance System — `finance-system.`
نظام PHP صغير مرتبط بمفاهيم الإدارة المالية. يحتاج اسمًا أفضل ووصفًا وصورًا حتى يفهم الزائر نطاقه بسرعة.

### PROJECT-MARCTING- — `PROJECT-MARCTING-`
نظام لتخطيط وإدارة المشاريع التسويقية بواجهة HTML/CSS/JS. يبقى كمشروع تعليمي أو dashboard case study.

### PROJECT-MARCTING — `PROJECT-MARCTING`
مستودع فارغ تقريبًا ومكرر وظيفيًا؛ يفضل أرشفته بعد التأكد من عدم الحاجة إليه.

### Web App — `web-app`
واجهة تسجيل مشاريع تخرج للطلاب باستخدام Google Sheets وGoogle Apps Script كخادم serverless.

### Web App 2 — `web-aApp2`
نسخة أخرى من نفس فكرة تسجيل مشاريع التخرج. اختر نسخة واحدة كـ canonical وأرشف الأخرى.

### DATA MINING 2 — `DATA_MINING2`
مشروع تحليل بيانات واستخراج أنماط. يحتاج dataset ونتائج ورسومًا وREADME حتى يصبح دليلًا حقيقيًا على مهارات data mining.

### MAINING — `MAINING`
أداة/تجربة معالجة بيانات صغيرة. الأفضل دمجها مع مشروع data mining أو وضعها تحت قسم educational experiments.

### System Graph — `system-graph`
صفحة تصور وتحليل graph للنظام. تحتاج شرحًا للمدخلات، الخوارزمية، ولقطة تفاعلية.

### Support System — `sup`
نظام دعم مبني بـ PHP/HTML/SQL. يمكن تحويله إلى case study جيد إذا أضيفت الصلاحيات، تذاكر الدعم، screenshots، وبيانات تشغيل تجريبية.

### Project 1 — `project_1`
مستودع تجريبي خاص وفارغ تقريبًا. لا يظهر في واجهة الشركات.

## ترتيب الظهور المقترح على الحساب

1. AuditFlow
2. Commerce Platform
3. Baybayin Mobile
4. Baybayin OCR
5. AI-AGET
6. E-Wallet بعد الإصلاح الأمني

## قاعدة تحرير موحدة لكل README

كل README عام يجب أن يبدأ بجملة واضحة عن المشكلة، ثم يوضح الحل، المستخدم المستهدف، أهم الميزات المنفذة، المعمارية، التقنيات، التشغيل، الاختبارات، demo، الحالة الحالية، والقيود. استخدم أرقامًا فقط عندما تكون قابلة للإثبات داخل المستودع أو مرتبطة بتقرير/تجربة.
