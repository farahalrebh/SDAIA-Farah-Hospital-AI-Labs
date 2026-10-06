# لابات سدايا للذكاء الاصطناعي — Farah Hospital AI

يحتوي هذا المستودع على مجموعة لابات من دورة سدايا، وتم تنظيمها كمشروع مترابط باسم **Farah Hospital AI**.  
توضح اللابات كيف يمكن تطوير مساعد ذكي من برنامج بسيط يستقبل الطلبات ويرد عليها، إلى نظام أكثر تنظيمًا وأمانًا وقابلية للاختبار والتحسين.

## فكرة المشروع
**Farah Hospital AI** هو مساعد تعليمي لخدمات المستشفى، ويستخدم في أمثلة مثل:
- توجيه المرضى إلى القسم المناسب.
- دعم حجز المواعيد.
- تنظيم بيانات الفرز الطبي (Triage).
- استخدام الأدوات بشكل آمن.
- حماية بيانات المرضى.
- تقييم جودة النظام.
- تقليل التكلفة وزمن الاستجابة.

> **ملاحظة مهمة:** هذا المشروع تعليمي فقط، ولا يمثل نظام تشخيص طبي حقيقي.

## اللابات

| اللاب | الموضوع | أهم المفاهيم |
|---|---|---|
| Lab 01 & 02 | أساسيات الـLLM والتوجيه | LLM Interface، الذاكرة، Routing، Streaming، Fallback، Triage |
| Lab 03 | المخرجات المنظمة والتحقق | Pydantic، Structured Output، Validation، Repair، Escalation |
| Lab 03B | استخدام الأدوات والأمان | Tool Registry، Authorization، Confirmation، Agent Loop، Escalation |
| Lab 04 | الحماية والأمان | Prompt Injection، Scope Control، PII Masking، Output Filtering |
| Lab 05 | التقييم واختبار التراجع | Golden Set، Scoring، Judge Logic، Regression Gate |
| Lab 06 | تحسين التكلفة والسرعة | Cache، Smart Routing، Token Cost، Latency Reduction |

## هيكل المشروع

```text
SDAIA_Farah_Hospital_AI_Labs/
├── README.md
├── requirements.txt
├── .gitignore
├── Lab_01_02_Foundations_and_Routing/
│   ├── Lab_01_02.ipynb
│   └── README.md
├── Lab_03_Structured_Validation/
│   ├── Lab_03.ipynb
│   └── README.md
├── Lab_03B_Tool_Use_and_Safety/
│   ├── Lab_03B.ipynb
│   └── README.md
├── Lab_04_Security_Guardrails/
│   ├── Lab_04.ipynb
│   └── README.md
├── Lab_05_Evaluation_and_Regression/
│   ├── Lab_05.ipynb
│   └── README.md
└── Lab_06_Cost_and_Latency_Optimisation/
    ├── Lab_06.ipynb
    └── README.md
```

## المتطلبات
معظم اللابات تعتمد على مكتبات Python الأساسية.  
Lab 03 يستخدم **Pydantic v2** للتحقق من البيانات المنظمة.

```bash
pip install -r requirements.txt
```

## طريقة التشغيل
1. قم بتحميل أو استنساخ المستودع.
2. ثبّت المتطلبات.
3. افتح ملفات الـNotebook باستخدام Jupyter Notebook أو JupyterLab أو VS Code أو Google Colab.
4. شغّل الخلايا من الأعلى إلى الأسفل.

## تسلسل التعلم
المشروع يتدرج بالشكل التالي:

**مساعد بسيط → إدارة السياق والتوجيه → التحقق من البيانات → أمان الأدوات → الحماية الأمنية → التقييم → التحسين**

كل لاب يضيف مفهومًا جديدًا مرتبطًا ببناء أنظمة ذكاء اصطناعي أكثر اعتمادية.
