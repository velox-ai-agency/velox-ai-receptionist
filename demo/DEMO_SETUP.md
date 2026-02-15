# Velox AI - Demo Script & Setup
## AI Receptionist Live Demo

---

## 🔧 Technical Setup

### LiveKit Server
- **URL:** `ws://localhost:7880`
- **API Key:** `S84PTPd2vQ1ZC5HijTxRYBZnj4bhFNc6`
- **API Secret:** `ybHVqYXLMqlgLf1u12scXB2Uyyb6NGZT`

### Demo Room
- **Room Name:** `demo-receptionist`
- **Participant:** `ai-receptionist`

---

## 📞 Demo Flow (10 minutes)

### 1. Introduction (2 min)
```
"أهلاً! أنا هعرض عليك كيف الـ AI Receptionist بيشتغل.
ممكن تتصل على الرقم ده [نعرض الرقم] وهتلاقي الـ AI بيرد عليك."
```

### 2. Live Call Demo (5 min)
**العميل يتصل → الـ AI يرد:**

```
AI: "أهلاً بك في [اسم الشركة]، أنا المساعد الذكي.
كيف يمكنني مساعدتك اليوم؟

[لو العميل قال: عايز أحجز موعد]
AI: "طيب! ممكن تقولي اسمك ورقم تليفونك؟"

[العميل: اسمي أحمد، رقمي 01234567890]
AI: "شكراً أحمد! أيام الجالة المتاحة:
- الأحد 10 صباحاً
- الثلاثاء 2 ظهراً
أي يوم يناسبك؟"

[العميل: الأحد 10 صباحاً]
AI: "تم حجز موعدك يوم الأحد الساعة 10 صباحاً.
هنبعتلك تأكيد على الواتساب. شكراً لتصالك!"
```

### 3. Features Demo (3 min)
**نعرض:**
- ✅ الرد التلقائي
- ✅ فهم اللهجة المصرية
- ✅ حجز المواعيد
- ✅ تسجيل البيانات

---

## 🎯 Demo Checklist

### Before Demo
- [ ] تأكد إن LiveKit شغال
- [ ] تأكد إن Agent connected
- [ ] جهز رقم للاتصال (Tunnel URL)

### During Demo
- [ ] Intro سريع
- [ ] Live call
- [ ] Show features
- [ ] Answer questions

### After Demo
- [ ] Send pricing info
- [ ] Schedule follow-up
- [ ] Send contract (if interested)

---

## 📱 Public Access (Tunnel)

### Option 1: Cloudflare Tunnel
```bash
cloudflared tunnel --url http://localhost:7880
```

### Option 2: Tailscale Funnel
```bash
tailscale funnel 7880
```

---

## 💰 Pricing Recap

| Plan | Price | Features |
|------|-------|----------|
| **Standard** | $500/mo | 500 min, bilingual, lead capture |
| **Professional** | $800/mo | 1200 min, CRM, scheduling |

### Launch Offer
- 🎁 First month FREE
- 🎁 Free setup
- 📝 No commitment

---

## 📞 Contact After Demo

**WhatsApp/Voice:** [Your number]
**Email:** [Your email]
**Website:** veloxai.com (pending)

---

**Goal: Schedule demo → Show value → Close! 🚀**