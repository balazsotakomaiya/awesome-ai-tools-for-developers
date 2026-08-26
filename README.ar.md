# Awesome AI Tools for Developers

[English](README.md) · **العربية**

> قائمة منتقاة لأدوات الذكاء الاصطناعي في البرمجة والتنقيح والاختبار وعمليات التطوير والواجهات البرمجية وصناعة البرمجيات.

<!-- counts:start -->
![Tools](https://img.shields.io/badge/tools-104-informational)
![Categories](https://img.shields.io/badge/categories-13-informational)
<!-- counts:end -->
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](LICENSE)

كل قائمة ذكاء اصطناعي عامة تحدّث المطورين عن مساعد المحادثة نفسه. وهذه لا تفعل. فاختبار
الإدراج كان: هل تتصل الأداة بمسار تطوير حقيقي؟ محرر، أو طرفية، أو طلب دمج، أو مسار آلي، أو
نظام يعمل. وإن كانت قصة تكاملها «الصق شفرتك في مربّع المحادثة» فليست هنا.

والتصنيفات تتبع يوم العمل لا تصنيف التسويق، ولهذا نالت مراجعة الشفرة والاختبار والمراقبة
مساحة كمساحة توليد الشفرة. والأسماء تتغيّر بسرعة في هذا الميدان، والمنتجات التي أُعيدت
تسميتها أو طُويت أو تقاعدت مدرجة بما تُسمى به الآن، أو غير مدرجة أصلًا.

بإشراف [TiorAI](https://tiorai.com/)، وعملها اليومي فهرسة أدوات الذكاء الاصطناعي.

<!-- last-reviewed:start -->
**آخر مراجعة:** 2026-08-22
<!-- last-reviewed:end -->

## دليل الوسوم

الوسوم تُركت بالإنجليزية عمدًا لتطابق النسخة الإنجليزية سطرًا بسطر، فيسهل تتبّع أي تغيير
بين النسختين.

**التسعير:** `Free` مجاني · `Freemium` مجاني مع خطة مدفوعة · `Paid` مدفوع ·
`Open Source` مفتوح المصدر · `Free Trial` تجربة مجانية

**المنصات:** `Web` ويب · `Windows` · `macOS` · `Linux` · `iOS` · `Android` ·
`API` واجهة برمجية · `CLI` سطر أوامر · `Browser Extension` إضافة متصفح · `VS Code` ·
`JetBrains` · `Discord`

## المحتويات

- [المحررات وبيئات التطوير](#المحررات-وبيئات-التطوير)
- [مساعدو البرمجة](#مساعدو-البرمجة)
- [وكلاء البرمجة](#وكلاء-البرمجة)
- [مراجعة الشفرة](#مراجعة-الشفرة)
- [الاختبار](#الاختبار)
- [التنقيح وقابلية المراقبة](#التنقيح-وقابلية-المراقبة)
- [التوثيق](#التوثيق)
- [تطوير الواجهات البرمجية](#تطوير-الواجهات-البرمجية)
- [قواعد البيانات وSQL](#قواعد-البيانات-وsql)
- [عمليات التطوير والبنية التحتية](#عمليات-التطوير-والبنية-التحتية)
- [أمن التطبيقات](#أمن-التطبيقات)
- [الطرفية والصدفة](#الطرفية-والصدفة)
- [الواجهات الأمامية وتوليد الواجهات](#الواجهات-الأمامية-وتوليد-الواجهات)
- [كيف نختار الأدوات](#كيف-نختار-الأدوات)
- [اقتراح أداة](#اقتراح-أداة)
- [المساهمة](#المساهمة)
- [إخلاء مسؤولية](#إخلاء-مسؤولية)
- [الرخصة](#الرخصة)
- [عن TiorAI](#عن-tiorai)

## المحررات وبيئات التطوير

بيئات تطوير مبنية حول نموذج لا مركّب عليها نموذج.

- **[Antigravity](https://antigravity.google/)** — بيئة تطوير من Google تبدأ من الوكيل، والمحرر فيها سطح واحد يطلّ على وكيل عامل. `Freemium` `Windows` `macOS` `Linux`
- **[Cursor](https://cursor.com/)** — محرر مبني حول محادثة تعي قاعدة الشفرة وتحريرات متعددة الملفات، وأوسعها تبنيًا. `Freemium` `Windows` `macOS` `Linux` · [free vs paid](https://tiorai.com/compare/cursor-ai-free-vs-paid/)
- **[Devin Desktop](https://devin.ai/)** — بيئة سطح المكتب من Cognition، وكان اسمها Windsurf، تقرن محررًا بوكيلها المستقل. `Paid` `Windows` `macOS` `Linux`
- **[Firebase Studio](https://firebase.studio/)** — مساحة عمل من Google في المتصفح لبناء تطبيقات كاملة ونشرها بوكيل مرفق. `Freemium` `Web`
- **[JetBrains AI Assistant](https://www.jetbrains.com/ai-ides/)** — مساعد موصول ببيئات JetBrains، يستعمل الفهرس نفسه الذي يقود أدوات إعادة الهيكلة فيها. `Freemium` `JetBrains` · [vs Copilot](https://tiorai.com/compare/copilot-vs-jetbrains-ai/)
- **[Kiro](https://kiro.dev/)** — محرر من AWS يعمل من مواصفات مكتوبة، فيولّد المتطلبات والتصميم قبل الشفرة. `Freemium` `Windows` `macOS` `Linux`
- **[Replit](https://replit.com/)** — بيئة تطوير في المتصفح يستطيع فيها وكيل أن يبني مشروعًا ويشغّله وينشره من طرف إلى طرف. `Freemium` `Web` `iOS` `Android` · [vs Bolt](https://tiorai.com/compare/replit-ai-vs-bolt-new/)
- **[Trae](https://www.trae.ai/)** — محرر من ByteDance بوضع بناء يهيكل مشروعًا من وصف. `Freemium` `Windows` `macOS` `Linux`
- **[Zed](https://zed.dev/)** — محرر أصلي مكتوب بلغة Rust، بلوحات وكلاء وتحرير تعاوني في صميمه. `Open Source` `Windows` `macOS` `Linux`

## مساعدو البرمجة

إكمال ومحادثة داخل المحرر الذي تستعمله أصلًا.

- **[Amazon Q Developer](https://aws.amazon.com/q/developer/)** — مساعد من AWS للإكمال والترقيات والاستدلال عن الموارد في حساب AWS. `Freemium` `CLI` `VS Code` `JetBrains`
- **[Augment Code](https://www.augmentcode.com/)** — مساعد مبني حول فهرسة المستودعات الضخمة، موجّه لقواعد شفرة أكبر من أن تسع السياق. `Paid` `CLI` `VS Code` `JetBrains`
- **[Continue](https://continue.dev/)** — إكمال ومحادثة مفتوحا المصدر توجّههما إلى أي نموذج، مستضاف أو يعمل محليًا. `Open Source` `VS Code` `JetBrains`
- **[GitHub Copilot](https://github.com/features/copilot)** — إكمال ومحادثة ومساعدة في طلبات الدمج عبر المحررات الشائعة وعلى GitHub نفسه. `Freemium` `CLI` `VS Code` `JetBrains` · [free vs pro](https://tiorai.com/compare/github-copilot-free-vs-pro/)
- **[Pieces](https://pieces.app/)** — مدير قصاصات وسياق محلي يتذكّر ما كنت تعمل عليه عبر الأدوات. `Freemium` `Windows` `macOS` `Linux` `VS Code` `JetBrains`
- **[Qodo](https://www.qodo.ai/)** — يولّد الاختبارات ويراجع طلبات الدمج، وخطته المجانية موجّهة للمطورين الأفراد. `Freemium` `Web` `VS Code` `JetBrains`
- **[Sourcegraph Cody](https://sourcegraph.com/docs/cody)** — مساعد مؤسسي مؤسَّس على فهرس شفرة للمنظمة كلها لا لمستودع واحد. `Paid` `Web` `VS Code` `JetBrains`
- **[Tabnine](https://www.tabnine.com/)** — إكمال بخيار نشر مستضاف ذاتيًا، وهو كثيرًا ما يحسم الأمر للفرق المنظَّمة. `Freemium` `VS Code` `JetBrains` · [vs GitHub Copilot](https://tiorai.com/compare/tabnine-vs-github-copilot/)

## وكلاء البرمجة

تعطيها مهمة ومستودعًا فتعمل عليها وتعود بفرق.

- **[Aider](https://aider.chat/)** — وكيل طرفية يحرّر الملفات في مستودع محلي ويودع كل تغيير على حدة. `Open Source` `CLI` · [vs Cursor](https://tiorai.com/compare/cursor-ai-vs-aider/)
- **[Amp](https://ampcode.com/)** — أداة برمجة وكيلة من مؤسسي Sourcegraph الأصليين، صارت منتجًا مستقلًا. `Paid` `CLI` `VS Code`
- **[Claude Code](https://www.claude.com/product/claude-code)** — وكيل الطرفية من Anthropic، يستكشف قاعدة الشفرة ويحرّر الملفات ويشغّل الاختبارات. `Paid` `CLI` `VS Code` `JetBrains` · [vs GitHub Copilot](https://tiorai.com/compare/github-copilot-vs-claude-code/)
- **[Cline](https://cline.bot/)** — وكيل لـVS Code يعرض خطة ويشغّل الأوامر ويستأذن قبل كل كتابة ملف. `Open Source` `VS Code`
- **[Codex CLI](https://learn.chatgpt.com/docs/codex/cli)** — وكيل الطرفية من OpenAI، يعمل محليًا مقابل مستودعك بوضع تنفيذ معزول. `Open Source` `CLI`
- **[Jules](https://jules.google/)** — وكيل غير متزامن من Google، يستنسخ مستودعًا في آلة سحابية ويعيد فرقًا. `Freemium` `Web`
- **[OpenHands](https://www.openhands.dev/)** — وكيل مفتوح المصدر يفتح الملفات ويشغّل الاختبارات ويكرر داخل بيئة معزولة تتحكم فيها. `Open Source` `Web` `CLI`
- **[Roo Code](https://github.com/RooCodeInc/Roo-Code)** — وكيل لـVS Code بأوضاع متمايزة للمعمارية والتنفيذ والتنقيح. `Open Source` `VS Code`
- **[SWE-agent](https://swe-agent.com/)** — وكيل بحثي لإصلاح مشكلات GitHub، والتنفيذ الذي تُقاس عليه أكثر القياسات. `Open Source` `CLI`

## مراجعة الشفرة

مراجعة تعمل على طلب الدمج قبل أن يفتحه إنسان.

- **[Bito](https://bito.ai/)** — مراجع طلبات دمج بتحليل ساكن وفحوص اعتماديات مطوية في سلسلة التعليقات نفسها. `Freemium` `Web` `CLI` `VS Code`
- **[Codacy](https://www.codacy.com/)** — بوابة جودة وأمن عبر لغات كثيرة، صار فيها اقتراح إصلاحات بمساعدة النماذج. `Freemium` `Web`
- **[CodeAnt AI](https://www.codeant.ai/)** — يشير إلى العيوب ومخالفات السياسة في طلبات الدمج الواردة، وينشر داخل شبكتك. `Paid` `Web`
- **[CodeRabbit](https://www.coderabbit.ai/)** — يترك تعليقات مراجعة داخل السطور في كل طلب دمج، مع ملخص لما تغيّر ولماذا. `Freemium` `Web` `VS Code`
- **[Ellipsis](https://www.ellipsis.dev/)** — يفتح طلب دمج تاليًا يصلح ما وجدته مراجعته، بدل التعليق وحده. `Paid` `Web`
- **[Greptile](https://www.greptile.com/)** — يراجع طلبات الدمج برسم لقاعدة الشفرة كلها، فيستطيع الإشارة إلى الكسر العابر للملفات. `Paid` `Web` `API`
- **[PR-Agent](https://github.com/The-PR-Agent/pr-agent)** — يستجيب لأوامر الوصف والمراجعة والتحسين على طلب دمج، يُشغَّل من مسارك الآلي أو من صدفة. `Open Source` `CLI`
- **[Sourcery](https://sourcery.ai/)** — يقترح إعادات هيكلة في المحرر وفي طلبات الدمج، بتركيز قوي على بايثون. `Freemium` `Web` `VS Code` `JetBrains`

*للمزيد: [AI code review tools on TiorAI](https://tiorai.com/tool-category/ai-code-review/)*

## الاختبار

توليد الاختبارات، ومنع مجموعات الاختبار الشاملة من الانكسار مع كل تغيير تخطيط.

- **[Antithesis](https://antithesis.com/)** — اختبار محاكاة حتمي يصطاد عيوب التزامن والحالة النادرة، ثم يعيد تشغيلها بدقة. `Paid` `Web` `API`
- **[Applitools](https://applitools.com/)** — اختبار انحدار بصري يقارن الصفحات المصيَّرة كما يقارنها إنسان لا بكسلًا بكسل. `Freemium` `Web` `API` `CLI`
- **[Diffblue Cover](https://www.diffblue.com/)** — يكتب اختبارات وحدة لـJava تلقائيًا، موجّه لقواعد الشفرة القديمة بلا تغطية أصلًا. `Freemium` `CLI` `JetBrains`
- **[Meticulous](https://www.meticulous.ai/)** — يسجّل جلسات مستخدمين حقيقية ويعيد تشغيلها لالتقاط الانحدارات البصرية والسلوكية. `Paid` `Web`
- **[Momentic](https://momentic.ai/)** — اختبارات شاملة مكتوبة بلغة عادية، تنجو من تغيّر المحدِّدات أفضل من المكتوبة سكربتات. `Freemium` `Web` `CLI`
- **[QA Wolf](https://www.qawolf.com/)** — تغطية شاملة تُسلَّم خدمةً، بصيانة الاختبارات متكفَّلًا بها لا متروكة لك. `Paid` `Web`
- **[Qodo Cover](https://github.com/qodo-ai/qodo-cover)** — يولّد الاختبارات ويبقي منها ما يرفع التغطية المقيسة فعلًا. `Open Source` `CLI`
- **[Reflect](https://reflect.run/)** — اختبارات انحدار مسجَّلة في المتصفح يستطيع غير المهندس إنشاءها ويثق بها المهندس. `Paid` `Web`

*للمزيد: [AI software testing tools on TiorAI](https://tiorai.com/tool-category/software-testing/)*

## التنقيح وقابلية المراقبة

معرفة ما انكسر في الإنتاج، ولماذا.

- **[Datadog Bits AI](https://www.datadoghq.com/product/ai/bits-ai-agents/)** — يحقق في الحوادث عبر بيانات Datadog ويصوغ ملخصًا لما وجده. `Paid` `Web`
- **[Grafana Assistant](https://grafana.com/products/cloud/ai-tools-for-grafana/)** — يبني اللوحات والاستعلامات من وصف، داخل حزمة تشغّلها فرق كثيرة أصلًا. `Freemium` `Web`
- **[Honeycomb](https://www.honeycomb.io/)** — قابلية مراقبة مبنية للبيانات عالية التعدد، باستعلام بلغة طبيعية فوق التتبعات. `Freemium` `Web` `API`
- **[Incident.io](https://incident.io/)** — إدارة حوادث تصوغ التحديثات ومراجعات ما بعد الحادث من خط زمن الاستجابة. `Freemium` `Web` `API`
- **[Jam](https://jam.dev/)** — يلتقط بلاغ عطل بسجلات الطرفية وطلبات الشبكة وخطوات إعادة الإنتاج بنقرة واحدة. `Freemium` `Web` `Browser Extension`
- **[Sentry](https://sentry.io/)** — تتبع أخطاء بتحليل آلي للسبب الجذري وإصلاحات مقترحة على المشكلات الواردة. `Freemium` `Web` `API`
- **[Traversal](https://www.traversal.com/)** — يتتبع حادثة رجوعًا عبر اعتماديات الخدمات إلى التغيير الأرجح أنه سببها. `Paid` `Web`

## التوثيق

كتابة الوثائق، وإبقاؤها صحيحة بعد تغيّر الشفرة.

- **[Docusaurus](https://docusaurus.io/)** — مولّد مواقع توثيق ببحث وإصدارات، والخيار الافتراضي لمشاريع مفتوحة كثيرة. `Open Source` `Web` `CLI`
- **[Fern](https://buildwithfern.com/)** — يولّد حزم تطوير ووثائق واجهات برمجية من مواصفة OpenAPI، ويبقيهما متسقين. `Freemium` `Web` `CLI`
- **[GitBook](https://www.gitbook.com/)** — يستضيف التوثيق ويبلّغ أي أسئلة القرّاء لم تجب عنها الصفحات المنشورة. `Freemium` `Web` `API`
- **[Kapa.ai](https://www.kapa.ai/)** — يجيب عن أسئلة المطورين من وثائقك القائمة، ويبلّغ بما لم يستطع الإجابة عنه. `Paid` `Web` `API`
- **[Mintlify](https://mintlify.com/)** — منصة توثيق يجيب مساعدها المدمج من صفحاتك المنشورة، بتحليلات للاستعمال. `Freemium` `Web` `CLI`
- **[readme.so](https://readme.so/)** — يركّب ملف تعريف مشروع من أقسام قياسية، ينفع لإخراج نسخة أولى. `Free` `Web`
- **[Scalar](https://scalar.com/)** — مرجع واجهة برمجية وعميل مفتوحا المصدر يُولَّدان من مستند OpenAPI. `Open Source` `Web` `CLI`
- **[Swimm](https://swimm.io/)** — يربط التوثيق بشفرة بعينها فيسقط الفحص حين تتحرك الشفرة تحته. `Freemium` `Web` `VS Code` `JetBrains`

*للمزيد: [AI developer documentation tools on TiorAI](https://tiorai.com/tool-category/ai-developer-docs/)*

## تطوير الواجهات البرمجية

تصميم الواجهات البرمجية واختبارها وإطلاقها.

- **[Apidog](https://apidog.com/)** — تصميم واجهة برمجية ومحاكاتها واختبارها وتوثيقها في أداة واحدة بدل أربع. `Freemium` `Web` `Windows` `macOS` `Linux`
- **[Bruno](https://www.usebruno.com/)** — عميل واجهات برمجية يعمل دون إنترنت يخزّن المجموعات ملفات عادية في مستودعك، فتظهر فروقها. `Open Source` `Windows` `macOS` `Linux` `CLI`
- **[Hoppscotch](https://hoppscotch.io/)** — عميل واجهات برمجية خفيف مفتوح المصدر يعمل في تبويب متصفح ويمكن استضافته ذاتيًا. `Open Source` `Web` `CLI`
- **[Postman](https://www.postman.com/)** — منصة الواجهات البرمجية العريقة، باختبارات ووثائق ومساعدة في المجموعات مولَّدة. `Freemium` `Web` `Windows` `macOS` `Linux`
- **[Redocly](https://redocly.com/)** — يدقق مستندات OpenAPI مقابل دليل أسلوب وينشر منها وثائق مرجعية. `Freemium` `Web` `CLI`
- **[Speakeasy](https://www.speakeasy.com/)** — يولّد حزم تطوير اصطلاحية بعدة لغات من مواصفة OpenAPI. `Freemium` `Web` `CLI`
- **[Stainless](https://www.stainless.com/)** — توليد حزم تطوير يستعمله عدد من كبار مزوّدي النماذج لمكتبات عملائهم الرسمية. `Freemium` `Web` `CLI`
- **[Zuplo](https://zuplo.com/)** — بوابة واجهات برمجية قابلة للبرمجة بوثائق وإدارة مفاتيح مولَّدة من المواصفة نفسها. `Freemium` `Web` `API`

*للمزيد: [AI API tools on TiorAI](https://tiorai.com/tool-category/ai-api/)*

## قواعد البيانات وSQL

كتابة الاستعلامات وتشكيل المخططات وعدم إسقاط جدول الإنتاج.

- **[AI2sql](https://www.ai2sql.io/)** — يحوّل وصفًا عاديًا إلى SQL بعدة لهجات، موجّه لمن يكتبون الاستعلامات أحيانًا. `Freemium` `Web`
- **[Bytebase](https://www.bytebase.com/)** — ترحيل مخططات وتحكم في الوصول لقواعد البيانات، بسياسات مراجعة تُطبَّق قبل حلول التغيير. `Freemium` `Web` `CLI`
- **[Chat2DB](https://chat2db.ai/)** — عميل قواعد بيانات يحوّل الأوصاف العادية إلى SQL ويشرح خطط الاستعلام. `Freemium` `Web` `Windows` `macOS` `Linux`
- **[DBeaver](https://dbeaver.io/)** — عميل قواعد بيانات شامل بمساعدة في الاستعلام، ونسخته المفتوحة تغطي أكثر الحاجات. `Open Source` `Windows` `macOS` `Linux`
- **[Neon](https://neon.com/)** — Postgres بلا خوادم بتفريع فوري، يجعل الترحيلات التي يولّدها وكيل آمنة التجربة. `Freemium` `Web` `API` `CLI`
- **[pgAdmin](https://www.pgadmin.org/)** — عميل إدارة Postgres العريق، بأدوات استعلام وخطة تنفيذ مرئية. `Open Source` `Web` `Windows` `macOS` `Linux`
- **[Supabase](https://supabase.com/)** — منصة Postgres بالاستيثاق والتخزين ومساعد يكتب SQL وسياسات أمن على مستوى الصف. `Freemium` `Web` `API` `CLI`
- **[Vanna](https://vanna.ai/)** — تحويل نص إلى SQL مفتوح المصدر تدرّبه على مخططك أنت وعلى استعلاماتك السابقة. `Open Source` `API` `CLI`

## عمليات التطوير والبنية التحتية

المسارات الآلية والحاويات والبنية التحتية كشفرة.

- **[Dagger](https://dagger.io/)** — يعرّف مسارات التكامل المستمر شفرةً تعمل بالطريقة نفسها على حاسوبك وعلى منفّذ التكامل. `Open Source` `API` `CLI`
- **[Depot](https://depot.dev/)** — بناء حاويات وتكامل مستمر عن بعد بتخزين مؤقت دائم، موجّه لأزمنة البناء تحديدًا. `Freemium` `Web` `CLI`
- **[Kubiya](https://www.kubiya.ai/)** — يجيب عن أسئلة البنية التحتية ويشغّل المهام التشغيلية المعتمدة من داخل Slack. `Paid` `Web` `API`
- **[Pulumi](https://www.pulumi.com/)** — بنية تحتية كشفرة بلغات عامة الغرض، بمساعد يولّد الموارد. `Freemium` `Web` `CLI`
- **[Railway](https://railway.com/)** — منصة نشر تستنتج إعدادات البناء والتشغيل بدل أن تسألك عنها. `Freemium` `Web` `CLI`
- **[Spacelift](https://spacelift.io/)** — تنسيق للبنية التحتية كشفرة بفحوص سياسة تعمل قبل تطبيق الخطة. `Freemium` `Web` `CLI`
- **[Terramate](https://terramate.io/)** — تنسيق وكشف انحراف فوق حزم Terraform وOpenTofu القائمة. `Freemium` `Web` `CLI`

*للمزيد: [AI DevOps tools on TiorAI](https://tiorai.com/tool-category/ai-devops-tools/)*

## أمن التطبيقات

إيجاد الثغرات في الشفرة والاعتماديات، وإصلاحها.

- **[Aikido Security](https://www.aikido.dev/)** — يوحّد فحص الشفرة والاعتماديات والحاويات والسحابة، وترشيح الضجيج هو ادعاؤه الرئيس. `Freemium` `Web` `CLI`
- **[Corgea](https://corgea.com/)** — يفرز نتائج التحليل الساكن ويقترح رقعات، فيقلّص طابور الإيجابيات الكاذبة. `Freemium` `Web` `CLI`
- **[Endor Labs](https://www.endorlabs.com/)** — تحليل اعتماديات يفحص هل الدالة المصابة قابلة للوصول فعلًا من شفرتك. `Paid` `Web` `CLI`
- **[GitGuardian](https://www.gitguardian.com/)** — يكشف الأسرار المودعة عبر المستودعات وتاريخها، بمسارات معالجة مرفقة. `Freemium` `Web` `CLI`
- **[Semgrep](https://semgrep.dev/)** — تحليل ساكن بالأنماط بقواعد تُقرأ كالشفرة التي تطابقها. `Open Source` `Web` `CLI` `VS Code`
- **[Snyk](https://snyk.io/)** — يفحص الشفرة والاعتماديات والحاويات والبنية التحتية كشفرة، بطلبات دمج إصلاح مولَّدة. `Freemium` `Web` `CLI` `VS Code` `JetBrains`
- **[Socket](https://socket.dev/)** — يراقب تحديثات الاعتماديات بحثًا عن تغيّرات سلوك في سلسلة التوريد لا عن التحذيرات المعروفة وحدها. `Freemium` `Web` `CLI`
- **[Trivy](https://trivy.dev/)** — فاحص مفتوح المصدر للحاويات وأنظمة الملفات والمستودعات، يسهل وضعه في أي مسار آلي. `Open Source` `CLI`

## الطرفية والصدفة

سطر الأوامر، وخلفه نموذج.

- **[aichat](https://github.com/sigoden/aichat)** — عميل سطر أوامر بملف تنفيذي واحد لمزوّدي نماذج كثيرين، بتوليد أوامر صدفة مدمج. `Open Source` `CLI`
- **[Butterfish](https://butterfi.sh/)** — يغلّف صدفتك القائمة فيتقاسم التوجيه والأمر الجلسة نفسها والتاريخ نفسه. `Open Source` `macOS` `Linux` `CLI`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** — وكيل الطرفية مفتوح المصدر من Google، بخطة مجانية سخية للحسابات الشخصية. `Open Source` `CLI`
- **[mods](https://github.com/charmbracelet/mods)** — يمرّر مخرجات الأوامر عبر نموذج، فيتركّب مع كل شيء آخر في صدفة. `Open Source` `CLI`
- **[OpenCode](https://opencode.ai/)** — وكيل برمجة في الطرفية بفصل بين العميل والخادم، فتقود جلسة بعيدة من أي مكان. `Open Source` `CLI`
- **[Shell GPT](https://github.com/TheR1D/shell_gpt)** — يولّد أوامر الصدفة ويشغّلها من وصف، دون مغادرة سطر الأوامر. `Open Source` `CLI`
- **[Warp](https://www.warp.dev/)** — طرفية بمخرجات في كتل وبحث في الأوامر ووكيل يستطيع تنفيذ عمل متعدد الخطوات. `Freemium` `Windows` `macOS` `Linux`
- **[Wave Terminal](https://www.waveterm.dev/)** — طرفية مفتوحة المصدر بمعاينات ملفات ورسوم بيانية ومساعد في اللوحة نفسها. `Open Source` `Windows` `macOS` `Linux`

## الواجهات الأمامية وتوليد الواجهات

تحويل تصميم أو وصف إلى شفرة واجهة تستطيع الاحتفاظ بها.

- **[Bolt](https://bolt.new/)** — من التوجيه إلى تطبيق ويب يعمل في المتصفح، والمشروع قابل للتحرير والنشر. `Freemium` `Web`
- **[Builder.io](https://www.builder.io/)** — يحوّل إطارات Figma إلى مكوّنات في إطار عملك ونظام تصميمك. `Freemium` `Web` `API`
- **[Locofy](https://www.locofy.ai/)** — يحوّل تصاميم Figma إلى شفرة React أو Next.js أو React Native مع حفظ السلوك المتجاوب. `Freemium` `Web`
- **[Lovable](https://lovable.dev/)** — يبني تطبيقات كاملة من محادثة، والمستودع المولَّد متزامن مع GitHub. `Freemium` `Web`
- **[Magic Patterns](https://www.magicpatterns.com/)** — يولّد مكوّنات React من توجيه أو لقطة شاشة، بفرق مقابل نظام تصميمك. `Freemium` `Web`
- **[Onlook](https://onlook.com/)** — محرر بصري مفتوح المصدر لمشاريع React، يحرّر الشفرة الحقيقية خلف الصفحة المصيَّرة. `Open Source` `Web` `Windows` `macOS`
- **[Subframe](https://www.subframe.com/)** — محرر بصري يخرج React وTailwind مطابقين لمكتبة مكوّناتك أنت. `Freemium` `Web`
- **[v0](https://v0.app/)** — مولّد Vercel لواجهات React، ينتج مكوّنات shadcn/ui وTailwind تلصقها مباشرة. `Freemium` `Web` · [vs Replit](https://tiorai.com/compare/replit-ai-vs-v0/)

## كيف نختار الأدوات

تتأهل الأداة حين يستعملها مطوّر وهو يبني أو يختبر أو يطلق أو يشغّل برمجيات، وحين تتصل بموضع
يقع فيه العمل أصلًا: محرر، أو الطرفية، أو طلب دمج، أو مسار تكامل مستمر، أو نظام إنتاج.

والشرط الثالث أهمها: لا بد أن تأتي قيمة الأداة من نموذج يفعل ما لا تستطيع أداة قواعدية فعله.
فالمدقق اللغوي للشفرة غير مدرج لأنه سريع. وأداة المراجعة تُدرج حين تلتقط ما لا يستطيع المدقق
التقاطه بنيويًا.

وما لا يتأهل مهما كانت جودته: مساعد محادثة عام بلا تكامل خاص بالتطوير، وأداة كتابة أو تصميم
يصادف أن المطورين يستعملونها، ومزوّد نماذج منتجه الاستدلال لا التطوير، وبانٍ بلا شفرة موجّه
لمن لا يكتبون برمجيات.

ويُوسم مفتوح المصدر حيث تكون الرخصة معتمدة من OSI. وكثير من أدوات المطورين متاح المصدر برخصة
فيها قيد تجاري، وذلك شيء آخر لا ينال الوسم.

المداخل مرتبة أبجديًا داخل كل تصنيف. الترتيب لا يحمل معنى، ولا يوجد في هذا المستودع إدراج
مدفوع ولا رعاية ولا رابط إحالة.

## اقتراح أداة

- [اقترح أداة](../../issues/new?template=suggest-a-tool.yml)
- [أبلغ عن رابط معطّل](../../issues/new?template=report-a-broken-link.yml)

أنفع تصحيح في هذا المستودع هو إعادة التسمية. فالمنتجات في هذا الميدان تُشترى ويُعاد وسمها
باستمرار، والقائمة التي تحمل اسم منتج ميت أسوأ من قائمة ينقصها المنتج كليًا.

وإن كنت تعمل على أداة تقترحها فقل ذلك في النموذج. لن يُحتسب ضدك.

## المساهمة

اقرأ [CONTRIBUTING.md](CONTRIBUTING.md) لصيغة المدخل ولما يُرفض. والسؤال الذي يحسم أكثر
الطلبات: أين في مسار عمل المطوّر تعمل هذه الأداة؟ فإن كان الجواب «في تبويب متصفح، منفصلة»
فستُرفض عادةً.

## إخلاء مسؤولية

كل ما هو مدرج هنا تبنيه وتشغّله جهة أخرى، لا TiorAI. الأسعار والخطط المجانية والرخص وأسماء
المنتجات تتغيّر دون إشعار. افحص الرخصة الحالية قبل أن تبني على أي شيء موسوم `Open Source`،
وافحص التسعير الحالي قبل أن تلزم فريقًا بأي شيء. الإدراج هنا اختيار تحريري لا تزكية.

والأدوات التي تنفّذ شفرة أو تفتح طلبات دمج أو تتصرف في البنية التحتية تفعل ذلك بالصلاحيات
التي تمنحها إياها. ولم يُدقَّق شيء هنا، وتنطبق المراجعة المعتادة قبل أن تعطي أيًا منها صلاحية
كتابة على مستودع أو نظام إنتاج.

## الرخصة

[CC BY 4.0](LICENSE). انسخ هذه القائمة وعدّلها وأعد نشرها، تجاريًا أيضًا، بشرط نسبتها إلى
TiorAI وبيان ما غيّرته.

تغطي الرخصة الانتقاء والتصنيفات والأوصاف. ولا تغطي اسم TiorAI ولا شعارها، ولا تغطي المنتجات
المرتبطة ولا علاماتها التجارية ولا شفرتها، ولكل منها رخصته.

## عن TiorAI

[TiorAI](https://tiorai.com/) دليل لأدوات الذكاء الاصطناعي يغطي منتجات أكثر بكثير مما تغطيه
هذه القائمة، مع صفحات تعريف ومقارنات وبدائل.

هذا المستودع هو شريحته الموجّهة للمطورين، محدود بيوم عمل من يكتب برمجيات لا بسوق الذكاء
الاصطناعي كله.

- [دليل أدوات الذكاء الاصطناعي](https://tiorai.com/tools/)
- [أدوات البرمجة والتطوير](https://tiorai.com/tool-category/coding-development/)
