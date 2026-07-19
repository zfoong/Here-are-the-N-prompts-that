---
title: "7 Claude Cowork prompts that automate your most annoying tasks"
domain: productivity
source_url: "https://www.reddit.com/r/promptingmagic/comments/1s7gys7/7_claude_cowork_prompts_that_automate_your_most"
platform: reddit
author: "u/Beginning-Willow-801"
---

# 7 Claude Cowork prompts that automate your most annoying tasks

[← All prompt packs](../../CATALOG.md) · **Productivity** · [Original post ↗](https://www.reddit.com/r/promptingmagic/comments/1s7gys7/7_claude_cowork_prompts_that_automate_your_most)

## Prompts

Copy a prompt and replace the bracketed text with your own context.

### 1. Clean and Organize Any Messy Folder

```text
Scan every file in this folder. Create the following subfolders if they do not already exist: Documents, Spreadsheets, Images, Videos, Audio, Installers, Archives, and Old Files. For each file: 1. Identify what type of file it is based on both its extension AND its content. 2. Move it into the correct subfolder. 3. If a file is older than 6 months based on its last modified date, move it to the Old Files folder instead. 4. If you find duplicate files, put the duplicates in a subfolder called Duplicates inside each category folder. 5. For PDF files specifically: read the content. If it is an invoice or receipt, move it to Documents/Invoices. If it is a manual or guide, put it in Documents/Reference. Do not delete any files under any circumstances. When finished, create a file called Organization_Report.md that includes total files processed, how many went into each folder, duplicate files found, and any unclassified files (put these in a folder called Unsorted).
```

### 2. Create a Meeting Summary Document

```text
Read all files in this folder containing notes from our team meetings. Create a professional summary document called Meeting_Summary.docx with the following structure: SECTION 1 - EXECUTIVE OVERVIEW Write 3-5 sentences capturing the single most important takeaway. A busy executive should understand the situation from this section alone. SECTION 2 - KEY TOPICS DISCUSSED For each major topic, write a short paragraph explaining what was discussed and why it matters. Group related discussions together. SECTION 3 - DECISIONS MADE Create a numbered list of every concrete decision, noting which meeting it came from and who proposed it. SECTION 4 - ACTION ITEMS Create a table with columns: Action Item, Owner, Deadline, and Status. Fill in every task mentioned. If no deadline was stated, write TBD. If no owner was named, write Unassigned. SECTION 5 - OPEN QUESTIONS List anything raised but not resolved. Keep the entire document under 500 words. Use clear, direct language.
```

### 3. Build a Meeting Presentation from Notes

```text
Read all files in this folder containing background material for a presentation. Create a PowerPoint presentation called Meeting_Slides.pptx with exactly 10 slides: Slide 1: Title slide with topic and date Slide 2: Agenda Slide 3: Context and background Slides 4-6: Key findings or data points (one major point per slide, max 4 supporting bullets) Slides 7-8: Recommendations based on findings Slide 9: Timeline and next steps with owners Slide 10: Discussion and questions Design rules: - Maximum 6 lines of text per slide. - Use concise phrases, no full sentences. - Include a short speaker note beneath each slide with 2-3 sentences for talking points. - If data works well as a simple chart or table, include it.
```

### 4. Research and Write an Article on Any Topic

```text
I need a research paper on: [YOUR TOPIC] Step 1 - Research Use the browser to visit and read these sources: [paste URLs] Also read any documents inside the Research Materials subfolder. Step 2 - Write Create a document called Research_Report.docx structured as follows: - EXECUTIVE SUMMARY (200 words max) - BACKGROUND AND CONTEXT - CURRENT LANDSCAPE (Use specific facts and figures from sources) - ANALYSIS AND INSIGHTS (Where do experts agree/disagree?) - IMPLICATIONS AND RECOMMENDATIONS - SOURCES (List every source referenced with a one-sentence description) Rules: - Write in professional prose. No bullet-point lists in the body. - Every major claim must reference its source. - Total length: 1500-2500 words.
```

### 5. Extract Receipt Data into a Spreadsheet

```text
This folder contains images and PDFs of receipts and invoices. For each file: 1. Extract: Date of purchase, Store name, Description of purchase, Total amount paid, Payment method. 2. If you cannot read a field, write CHECK THIS instead of guessing. Create a spreadsheet called Expenses.xlsx with columns: Date (YYYY-MM-DD), Store, Description, Amount (numbers only), Payment Method, Source File. Sort all rows by date, oldest first. Add a SUM formula at the bottom of the Amount column. Add a second sheet called Summary grouping spending by Store, sorted highest to lowest.
```

### 6. Supercharge a To-Do List

```text
Read the To-Do List file in this folder. STEP 1 - TRIAGE For any urgent task: Create a separate file in an Urgent subfolder. Inside, write what the task is and 2-3 suggested first actions to start immediately. STEP 2 - RESEARCH For tasks needing research: Use the browser to find 3-5 high-quality sources. Add links and one-sentence summaries directly to the original file. STEP 3 - RESTRUCTURE Rewrite the entire list as Action_Plan.md organized into: DO TODAY, DO THIS WEEK, SCHEDULE FOR LATER, WAITING ON SOMEONE ELSE, and SOMEDAY MAYBE. Add estimated times to complete. Rewrite vague tasks into specific next steps.
```

### 7. Turn a Blog Post into a Content Calendar

```text
Read the blog post file in this folder. Create a Social_Content_Calendar.docx with: SECTION 1 - TWITTER/X THREAD (10 posts) Write a 10-post thread telling the main story. Under 280 characters each. Hook in post 1, call to action in post 10. SECTION 2 - LINKEDIN POST Write one post (1000-1300 characters) presenting the key insight. Open with a bold statement, use short paragraphs, end with a question. SECTION 3 - EMAIL NEWSLETTER BLURB Write a 150-word summary teasing the value with a call to action. SECTION 4 - SHORT-FORM VIDEO SCRIPT Write a 60-second script. Include a 3-second hook, main point, and closing engagement line. SECTION 5 - PULL QUOTES Extract 5 standalone quotes (10-20 words) for graphics. SECTION 6 - SUGGESTED HASHTAGS Provide 15 relevant hashtags: 5 broad, 5 niche, 5 branded.
```
