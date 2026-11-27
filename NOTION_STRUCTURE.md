# NOTION STRUCTURE - Setup Guide

**[How to Build the Entire Project in Notion — Step by Step]**

---

## 📋 Main Page Structure

```text
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
        └── Brand Partnership Terms
```

---

## 🏗️ How to Build It — Step by Step

### Step 1: Create the Master Page

1. Open Notion.
2. Click **"+ New Page"**.
3. Name the page: **"AI vs John — Master Dashboard"**.
4. Icon (emoji): 🤖
5. Template: Blank Page.

---

### Step 2: Create the Main Status Table

Add a **Database — Table** at the top of the page:

| Property | Type | Purpose |
|-----|------|------|
| Episode | Number | Episode number |
| Title | Text | Episode title |
| Status | Select | Draft / Ready / Posted / Analyzed |
| Views | Number | Number of views |
| Engagement | Number | Engagement percentage |
| Posted Date | Date | Publishing date |
| Script Link | Relation | Link to the script page |

**Status Select options:**
- 🔴 Draft
- 🟡 Ready for Production
- 🟢 Posted
- 🔵 Analyzed

---

### Step 3: Build the Sub-Pages

#### 📊 Production Hub

Create a page called **"Production Hub"** with 5 sub-pages:

1. **Character Bible**
   - Copy the content from `01_CHARACTER_BIBLE.md`.
   - Add toggle lists for each character.
   - Add a table of signature lines.

2. **Tone Guide**
   - Copy the content from `02_TONE_GUIDE.md`.
   - Add callout boxes for examples.
   - Highlight Wrong vs. Right examples in different colors.

3. **Episode Structure**
   - Copy the content from `03_EPISODE_STRUCTURE.md`.
   - Add a template button for creating new episodes.
   - Add a checklist for each stage.

4. **Season 1 Arc**
   - Create a table covering all 10 episodes.
   - Add a timeline visualization.
   - Link each entry to its corresponding script.

5. **Token Plan**
   - Add a progress bar (34,000 tokens).
   - Add a breakdown table.
   - Track the running total.

---

#### 🎬 Scripts Section

Create a **Database — Gallery** for scripts.

**Template for Each Episode:**

```text
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

Performance (After Posting):
Views: [number]
Engagement: [%]
Best comment: [text]
```

---

#### 🎨 Prompts & Assets

Create sub-pages for:

1. **Leonardo Visual Prompts**
   - Base scene (ready to copy and paste)
   - Episode modifiers (dropdown)
   - Settings checklist

2. **ElevenLabs Voice**
   - AI voice settings
   - John voice settings
   - Sample audio links

3. **Ollama Agent**
   - System prompt (ready to copy and paste)
   - Usage examples
   - Command reference

---

#### 💰 Business Section

Create a **Dashboard Page** with 4 widgets:

**Widget 1: Revenue Tracker**

| Stream | This Month | Last Month | Total |
|--------|------------|------------|-------|
| Affiliate | $[X] | $[X] | $[X] |
| Digital Product | $[X] | $[X] | $[X] |
| Sponsorships | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** |

**Widget 2: Growth Metrics**

```text
Followers:      [number] (+[%] this week)
Average Views:  [number]
Engagement:     [%]
Profile Visits: [number]
```

**Widget 3: Next Milestones**
- [ ] First $100 revenue month
- [ ] 10K followers
- [ ] First sponsor inquiry
- [ ] First $1,000 revenue month

**Widget 4: This Week's Focus**
- [ ] Publish EP [X-Y]
- [ ] A/B test a new hook
- [ ] Email 3 potential sponsors
- [ ] Update affiliate links

---

#### 📈 Analytics Section

Create a **Database — Table** for episode performance:

| Episode | Posted | Views | Completion % | Profile Visits | Shares | Comments | Best Hook Score |
|---------|--------|-------|--------------|----------------|--------|----------|-----------------|
| EP01 | [date] | [X] | [%] | [X] | [X] | [X] | [1-10] |

**Calculated Properties:**
- Engagement Rate = (Likes + Comments + Shares) / Views
- Conversion Rate = Profile Visits / Views

---

## 🎨 Visual Design in Notion

### Recommended Colors

**Headers:**
- Production: 🔵 Blue
- Business: 🟢 Green
- Analytics: 🟡 Yellow
- Legal: 🔴 Red

**Callout Boxes:**
- ✅ Success: Green background
- ❌ Avoid: Red background
- 💡 Tip: Yellow background
- 📝 Note: Gray background

---

## 🤖 Automations (Optional)

### If You Have Notion Pro

**Automation 1: Episode Status**

```text
When: Script status changes to "Posted"
Then:
  - Add to Analytics table
  - Send notification
  - Create follow-up task (check metrics in 24h)
```

**Automation 2: Revenue Milestone**

```text
When: Total revenue > $100
Then:
  - Check milestone box
  - Create celebration note
  - Update next milestone target
```

---

## 📱 Mobile View

**Mobile Setup:**
1. Use Board view for Scripts (drag between statuses).
2. Use Gallery view for Episodes (visual thumbnails).
3. Use Timeline view for the posting schedule.

---

## 🔗 Integration Ideas

**Connect to:**
- [ ] Google Sheets (if tracking externally)
- [ ] TikTok Analytics (manual export)
- [ ] Gumroad dashboard (revenue)
- [ ] Google Drive (video files)

---

## ✅ Setup Checklist

### Essential (Week 1)
- [ ] Create the Master Dashboard
- [ ] Build the episode tracker table
- [ ] Upload all 20 scripts
- [ ] Copy the Character Bible
- [ ] Make prompts accessible

### Nice to Have (Weeks 2-4)
- [ ] Analytics database
- [ ] Revenue tracker
- [ ] Sponsor outreach tracker
- [ ] A/B testing log
- [ ] Content calendar

### Advanced (Month 2+)
- [ ] Automated workflows
- [ ] Custom views for each role
- [ ] Archive previous seasons
- [ ] Add a Season 2 planning section

---

## 💡 Pro Tips

1. **Use Templates**
   - Create a "New Episode" button that automatically generates the episode structure.
   - Saves 5 minutes per episode.

2. **Link Everything**
   - Every script should link back to the Character Bible.
   - Every analytics entry should link to its script.

3. **Color-Code Status**
   - Visual scanning means faster decisions.
   - Red = needs attention; Green = ready to go.

4. **Weekly Review Page**
   - Create one page containing:
     - This week's posts
     - This week's revenue
     - This week's tasks
     - Next week's plan

5. **Archive Old Content**
   - After Season 1 ends, move it to an "Archive" section.
   - Keeps the main workspace clean.

---

## 🎯 The Most Important Page — Weekly Command Center

Create a page called **"This Week"** that gets updated every week:

```text
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
[One sentence — what matters most this week]

⚡ Quick Actions:
- [ ] Check TikTok analytics
- [ ] Reply to the top 5 comments
- [ ] Update affiliate dashboard
- [ ] Plan the next 5 scripts
```

---

**That's it. Now copy your files directly into Notion.**

**Setup time:** 2-3 hours  
**Benefit:** For the entire lifetime of the project

**Go build it now. 🚀**
