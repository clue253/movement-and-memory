---
title: EPIC Documentation Guide
parent: Learner Resources
nav_order: 1
has_toc: false
---

<div class="epic-guide" markdown="1">

# EPIC Documentation Guide

Learn the documentation workflow used in Dr. Morgan's clinic.

This guide covers:

- Saving the required SmartPhrases
- Creating notes for new and returning patients
- Reviewing documentation before presentation
- Reviewing an example completed clinic note

{% capture sample_note_top_content %}

<div class="guide-callout">

<strong>Review this first</strong>

Before documenting your first patient, review this completed clinic note to become familiar with the expected organization, formatting, and level of detail used in Dr. Morgan's clinic.

</div>

<div class="sample-note-gallery">

  <figure class="sample-note-page">
    <img src="{{ '/assets/images/epic/sample-note/firstpartofnoteex.png' | relative_url }}" alt="Full example clinic note showing assessment, history, examination, plan, and signatures">
    <figcaption>Full example completed clinic note.</figcaption>
  </figure>

  <figure class="sample-note-page sample-note-page-narrow">
    <img src="{{ '/assets/images/epic/sample-note/secondnoteex.png' | relative_url }}" alt="Detailed view of the assessment, plan, problem list, and signature section from the same example clinic note">
    <figcaption>Detailed view of the assessment, plan, problem list, and signature section from the same note.</figcaption>
  </figure>

</div>

Sorry, I was fighting AI, so this is the best i got rn.

<div class="guide-callout">

<strong>Remember</strong>

Use this example to understand the overall organization and formatting of a clinic note. Every patient note should be individualized and updated to accurately reflect today's visit.

</div>

{% endcapture %}

{% include accordion.html
  id="example-clinic-note"
  title="Example Completed Clinic Note"
  description="Review a completed note before documenting your first patient"
  content=sample_note_top_content
%}

<div class="guide-callout" markdown="1">

<strong>Jump to</strong>

- [Before Your First Clinic](#before-your-first-clinic)
- [Saving the SmartPhrases](#saving-the-smartphrases)
- [Using the SmartPhrases](#using-the-smartphrases)
- [Creating Today's Note](#creating-todays-note)
- [New Patient Documentation](#new-patient-documentation)
- [Returning Patient Documentation](#returning-patient-documentation)
- [Before Sending or Pending the Note](#before-sending)
- [Final Review Checklist](#final-review)
- [Example Completed Clinic Note](#example-clinic-note)

</div>

{% capture before_clinic_content %}

<div class="guide-callout">

<strong>One-Time Setup</strong>

These steps only need to be completed once. After the SmartPhrases are copied into your account, they should remain available for future clinics.

</div>

Before documenting patients for the first time, save the required SmartPhrases from **Caty Lue**.

## Required SmartPhrases

| SmartPhrase | Purpose |
|---|---|
| `.AJPE` | Physical examination |
| `.KMROS` | Review of systems |
| `.CELNEWPATIENT` | New-patient note template |

{% endcapture %}

{% include accordion.html
  id="before-your-first-clinic"
  title="Before Your First Clinic"
  description="Complete the required one-time setup"
  content=before_clinic_content
%}

{% capture saving_smartphrases_content %}

## Step 1 — Open the EPIC Menu

Double-click the EPIC hamburger menu.

<figure class="epic-tutorial-card epic-tutorial-card-small">
  <img src="{{ '/assets/images/epic/EPIChamburger.png' | relative_url }}" alt="EPIC hamburger menu">
  <figcaption>Double-click the EPIC hamburger menu to open the search menu.</figcaption>
</figure>

---

## Step 2 — Open My SmartPhrases

1. Search for **SmartPhrase**.
2. Select **My SmartPhrases**.

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/searchSP.png' | relative_url }}" alt="Search results for My SmartPhrases in EPIC">
  <figcaption>Search for SmartPhrase, then select My SmartPhrases.</figcaption>
</figure>

---

## Step 3 — Search for Caty Lue

1. Search for **Caty Lue**.
2. Open Caty Lue’s SmartPhrases.
3. Locate:
   - `AJPE`
   - `KMROS`
   - `CELNEWPATIENT`

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/searchme.png' | relative_url }}" alt="Searching for Caty Lue's SmartPhrases in EPIC">
  <figcaption>Search for Caty Lue to view the required SmartPhrases.</figcaption>
</figure>

---

## Step 4 — Create a Copy

For each required SmartPhrase:

1. Double-click the SmartPhrase.
2. Click **Create Copy**.

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/createcopy.png' | relative_url }}" alt="Create Copy button for a SmartPhrase in EPIC">
  <figcaption>Click Create Copy after opening the SmartPhrase.</figcaption>
</figure>

---

## Step 5 — Keep the Original Name

Keep the SmartPhrase name unchanged so it matches the names used throughout this handbook.

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/rename.png' | relative_url }}" alt="SmartPhrase naming screen in EPIC">
  <figcaption>Keep the original SmartPhrase name unchanged.</figcaption>
</figure>

---

## Step 6 — Save the SmartPhrase

1. Click **Accept** or **Save**.
2. Close the SmartPhrase tab.
3. Repeat the process for all three required SmartPhrases.

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/saveit.png' | relative_url }}" alt="Save or accept button for a SmartPhrase in EPIC">
  <figcaption>Accept or save the copied SmartPhrase.</figcaption>
</figure>

{% endcapture %}

{% include accordion.html
  id="saving-the-smartphrases"
  title="Saving the SmartPhrases"
  description="Copy the required phrases from Caty Lue"
  content=saving_smartphrases_content
%}

{% capture using_smartphrases_content %}

After the SmartPhrases have been saved, they can be inserted into any note by typing a period (`.`) followed by the SmartPhrase name and pressing **Enter/Return**.

## New Patient Template

Use this SmartPhrase when starting a **new patient note**.

```text
.CELNEWPATIENT
```

Press **Enter/Return** to populate the complete new-patient template.

---

## Physical Examination

Use this SmartPhrase only when you need to insert or replace a physical examination section within a note.

```text
.AJPE
```

Press **Enter/Return** to populate the physical examination template.

---

## Review of Systems

Use this SmartPhrase only when you need to insert or replace a Review of Systems section within a note.

```text
.KMROS
```

Press **Enter/Return** to populate the Review of Systems section.

{% endcapture %}

{% include accordion.html
  id="creating-todays-note"
  title="Creating Today's Note"
  description="Begin with a blank note in the correct encounter"
  content=creating_note_content
%}

{% capture new_patient_content %}

For both new and returning patients:

1. Open the patient’s chart.
2. Click the **Create New Note** dropdown.
3. Select **Blank Note**.

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/blanknote.png' | relative_url }}" alt="Blank Note option under Create New Note in EPIC">
  <figcaption>Select Blank Note from the Create New Note dropdown.</figcaption>
</figure>

{% endcapture %}

{% include accordion.html
  id="creating-todays-note"
  title="Creating Today's Note"
  description="Begin with a blank note in the correct encounter"
  content=creating_note_content
%}

{% capture new_patient_content %}

<div class="guide-callout">

<strong>When should I use this?</strong>

Use this workflow whenever you are documenting a patient's **first visit** with Dr. Morgan.

</div>

## Step 1 — Create a Blank Note

1. Open the patient's chart.
2. Click **Create New Note**.
3. Select **Blank Note**.

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/blanknote.png' | relative_url }}" alt="Blank Note option under Create New Note in EPIC">
  <figcaption>Select <strong>Blank Note</strong> from the Create New Note menu.</figcaption>
</figure>

---

## Step 2 — Insert the New Patient Template

Type:

```text
.CELNEWPATIENT
```

Press **Enter/Return** to populate the complete new-patient template.

<div class="guide-callout">

<strong>Tip</strong>

This SmartPhrase automatically inserts the clinic's standard new-patient documentation template.

</div>

---

## Step 3 — Complete the Note

- Complete every applicable section.
- Remove all instructional text.
- Remove unused placeholders.
- Confirm the note reflects the correct patient and encounter.
- Verify all copied information is accurate.

---

## Step 4 — Insert Additional SmartPhrases When Needed

If you need to **add or replace** the Physical Examination or Review of Systems, insert the appropriate SmartPhrase.

### Physical Examination

```text
.AJPE
```

### Review of Systems

```text
.KMROS
```

<div class="guide-callout">

<strong>Important</strong>

Use <code>.AJPE</code> and <code>.KMROS</code> only when you need to insert or replace those individual sections. They do not replace the complete <code>.CELNEWPATIENT</code> template.

</div>

{% endcapture %}

{% include accordion.html
  id="new-patient-documentation"
  title="New Patient Documentation"
  description="Create and complete a new-patient note"
  content=new_patient_content
%}

{% capture returning_patient_content %}

<div class="guide-callout">

<strong>When should I use this?</strong>

Use this workflow for follow-up or established patients who have previously been seen in Dr. Morgan's clinic.

</div>

## Step 1 — Create a Blank Note

1. Open the patient's chart.
2. Click **Create New Note**.
3. Select **Blank Note**.

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/blanknote.png' | relative_url }}" alt="Blank Note option under Create New Note in EPIC">
  <figcaption>Select <strong>Blank Note</strong> from the Create New Note menu.</figcaption>
</figure>

---

## Step 2 — Populate the Previous Note

1. Click the **Populate Established Patient** button highlighted in purple.
2. Select the patient's **most recent note from Dr. Morgan's clinic**.
3. Populate the new note using that previous clinic note.

<figure class="epic-tutorial-card">
  <img src="{{ '/assets/images/epic/lastnotebutton.png' | relative_url }}" alt="Populate Established Patient button">
  <figcaption>Select the established-patient button and populate today's note using the patient's most recent note from Dr. Morgan's clinic.</figcaption>
</figure>

<div class="guide-callout">

<strong>Preferred Workflow</strong>

Whenever possible, populate the note from the patient's most recent note from **Dr. Morgan's clinic**. This preserves the clinic's formatting and allows you to update today's visit rather than creating a note from scratch.

</div>

---

## Step 3 — Update Today's Visit

Carefully review the populated note and update every section for today's encounter.

- Update the interval history (HPI).
- Review and update the medication list.
- Remove outdated information.
- Update the physical examination.
- Update the assessment and plan.
- Confirm testing and referrals.
- Update follow-up instructions.

<div class="guide-callout">

<strong>Review Carefully</strong>

Never assume information copied from a previous note is still correct. Every section should be reviewed and updated before presenting or sending the note.

</div>

---

## Step 4 — Alternative Method

If you choose **not** to populate the previous note, you may document the visit using the standard new-patient template.

Type:

```text
.CELNEWPATIENT
```

Press **Enter/Return**, then:

- Remove sections that do not apply.
- Update the note for today's returning-patient visit.
- Confirm all copied information is accurate.

<div class="guide-callout">

<strong>Important</strong>

Using the previous clinic note is generally preferred because it preserves the patient's existing documentation and clinic formatting.

</div>

{% endcapture %}

{% include accordion.html
  id="returning-patient-documentation"
  title="Returning Patient Documentation"
  description="Populate and update the most recent clinic note"
  content=returning_patient_content
%}

{% capture before_sending_content %}

Before sending or pending your note, verify the following:

- [ ] Correct patient and date of service
- [ ] Correct encounter
- [ ] Removed unused template text and placeholders
- [ ] Updated HPI or interval history
- [ ] Reviewed current medications
- [ ] Documented medication changes
- [ ] Removed outdated copied information
- [ ] Updated today's physical examination
- [ ] Updated assessment and plan
- [ ] Confirmed testing and referrals
- [ ] Updated follow-up instructions
- [ ] Reviewed the note for accuracy
- [ ] Sent or pended the note according to clinic workflow

<div class="guide-callout">

<strong>Need help?</strong>

If you are unsure whether the note is ready to send, ask Caty, the fellow, or Dr. Morgan before presenting the patient.

</div>

{% endcapture %}

{% include accordion.html
  id="before-sending"
  title="Before Sending or Pending the Note"
  description="Final review before sending the encounter"
  content=before_sending_content
%}

{% capture final_checklist_content %}

Use this checklist before presenting your patient.

- [ ] Correct patient
- [ ] Correct encounter
- [ ] Updated HPI
- [ ] Updated medications
- [ ] Updated physical examination
- [ ] Updated assessment and plan
- [ ] Updated referrals
- [ ] Updated follow-up
- [ ] Removed template placeholders
- [ ] Ready to present

{% endcapture %}

{% include accordion.html
  id="final-review"
  title="Final Review Checklist"
  description="Quick checklist before presentation"
  content=final_checklist_content
%}

[Return to Learner Resources](./)

<div class="guide-callout">

<strong>Questions?</strong>

If you are unsure about the documentation workflow, SmartPhrases, or how to complete a note, ask Caty, the fellow, or Dr. Morgan before presenting or sending the note.

</div>

</div>