---
title: Home
nav_order: 1
---

<div class="clinic-dashboard">

<section class="dashboard-hero">

<img src="{{ '/assets/images/miffy-logo.png' | relative_url }}" alt="Miffy logo for the Movement and Memory Clinic Handbook">

<div>

<h1>Movement &amp; Memory Clinic Handbook</h1>

<p>
A centralized clinic reference for patient workflows, EPIC documentation, special treatment pathways, and learner guidance.
</p>

</div>

</section>

{% capture first_day %}

**Welcome!** If this is your first day in clinic, start here.

1. Review the EPIC Documentation Guide to understand note formatting and workflow.
2. Open the appropriate Clinic Visit Guide based on the patient you are seeing.
3. If your patient is receiving anti-amyloid therapy or has another special workflow, review those additional steps before entering the room.
4. Use the guide throughout the visit—it is intended to be referenced during clinic, not memorized beforehand.

{% endcapture %}

{% include callout.html
  icon="🐰"
  title="First Day in Clinic?"
  content=first_day
  type="tip"
%}

<section class="dashboard-section">

<h2>Today’s Clinic</h2>

<p class="dashboard-section-intro">
Select the visit type to open the complete clinic workflow, including intake, chart review, presentation, documentation, and follow-up.
</p>

<div class="dashboard-workflow-grid">

<div class="dashboard-workflow-group">

<h3>Memory Patients</h3>

<div class="dashboard-link-grid">

<a class="dashboard-link" href="{{ '/clinic-guides/memory/new-patient.html' | relative_url }}">
  <strong>New Patient</strong>
  <span>Initial memory evaluation</span>
</a>

<a class="dashboard-link" href="{{ '/clinic-guides/memory/second-visit.html' | relative_url }}">
  <strong>Second Visit</strong>
  <span>Review completed testing and diagnosis</span>
</a>

<a class="dashboard-link" href="{{ '/clinic-guides/memory/established-patient.html' | relative_url }}">
  <strong>Established Patient</strong>
  <span>Routine memory follow-up</span>
</a>

</div>

</div>

<div class="dashboard-workflow-group">

<h3>Movement Patients</h3>

<div class="dashboard-link-grid">

<a class="dashboard-link" href="{{ '/clinic-guides/movement/new-patient.html' | relative_url }}">
  <strong>New Patient</strong>
  <span>Initial movement evaluation</span>
</a>

<a class="dashboard-link" href="{{ '/clinic-guides/movement/second-visit.html' | relative_url }}">
  <strong>Second Visit</strong>
  <span>Review response, testing, and plan</span>
</a>

<a class="dashboard-link" href="{{ '/clinic-guides/movement/established-patient.html' | relative_url }}">
  <strong>Established Patient</strong>
  <span>Routine movement follow-up</span>
</a>

</div>

</div>

</div>

</section>

<section class="dashboard-section">

<h2>Documentation</h2>

<div class="dashboard-card-grid">

<a class="dashboard-card" href="{{ '/medical-students/epic-documentation.html' | relative_url }}">
  <h3>EPIC Documentation Guide</h3>
  <p>SmartPhrase setup, new and returning note workflows, documentation standards, and a completed sample note.</p>
  <span>Open documentation guide →</span>
</a>

<a class="dashboard-card" href="{{ '/medical-students/epic-documentation.html#example-clinic-note' | relative_url }}">
  <h3>Example Clinic Note</h3>
  <p>Review the expected note structure, formatting, and level of detail before documenting a patient.</p>
  <span>View sample note →</span>
</a>

<a class="dashboard-card" href="{{ '/medical-students/' | relative_url }}">
  <h3>Learner Resources</h3>
  <p>Open practical resources for students, residents, fellows, PA students, and observers.</p>
  <span>Open learner resources →</span>
</a>

</div>

</section>

<section class="dashboard-section dashboard-special">

<h2>Special Workflows</h2>

<p class="dashboard-section-intro">
Use these guides when the standard clinic workflow requires additional monitoring, safety review, or documentation.
</p>

<div class="dashboard-card-grid">

<a class="dashboard-card dashboard-card-featured" href="{{ '/drug-treatments/alzheimers-infusions.html' | relative_url }}">
  <h3>Anti-Amyloid Patients</h3>
  <p>Review infusion number, MoCA and FAQ timing, ARIA symptoms, MRI monitoring, amyloid PET information, and treatment-specific follow-up.</p>
  <span>Open anti-amyloid workflow →</span>
</a>

<a class="dashboard-card" href="{{ '/drug-treatments/' | relative_url }}">
  <h3>Drug Treatments</h3>
  <p>Open medication, infusion, and treatment-related clinic references.</p>
  <span>Open treatment guides →</span>
</a>

</div>

</section>

<section class="dashboard-section">

<h2>Clinic Reference</h2>

<div class="dashboard-reference-grid">

<a href="{{ '/clinic-guides/memory/' | relative_url }}">
  <strong>Memory Disorders</strong>
  <span>All memory visit workflows</span>
</a>

<a href="{{ '/clinic-guides/movement/' | relative_url }}">
  <strong>Movement Disorders</strong>
  <span>All movement visit workflows</span>
</a>

<a href="{{ '/drug-treatments/' | relative_url }}">
  <strong>Drug Treatments</strong>
  <span>Treatment and infusion references</span>
</a>

<a href="{{ '/medical-students/' | relative_url }}">
  <strong>Learner Resources</strong>
  <span>Documentation and clinic guidance</span>
</a>

</div>

</section>

{% capture clinic_pearl %}

Start with the standard visit workflow, then review any additional steps required for patients with special care or monitoring needs.

{% endcapture %}

{% include callout.html
  icon="🐰"
  title="Clinic Pearl"
  content=clinic_pearl
  type="tip"
%}

<div class="home-note">

<strong>Educational use only:</strong> This handbook supports learning and clinic workflow. It does not replace clinical judgment, supervision, institutional policy, or local guidelines.

</div>

</div>