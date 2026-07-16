# My Website Maintenance Guide
## For Sai Sharat Khambampati
### Last Updated: June 2026

---

# WHAT I HAVE AND WHERE IT LIVES

I have two websites and one resume file:

| What | File Name | Where It Lives Online |
|---|---|---|
| Project Portfolio | aevolan.html | www.aevolantech.com (Vercel) |
| Career Portfolio | index.html | ksaisharatkumar.github.io (GitHub) |
| Resume | SaiSharat_Resume_Premium.docx | Embedded inside index.html |

**Rule to remember:**
- Changes to AEVOLAN projects, KODE, about me as a builder → edit aevolan.html → upload to Vercel
- Changes to career experience, certifications, education, skills → edit index.html → upload to GitHub
- Changes to resume content → edit the .docx → re-embed into index.html → upload to GitHub

---

# PART 1 — HOW TO EDIT ANY FILE

## The Tool I Need: VS Code (Free)
Download from: code.visualstudio.com
Install it. Open it. Drag any .html or .docx file into it to open.

## The Magic Button: Ctrl + H (Find and Replace)
This is how I make all changes without knowing any code.
- Press Ctrl+H on Windows (or Cmd+H on Mac)
- Top box = what to find
- Bottom box = what to replace it with
- Click Replace All

---

# PART 2 — UPDATING AEVOLAN (aevolantech.com)

## How to Upload to Vercel After Any Change

1. Go to vercel.com and sign in
2. Click on my AEVOLAN project
3. Click Deployments
4. Drag and drop the aevolan.html file (renamed to index.html) into the upload area
5. Wait 30 seconds
6. Visit www.aevolantech.com to confirm it is live

---

## CHANGE A1 — Add a New Project to AEVOLAN

Open aevolan.html in VS Code.
Press Ctrl+F and search for: HOW TO ADD A NEW PROJECT

You will find a template comment block. Copy this template:

```
<div class="proj-card">
    <div class="proj-card-body">
        <span class="proj-tag">CATEGORY . SUBCATEGORY</span>
        <h3>Project Name</h3>
        <p>2-3 sentence description of what it does and who it is for.</p>
        <div class="proj-meta">
            <span>Tech 1</span><span>Tech 2</span><span>Key Feature</span>
        </div>
    </div>
    <div class="proj-actions">
        <a href="https://your-live-url.com" target="_blank" class="btn-primary">View Live</a>
        <button class="btn-secondary" onclick="requestDemo('Project Name')">Request Demo</button>
    </div>
</div>
```

Paste it just before the line that says: closing div of grid-2
Fill in the details. Save. Upload to Vercel.

Also add it to the contact dropdown. Search for: Select a project or topic
Copy one of the option lines and update the name.

---

## CHANGE A2 — Update About Me Text on AEVOLAN

Search for: I independently design and ship technology products
Edit the paragraph text around it.
Save. Upload to Vercel.

---

## CHANGE A3 — Update KODE Methodology Cards

Search for: K. Knowledge
The four cards are right there. Edit the text inside each card.
Save. Upload to Vercel.

---

## CHANGE A4 — Update Contact Email

Search for: aevolantechnologies@gmail.com
Replace with new email if it ever changes.
It appears in 2 places. Replace both.

---

# PART 3 — UPDATING GITHUB PORTFOLIO (ksaisharatkumar.github.io)

## How to Upload to GitHub After Any Change

1. Go to github.com and sign in
2. Go to my repository: github.com/ksaisharatkumar/ksaisharatkumar.github.io
3. Click Add file then Upload files
4. Drag my updated index.html file into the box
5. Scroll down and click Commit changes
6. Wait 2 minutes
7. Visit ksaisharatkumar.github.io to confirm

---

## CHANGE G1 — Add a New Job to Experience

Open index.html in VS Code.
Search for: SEP 2021 (my current job start date)

Just above this, paste a new job block:

```
<div class="tl-item">
  <div class="tl-period">MON YEAR to MON YEAR</div>
  <div class="tl-role">My Job Title</div>
  <div class="tl-co">Company Name</div>
  <ul class="tl-ul">
    <li>What I did, outcome focused, one sentence</li>
    <li>Second achievement</li>
    <li>Third achievement</li>
  </ul>
</div>
```

Save. Upload to GitHub.

---

## CHANGE G2 — Add a New Certification

I need to update THREE places for a new certification.

PLACE 1 — The cert bar at the top of the page:
Search for: Fabric Analytics Engineer
Copy the block just above it and paste a new one:

```
<div class=cb-badge>
  <div class=ms-sq><span></span><span></span><span></span><span></span></div>
  <div class=cb-text>New Cert Name . Level</div>
</div>
```
For non-Microsoft certs, remove the ms-sq div.

PLACE 2 — The certifications section:
Search for: id="certifications"
Copy any cert card and update the name and year.

PLACE 3 — The chatbot:
Search for: Sai holds: and add the new cert to that sentence.

Save. Upload to GitHub.

---

## CHANGE G3 — Add a New Skill

Search for: CLOUD and DATA PLATFORMS
The skill groups are listed there. Find the right group and add:

```
<span class="pill">New Skill Name</span>
```

inside the pills div of that group.
Save. Upload to GitHub.

---

## CHANGE G4 — Update Years of Experience

If it changes from 15+ to 16+:
Press Ctrl+H
Find: 15+
Replace: 16+
Click Replace All
Save. Upload to GitHub.

---

## CHANGE G5 — Update Contact Details

Search for: saisharat2906@gmail.com
Replace with new email if it changes. It appears 2-3 times.

Search for: 210-216-8499
Replace with new number if it changes.

---

## CHANGE G6 — Add a New Project to the Portfolio

Search for: proj-name">ZeroToAI
Paste a new project card just after the ZeroToAI closing div:

```
<div class="proj">
  <div class="proj-cat">CATEGORY . SUBCATEGORY</div>
  <div class="proj-name">Project Name</div>
  <div class="proj-desc">Description here.</div>
  <div class="techs">
    <span class="tech">Tech 1</span>
    <span class="tech">Tech 2</span>
  </div>
  <div class="proj-actions">
    <a href="https://live-url.com" target="_blank" class="btn-ink">View Live</a>
    <button class="btn-outline">Request Demo</button>
  </div>
</div>
```

Save. Upload to GitHub.

---

## CHANGE G7 — Update Chatbot Answers

The chatbot answers are stored in a list inside the file.
Search for the topic keyword, for example: fabric
Find the line starting with: k:["fabric"
Edit the text after: a:"
Important: Never use apostrophes inside the answer. Write "Sai has" not "Sai's".
Save. Upload to GitHub.

---

# PART 4 — UPDATING THE RESUME

## CHANGE R1 — Simple Text Edits (Do It Yourself in Word)

Open SaiSharat_Resume_Premium.docx in Microsoft Word or Google Docs.
Make changes directly:
- New job bullet points
- Update years of experience
- Add new certification
- Change contact details

Save as .docx format. Do not save as PDF.

Important rules when editing:
- Never use em dashes like this character: —
- Use commas, periods, or the word "and" instead
- Keep the same font and style as existing content

---

## CHANGE R2 — Re-Embed the Resume into the GitHub Portfolio

Every time I update the resume I must re-embed it into index.html so the download button gives visitors the latest version.

Step 1 — Convert the .docx to Base64:
Go to this website: base64.guru/converter/encode/file
Click Choose File and select my updated .docx file
Click Encode to Base64
Click Copy to Clipboard (the result is a very long string of letters and numbers, that is normal)

Step 2 — Replace the old resume in index.html:
Open index.html in VS Code
Press Ctrl+H
In the Find box type exactly: var B64 = "
Find that line in the file
Delete everything between the opening quote and the closing ";
Paste the new Base64 string between the quotes
The line should now look like: var B64 = "UEsDB...verylongstring...";
Save the file

Step 3 — Upload to GitHub:
Follow the GitHub upload steps in Part 3 above
Test by visiting ksaisharatkumar.github.io and clicking the Resume button
The downloaded file should be my latest version

---

# PART 5 — ADDING THE SOAMED AI INTERFACE SCREENS

The Soamed AI card has a Learn More button that shows interface screenshots.
These screens come from the file: soamed-ai-mockscreens.html

If I ever update the Soamed AI interface and want to update the screens:
1. Save the new screens file as soamed-ai-mockscreens.html
2. Bring it to Claude with this message:
"Please update the Soamed AI Learn More screens in my aevolan.html with this new file"

---

# PART 6 — IMPORTANT RULES FOR ALL EDITS

NEVER use these characters in any content:
- Em dash: —
- Use commas, periods, colons, or the word "and" instead

NEVER use these words if they sound AI-generated:
- "Leveraging", "Utilizing", "Seamlessly", "Robust"
- Write naturally as if explaining to a colleague

ALWAYS test after uploading:
- Visit the live site on your phone
- Click through all tabs
- Test any button you changed
- Check on both Chrome and Safari

ALWAYS keep a backup:
- Before making big changes, save a copy of the file with today's date
- Example: aevolan_backup_june2026.html

---

# PART 7 — QUICK REFERENCE

## Where Everything Is Published

| Site | How to Update | URL After Update |
|---|---|---|
| AEVOLAN | Upload to Vercel | www.aevolantech.com |
| GitHub Portfolio | Upload to GitHub | ksaisharatkumar.github.io |

## Search Terms Cheat Sheet

| What I Want to Change | Search For This |
|---|---|
| AEVOLAN about me text | I independently design |
| AEVOLAN projects | HOW TO ADD A NEW PROJECT |
| AEVOLAN contact email | aevolantechnologies@gmail.com |
| GitHub experience timeline | SEP 2021 |
| GitHub certifications | id="certifications" |
| GitHub skills | CLOUD and DATA PLATFORMS |
| GitHub projects | proj-name">ZeroToAI |
| GitHub chatbot answers | k:["fabric" or any keyword |
| Resume in portfolio | var B64 = " |
| Years of experience | 15+ |
| Portfolio URL | aevolantech.com |

## When to Come Back to Claude

| Situation | Need Claude? |
|---|---|
| Add new bullet to existing job | No, edit directly in Word |
| Add new certification | No, follow Change G2 above |
| Add new skill | No, follow Change G3 above |
| Update contact details | No, follow Change G5 above |
| New job section formatted correctly | Yes |
| Complete resume rewrite for a role | Yes |
| New section or major redesign | Yes |
| Re-embed resume after updates | No, follow Change R2 above |
| Soamed AI interface screens update | Yes |
| Counter feature with JSONBin | Yes, when ready |
| Anime avatar Phase 2 | Yes, when ready |
| Site looks broken after edits | Yes |

---

# PART 8 — UPCOMING FEATURES (When Ready)

These are planned but not yet built:

1. Interest counters on each project card (needs JSONBin account)
   When ready: share JSONBin Bin ID and API Key with Claude

2. Reached out counter in nav (needs JSONBin)
   Same as above

3. Anime avatar on GitHub portfolio
   When ready: share photo and Claude will guide through HeyGen or build interactive version

---

*Guide prepared June 2026*
*AEVOLAN: www.aevolantech.com*
*GitHub Portfolio: ksaisharatkumar.github.io*
*Contact: saisharat2906@gmail.com*
