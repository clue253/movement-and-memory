---
title: Test Callout
nav_exclude: true
---

{% capture workflow %}

Complete the MoCA before presenting.

Review the MRI.

Ask Caty about the infusion number.

{% endcapture %}

{% include callout.html
  icon="🧠"
  title="Memory Clinic Workflow"
  content=workflow
%}

{% capture warning %}

Never present an anti-amyloid patient without reviewing the latest MRI.

{% endcapture %}

{% include callout.html
  icon="⚠️"
  title="Important"
  content=warning
  type="warning"
%}

{% capture tip %}

Use the most recent note from Dr. Morgan’s clinic when documenting a returning patient.

{% endcapture %}

{% include callout.html
  icon="💡"
  title="Clinic Tip"
  content=tip
  type="tip"
%}

{% capture checklist %}

- Complete the MoCA
- Complete the FAQ
- Review imaging
- Confirm medications

{% endcapture %}

{% include callout.html
  icon="📋"
  title="Before Presenting"
  content=checklist
  type="checklist"
%}

{% capture documentation %}

Confirm that all copied information reflects today’s patient and encounter.

{% endcapture %}

{% include callout.html
  icon="📄"
  title="Documentation Reminder"
  content=documentation
  type="documentation"
%}