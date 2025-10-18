<!--
SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
-->

# Review Process for Transitioning a Library to “Production Ready”

This proposal establishes a formal process for transitioning a Beman Project library from **Under Development** to **Production Ready** status.
The intent is to ensure that every production-ready library meets the Beman standard for quality, completeness, and documentation, and that it has received sufficient community review and testing.

---

## Review Process Details


1. **Review Logistics**
   Typically this is requested by the library author, but any community member that feels a library is ready can suggest
   a review.  The review will be managed by one or more leads or an lead appointee/volunteer.

   A post is made on [Discourse](https://discourse.bemanproject.org) announcing the start of a **two-week library review** period.
   The announcement should include:

   * The released version of the library to review
   * Link to a PR to review for review comments
     - Note: The PR may not have much diff content but is the place for gathering feedback
   * Any other guidance for the reviewers
   
3. **Review Criteria**
   To be eligible for *Production Ready* status, a library must demonstrate that it:

   * Meets the **Beman Standard** with deviations documented (passes beman.tidy checks)
   * Has **comprehensive unit test coverage** validating functionality and edge cases
   * Includes **complete and accurate documentation**, including tutorial, design rationale, and examples

   Note that much of the design documentation may simply reference the WG21 paper. 
   Also note that since the current documentation system is a work in progress, docs should be Markdown for now.

4. **Community Evaluation**
   During the review period, the community is encouraged to:

   * Build and test the library on supported platforms
   * Review its design, documentation, and adherence to the Beman standard
   * Provide feedback and raise issues for discussion

4. **Approval Requirements**
   A library may transition to *Production Ready* status only after:

   * Approval by **at least two project leads**, and
   * Demonstrated **positive community consensus** that the review criteria have been met
