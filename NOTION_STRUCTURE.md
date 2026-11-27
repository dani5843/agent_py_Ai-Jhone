# NOTION STRUCTURE — מדריך העתקה

**[איך לבנות את כל הפרויקט ב-Notion - צעד אחר צעד]**

---

## 📋 מבנה עמודים ראשי

```
🏠 AI vs John — Master Dashboard
    │
    ├── 📊 Production Hub
    │   ├── Character Bible
    │   ├── Tone Guide
    │   ├── Episode Structure
    │   ├── Season 1 Arc
    │   └── Token Plan
    │
    ├── 🎬 Scripts
    │   ├── Batch 01 (EP 1-20)
    │   ├── Batch 02 (EP 21-40)
    │   └── Script Template
    │
    ├── 🎨 Prompts & Assets
    │   ├── Leonardo Visual Prompts
    │   ├── ElevenLabs Voice Settings
    │   ├── Ollama Agent Instructions
    │   └── Brand Assets (logo, colors)
    │
    ├── 💰 Business
    │   ├── Revenue Model
    │   ├── Affiliate Strategy
    │   ├── Sponsorship Kit
    │   ├── Metrics Tracker
    │   └── Financial Projections
    │
    ├── 📈 Analytics
    │   ├── Episode Performance
    │   ├── Growth Metrics
    │   ├── Revenue Tracking
    │   └── A/B Test Results
    │
    └── ⚖️ Legal
        ├── Copyright Notice
        ├── Trademark Plan
        └── Brand Partnerships Terms
```

---

## 🏗️ איך לבנות - צעד אחר צעד

### שלב 1: יצירת דף Master

1. פתחי Notion
2. לחצי על **"+ New Page"**
3. שם הדף: **"AI vs John — Master Dashboard"**
4. סמל (emoji): 🤖
5. תבנית: Blank page

---

### שלב 2: יצירת טבלת סטטוס ראשית

הוסיפי **Database - Table** בראש הדף:

| שדה | סוג | מטרה |
|-----|-----|------|
| Episode | Number | מספר פרק |
| Title | Text | כותרת הפרק |
| Status | Select | Draft / Ready / Posted / Analyzed |
| Views | Number | צפיות |
| Engagement | Number | אחוז engagement |
| Posted Date | Date | תאריך העלאה |
| Script Link | Relation | קישור לעמוד הסקריפט |

**ערכים ל-Status Select:**
- 🔴 Draft
- 🟡 Ready for Production
- 🟢 Posted
- 🔵 Analyzed

---

### שלב 3: בניית עמודי Sub-Pages

#### 📊 Production Hub

יצרי דף **"Production Hub"** עם 5 sub-pages:

1. **Character Bible**
   - העתקי את התוכן מ-`01_CHARACTER_BIBLE.md`
   - הוסיפי Toggle lists לכל דמות
   - הוסיפי טבלה למשפטים אופייניים

2. **Tone Guide**
   - העתקי את התוכן מ-`02_TONE_GUIDE.md`
   - הוסיפי Callout boxes לדוגמאות
   - סמני Wrong vs Right בצבעים שונים

3. **Episode Structure**
   - העתקי את התוכן מ-`03_EPISODE_STRUCTURE.md`
   - הוסיפי Template button ליצירת פרק חדש
   - Checklist לכל שלב

4. **Season 1 Arc**
   - טבלה של 10 הפרקים
   - Timeline visualization
   - קישורים לכל סקריפט

5. **Token Plan**
   - Progress bar (34,000 tokens)
   - Breakdown table
   - Running count

---

#### 🎬 Scripts Section

יצרי **Database - Gallery** עבור Scripts:

**תבנית לכל פרק:**
```
📄 Episode [X] — [Title]

Status: [Select]
Word Count: [Number]
Estimated Duration: [Text]

---

[Hook]
[Full script here]

---

Production Notes:
• Visual: [description]
• AI voice: [tone]
• John voice: [tone]
• Key moment: [what to emphasize]

---

Performance (post-posting):
Views: [number]
Engagement: [%]
Best comment: [text]
```

---

#### 🎨 Prompts & Assets

יצרי sub-pages עבור:

1. **Leonardo Visual Prompts**
   - Base scene (copy-paste ready)
   - Episode modifiers (dropdown)
   - Settings checklist

2. **ElevenLabs Voice**
   - AI voice settings
   - John voice settings
   - Sample audio links

3. **Ollama Agent**
   - System prompt (copy-paste ready)
   - Usage examples
   - Command reference

---

#### 💰 Business Section

יצרי **Dashboard page** עם 4 widgets:

**Widget 1: Revenue Tracker**
| Stream | This Month | Last Month | Total |
|--------|------------|------------|-------|
| Affiliate | $[X] | $[X] | $[X] |
| Digital Product | $[X] | $[X] | $[X] |
| Sponsorships | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** |

**Widget 2: Growth Metrics**
```
Followers:     [number] (+[%] this week)
Avg Views:     [number]
Engagement:    [%]
Profile Visits: [number]
```

**Widget 3: Next Milestones**
- [ ] First $100 month
- [ ] 10K followers
- [ ] First sponsor inquiry
- [ ] First $1,000 month

**Widget 4: This Week's Focus**
- [ ] Post EP [X-Y]
- [ ] A/B test new hook
- [ ] Email 3 potential sponsors
- [ ] Update affiliate links

---

#### 📈 Analytics Section

יצרי **Database - Table** לכל פרק:

| Episode | Posted | Views | Completion % | Profile Visits | Shares | Comments | Best Hook Score |
|---------|--------|-------|--------------|----------------|--------|----------|-----------------|
| EP01 | [date] | [X] | [%] | [X] | [X] | [X] | [1-10] |

**עמודות מחושבות:**
- Engagement Rate = (Likes + Comments + Shares) / Views
- Conversion Rate = Profile Visits / Views

---

## 🎨 עיצוב ויזואלי ב-Notion

### צבעים מומלצים

**Headers:**
- Production: 🔵 Blue
- Business: 🟢 Green
- Analytics: 🟡 Yellow
- Legal: 🔴 Red

**Callout boxes:**
- ✅ Success: Green background
- ❌ Avoid: Red background
- 💡 Tip: Yellow background
- 📝 Note: Gray background

---

## 🤖 אוטומציות (אופציונלי)

### אם יש Notion Pro:

**אוטומציה 1: Episode Status**
```
When: Script status changes to "Posted"
Then: 
  - Add to Analytics table
  - Send notification
  - Create follow-up task (check metrics in 24h)
```

**אוטומציה 2: Revenue Milestone**
```
When: Total revenue > $100
Then:
  - Check milestone box
  - Create celebration note
  - Update next milestone target
```

---

## 📱 Mobile View

**בנייה ל-mobile:**
1. Board view עבור Scripts (drag between statuses)
2. Gallery view עבור Episodes (visual thumbnails)
3. Timeline עבור posting schedule

---

## 🔗 Integration Ideas

**Link to:**
- [ ] Google Sheets (if tracking externally)
- [ ] TikTok Analytics (manual export)
- [ ] Gumroad dashboard (revenue)
- [ ] Google Drive (video files)

---

## ✅ Setup Checklist

### Essential (Week 1)
- [ ] Master dashboard created
- [ ] Episode tracker table built
- [ ] All 20 scripts uploaded
- [ ] Character Bible copied
- [ ] Prompts accessible

### Nice to Have (Week 2-4)
- [ ] Analytics database
- [ ] Revenue tracker
- [ ] Sponsor outreach tracker
- [ ] A/B test log
- [ ] Content calendar

### Advanced (Month 2+)
- [ ] Automated workflows
- [ ] Custom views per role
- [ ] Archive old seasons
- [ ] Season 2 planning section

---

## 💡 Pro Tips

1. **Use Templates**
   - Create "New Episode" button that auto-generates structure
   - Saves 5 minutes per episode

2. **Link Everything**
   - Every script should link back to Character Bible
   - Every analytics entry should link to script

3. **Color Code Status**
   - Visual scanning = faster decisions
   - Red = needs attention, Green = good to go

4. **Weekly Review Page**
   - One page with:
     - This week's posts
     - This week's revenue
     - This week's tasks
     - Next week's plan

5. **Archive Old Content**
   - After Season 1 ends, move to "Archive"
   - Keeps main workspace clean

---

## 🎯 הדף הכי חשוב - Weekly Command Center

צרי דף **"This Week"** שמתעדכן כל שבוע:

```
🗓️ Week of [Date]

📤 To Post:
- [ ] Monday: EP [X]
- [ ] Tuesday: EP [X]
- [ ] Wednesday: EP [X]
...

💰 Revenue Goal: $[X]
Current: $[Y] ([Z]%)

📊 Top Performer This Week:
EP [X] — [Y] views

🎯 Focus:
[One sentence - what matters most this week]

⚡ Quick Actions:
- [ ] Check TikTok analytics
- [ ] Reply to top 5 comments
- [ ] Update affiliate dashboard
- [ ] Plan next 5 scripts
```

---

**זה הכל. עכשיו תעתיקי את הקבצים שלי ישר ל-Notion.**

**זמן בנייה:** 2-3 שעות  
**תועלת:** לכל החיים של הפרויקט

**לכי עשי את זה עכשיו. 🚀**
