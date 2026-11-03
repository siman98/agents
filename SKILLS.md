# مهارات صفحات الويب (Claude Code Skills)

هذا المستودع يحتوي على سوق إضافات (plugin marketplace) باسم `siman-web-skills` يضم مهارات لإنشاء صفحات وملفات HTML:

| الإضافة | المحتوى |
|---|---|
| `html-skills` | 17 مهارة HTML (خطط ومواصفات، مخططات SVG ومعمارية، عروض شرائح، رموز التصميم، مستكشف بيانات، خرائط ذهنية، مصفوفات مقارنة، جداول زمنية، قوائم اختبار...) — المصدر: [f-labs-io/agent-html-skills](https://github.com/f-labs-io/agent-html-skills) برخصة MIT |
| `html-visualization` | مهارة لإنشاء صفحات HTML تفاعلية (صفحة طويلة، عرض شرائح، لوحة معلومات، إنفوجرافيك) مع مخططات Mermaid |

## الاستخدام في أي مشروع جديد

داخل Claude Code:

```text
/plugin marketplace add siman98/agents
/plugin install html-skills@siman-web-skills
/plugin install html-visualization@siman-web-skills
```

أو انسخ ملف `.claude/settings.json` من هذا المستودع إلى مشروعك الجديد، فتُفعَّل الإضافتان تلقائيًا.

بعد التثبيت لا تحتاج لاستدعاء المهارات يدويًا؛ يختار Claude المهارة المناسبة حسب الطلب (مثل: "اعمل لي عرض شرائح HTML" أو "ارسم مخطط معمارية النظام").
