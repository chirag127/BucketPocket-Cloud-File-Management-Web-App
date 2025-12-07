---
name: 🐛 Bug Report
about: Report an unexpected error, incorrect behavior, or crash in BucketPocket.
title: "[BUG]: Short summary of the unexpected behavior"
labels: ['bug', 'triage', 'needs-reproduction']
assignees: []
---

## 🛑 Apex Triage Checklist

Before submitting, please complete the following steps:

- [ ] I have searched the [existing issues](https://github.com/chirag127/BucketPocket-Cloud-File-Management-Web-App/issues) to ensure this bug has not already been reported.
- [ ] I have verified that I am using the latest stable version of `BucketPocket` (check the application settings or the version badge).
- [ ] I have isolated the issue to a minimum reproducible case.

---

## 📝 Description of the Bug

A clear and concise description of what the bug is. Why is this behavior incorrect or unexpected? Focus on the system component affected (e.g., Frontend UI, File Upload API, Authentication Layer).

## 🔄 Steps to Reproduce

Please provide precise, numbered steps to reproduce the issue. This is CRITICAL for rapid resolution.

1. Go to '...' in the application.
2. Execute action '...'
3. Input data: '...'
4. Observe the unexpected output/error message.

### Code Snippet (If Applicable)

If the bug involves a specific client-side interaction or API request structure, provide the relevant (minimal) code snippet here.

typescript
// Example: relevant React component logic or API request parameters


## ✅ Expected Behavior

A clear and concise description of what you expected to happen instead of the erroneous behavior, based on the documented functionality.

## 🖥️ Environment & Technical Details

Please provide comprehensive details about your operating environment.

| Component | Detail |
| :--- | :--- |
| **BucketPocket Version** | e.g., v1.5.0-beta.2 (Found in settings) |
| **Operating System** | e.g., macOS Sonoma 14.2, Windows 11 Pro |
| **Browser (Frontend)** | e.g., Chrome 120.0, Firefox 121.0 |
| **Node.js Version (Backend/Dev)** | e.g., v20.10.0 |
| **Storage Backend Type** | e.g., AWS S3, Azure Blob, Local Disk |

## 📸 Screenshots or Video (Optional)

If applicable, add screenshots or a short video clip to help visualize the problem.

## ⚡ Severity and Priority (Internal Triage)

How severely does this bug affect your ability to use BucketPocket? (Choose one option)

- [ ] **Critical (P1):** Application is crashing, data integrity is compromised, or core features (file upload/download/authentication) are completely unusable. *Requires immediate hotfix.* 
- [ ] **Major (P2):** A primary feature is broken or severely degraded, but workarounds exist or the feature is peripheral to core functionality.
- [ ] **Minor (P3):** Cosmetic issue, typo, minor UI misalignment, or slight performance degradation that does not impede functional usage.