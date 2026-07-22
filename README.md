# 🌞 Solar System Calculator - India

**Interactive ROI Calculator for Residential Solar Systems** | Calculate costs, savings, payback period & government subsidies instantly

![Solar Calculator](https://img.shields.io/badge/Version-2.0-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active%20Development-success?style=flat-square)

---

## ✨ Features

### 💰 **Real-Time Calculations**
- Instant cost calculation for 3-10 kW systems
- Government subsidy integration (₹1,08,000 fixed)
- Monthly, yearly & 25-year savings projections
- Payback period analysis with panel degradation modeling

### 📊 **ROI Analysis**
- Year-by-year ROI tracking
- Cumulative savings visualization
- Investment payback timeline
- 25-year performance analysis

### 🌍 **Environmental Impact**
- CO₂ emissions saved (in tons)
- Trees equivalent calculation
- Coal consumption avoided
- Car travel equivalent

### 📱 **Lead Generation**
- WhatsApp integration for instant contact
- Free quotation form
- Email & phone support options
- Direct messaging to your team

### 🎨 **Responsive Design**
- Mobile-first approach
- Works on all devices
- Touch-friendly interface
- Smooth animations & transitions

### 📋 **Comparison Tables**
- 8 system size comparison (3-10 kW)
- Side-by-side cost analysis
- Warranty information included
- Subsidy scheme details

---

## 🚀 Quick Start

### Usage
1. Open `index.html` in any modern web browser
2. Select your desired system size (3-10 kW)
3. Adjust electricity rate (default: ₹8/unit)
4. Set savings target percentage (50-95%)
5. View instant calculations & ROI analysis
6. Fill form for free quotation

### No Installation Required
- Pure HTML5 + CSS3 + Vanilla JavaScript
- Works offline
- No dependencies
- Self-contained single file

---

## 📐 System Specifications

| Parameter | Value |
|-----------|-------|
| **Solar Panel Wattage** | 540W per panel |
| **Cost per kW** | ₹60,000 |
| **Government Subsidy** | ₹1,08,000 (Fixed) |
| **Panel Area** | 22 sq ft per panel |
| **Generation per kW** | 4.5 units/day |
| **Panel Degradation** | 0.5% per year |
| **Warranty** | 25 years (panels) |

---

## 💡 How It Works

### Cost Breakdown
```
Total Cost = System Size (kW) × ₹60,000/kW
Your Cost = Total Cost - ₹1,08,000 (Subsidy)
```

### Daily Generation
```
Daily Units = System Size (kW) × 4.5 units/kW/day
Monthly Units = Daily Units × 30 days
```

### Monthly Savings
```
Monthly Savings = Monthly Units × Electricity Rate × (Savings %/100)
```

### Payback Period
```
Payback Period = Your Cost ÷ Average Annual Savings (in years)
```

### 25-Year ROI
```
Includes:
- Panel degradation (0.5% annually)
- Annual maintenance (0.5% of gross cost)
- Cumulative savings tracking
- Break-even analysis
```

---

## 🎯 Key Metrics

### For 5 kW System (Default)
- **System Size:** 5 kW
- **Solar Panels:** 10 (540W each)
- **Total Cost:** ₹3,00,000
- **After Subsidy:** ₹1,92,000
- **Daily Generation:** 22.5 units
- **Monthly Savings:** ~₹14,400 (at 80% coverage)
- **Yearly Savings:** ~₹1,73,000 (after maintenance)
- **Payback Period:** 1.1 years
- **25-Year Total Savings:** ~₹40,00,000+

---

## 📱 Contact Integration

**WhatsApp:** [8081013935](https://wa.me/918081013935)  
**Phone:** [8181030767](tel:+918181030767)  
**Email:** [karmendra81@gmail.com](mailto:karmendra81@gmail.com)

---

## 🛡️ Warranty & Subsidy Info

### Panel Warranty
✅ 25 Years Performance Warranty  
✅ 80%+ efficiency till Year 25  
✅ Manufacturing defect covered  

### Inverter Warranty
✅ 5-10 Years  
✅ Replacement available  

### Structure Warranty
✅ 10 Years  
✅ Weatherproof design  

### Government Subsidy (MNRE)
✅ ₹1,08,000 (Fixed for residential)  
✅ Apply via MNRE Portal  
✅ Vendor must be MNRE registered  
✅ 60-90 days refund timeline  

---

## 🌍 Environmental Impact (25 Years)

For a typical 5 kW system:
- **CO₂ Saved:** ~90+ tons
- **Trees Equivalent:** ~4,000+ trees
- **Coal Saved:** ~30+ tons
- **Car Travel Equivalent:** ~400,000+ km

---

## 🧮 Calculation Features

### Interactive Inputs
- **System Size:** 3-10 kW buttons
- **Electricity Rate:** Adjustable (₹/unit)
- **Savings Target:** 50-95% slider

### Dynamic Tables
- **Comparison Table:** All 8 system sizes
- **ROI Analysis:** Year-by-year breakdown
- **Info Cards:** Real-time metrics

### Visual Feedback
- Color-coded result cards
- Gradient backgrounds
- Highlight payback year
- Select current system

---

## 📊 Data & Calculations

All calculations are based on:
- Average solar irradiance in India (4.5 kWh/m²/day)
- Conservative degradation model (0.5% annually)
- MNRE subsidy guidelines (₹1,08,000 fixed)
- Typical maintenance costs (0.5% of system cost/year)
- Standard panel specifications (540W Mono-crystalline)

---

## 🎨 Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Architecture:** Client-side only (no backend needed)
- **Styling:** Custom CSS with gradients & animations
- **Layout:** CSS Grid & Flexbox
- **Responsiveness:** Mobile-first design
- **Icons:** Unicode emojis
- **Charts:** Dynamic table generation
- **Integration:** WhatsApp, Email, Phone links

---

## 📁 Project Structure

```
solar-calculater/
├── index.html          # Single-file application
├── README.md          # Documentation
└── LICENSE            # MIT License
```

---

## 💻 Browser Compatibility

✅ Chrome 90+  
✅ Firefox 88+  
✅ Safari 14+  
✅ Edge 90+  
✅ Mobile browsers (iOS Safari, Chrome Mobile)  

---

## 🔧 Customization

### Change Contact Details
Edit the WhatsApp, phone, and email links:
```html
<a href="https://wa.me/YOUR_NUMBER">WhatsApp</a>
<a href="tel:+YOUR_NUMBER">Call</a>
<a href="mailto:YOUR_EMAIL">Email</a>
```

### Adjust Pricing
Modify constants in JavaScript:
```javascript
const COST_PER_KW = 60000;        // Change system cost
const SUBSIDY_AMOUNT = 108000;    // Change subsidy
const GEN_PER_KW = 4.5;           // Change generation rate
```

### Update Location/Language
Replace "India" text and adjust for your region

---

## 📈 Future Enhancements

- [ ] Multi-language support (Hindi, English, etc.)
- [ ] State-specific subsidy schemes
- [ ] Battery storage calculations
- [ ] Loan & financing options
- [ ] PDF quotation export
- [ ] Google Maps integration for site selection
- [ ] Weather data API integration
- [ ] CRM backend integration
- [ ] Mobile app (React Native)
- [ ] AI-powered recommendations

---

## 📞 Support & Contact

**Business Inquiries:**
- WhatsApp: [8081013935](https://wa.me/918081013935)
- Phone: [8181030767](tel:+918181030767)
- Email: [karmendra81@gmail.com](mailto:karmendra81@gmail.com)

**Technical Issues:**
- Create an issue in this repository
- Include browser details & screenshots
- Describe the problem clearly

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Credits

**Developer:** Armendra Kumar  
**Purpose:** Making solar energy accessible to every Indian household  
**Built with:** ❤️ for sustainable energy adoption  

---

## 🌟 Give Us a Star!

If this calculator helped you understand solar ROI better, please star this repository! ⭐

---

<div align="center">

### **Making Solar Energy Affordable & Accessible** ☀️

*Today's Investment in Solar = Tomorrow's Savings & Sustainability*

[GitHub](https://github.com/kaarmendra81-hue/solar-calculater) | [WhatsApp](https://wa.me/918081013935) | [Email](mailto:karmendra81@gmail.com)

**Last Updated:** July 2026

</div>
