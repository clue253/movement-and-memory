---
title: EPIC Documentation Guide
parent: Learner Resources
nav_order: 1
has_toc: false
---

# EPIC Documentation Guide

This guide explains how to save the clinic SmartPhrases and create notes for new and returning patients in EPIC.

---

# Before Your First Clinic

Before documenting patients for the first time, save the required SmartPhrases from **John Doe**.

## Required SmartPhrases

| SmartPhrase | Purpose |
|--------------|----------|
| AJPE | Physical Examination |
| KMROS | Review of Systems |
| CELNEWPATIENT | New Patient Template |

---

## Step 1 — Open the SmartPhrase Manager

1. Double-click the EPIC hamburger menu.
2. Search **SmartPhrase**.
3. Select **My SmartPhrases**.

![Open SmartPhrase Manager]({{ '/assets/images/epic/EPIChamburger.png' | relative_url }})

![Search SmartPhrase]({{ '/assets/images/epic/searchSP.png' | relative_url }})

---

## Step 2 — Search John Doe

Search for:

**John Doe**

Open John's SmartPhrases.

Locate:

- AJPE
- KMROS
- CELNEWPATIENT

![Search John Doe]({{ '/assets/images/epic/searchme.png' | relative_url }})

---

## Step 3 — Save the SmartPhrases

For each SmartPhrase:

1. Double-click the SmartPhrase.
2. Click **Create Copy**.
3. Leave the SmartPhrase name unchanged.
4. Click **Accept**.
5. Close the window.
6. Repeat for all three SmartPhrases.

![Create Copy]({{ '/assets/images/epic/createcopy.png' | relative_url }})

![Rename SmartPhrase]({{ '/assets/images/epic/rename.png' | relative_url }})

![Accept SmartPhrase]({{ '/assets/images/epic/saveit.png' | relative_url }})

---

## Step 4 — Using SmartPhrases

Type the SmartPhrase and press **Enter/Return**.

Example:

```text
.AJPE
```

Populates the Physical Examination.

```text
.KMROS
```

Populates the Review of Systems.

```text
.CELNEWPATIENT
```

Populates the New Patient template.

---

# Creating Today's Note

## New Patient

1. Click **Create New Note**.
2. Select **Blank Note**.

![Blank Note]({{ '/assets/images/epic/blanknote.png' | relative_url }})

3. Type:

```text
.CELNEWPATIENT
```

4. Press **Enter/Return**.

5. Complete every section.

6. Remove all instructional text before submitting the note.

---

## Returning Patient

**Preferred Method**

1. Click the highlighted **Populate Established Patient** button.

2. Select the patient's most recent clinic note from Dr. Morgan.

3. Update every section for today's visit.

4. Remove any outdated information.

![Populate Previous Note]({{ '/assets/images/epic/lastnotebutton.png' | relative_url }})

### Alternative Method

If you choose not to populate the previous note:

- Start with a Blank Note.
- Type:

```text
.CELNEWPATIENT
```

- Press **Enter/Return**.
- Remove sections that are not applicable.
- Complete the note normally.

---

# Before Sending the Note

- [ ] Remove all instructional text.
- [ ] Update today's HPI.
- [ ] Update the Physical Examination.
- [ ] Update the Assessment.
- [ ] Update the Plan.
- [ ] Remove outdated information copied from previous notes.
- [ ] Confirm medications.
- [ ] Confirm follow-up instructions.

---

# Sample Notes

*(Link to be added.)*

- New Patient Example
- Established Patient Example