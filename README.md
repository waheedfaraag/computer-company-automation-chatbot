# Computer Company AI Chatbot (n8n Automation)

مشروع أتمتة متكامل لبناء شات بوت ذكي مخصص لشركات الكمبيوتر باستخدام منصة **n8n**.

## 🚀 مميزات المشروع (Features)
- **AI Agent Node:** يمتلك البوت القدرة على فهم سياق العميل واتخاذ القرارات تلقائياً.
- **Google Gemini Integration:** الاعتماد على نموذج ذكاء اصطناعي متطور للاستجابة السريعة والدقيقة.
- **Simple Memory:** البوت يتذكر المحادثة السابقة مع العميل لتقديم تجربة سلسة.
- **Gmail Automation:** إرسال رسائل بريد إلكتروني تلقائية بناءً على طلب العميل أو تأكيد الطلب.
- **Google Sheets Integration:** (قيد التطوير/مدمج) لقراءة بيانات المنتجات والأسعار وتحديثها.

## 🛠️ الأدوات المستخدمة (Tech Stack)
- [n8n](https://n8n.io/) - لمنظومة الأتمتة وسير العمل.
- Google Gemini Chat Model - كعقل مدبر للبوت.
- Gmail Tool - لإرسال الإيميلات.
- Google Sheets Tool - لإدارة البيانات.

## 📸 مخطط سير العمل (Workflow Screenshot)
![Workflow](./computer%20compuny%20chatbot.png)

## ⚙️ كيف تشغل المشروع؟ (How to use)
1. قم بتحميل ملف `n8n_workflow.json` الموجود في هذا المستودع.
2. افتح حساب n8n الخاص بك واعمل له Import.
3. قم بربط الحسابات الخاصة بك (Gemini API Key, Gmail Credentials, Google Sheets).
