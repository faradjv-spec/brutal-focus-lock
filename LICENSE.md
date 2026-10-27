# Brutal Focus Lock — End User License Agreement

Copyright © 2026 the Brutal Focus project. All rights reserved.

Version 1.3 · Effective 27 October 2026 · Applies to the Brutal Focus Lock v0.2.0 Windows release and its companion extension (together, "the Software"). Older releases retain the agreement supplied with their installer.

By installing or using the Software you agree to this Agreement. If you do not agree, do not install or use it.

## Read this first

**THE SOFTWARE IS PROVIDED "AS IS" AND "AS AVAILABLE", WITHOUT WARRANTY OF ANY KIND. IT DELIBERATELY CHANGES HOW YOUR COMPUTER BEHAVES: IT BLOCKS KEYBOARD SHORTCUTS, EDITS THE WINDOWS HOSTS FILE AND CAN MAKE WEBSITES UNREACHABLE. YOU USE IT AT YOUR OWN RISK. TO THE MAXIMUM EXTENT THE LAW ALLOWS, THE AUTHOR IS NOT LIABLE FOR CHANGED OR DAMAGED HOSTS FILES, BLOCKED OR UNREACHABLE WEBSITES, LOSS OF NETWORK ACCESS, MISSED, FAILED, INTERRUPTED OR INVALIDATED EXAMS, ACADEMIC PENALTIES OR MISCONDUCT FINDINGS, OR LOST DATA. THE SOFTWARE IS NOT EXAM-SECURITY OR PROCTORING SOFTWARE. NOTHING IN THIS AGREEMENT LIMITS RIGHTS THAT CANNOT BE LIMITED BY LAW (SECTION 9).**

## 1. Ownership

The Software, including its source code, object code, design, text, graphics and the names "Brutal Focus" and "Brutal Focus Lock", is owned by the Brutal Focus project ("the Author") and is protected by copyright law, including Italian Law No. 633/1941 and Directive 2009/24/EC. The Software is licensed, not sold. All rights not expressly granted are reserved.

## 2. Licence

The Author grants you a personal, non-exclusive, non-transferable licence to install and use the Software on computers you own or are authorised to modify, for your own focus and study purposes.

## 3. Restrictions

You may not, except as expressly permitted by this Agreement or by mandatory law:

- copy, redistribute, sell, rent, lend, sublicense or publish the Software, including re-uploading the installer to other download sites;
- modify, translate or create derivative works of the Software;
- remove or alter any copyright, trademark or licence notice;
- decompile, disassemble or reverse engineer the Software. This restriction does not apply to the extent such activity is expressly permitted by applicable law notwithstanding this limitation, including Article 6 of Directive 2009/24/EC and Article 64-quater of Italian Law No. 633/1941.

The official download locations are the GitHub releases page at github.com/faradjv-spec/brutal-focus-lock and the Brutal Focus Lock website. Copies obtained elsewhere are not supported and may have been tampered with.

## 4. What the Software does to your computer — and your consent to it

When you start the relevant features, you instruct and consent to the Software doing the following:

- **Exam mode** installs a Windows low-level keyboard hook that blocks task-switching keys (such as Alt+Tab, the Windows key, Alt+F4 and Ctrl+Esc) until the session ends. The Narrator (Windows+Ctrl+Enter) and Magnifier (Windows+Plus) shortcuts are designed to keep working, with the Software starting those tools itself; this has not yet been verified on all hardware, so if you rely on either tool, test it in a short session first. Other Windows-key shortcuts, including other accessibility shortcuts (for example Windows+Ctrl+O for the on-screen keyboard or Windows+U for accessibility settings), do not work until the session ends; if you rely on them, do not use Exam mode. Keystrokes are not recorded or transmitted. Exam mode blocks keys and does not restrict the mouse. In the locked app window's full-screen layout, the exam window covers the screen it opens on, apart from the Windows taskbar; in its split-screen layouts, only the exam half is covered, and the other half is your normal desktop, where apps and websites stay usable, except sites on your blocklist.
- **Site blocking in Exam mode** writes entries to the Windows hosts file after you approve a Windows administrator prompt. Listed websites, and any login, payment or exam service that depends on them, become unreachable on the whole computer, in every browser and app. If the Software is force-quit, crashes or loses power during a session, the entries can remain until you reopen the Software or use Settings → RESET HOSTS FILE NOW. Uninstalling the Software also tries to remove them. The Software changes only the lines it added and leaves the rest of the file as it was. Do not add a website to your blocklist that your exam or work needs, including shared sign-in services.
- **The optional camera view** uses your webcam only after you turn it on and Windows grants permission. Video is not recorded, stored or transmitted.

You can always leave: typing your exit phrase is the normal way to end an exam early, **Ctrl+Shift+Q** is the emergency exit that closes the Software immediately in every mode, and Ctrl+Alt+Del (which no application can block) gives access to Task Manager, sign-out and restart.

Keep backups of important data and of any custom hosts-file entries. Do not use the Software on computers you are not authorised to modify, such as school, exam-centre or employer machines, without the owner's permission.

## 5. Exams, proctoring, accessibility and safety

The Software is a self-discipline tool. It is **not** a proctoring, anti-cheating or exam-security product. It is not approved, endorsed or certified by any school, university, examination body, proctoring provider or learning platform, and it makes no promise that it is compatible with any of them.

**Do not run the Software during a proctored or supervised exam, or an exam that uses its own lockdown browser, unless your institution has told you that other software may run.** Proctoring and lockdown software may detect keyboard hooks, hosts-file changes or other running applications and may flag, stop or invalidate your exam.

You are solely responsible for:

- checking whether your institution or exam allows third-party software to run, and complying with its rules;
- making sure the Software does not conflict with any browser, proctoring or lockdown software your exam requires;
- testing a harmless session on the same computer, browser and network before relying on the Software for any exam or deadline.

**Not an exam service or an accessibility tool.** The Software does not provide, administer, mark or certify any exam, and it is not an assistive technology or accessibility service. Exam mode disables Windows-key shortcuts, including some accessibility shortcuts (section 4). If you rely on assistive technology, test it before an exam and do not use Exam mode if it stops working for you.

**Not for safety-critical use.** The Software is not designed or tested for use where a blocked key, website or program could endanger life, health or safety. Do not use it on a computer that you rely on to receive emergency alerts, to reach emergency or medical services, or to control or monitor medical, industrial or other safety-related equipment.

## 6. No warranty

The Software is provided "as is" and "as available". To the maximum extent permitted by applicable law, the Author gives no warranty or condition of any kind, express or implied, including of merchantability, satisfactory quality, fitness for a particular purpose, uninterrupted or error-free operation, or that the Software will block, or will not block, any particular website, application or key combination. Statutory rights that cannot be waived are not affected (section 9).

## 7. Limitation of liability

To the maximum extent permitted by applicable law:

- the Author is not liable for any indirect, incidental, special or consequential loss, or for any of the following, however caused: changes to, or corruption of, the hosts file or other system settings; websites or services becoming unreachable; loss of network access; missed, failed, interrupted, delayed or invalidated exams, assignments or deadlines; academic penalties, misconduct allegations or findings, lost grades, places or scholarships; lost data; lost profits, wages or opportunities; conflicts with third-party software;
- the Author's total liability for all claims arising out of or relating to the Software is limited to the greater of (a) the amount you paid for the Software in the 12 months before the claim, or (b) fifty euros (EUR 50).

## 8. Your responsibility, and third-party systems

You are responsible for your choice of blocklist, session length and settings, for using the Software only where you are allowed to, and for any consequence of using it in breach of your institution's or employer's rules.

The Software relies on Windows, your browser, your network and other systems that the Author does not control, for example antivirus software, proctoring or lockdown tools, school, employer and exam platforms, DNS and VPN services, and the websites you choose to block or visit. They can change or behave differently at any time, which can stop a feature from working or have unexpected effects. The Author is not responsible for those systems or for their terms, availability, content or policies, and does not promise that the Software works with any of them.

## 9. What this Agreement cannot limit

Nothing in this Agreement excludes or limits:

- liability for intent (dolo) or gross negligence (colpa grave) (Article 1229 of the Italian Civil Code), or for death or personal injury;
- liability under mandatory product-liability law, including laws implementing Directive (EU) 2024/2853;
- any right you have as a consumer under the mandatory law of your country of habitual residence, including conformity remedies for digital content and the right to bring proceedings in your local courts;
- any other liability that cannot lawfully be excluded or limited.

Sections 6 and 7 apply only as far as this section allows.

## 10. Free of charge, with optional voluntary support

- **Free.** This release, including Exam mode, is free for personal use, without a licence key, account, advertising or paid upgrades. No feature is withheld, limited or time-limited for people who do not pay.
- **Support reminder.** After some completed sessions the Software may show a message inviting you to support its development. It never appears during a session, never locks or limits anything, and you can turn it off in Settings.
- **Voluntary support.** Any support you give is a voluntary contribution. It is not a purchase of the Software, a licence or any feature, and it creates no obligation to provide support, updates or availability beyond this Agreement. If contributions are ever accepted, it will be through a third-party platform whose own terms govern the payment. The Software itself is designed not to collect or process payment data.
- **Future versions.** Any different terms for a future version will be disclosed before that version is offered and will not change this licence for a version already installed.

## 11. Third-party components

The Software includes open-source components and fonts licensed by third parties under their own terms (for example the MIT, Apache 2.0, MPL 2.0 and SIL Open Font License 1.1 licences), listed in THIRD_PARTY_NOTICES.md, installed with the Software. Nothing in this Agreement restricts rights granted by those licences.

## 12. Trademarks

"Brutal Focus", "Brutal Focus Lock" and the BF logo are trademarks of the Author. Microsoft, Windows, Blackboard, Canvas, Moodle, Pearson, Respondus, LockDown Browser, Proctorio, Honorlock and all other names mentioned in the Software or its documentation are the property of their respective owners. The Software is not affiliated with, sponsored by or endorsed by any of them. Such names are used only to describe compatibility or warn about conflicts.

## 13. Privacy

How the Software handles data is described in the Privacy Policy on the Brutal Focus Lock website.

## 14. Security updates and support

The Author aims to fix security problems promptly and publishes fixes as new versions on the official download pages. Report security issues as described on the website. Updates are not installed automatically; keep the Software up to date.

## 15. Updates and termination

The Author may release updates, change or remove features, or stop providing the Software at any time, with or without notice, except where mandatory law requires otherwise. You may keep using a version you have installed under this Agreement, but the Author has no duty to update it, and changes in Windows, browsers or other third-party systems may stop parts of it from working. This licence ends automatically if you breach this Agreement. You may end it at any time by uninstalling the Software; before uninstalling during a session, end the session or use RESET HOSTS FILE NOW. Sections 1, 6, 7, 9, 12 and 16 survive termination.

## 16. Governing law and disputes

This Agreement is governed by the laws of Italy, excluding the United Nations Convention on Contracts for the International Sale of Goods, subject to any mandatory protection that applies in your country of habitual residence. You may contact the Author (section 17) to seek an informal resolution, but doing so is voluntary and does not affect legal time limits. No exclusive court is selected; jurisdiction follows applicable law, including any mandatory consumer right to bring proceedings locally.

If any provision of this Agreement is held invalid or unenforceable, the remaining provisions stay in effect. This Agreement is the entire agreement between you and the Author regarding the Software.

## 17. Contact

the Brutal Focus project. Privacy, support and confidential security contact: brutalfocussupport@gmail.com. Ordinary public bug reports: github.com/faradjv-spec/brutal-focus-lock/issues. Avoid posting private information in public issues.
