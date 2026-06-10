# Curriculum Vitae Template for iA Writer

Bottom-line up front: Submitting a CV will never replace knowing someone in person. Therefore, think of a CV more as a way to record your experiences rather to become employed or get a gig. Further, if the opportunity you’re applying for lists someone to contact—especially the hiring manager or recruiter—reach out to them, join affinity groups (meetups), and similar. Also, the most low-tech (plain text) and stylistically boring CV is the safest one.

[iA Writer](https://ia.net/writer) is a [markdown editor](https://ia.net/writer/support/basics/markdown-guide) for macOS, Windows, iOS, and iPadOS.

This template is to help you create a Curriculum Vitae (CV or résumé, depending on how pedantic we want to be).

There are multiple template variations you can install. The templates fall into two categories: those considered Applicant Tracking System (ATS) friendly, and those designed more for human consumption. That’s not to say the ATS-friendly versions *aren’t* human-friendly, just that ATSs have some different processing needs.

The syntax—the way you write the CV—is the same; however, when exported to the file formats supported by iA Writer, they look different. See the [Formatting Your CV](https://github.com/8fold/CV-template-for-iA-Writer#formatting-your-cv) and [Writing Your CV](https://github.com/8fold/CV-template-for-iA-Writer#writing-your-cv) sections for details.

## Installing Templates

### macOS

- Double-click a template in Finder
- Drag to iA Writer icon in Dock
- Add in Preferences → Templates

Note: Template bundles are copied when installed. Any changes made to the original bundle will not be visible in iA Writer. You may modify the installed bundles. To find an installed bundle, right-click one in Preferences and select “Show in Finder”.

### iOS

iOS supports adding template bundles, as well as ZIP archives, with one template per archive.

- Send via AirDrop
- “Copy to iA Writer” from Safari, Mail, iCloud Drive, or another sync service

### Windows (v. 1.2+)

Download the template then, from iA Writer's menu choose: File → Install Template → Select 'TemplateName.iatemplate.zip' file.

## Formatting Your CV

**Terms:**

- *Client*:  
  The legal entity you did the work with or for. (It might be difficult for some to think of an employer as a Client, but it’s valid and keeps things concise.)
- *Payer*:  
  The legal entity responsible for paying you (tax liability). (Under traditional employment contexts, the Payer and Client are the same.)
- *Role*:  
  A label or profession that encapsulates the primary responsibilities you performed. (ex. Software Developer)
- *Title*:  
  A label given to you by someone else. *Sometimes employers don’t give you profession- or responsibility-based titles.* (ex. Code Ninja)

**Standards and Sources:**

How we came to our recommendations.

- HR Open Standards: [Candidate Use Case 2 - Resume/CV Data Extraction](https://hropentech.org/4.5R/specifications/recruiting/candidate_uc002)
- HR Open Standards: [Candidate Use Case 1 - Transfer of Candidate Data from ATS to HRIS](https://hropentech.org/4.5R/specifications/recruiting/candidate_uc001)

**Recommendations:**

1. Don’t make people or systems think.
2. Use the [Gregorian calendar](https://en.wikipedia.org/wiki/Gregorian_calendar)
2. Use the same date format throughout; we recommend two-digit month, followed by a forward slash (`/`), followed by the four-digit year (`MM/YYYY`).  
   ex. 09/2026
3. *You* the individual person are the important entity and a CV is your story; front load Roles, not Payers.
4. Use *common* (boring) language.  
   You may be a highly emotional/creative/romantic individual, but the people and software systems interacting with CVs will get frustrated by the labor required to translate your language to theirs or they might not put you in the right place in their database. ex. Human Resources over Helpers of Humans.
5. Use standard dots (discs) or dashes for bulleted lists.
6. Avoid nested lists.  
   ATSs (most software meant for parsing text) does better with single levels of hierarchy in general.
7. Avoid graphics, columns, tables, special characters (this includes [ligatures](https://en.wikipedia.org/wiki/Ligature_(writing))).
8. Use common (popular) system fonts and disable ligatures or choose fonts that don’t use them.  
   ex. Times New Roman or New York (default serif on Windows and macOS, respectively), Arial or Helvetica (popular sans-serif), and Courier New or Menlo (popular monospace fonts). (ATS and other Optical Character Recognition software may not do well with that “wicked cool” font you found).
9. Avoid page headers and footers.  
   This is specifically for modern word processors where you might put page numbers, contact information on each page, and so on. (I uploaded my CV to an ATS once and it made an engagement entry for January 1905 because it thought 1/5 was a date, not page 1 of 5.)

## Writing Your CV

CVs typically operate using the [Inverted Pyramid](https://en.wikipedia.org/wiki/Inverted_pyramid_(journalism)) for content, which is that the perceived most valuable information is at the top, and less valuable is at the bottom. (The width of the triangle is perceived value, while the content’s physical position is relative to each other, which is why the pyramid is inverted.)

### Headers

To make ATS-parsing as safe as possible, we recommend using only two-levels of headers, and that you use *common* header titles; automated parsers won’t understand that “Awesomesauce” means “Professional Experience.”

Further, you can reorder these sections, and this is not an exhaustive sample of headings. For example, if you have not had much work experience, because you’ve been attending school, your “Education” section may be higher in the pyramid than your “Professional Experience” section.

```
# [Your name]

## Contact Information [optional header]

[various contact details]

## Professional Summary

[Short paragraph or so summarizing the rest of the CV with minimal extras]

## Professional Experience

[Engagements and highlights]

## Projects

[Similar to Professional Experience Engagements and Highlights, but were beyond, or tangential to, your regular duties in the Professional Experience section highlighting applied skills, with tangible results, showcasing initiative and ownership]

## Professional Certifications

[List of relevant certifications you hold or have held; delineated by the certifying body]

## Education

[List of relevant formal education]

## Skills

[List of relevant skills, which are not already covered in other sections higher in the document structure]

## Other

[List of other things you want to highlight]
```

By using the Inverted Pyramid approach the reader gets—what the author believes—is the most valuable information first, and the author (you) know what to delete first if working with limited space. 

For example, someone asks you for a two-page CV. The “Other” section can probably just be deleted. Older engagements in the “Professional Experience” section can probably go. The number of bullets in lists can be reduced by dropping the ones lower in the list.

### Professional Experience Engagement Entries

If you’re “normal” in the sense that you typically get a job with a company and typically perform duties for that company, and those duties were always related to your assigned Role, then your CV is going to be pretty straightforward. If you’re operating in the gig-economy or similar, it can be a little more challenging, because it doesn’t match what’s considered the standard (the dominant mode).

Personal story: I’ve always worked outside of companies that have hired me. I’ve frequently fulfilled responsibilities outside the scope of my hired Role; whether as an employee of a company, as a freelancer, or as a business operator myself. Therefore, trying to write a CV that *actually* tells my story has been rough. So, a fair amount of research, paying two professional CV writers, and living in the 21st century led me to create this project.

#### Standard Engagement

For the sake of your CV, we recommend using a single Role for each engagement. This should indicate/summarize what the bullets describe, without being false; don’t be shady.

```
## Professional Experience

**[Role], [Payer]** [MM/YYYY]–[MM/YYYY or present]
```

Note: In some cases, you don’t need to add “present,” because an empty end date is presumed to be “present,” but it’s recommended to explicitly write “present.”

Engagements use a single paragraph formatted specifically because different ATSs may not understand a custom pattern your’ve come up with. 

**Examples**

You (a human) are hired as Bank Teller by Company A (a legal entity who pays you directly).

```
## Professional Experience

**Bank Teller, Company A** 01/2020–present
```

If you never change Roles or employers, you’re done.

Alright, continuing from the above, you get promoted to be a Lead Teller.

```
## Professional Experience

**Lead Teller, Company A** 02/2021–present

**Bank Teller, Company A** 01/2020–02/2021
```

Even though the Payer has not changed, it would be technically inaccurate (if not unethical) to change the entry based on the Payer, because you weren’t a Lead Teller for the entire time you worked with that Payer. Further, in theory, your responsibilities will be different.

Note: If the new Role still retains some or all of the responsibilities of the previous Role, you could just add a bullet to the Lead Teller Role that says something like “Other Bank Teller responsibilities” (like a tiered subscription where “everything from the previous tier+” is applicable).

Now, let’s say you get hired as a Branch Manager at Company B.

```
## Professional Experience

**Branch Manager, Company B** 09/2023–present

**Lead Teller, Company A** 02/2021–09/2023

**Bank Teller, Company A** 01/2020–02/2021
```

Now, lets’s say you get hired by Company C. From a responsibilities-perspective, you’re a Branch Manager, but Company C uses the Title “Teller of Tellers.” Don’t ask why, they could call it “Blueberry Waffle” and it wouldn’t change your responsibilities, but putting that on your CV might confuse the hell out of a recruiter and ATS. That’s why we recommend putting the *Role* first; it summarizes the story told by the highlights and responsibilities. However, *not* listing “Teller of Tellers” somewhere could cause issues for a recruiter wishing to verify employment with the Payer; if that concerns you, follow the Role paragraph with a block quote (the greater than sign, “>”) *or* add it as one bullet in your list of responsibilities.

Note: The more ATS-friendly approach would be to make it a bullet in a list, because the ATS *may* remove or misinterpret non-list text following an engagement entry as a separate engagement. You ever upload your CV to one of those systems that will “automatically” add your information to their system, only to discover you have to fix most of it? While the system they use to do it may genuinely suck, it’s also possible that their system is geared for a specific format, and your custom layout isn’t it. Again, the most low-tech and non-designed CV is the safest; that’s why we’re using plain text with minimal syntax. Much like a toilet, a CV doesn’t need to be pretty, but it should at least work.

```
## Professional Experience

**Branch Manager, Company C** 10/2024–present

> Formal title: "Teller of Tellers."

**Branch Manager, Company B** 09/2023–10/2024

**Lead Teller, Company A** 02/2021–09/2023

**Bank Teller, Company A** 01/2020–02/2021
```

This is a straight chronological CV; one Role, with one Payer, for a specific duration—no concurrent work. Easy. But, for some, it’s inaccurate and unhelpful. What if you had a full-time role and a part-time role?


