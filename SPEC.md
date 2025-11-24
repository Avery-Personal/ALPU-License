              ALPU SOFTWARE LICENSE v1.2
          (Asuka License for Protective Use)
          
                 TECHNICAL SPECIFICATION
                       Version 1.2
                    2025 © Asuka Org
---

1. INTRODUCTION
---

This document defines the formal specification for the ALPU
(Asuka License for Protective Use) software license. Its
purpose is to describe the structure, terminology, rules, and
enforcement model of ALPU in a consistent and legally stable
format.

The specification governs all implementations or references
to **ALPU v1.2** and ensures that derivative licenses and
variants maintain compatibility.

This specification does *not* grant permissions. The actual
license text (LICENSES\ALEPU.md) is the legally operative
document.

This specification is authoritative for:
  - Vocabulary and definitions
  - Rule interpretation
  - Enforcement expectations
  - Derivative license creation requirements


2. TERMINOLOGY
---

The following terms have specific meanings within ALPU v1.2:

"Software"
  The original work of authorship distributed under ALPU,
  including source code, binaries, documentation, or any
  associated files.

"Licensor"
  The copyright holder or designated rights owner who is
  granting permission under ALPU.

"Licensee"
  Any individual or entity who obtains the Software and is
  subject to ALPU’s terms.

"Modification"
  Any alteration to the Software, including editing,
  removing, adding, reorganizing, or wrapping it inside
  another system. Compilation into a different format is not
  considered a modification unless the content itself changes.

"Redistribution"
  Any act of sharing, hosting, publishing, or transmitting
  the Software, modified or unmodified.

"Derivative Work"
  A work based upon the Software that changes its behavior,
  structure, function, or content. Derivative works are NOT
  permitted unless explicitly authorized.

"Explicit Written Permission"
  Direct written approval from the Licensor. Email, signed
  digital communication, physical letter, or authenticated
  online message are valid forms.

"Closed-Source License"
  Any license that does not guarantee public access to
  readable source code.

"Revocation"
  The termination of Licensee rights due to violation.


3. LICENSE CLASSIFICATION
---

ALPU belongs to the category of:
  - Source-available licenses
  - Highly protective, author-controlled licenses
  - Anti-modification / anti-fork licenses
  - Redistribution-limited licenses
  - Patent-grant-optional licenses

It is NOT:
  - Open source (OSD-incompatible)
  - Copyleft (GPL-style)
  - Permissive (MIT/BSD-style)
  - Proprietary (it allows redistribution)


4. PERMISSION MODEL
---

ALPU provides only the following default permissions:

  (1) Use of the Software  
  (2) Copying the Software  
  (3) Redistribution of unmodified copies  
  (4) Optional patent rights (if the Licensor chooses)

No other rights are implicitly granted.

Any action not explicitly permitted is disallowed.

Modification requires explicit written permission.  
Redistribution of modified versions requires explicit written permission.  
Relicensing requires explicit written permission.  
Sublicensing modification rights is explicitly disallowed.


5. RESTRICTION MODEL
---

ALPU enforces strong control by the Licensor.

5.1 Modification Restriction
  - Licensee may NOT modify the Software under any
    circumstance without written authorization.

5.2 Redistribution Restriction
  - Only original, unmodified copies may be redistributed.

5.3 Sublicensing Restriction
  - The Licensee may not grant modification rights to anyone
    else, with or without payment.

5.4 Derivative Works Restriction
  - Derivatives are allowed only when the Licensor grants
    written authorization.
  - Authorized derivative works MUST use ALPU v1.2.
  - They may not be relicensed to closed-source licensing
    without additional explicit permission.

5.5 Anti-Circumvention
  - Any attempt to evade or bypass ALPU’s restrictions
    results in immediate loss of all granted rights.


6. ATTRIBUTION MODEL
---

Attribution is *recommended* but not required.

If the Software is redistributed with documentation or
notices, referencing the Licensor is encouraged but optional.


7. PATENT GRANT (OPTIONAL)
---

ALPU contains an optional patent grant clause:

  - Royalty-free, worldwide, non-exclusive rights to practice
    any Licensor-owned patents required to use the Software.
  - Automatically revoked if the Licensee initiates any form
    of patent litigation that targets the Software.


8. WARRANTY + LIABILITY MODEL
---

ALPU adopts a full-disclaimer model:

  - Software is provided “as is.”
  - No warranties of any kind.
  - Licensor is not liable for damages, loss, or claims.


9. ENFORCEMENT AND TERMINATION
---

9.1 Immediate Revocation
  Rights are instantly revoked upon:
    - Unauthorized modification
    - Unauthorized redistribution
    - Unauthorized sublicensing
    - Unauthorized relicensing
    - Attempted circumvention

9.2 Effect of Termination
  - Rights granted prior to violation remain valid.
  - Post-violation use is prohibited.

9.3 Enforcement Expectation
  - Licensor is encouraged to maintain revision logs,
    written permission records, and derivative tracking.


10. VERSIONING POLICY
---

ALPU uses semantic versioning for legal documents:
  MAJOR.MINOR

MAJOR
  - Breaking changes
  - New rules
  - New restrictions or freedoms

MINOR
  - Wording improvements
  - Clarifications
  - Formatting updates

ALPU v1.2 is a minor revision update to the v1.0 baseline.


11. GOVERNING LAW
---
All interpretations of ALPU v1.2 are governed by:

  Laws of California, United States.

Conflict-of-law principles do not apply.


12. COMPARISON TO OTHER LICENSES
---

ALPU is structurally closest to:

  - PolyForm Shield  
  - Business Source License  
  - Server-Side Public License (SSPL)  
  - The Anti-Cheat Licenses used in game engines  
  - “Source-available with no modification” licenses

Key distinctions:
  - Stricter control over derivatives than PolyForm
  - Does not include release-timer conditions like BSL
  - Allows redistribution unlike SSPL’s SaaS provisions
  - Explicit anti-sublicensing clause
  - More formal authority over authorized forks


13. COMPLIANCE REQUIREMENTS
---

To comply with ALPU, Licensees must:

  - Keep unmodified copies unaltered
  - Request permission before making changes
  - Store written authorization when granted
  - Distribute only the forms they are authorized to distribute
  - Follow governing law and enforcement terms


14. OFFICIAL IMPLEMENTATION REQUIREMENTS
---

Any license claiming to be “ALPU v1.2 compliant” MUST:

  (1) Include the entire license text verbatim  
  (2) Include the copyright line properly filled in  
  (3) Refer to ALPU by version number  
  (4) Follow all rules in this specification  
  (5) Not declare conflicting permissions


15. APPENDIX A — OFFICIAL COPYRIGHT BLOCK
---

This is the formally required header:

  Copyright 2025 © Asuka Org  
  Licensed under ALPU v1.2  
  See LICENSE_ALPU.txt for details.


16. APPENDIX B — OFFICIAL REPOSITORY STRUCTURE
---

/LICENSE
/SPEC.md
/README.md  
/CHANGELOG.md  
/PROJECT_NOTICE.md  
/LICENSES/ALPU.md
/LICENSES/ALEPU.md
/LICENSES/ALLPU.md
