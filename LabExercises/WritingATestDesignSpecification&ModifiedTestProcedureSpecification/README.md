# Writing a Test Design Specification & Modified Test Procedure Specification

Write a formal **Test Design Specification** that follows the outline on pages 192-193 of your textbook:

1. **Test design specification identifier**. Use this naming scheme: **yyyymmdd-LastnameFirstname-TDS**. Thus, if I wrote the assigned TDS on the first of May, my identifier would be 20160501-May-PumphreyMaryAnn-TDS.

2. **Features to be tested**. Provide the URL and overlay name if applicable. (For example, ResumeSmarts needs the latter, since it appears to be a Single Page App.) 

Then describe exactly what your TDS is going to cover. Examples include:

* ResumeSmarts Preferences 
* ResumeSmarts template creation
* NSHSF home page rendering on mobile devices
* DeAnza Search Center's four top forms: Admissions, Registrations, & Fees; Financial Aid; Counseling; and Faculty Web Sites.

3. **Approach refinements**. You only need this if your tests would be best executed with the aid of some tool (such as BrowserStack's Screenshots for a TDS about rendering), or if they need to be executed on a specific browser or mobile device.

4. **Test identification**. This is the most important part of your TDS--a one-liner describing as succinctly as possible what each test case would test. For example, if your TDS's Features to be tested specified the ResumeSmarts Preferences, a few of the one-liners might be:

* Invite with valid/matching Email/Confirm values (***Happy Path*** case)
* Invite with valid/matching Email/Confirm values, each with identical number of trailing blanks => confirmation of send
* Invite with valid/matching Email/Confirm values, each with identical number of leading blanks => confirmation of send
* Invite with valid but mismatched Email/Confirm values => error message
* Negative: Invite with invalid/matching Email/Confirm values => error message

It is important that you strive for complete testing coverage with your test cases. However, only 10 test cases are required for this TDS assignment. Thus, in order to do the minimal work for the maximal grade ;-), you should find a feature(s) for which complete coverage can be attained via only 10 test cases.

==========

Once your TDS is complete, write a **Test Procedure Specification** (TPS) for just **one** of the test cases specified in your TDS. I have slightly modified the TPS outline given in your book on pages 193-194 to include the input and output specifications from the **Test Case Specification** from page 193. 

1. Test procedure specification identifier. Use this naming scheme: **yyyymmdd-LastnameFirstname-TPS-nn**, where **nn** is the number of the test case from your TDS which you are expanding in this TPS. Thus, if I wrote this TPS on the 3rd of May, for the second bulleted test case above, my TPS identifier would be: 20160503-May-PumphreyMaryAnn-TPS-2.

2. Purpose. Copy/paste the test case's one-line summary from your TDS here.

3. Special requirements. Again, if your test would be best executed with the aid of some tool (such as BrowserStack's Screenshots for a TDS about rendering), or if it needs to be executed on a specific browser or mobile device, detail that here. 

4. Procedure steps. This is the meat of the TPS. Specify every step that the user must take in order to execute the test case. Include any inputs right in the steps. End with an **EXPECTED RESULTS** paragraph, just as you would do with a bug report. However, do not include an **ACTUAL RESULTS** paragraph as this is a test case, to be reused many times, not a bug report or test report of any type.

**To submit this assignment**: upload two separate files (.doc, .docx, .pages, .pdf), one of your TDS and one of your TPS. I would not expect either of these files to be over a page, although up to two pages is permissible, i.e., don't sacrifice readability for document length!

Having your TDS and TPS reviewed/critiqued by a classmate is highly encouraged! I will be just as fussy about the writing of these two test documents as for the Meetup Review assignment, so please get the errors, typos, etc., out before handing in your assignment!

**Grading criteria for this assignment**:

* Coverage completeness of test cases
* Clarity of test case summaries in TDS
* Clarity of steps to execute in TPS
* Absence of errors!
* Adherence to formal outlines of TDS and TPS