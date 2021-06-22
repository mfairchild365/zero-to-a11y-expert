# Zero to accessibility expert

Status: draft

This is a non-exhaustive and opinionated guide to becoming an accessibility expert. What you should learn depends on the specialization that you want to target.

In general, this will look something like this: 

1. Find a personal a11y coach
2. Learn the fundamentals (types of disabilities, standards, laws, etc)
3. Learn how to use assistive technologies
4. Learn how to do an assessment
5. Specific topics for your specialization(s)

## Find a personal a11y coach

A personal accessibility coach is someone who will work directly with you on a one-on-one basis to help you achieve your goal of becoming an expert. While a coach is not a hard requirement, a coach can be very helpful by:

* Answering your questions
* Tailoring your learning jounry to meet your specific needs
* Helping you keep on track and be accountable
* Challenging you to better your skills

TODO: list ways to find personal a11y coaches

## Learn the fundamentals

The fundamentals include topics such as types of disabilities, standards, laws, etc.

* (paid, course) [Deque University Accessibility Fundamentals: Disabilities, Guidelines, and Laws](https://dequeuniversity.com/curriculum/courses/fundamentals)
* (free, site) [WAI - Accessibility Fundamentals](https://www.w3.org/WAI/fundamentals/)
* (free, course) [Microsoft - Accessibility fundamentals](https://docs.microsoft.com/en-us/learn/paths/accessibility-fundamentals/)
* (free, site) [WCAG](https://www.w3.org/WAI/WCAG21/quickref/)

Practice this skill: create a set of personas that include a mix of different disabilities. Think about the experience each persona might have when trying to complete a task on some of the sites that you visit most frequently.

### Learn WCAG

[WCAG](https://www.w3.org/WAI/WCAG21/quickref/) is the international standard for digital accessibility. It has been adopted by many governments as a legal requirement. As such, it is used to assess how well a given digital resource meets the minimal requirements for accessibility. As such, this is a vital resource to learn.

One critical thing to understand about WCAG (and standards in general) is the difference between "normative" and "non-normative" or "informative". Parts of WCAG are marked as "normative", which means that these sections are required for conformance. The rest of WCAG, including supporting documents, are marked as "non-normative" or "informative", which means that these sections are not required for conformance. In other words, when performing an WCAG audit, an accessibility expert must only test to the "normative" parts of WCAG, and can not fail something if it is not a "normative" requirement or if it is only mentioned in "non-normative" information. For more information on why this is important, read [Accessibility auditing and ego](https://ericwbailey.design/writing/accessibility-auditing-and-ego/).

WCAG isn't something you will learn or memorize over night. Learn how it is structured. Learn how to use it as a reference and a resource. 

Pay close attention to:

* [The WCAG SC for level A and AA](https://www.w3.org/TR/WCAG/#perceivable) (normative). These are the requirements that WCAG defines. Most laws do not include level AAA SC.
* [WCAG conformance requirements](https://www.w3.org/TR/WCAG/#conformance) (normative).
* [WCAG glossary](https://www.w3.org/TR/WCAG/#glossary) (normative).
* [Understanding WCAG](https://www.w3.org/WAI/WCAG21/Understanding/) (informative). Many parts of WCAG, including the SC, can be difficult to understand. This document attempts to make WCAG more understandable, by providing examples, further details, and further information about different parts of WCAG.
* [WCAG Techniques](https://www.w3.org/WAI/WCAG21/Techniques/). The WCAG techniques describe different ways that SC can pass or fail.

Practice this skill: Practice applying the conformance requirements and SC to your favorite websites.

## Learn how to use assistive technologies

Deque University has great [screen reader guides](https://dequeuniversity.com/screenreaders/) that are free to use. Pick one screen reader and practice using it. Also famailiarze yourself with other assistive technologies such as [Voice Control for iOS](https://support.apple.com/en-us/HT210417#:~:text=To%20turn%20Voice%20Control%20on,%2C%20turn%20on%20Voice%20Control.%22), [Voice Control for MacOS](https://support.apple.com/en-us/HT210539), and [Switch Control for iOS](https://support.apple.com/en-us/HT201370) and [Switch Access for Android](https://support.google.com/accessibility/android/answer/6122836?hl=en).

TODO: more guides and resources

Practice this skill: Try to use a screen reader to complete some tasks on sites that you frequently visit.

## Learn how to do an assessment

Practice performing a few WCAG assessments on some websites and/or native mobile applications. While WCAG was originally crafted for web content, the requirements are usually abstract enough that they can be applied to other technologies, such as native mobile applications and PDFs. The purpose of this exercise is less about memorizing how to perform an assessment for a specific technology, and more about learning how to approach perfomring an audit for any technology.

* (free) [Website Accessibility Conformance Evaluation Methodology](https://www.w3.org/WAI/test-evaluate/conformance/wcag-em/) - a free resource to help guide you through performing a solid WCAG assessment.
* (paid) [Deque University - WCAG Conformance Testing, Detailed Methodology](https://dequeuniversity.com/curriculum/courses/wcagtesting) - has detailed WCAG testing instructions for multiple platforms, including web, native mobile, PDF, etc.

Practice this skill: Perform an audit on at least two different sites or applications.

## Specific topics for your specialization(s)

Digital accessibility can be broken into many sub-specializations. The general goals of each specialization are:

1. To deeply understand how to apply WCAG to the specific technology and perform actionable audits
2. To understand how to craft good remediation advice for the specific technology (often requires a solid understanding of code)
4. To understand how to go above and beyond the minimal requirements of WCAG for the specific technology
5. To understand techniques and behaviors that development crews can follow to become proactive rather than reactive when it comes to accessibility

### Web accessibility

TODO

### Native mobile accessibility

TODO

### Design accessibility

TODO
