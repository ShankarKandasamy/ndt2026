# Test 1: the 240 questions

All 240 templates in family order. 90 questions were tested; the rest were not.

**Measured results** (Search, Padded, G v1, G v2, G_X2) are language-model recall per context, for the tested questions only. For a tested question with no expected record, "none" means the answer cited only correct records or none, and "cited" means it cited a record outside the key. Contexts: Search = top-10 search results; Padded = search results padded to the length of the graph context; G v1, G v2, G_X2 = the same results plus typed links from the curated graph, the curated graph with four audited links retyped, and the extracted graph.

**Predicted values** (the four Pred. columns) are **not test results**. They are given for the 61 untested questions that have a positive answer key, as the mean recall of the tested questions with the same family, wording and language (at least two), else the family mean, else the overall mean. They show what similar questions scored and must not be pooled with the measured results. Untested questions whose answer is that nothing exists, and templates that could not be filled on this archive, have no prediction.

A template that could not be filled on this archive shows its template wording, with placeholders in angle brackets. The same table as CSV: `questions_240.csv`. Results by family and stratum: `results/test1-results.md`.

| ID | Status | Question | Key | Search | Padded | G v1 | G v2 | G_X2 | Pred. Search | Pred. Padded | Pred. G v2 | Pred. G_X2 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| F01-001 | Tested | Which record set the current inspection interval for 6-SG-101? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.50 |  |  |  |  |
| F01-002 | Tested | 6-SG-102 is on a 3-year interval. Which decision set it, and when? | 2 | 0.00 | 0.00 | 0.50 | 1.00 | 0.00 |  |  |  |  |
| F01-003 | Tested | Where does the inspection frequency for 8-TG-101 actually come from: the plan, or something upstream of the plan? | 2 | 0.00 | 0.00 | 1.00 | 1.00 | 0.00 |  |  |  |  |
| F01-004 | Not tested | Who decided how often 4-LA-101 gets surveyed, and in which document? | 2 |  |  |  |  |  | 0.17 | 0.17 | 0.83 | 0.17 |
| F01-005 | Tested | Trace the interval on 4-LA-102 back to the decision that set it. | 2 | 0.00 | 0.00 | 1.00 | 1.00 | 0.00 |  |  |  |  |
| F01-006 | Not tested | Which record set the current inspection interval for 4-RA-101? | 1 |  |  |  |  |  | 0.14 | 0.34 | 0.20 | 0.10 |
| F01-007 | Not tested | 4-RA-102 is on a 3-year interval. Which decision set it, and when? | 1 |  |  |  |  |  | 0.14 | 0.34 | 0.20 | 0.10 |
| F01-008 | Not tested | Where does the inspection frequency for 6-RA-103 actually come from: the plan, or something upstream of the plan? | 2 |  |  |  |  |  | 0.17 | 0.17 | 0.83 | 0.17 |
| F01-009 | Not tested | Who decided how often 2-RV-102 gets surveyed, and in which document? | 2 |  |  |  |  |  | 0.17 | 0.17 | 0.83 | 0.17 |
| F01-010 | Tested | Trace the interval on 3-RF-101 back to the decision that set it. | 2 | 0.50 | 0.50 | 0.50 | 0.50 | 0.50 |  |  |  |  |
| F01-011 | Tested | The 2-RF-102 interval went from 6 years to 1 year in 2024. Which record set the 1-year interval, and which record had set the 6-year one? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F01-012 | Not tested | Why was &lt;LINE&gt; on a &lt;N&gt;-year interval when &lt;K&gt; of its CMLs fell below t-min in &lt;YEAR&gt;? |  |  |  |  |  |  |  |  |  |  |
| F01-013 | Not tested | &lt;CML&gt; on &lt;LINE&gt; read below minimum required thickness in &lt;YEAR&gt;. Which record justified leaving the interval at &lt;N&gt; years? |  |  |  |  |  |  |  |  |  |  |
| F01-014 | Not tested | The &lt;YEAR&gt; readings on &lt;LINE&gt; were under the retirement limit, yet the line was not re-surveyed for &lt;N&gt; years. What was that interval resting on? |  |  |  |  |  |  |  |  |  |  |
| F01-015 | Not tested | A reviewer sees a thin reading on &lt;LINE&gt; in &lt;YEAR&gt; and a long gap before the next survey. Which decision explains the gap, and did it consider that line specifically? |  |  |  |  |  |  |  |  |  |  |
| F01-016 | Not tested | Welche Unterlage hat das aktuelle Prüfintervall für &lt;LINE_DE&gt; festgelegt? |  |  |  |  |  |  |  |  |  |  |
| F01-017 | Not tested | &lt;LINE_DE&gt; wird alle &lt;N&gt; Jahre geprüft. Aus welcher Entscheidung stammt dieses Intervall? |  |  |  |  |  |  |  |  |  |  |
| F01-018 | Not tested | Woher kommt die Prüffrequenz für &lt;LINE_DE&gt;: aus dem Prüfplan selbst oder aus einer vorgelagerten Entscheidung? |  |  |  |  |  |  |  |  |  |  |
| F01-019 | Not tested | Warum wurde das Prüfintervall für &lt;LINE_DE&gt; im Jahr &lt;YEAR&gt; auf &lt;N&gt; Jahre geändert, und welche Unterlage hat das festgelegt? |  |  |  |  |  |  |  |  |  |  |
| F01-020 | Tested | Welche Unterlage hat nach der Ursachenanalyse NR-UA-2014-01 das Prüfintervall für die isolierten Edelstahlleitungen in Werk Niederrhein geändert? | 2 | 1.00 | 1.00 | 0.50 | 0.50 | 0.50 |  |  |  |  |
| F01-021 | Not tested | Die Prüffrequenz an &lt;LINE_DE&gt; wurde nach &lt;YEAR&gt; angepasst. Wer hat das entschieden und wo ist es dokumentiert? |  |  |  |  |  |  |  |  |  |  |
| F01-022 | Tested | QSCP-DMR-2014-002 is a governing decision with no link into it. Which lines' inspection intervals or scope rest on it? | 7 | 0.71 | 0.71 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F01-023 | Tested | Which lines does CIE-FFS-2025-005-R0 govern, and through which plan revision does it reach them? | 1 | 0.00 | 1.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F01-024 | Not tested | Which lines does QSCP-RCA-2007-002 govern, and through which plan revision does it reach them? | 2 |  |  |  |  |  | 0.14 | 0.34 | 0.20 | 0.10 |
| F01-025 | Not tested | Name every decision record in the archive that set an inspection interval but is cited by fewer than three other records. | 1 |  |  |  |  |  | 0.14 | 0.34 | 0.20 | 0.10 |
| F02-001 | Not tested | Which procedure revision and inspection plan revision governed survey LNDE-FN-20241025-031 of 6-SG-101 on 2024-11-04? | 4 |  |  |  |  |  | 0.33 | 0.63 | 0.74 | 0.61 |
| F02-002 | Tested | What governed LNDE-RPT-20220906-033-R0 (6-SG-102, 2022-09-16): the procedure, the plan, and the standard they implement, each at the revision in force that day? | 3 | 0.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F02-003 | Not tested | What applies to 8-TG-101 now, and what governed its October 2019 survey? | 7 |  |  |  |  |  | 0.33 | 0.63 | 0.74 | 0.61 |
| F02-004 | Tested | When 4-LA-101 was surveyed in February 2016, which versions of the procedure and the plan were in force? Not the current ones, the ones in force that day. | 2 | 0.00 | 0.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F02-005 | Not tested | An auditor asks what rules the February 2006 inspection of 4-LA-102 was done to. Which documents, at which revision? | 3 |  |  |  |  |  | 0.22 | 0.22 | 0.83 | 0.67 |
| F02-006 | Tested | For the March 1996 thickness survey on 6-LA-103, were the inspectors working to a procedure that has since been replaced? If so, which one were they using? | 2 | 0.00 | 0.00 | 0.00 | 0.50 | 0.00 |  |  |  |  |
| F02-007 | Not tested | Which procedure revision and inspection plan revision governed survey LNDE-RPT-20241202-036-R0 of 4-RA-101 on 2024-12-10? | 4 |  |  |  |  |  | 0.33 | 0.63 | 0.74 | 0.61 |
| F02-008 | Not tested | What governed LNDE-RPT-20140902-024-R0 (4-RA-102, 2014-09-19): the procedure, the plan, and the standard they implement, each at the revision in force that day? | 2 |  |  |  |  |  | 0.33 | 0.63 | 0.74 | 0.61 |
| F02-009 | Tested | What applies to 6-RA-103 now, and what governed its February 2011 survey? | 7 | 0.14 | 0.14 | 0.71 | 0.71 | 0.57 |  |  |  |  |
| F02-010 | Not tested | When 3-RV-101 was surveyed in September 2013, which versions of the procedure and the plan were in force? Not the current ones, the ones in force that day. | 3 |  |  |  |  |  | 0.22 | 0.22 | 0.83 | 0.67 |
| F02-011 | Tested | An auditor asks what rules the September 2010 inspection of 2-RV-102 was done to. Which documents, at which revision? | 3 | 0.67 | 0.67 | 0.67 | 1.00 | 1.00 |  |  |  |  |
| F02-012 | Not tested | For the December 2013 thickness survey on 3-RF-101, were the inspectors working to a procedure that has since been replaced? If so, which one were they using? | 3 |  |  |  |  |  | 0.22 | 0.22 | 0.83 | 0.67 |
| F02-013 | Not tested | Which procedure revision and inspection plan revision governed survey LNDE-RPT-01-037 of 4-RA-104 on 2001-03-02? | 2 |  |  |  |  |  | 0.33 | 0.63 | 0.74 | 0.61 |
| F02-014 | Not tested | What governed &lt;SURVEY&gt; (&lt;LINE&gt;, &lt;SURVEY_DATE&gt;): the procedure, the plan, and the standard they implement, each at the revision in force that day? |  |  |  |  |  |  |  |  |  |  |
| F02-015 | Not tested | What applies to &lt;LINE&gt; now, and what governed its &lt;MONTH_YEAR&gt; survey? |  |  |  |  |  |  |  |  |  |  |
| F02-016 | Not tested | When &lt;LINE&gt; was surveyed in &lt;MONTH_YEAR&gt;, which versions of the procedure and the plan were in force? Not the current ones, the ones in force that day. |  |  |  |  |  |  |  |  |  |  |
| F02-017 | Not tested | An auditor asks what rules the &lt;MONTH_YEAR&gt; inspection of &lt;LINE&gt; was done to. Which documents, at which revision? |  |  |  |  |  |  |  |  |  |  |
| F02-018 | Not tested | For the &lt;MONTH_YEAR&gt; thickness survey on &lt;LINE&gt;, were the inspectors working to a procedure that has since been replaced? If so, which one were they using? |  |  |  |  |  |  |  |  |  |  |
| F02-019 | Tested | Welche Revision der Prüfanweisung und des Prüfplans galt für die Prüfung RLW-PB-2023-0144 an NR-21-L-0401 am 2023-03-13? | 5 | 0.00 | 0.00 | 0.40 | 0.40 | 0.40 |  |  |  |  |
| F02-020 | Tested | Nach welchen Vorgaben, Prüfanweisung und Prüfplan jeweils in welcher Fassung, wurde NR-21-L-0412 im März 2018 geprüft? | 4 | 0.00 | 0.00 | 0.50 | 0.50 | 0.25 |  |  |  |  |
| F02-021 | Not tested | Was gilt heute für NR-21-L-0415, und was galt bei der Prüfung im März 2013? | 8 |  |  |  |  |  | 0.00 | 0.00 | 0.45 | 0.45 |
| F02-022 | Not tested | Welche Fassung der Prüfanweisung war am 2008-04-01 in Werk Niederrhein in Kraft, und welche gilt heute? | 8 |  |  |  |  |  | 0.10 | 0.10 | 0.35 | 0.23 |
| F02-023 | Tested | Unter welcher Revision der Prüfanweisung des Prüfdienstleisters wurde RLW-PB-2003-0112 durchgeführt, und ist diese Revision noch gültig? | 2 | 0.00 | 0.00 | 0.50 | 0.50 | 0.50 |  |  |  |  |
| F02-024 | Tested | Ein Auditor fragt, nach welchen Regeln die Prüfung an NR-21-L-0207 im Juli 2023 erfolgt ist. Welche Dokumente, in welcher Revision? | 5 | 0.20 | 0.20 | 0.20 | 0.20 | 0.20 |  |  |  |  |
| F02-025 | Not tested | Wurde NR-21-L-0209 im September 2020 nach einer inzwischen ersetzten Prüfanweisung geprüft? Wenn ja, nach welcher? | 5 |  |  |  |  |  | 0.10 | 0.10 | 0.35 | 0.23 |
| F02-026 | Tested | Which revision of QSCP-NDT-001 Rev 3 is current? | 1 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F02-027 | Not tested | If I am surveying 6-SG-101 next month, which version of the UT procedure and of the plan do I follow? | 2 |  |  |  |  |  | 0.22 | 0.22 | 0.83 | 0.67 |
| F02-028 | Tested | What applies to 6-SG-102 now? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F02-029 | Not tested | Is QSCP-IP-ATU100 Rev 3 still in force, or has it been superseded, and by what? | 1 |  |  |  |  |  | 0.33 | 0.63 | 0.74 | 0.61 |
| F02-030 | Tested | List the current revision of every procedure and plan that applies to 8-TG-101. | 2 | 0.50 | 1.00 | 1.00 | 1.00 | 0.50 |  |  |  |  |
| F02-031 | Not tested | Someone handed me &lt;DOC&gt; Rev &lt;N&gt; for a job on &lt;LINE&gt;. Is that the right version? |  |  |  |  |  |  |  |  |  |  |
| F02-032 | Not tested | Which of the three revisions of &lt;DOC&gt; on file should a new technician be trained to? |  |  |  |  |  |  |  |  |  |  |
| F02-033 | Not tested | Welche Revision von RLW-PA-UT-07 Rev 3 ist aktuell gültig? | 1 |  |  |  |  |  | 0.00 | 0.00 | 0.45 | 0.45 |
| F02-034 | Not tested | Ist NR-PP-21 Rev 2 noch in Kraft, oder wurde sie ersetzt, und wodurch? | 1 |  |  |  |  |  | 0.00 | 0.00 | 0.45 | 0.45 |
| F02-035 | Not tested | Welche Fassungen der Prüfanweisungen und des Prüfplans gelten heute für NR-21-L-0401? | 4 |  |  |  |  |  | 0.10 | 0.10 | 0.35 | 0.23 |
| F03-001 | Tested | For the F-2-RF-102-05-2024-11-04 finding, what is the full trail: survey report, NCR, PAUT follow-up, FFS, plan revision, MOC and turnaround baseline? | 6 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F03-002 | Not tested | List every record in the close-out of F-2-RF-102-06-2024-11-04, in date order, with what each one did. | 6 |  |  |  |  |  | 0.50 | 0.83 | 0.50 | 0.50 |
| F03-003 | Tested | NR-AB-2023-04 was raised against F-NR-21-L-0207-05-2023-03-13. What followed it, through to the baseline survey after the turnaround? | 4 | 0.50 | 0.50 | 0.50 | 0.50 | 0.50 |  |  |  |  |
| F03-004 | Tested | Walk me through how the 2024 wall-loss call at 2-RF-102-07 on 2-RF-102 was closed out, from the first reading to the baseline after the turnaround. | 6 | 0.83 | 0.83 | 0.83 | 0.83 | 0.83 |  |  |  |  |
| F03-005 | Not tested | A thin spot was found on 4-RA-101 in 2024. What was done about it, and is there a record of the repair being checked afterwards? | 6 |  |  |  |  |  | 0.28 | 0.28 | 0.28 | 0.28 |
| F03-006 | Not tested | What is the paper trail for the &lt;MECHANISM&gt; finding on &lt;LINE&gt; in &lt;YEAR&gt;: who flagged it, who assessed it, and what changed as a result? |  |  |  |  |  |  |  |  |  |  |
| F03-007 | Not tested | For the &lt;FINDING&gt; finding, what is the full trail: survey report, NCR, PAUT follow-up, FFS, plan revision, MOC and turnaround baseline? |  |  |  |  |  |  |  |  |  |  |
| F03-008 | Not tested | List every record in the close-out of &lt;FINDING&gt;, in date order, with what each one did. |  |  |  |  |  |  |  |  |  |  |
| F03-009 | Not tested | QSCP-NCR-2024-032 was raised against F-2-RF-102-04-2024-11-04. What followed it, through to the baseline survey after the turnaround? | 6 |  |  |  |  |  | 0.50 | 0.83 | 0.50 | 0.50 |
| F03-010 | Not tested | Walk me through how the &lt;YEAR&gt; wall-loss call at &lt;CML&gt; on &lt;LINE&gt; was closed out, from the first reading to the baseline after the turnaround. |  |  |  |  |  |  |  |  |  |  |
| F03-011 | Not tested | A thin spot was found on &lt;LINE&gt; in &lt;YEAR&gt;. What was done about it, and is there a record of the repair being checked afterwards? |  |  |  |  |  |  |  |  |  |  |
| F03-012 | Tested | What happened after F-2-RF-102-06-2019-10-18 was raised? Which close-out steps exist on file, and which are missing? | 1 | 0.00 | 1.00 | 1.00 | 0.00 | 0.00 |  |  |  |  |
| F03-013 | Tested | Is the 2019 finding on 2-RF-102 closed? Show me what exists and what does not. | 1 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F03-014 | Not tested | F-4-RA-101-06-2024-12-10 has an NCR. Is there an FFS, a plan change and a follow-up examination, or did it stop at the NCR? | 7 |  |  |  |  |  | 0.50 | 0.83 | 0.50 | 0.50 |
| F03-015 | Tested | Which of the open findings on 2-RF-102 never got a fitness-for-service assessment? | 1 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F03-016 | Not tested | For F-2-RF-102-05-2019-10-18, which stage of the close-out is the last one on file, and what should have followed it? | 1 |  |  |  |  |  | 0.50 | 0.83 | 0.50 | 0.50 |
| F03-017 | Not tested | Did anyone ever go back and re-measure 6-RA-103-11 after the 2024 call on it? | 4 |  |  |  |  |  | 0.28 | 0.28 | 0.28 | 0.28 |
| F03-018 | Not tested | Welche Schritte zur Abarbeitung der Feststellung F-NR-21-L-0207-05-2023-07-05 sind dokumentiert (Prüfbericht, Abweichungsmeldung, Nachprüfung, Bewertung, Prüfplanänderung), und welche fehlen? | 5 |  |  |  |  |  | 0.40 | 0.55 | 0.40 | 0.40 |
| F03-019 | Tested | Ist die Feststellung von 2026 an NR-21-L-0207 abgeschlossen? Was liegt vor, was fehlt? | 4 | 0.50 | 0.50 | 0.50 | 0.50 | 0.50 |  |  |  |  |
| F03-020 | Not tested | Zu &lt;FINDING_DE&gt; gibt es eine Abweichungsmeldung. Gibt es auch eine Bewertung und eine Nachprüfung, oder endet der Vorgang dort? |  |  |  |  |  |  |  |  |  |  |
| F04-001 | Tested | Suppose Olympus OmniScan X3 1022157 (calibration certificate LNDE-CAL-2024-0921) failed its next calibration. Which readings are suspect? | 2 | 0.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F04-002 | Not tested | Which survey reports used &lt;INSTRUMENT&gt; between &lt;CAL_DATE&gt; and its next calibration? |  |  |  |  |  |  |  |  |  |  |
| F04-003 | Not tested | The gauge used on &lt;LINE&gt; in &lt;YEAR&gt; turned out to read high. Which other surveys used the same gauge in that period? |  |  |  |  |  |  |  |  |  |  |
| F04-004 | Not tested | List every reading taken with serial &lt;SERIAL&gt; after &lt;CAL_DATE&gt;. |  |  |  |  |  |  |  |  |  |  |
| F04-005 | Not tested | One of the thickness gauges on the &lt;YEAR&gt; campaign is being recalled. Which CMLs were measured with it? |  |  |  |  |  |  |  |  |  |  |
| F04-006 | Not tested | &lt;CAL_CERT&gt; has been withdrawn by the lab. Which reports cite it? |  |  |  |  |  |  |  |  |  |  |
| F04-007 | Tested | Olympus OmniScan X3 1022157 failed its next calibration. Which interval or FFS decisions rest on readings it produced? | 3 | 0.33 | 0.33 | 0.33 | 0.33 | 0.33 |  |  |  |  |
| F04-008 | Not tested | If the readings under &lt;CAL_CERT&gt; are thrown out, which fitness-for-service assessments and interval changes lose their basis? |  |  |  |  |  |  |  |  |  |  |
| F04-009 | Not tested | A gauge used on the &lt;YEAR&gt; campaign was out of tolerance. Which decisions about how often to inspect, or whether to keep running, depend on numbers from that gauge? |  |  |  |  |  |  |  |  |  |  |
| F04-010 | Not tested | Which NCR dispositions cite readings that were taken with &lt;INSTRUMENT&gt;? |  |  |  |  |  |  |  |  |  |  |
| F04-011 | Not tested | Something was wrong with the instrument on &lt;LINE&gt; in &lt;YEAR&gt;. Downstream of that, what was decided on the strength of those numbers? |  |  |  |  |  |  |  |  |  |  |
| F04-012 | Not tested | Trace &lt;CAL_CERT&gt; forward: reports, then findings, then the decisions that used those findings. |  |  |  |  |  |  |  |  |  |  |
| F04-013 | Tested | QSCP-NCR-2013-019 rejected the readings in HIS-2013-0402. Does any later record still rely on them? | 1 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F04-014 | Not tested | A survey on &lt;LINE&gt; was thrown out as unreliable in &lt;YEAR&gt;. Was anything decided afterwards on the basis of it anyway? |  |  |  |  |  |  |  |  |  |  |
| F04-015 | Not tested | Which decisions dated after &lt;NCR_DATE&gt; cite findings from &lt;REPORT&gt;, the report that &lt;NCR&gt; withdrew? |  |  |  |  |  |  |  |  |  |  |
| F04-016 | Not tested | Did the rejection of the &lt;YEAR&gt; survey on &lt;LINE&gt; actually propagate, or did the FFS keep using its numbers? |  |  |  |  |  |  |  |  |  |  |
| F04-017 | Tested | Das Wanddickenmessgerät RLW-UT-31 ist bei der Rekalibrierung durchgefallen. Welche Messwerte sind betroffen, und welche Intervall- oder Bewertungsentscheidungen stützen sich darauf? | 5 | 1.00 | 0.40 | 0.40 | 0.40 | 1.00 |  |  |  |  |
| F04-018 | Not tested | Der Kalibrierschein &lt;CAL_CERT_DE&gt; wurde zurückgezogen. Welche Prüfberichte beruhen auf diesem Gerät? |  |  |  |  |  |  |  |  |  |  |
| F04-019 | Not tested | Ein Messgerät aus der Kampagne &lt;YEAR&gt; war außerhalb der Toleranz. Welche Entscheidungen über Prüfintervalle hängen an diesen Messwerten? |  |  |  |  |  |  |  |  |  |  |
| F04-020 | Not tested | Die Messwerte der Prüfung &lt;YEAR&gt; an &lt;LINE_DE&gt; wurden verworfen. Wurde danach trotzdem etwas auf dieser Grundlage entschieden? |  |  |  |  |  |  |  |  |  |  |
| F05-001 | Tested | Which surveys were performed under QSCP-IP-ATU100 Rev 3? | 4 | 0.75 | 0.75 | 0.75 | 0.75 | 0.75 |  |  |  |  |
| F05-002 | Tested | List every report made to QSCP-IP-ATU100 Rev 4, and nothing made to any other revision. | 4 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F05-003 | Tested | Which reports were done to the version of the inspection plan that was in force during 1996? | 4 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F05-004 | Not tested | HIS-UT-002 Rev 1 has been found defective. Which inspections does that touch? | 6 |  |  |  |  |  | 0.88 | 0.88 | 0.88 | 0.88 |
| F05-005 | Not tested | Between 1995-11-20 and 2008-04-01 the UT procedure was at one particular revision. Everything done to it: which reports? | 4 |  |  |  |  |  | 0.20 | 0.20 | 0.20 | 0.20 |
| F05-006 | Not tested | Which surveys cite &lt;PROC&gt; Rev &lt;N&gt; only in passing, as opposed to having been performed under it? |  |  |  |  |  |  |  |  |  |  |
| F05-007 | Not tested | Which surveys were performed under &lt;PROC&gt; Rev &lt;N&gt;? |  |  |  |  |  |  |  |  |  |  |
| F05-008 | Not tested | List every report made to &lt;PROC&gt; Rev &lt;N&gt;, and nothing made to any other revision. |  |  |  |  |  |  |  |  |  |  |
| F05-009 | Tested | Which reports were done to the version of the inspection plan that was in force during 2011? | 5 | 0.40 | 0.40 | 0.40 | 0.40 | 0.40 |  |  |  |  |
| F05-010 | Not tested | &lt;PROC&gt; Rev &lt;N&gt; has been found defective. Which inspections does that touch? |  |  |  |  |  |  |  |  |  |  |
| F05-011 | Not tested | Between 2011-01-17 and 2024-01-15 the UT procedure was at one particular revision. Everything done to it: which reports? | 7 |  |  |  |  |  | 0.20 | 0.20 | 0.20 | 0.20 |
| F05-012 | Not tested | Which surveys cite &lt;PROC&gt; Rev &lt;N&gt; only in passing, as opposed to having been performed under it? |  |  |  |  |  |  |  |  |  |  |
| F05-013 | Not tested | Which surveys were performed under &lt;PROC&gt; Rev &lt;N&gt;? |  |  |  |  |  |  |  |  |  |  |
| F05-014 | Tested | Welche Prüfungen wurden nach RLW-PA-UT-07 Rev 2 durchgeführt? | 3 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F05-015 | Tested | Welche Prüfberichte beruhen auf der Fassung der Prüfanweisung, die im Jahr 2003 galt? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F05-016 | Not tested | RLW-PA-UT-07 Rev 3 ist fehlerhaft. Welche Prüfungen sind davon betroffen, und welche Berichte erwähnen die Revision nur beiläufig? | 2 |  |  |  |  |  | 0.53 | 0.53 | 0.53 | 0.53 |
| F05-017 | Not tested | If LNDE-CAL-UT-001 Rev 3 is found defective, which reports were made under it, and which interval or FFS decisions rest on those reports? | 10 |  |  |  |  |  | 0.88 | 0.88 | 0.88 | 0.88 |
| F05-018 | Not tested | A revision of the UT procedure in force around 2024 had a wrong calibration block. What was measured under it, and what was decided from those measurements? | 6 |  |  |  |  |  | 0.20 | 0.20 | 0.20 | 0.20 |
| F06-001 | Tested | Which of LNDE-RPT-20241025-031 R0, R1 and R2 is the record of record, and what changed between them? | 3 | 0.00 | 0.33 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F06-002 | Not tested | Which revision of &lt;REPORT_B&gt; is current, and which earlier revisions exist? |  |  |  |  |  |  |  |  |  |  |
| F06-003 | Tested | Is LNDE-RPT-20191001-027-R0 (signed scan) a signed copy of LNDE-RPT-20191001-027-R0, or a separate revision? | 2 | 1.00 | 0.50 | 0.50 | 1.00 | 1.00 |  |  |  |  |
| F06-004 | Not tested | There are two near-identical PDFs of the &lt;YEAR&gt; report on &lt;LINE&gt;. Is one a scan of the other, or did the numbers change? |  |  |  |  |  |  |  |  |  |  |
| F06-005 | Not tested | Which revision of &lt;REPORT&gt; do the thickness-tracker values for &lt;LINE&gt; come from? |  |  |  |  |  |  |  |  |  |  |
| F06-006 | Tested | The tracker shows 3.6 mm for 4-RA-101-06. Which version of which report is that number from, and is it the final one? | 4 | 0.00 | 0.00 | 0.00 | 0.50 | 0.00 |  |  |  |  |
| F06-007 | Not tested | List every copy and revision of QSCP-NDT-001 on file and mark the one that is current. | 5 |  |  |  |  |  | 0.50 | 0.42 | 0.50 | 0.50 |
| F06-008 | Not tested | I have a draft, a final and a signed scan of the &lt;YEAR&gt; survey on &lt;LINE&gt;. Which one should the FFS have used, and which one did it use? |  |  |  |  |  |  |  |  |  |  |
| F06-009 | Not tested | Does CIE-FFS-2025-004-R0 cite the superseded or the current revision of LNDE-RPT-20241025-031? | 1 |  |  |  |  |  | 0.50 | 0.42 | 0.50 | 0.50 |
| F06-010 | Not tested | Welche Fassung des Prüfberichts &lt;REPORT_DE&gt; ist die gültige, und welche früheren Fassungen gibt es? |  |  |  |  |  |  |  |  |  |  |
| F06-011 | Tested | Von der Prüfung 2026 an NR-21-L-0207 liegen zwei fast gleiche Berichte vor. Ist einer eine unterschriebene Kopie des anderen, oder wurden Werte geändert? | 2 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F06-012 | Not tested | Auf welche Fassung von &lt;REPORT_DE&gt; stützt sich die Bewertung &lt;FFS_DE&gt;? |  |  |  |  |  |  |  |  |  |  |
| F07-001 | Not tested | What did the Niederrhein root-cause analysis NR-UA-2014-01 conclude, and which Hamilton lines carry the same damage mechanism? | 3 |  |  |  |  |  | 0.17 | 0.42 | 0.42 | 0.42 |
| F07-002 | Tested | Which German-site record does QSCP-TRL-2013-01 summarize, and does the summary carry the interval change? | 1 | 0.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F07-003 | Tested | The German plant found cracking under insulation on stainless lines some years ago. Where is the original investigation, and has the same mechanism been looked for in Hamilton? | 1 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F07-004 | Not tested | Which corporate standard revision implemented the &lt;YEAR&gt; Niederrhein lesson, and which Niederrhein record prompted it? |  |  |  |  |  |  |  |  |  |  |
| F07-005 | Not tested | Has Lower Rhine seen the damage mechanism found at 2-RF-102-04 on 2-RF-102 in 2019? | none |  |  |  |  |  |  |  |  |  |
| F07-006 | Not tested | Is there anything in the German archive that would have warned Hamilton about local attack from flashing downstream of the let-down valve before it was found on 4-RA-101? | none |  |  |  |  |  |  |  |  |  |
| F07-007 | Not tested | Which Niederrhein Prüfberichte are summarized in English for Hamilton, and which are not? | 23 |  |  |  |  |  | 0.17 | 0.42 | 0.42 | 0.42 |
| F07-008 | Tested | What does the German site do differently from Hamilton for the same corrosion mechanism, and which documents show it? | 3 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F07-009 | Tested | Welche Unterlage aus Hamilton hat die Erkenntnisse aus NR-UA-2014-01 aufgegriffen? | none | none | none | none | none | none |  |  |  |  |
| F07-010 | Not tested | Gibt es in Hamilton eine dokumentierte Folgemaßnahme zur Chlorid-Spannungsrisskorrosions-Feststellung von 2014? | 2 |  |  |  |  |  | 0.07 | 0.19 | 0.19 | 0.19 |
| F07-011 | Tested | Welche Hamilton-Leitungen sind von der in NR-UA-2014-01 beschriebenen Schadensart betroffen? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F07-012 | Not tested | In welcher Konzernnorm wurde die Niederrhein-Erkenntnis von &lt;YEAR&gt; verankert, und welche Revision davon gilt in Hamilton? |  |  |  |  |  |  |  |  |  |  |
| F07-013 | Not tested | Welche englischsprachige Zusammenfassung gibt den Bericht ANG-DA-2023-04018 wieder, und stimmen die Zahlen überein? | 1 |  |  |  |  |  | 0.07 | 0.19 | 0.19 | 0.19 |
| F07-014 | Tested | Wurde die in Hamilton 2024 festgestellte örtliche Korrosion durch Ausdampfen hinter dem Entspannungsventil auch in Werk Niederrhein beobachtet? | none | none | none | none | none | none |  |  |  |  |
| F07-015 | Tested | Was hat Hamilton aus unserer Ursachenanalyse von 2014 gelernt, und wo steht das? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F07-016 | Not tested | Welche Unterlagen verbinden die Prüfprogramme der beiden Standorte? | 26 |  |  |  |  |  | 0.07 | 0.19 | 0.19 | 0.19 |
| F07-017 | Tested | Did the 2014 chloride SCC finding at Werk Niederrhein reach Hamilton's insulated stainless lines? Which records carried it, and where did it stop? | 5 | 0.40 | 0.40 | 0.40 | 0.40 | 0.40 |  |  |  |  |
| F07-018 | Not tested | Follow the German cracking lesson across the corporate boundary: how far did it get, and what was the last record to mention it? | 4 |  |  |  |  |  | 0.00 | 0.00 | 0.00 | 0.00 |
| F07-019 | Tested | Which Niederrhein findings produced a corporate summary, and which of those summaries led to a Hamilton plan revision? | 6 | 0.17 | 0.17 | 0.17 | 0.17 | 0.17 |  |  |  |  |
| F07-020 | Not tested | Has any lesson from one site ever changed an inspection plan at the other? Show the chain, or show where each one stopped. | 8 |  |  |  |  |  | 0.00 | 0.00 | 0.00 | 0.00 |
| F07-021 | Tested | For each declared cross-site record, which site-level document implemented it at each site, if any? | 10 | 0.10 | 0.10 | 0.10 | 0.10 | 0.10 |  |  |  |  |
| F07-022 | Not tested | Which records apply to both sites? | 13 |  |  |  |  |  | 0.17 | 0.42 | 0.42 | 0.42 |
| F07-023 | Not tested | Which corporate standards does each site implement, and at which revision today? | 1 |  |  |  |  |  | 0.17 | 0.42 | 0.42 | 0.42 |
| F07-024 | Not tested | Welche Unterlagen gelten für beide Standorte? | 13 |  |  |  |  |  | 0.07 | 0.19 | 0.19 | 0.19 |
| F07-025 | Tested | Which e-mails connect the two inspection programs, and what did each one hand over? | 5 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F08-001 | Not tested | What changed on the Hamilton amine unit without an MOC? | 5 |  |  |  |  |  | 0.00 | 0.00 | 0.50 | 0.50 |
| F08-002 | Tested | Was there any physical change to the unit in 2019 that skipped the change-management process? | 5 | 0.60 | 0.60 | 0.60 | 0.60 | 0.60 |  |  |  |  |
| F08-003 | Tested | Which findings in the archive have no NCR? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F08-004 | Not tested | Which NCRs have no disposition on file? | none |  |  |  |  |  |  |  |  |  |
| F08-005 | Not tested | Which FFS recommendations were never followed by a plan revision? | none |  |  |  |  |  |  |  |  |  |
| F08-006 | Not tested | Which of the 2024-2025 findings on 4-RA-101 stopped at the NCR and never got an engineering assessment? | none |  |  |  |  |  |  |  |  |  |
| F08-007 | Tested | Which survey reports have no transmittal on file? | none | cited | cited | none | none | none |  |  |  |  |
| F08-008 | Tested | Which surveys have a report but no field notes? | none | cited | cited | cited | cited | cited |  |  |  |  |
| F08-009 | Not tested | Which inspector recommendations were repeated in two or more consecutive surveys of the same line without any action record in between? | none |  |  |  |  |  |  |  |  |  |
| F08-010 | Tested | Is there any line whose inspection interval was changed without a decision record behind the change? | none | none | none | none | none | none |  |  |  |  |
| F08-011 | Tested | Does every corporate standard revision have an implementing plan revision at both sites? | 1 | 0.00 | 0.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F08-012 | Tested | Which NCRs were closed without evidence of the fix? | none | none | none | none | none | cited |  |  |  |  |
| F08-013 | Tested | Which calibration certificates on file are cited by no report at all? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F08-014 | Not tested | Which lines have had no survey of any kind for more than twice their plan interval? | none |  |  |  |  |  |  |  |  |  |
| F08-015 | Tested | Which turnaround baselines were never followed by a routine survey? | none | none | none | none | none | none |  |  |  |  |
| F08-016 | Not tested | Where in the archive does someone say a step was skipped, and is there a record that contradicts them? | 13 |  |  |  |  |  | 0.30 | 0.30 | 0.30 | 0.30 |
| F08-017 | Tested | Welche Änderungen an der Lösemittelrückgewinnung in Werk Niederrhein wurden ohne MOC-Verfahren durchgeführt? | none | none | none | none | none | none |  |  |  |  |
| F08-018 | Tested | Welche Feststellungen in Werk Niederrhein haben keine Abweichungsmeldung? | none | cited | none | cited | cited | cited |  |  |  |  |
| F08-019 | Not tested | Gibt es Empfehlungen der ZÜS, die in keiner späteren Unterlage aufgegriffen wurden? | none |  |  |  |  |  |  |  |  |  |
| F08-020 | Not tested | Welche Prüfberichte aus Werk Niederrhein haben kein Übergabeschreiben? | none |  |  |  |  |  |  |  |  |  |
| F09-001 | Tested | Which CMLs were recorded as inaccessible in LNDE-FN-20241025-031, and was each one measured later? | none | cited | cited | cited | cited | cited |  |  |  |  |
| F09-002 | Tested | LNDE-RPT-01-037 lists 6-SG-101-01 as not accessible. When was it next measured, if ever? | none | cited | cited | cited | cited | cited |  |  |  |  |
| F09-003 | Tested | Some locations on 6-SG-101 could not be reached in 2006 because of scaffolding. Did anyone get to them afterwards? | none | none | none | none | none | none |  |  |  |  |
| F09-004 | Tested | List every CML carried from HIS-2007-0388 to a later survey, and the survey that finally measured it. | none | none | none | none | none | none |  |  |  |  |
| F09-005 | Tested | Which spots on 6-SG-101 have never actually been measured, despite being on the plan since 1995? | none | none | none | none | none | none |  |  |  |  |
| F09-006 | Not tested | Of the CMLs marked inaccessible in the 2022 report (4-RA-101-06 and 6-RA-103-11), which has a later reading? | 1 |  |  |  |  |  | 0.75 | 0.75 | 0.75 | 0.75 |
| F09-007 | Not tested | Is there a CML on 6-SG-102 that keeps getting deferred from one survey to the next? | none |  |  |  |  |  |  |  |  |  |
| F09-008 | Tested | Which surveys on 6-LA-103 reported fewer CMLs than the plan requires, and which CMLs were missing each time? | 1 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F09-009 | Not tested | Which CMLs on &lt;LINE&gt; read below t-min in &lt;YEAR&gt;? |  |  |  |  |  |  |  |  |  |  |
| F09-010 | Tested | In LNDE-RPT-20241202-036-R0, which readings were under the minimum required thickness stated in the plan? | 2 | 0.50 | 0.50 | 0.50 | 0.50 | 0.50 |  |  |  |  |
| F09-011 | Not tested | Where on &lt;LINE&gt; was the wall thinner than allowed in &lt;YEAR&gt;? |  |  |  |  |  |  |  |  |  |  |
| F09-012 | Not tested | Which CMLs on &lt;LINE&gt; are below t-min today, taking t-min from &lt;PLAN_REV&gt; and the readings from the latest survey? |  |  |  |  |  |  |  |  |  |  |
| F09-013 | Not tested | Across the Hamilton amine unit, which locations were under their retirement thickness at the last survey? |  |  |  |  |  |  |  |  |  |  |
| F09-014 | Not tested | Which readings in &lt;SURVEY&gt; were within 0.5 mm of t-min without being below it? |  |  |  |  |  |  |  |  |  |  |
| F09-015 | Not tested | How many locations on &lt;LINE&gt; have gone from above to below the limit between &lt;YEAR&gt; and &lt;YEAR2&gt;? |  |  |  |  |  |  |  |  |  |  |
| F09-016 | Not tested | For &lt;CML&gt;, list every reading on file with its date, and the t-min that applied at each date. |  |  |  |  |  |  |  |  |  |  |
| F09-017 | Not tested | What was the minimum reading on 6-SG-101-01 in LNDE-RPT-96-014? | 1 |  |  |  |  |  | 0.75 | 0.75 | 0.75 | 0.75 |
| F09-018 | Not tested | Which method and which technique sheet does &lt;SURVEY&gt; record for &lt;CML&gt;? |  |  |  |  |  |  |  |  |  |  |
| F09-019 | Not tested | What did the last survey say about the elbow at the let-down valve on 4-RA-101? | 1 |  |  |  |  |  | 0.61 | 0.61 | 0.61 | 0.61 |
| F09-020 | Not tested | How many CMLs did LNDE-RPT-20250811-029-R0 measure, and how many does the plan list for that line? | 1 |  |  |  |  |  | 0.75 | 0.75 | 0.75 | 0.75 |
| F09-021 | Tested | Welche Messstellen wurden bei der Prüfung RLW-PB-2008-0187 als nicht zugänglich vermerkt, und wurden sie später gemessen? | none | cited | cited | cited | none | cited |  |  |  |  |
| F09-022 | Tested | An NR-21-L-0207 konnten 2010 einige Messstellen wegen des Gerüsts nicht erreicht werden. Wurden sie nachgeholt? | none | cited | cited | cited | cited | cited |  |  |  |  |
| F09-023 | Tested | Welche Messstellen an NR-21-L-0207 lagen 2023 unter der Mindestwanddicke? | 3 | 0.33 | 0.33 | 0.33 | 0.33 | 0.33 |  |  |  |  |
| F09-024 | Not tested | Wo an NR-21-L-0207 war die Wand 2026 dünner als zulässig? | 2 |  |  |  |  |  | 0.61 | 0.61 | 0.61 | 0.61 |
| F09-025 | Not tested | Welche Messstellen aus RLW-PB-2013-0164 wurden in eine spätere Prüfung übertragen, und welche Prüfung hat sie schließlich gemessen? | none |  |  |  |  |  |  |  |  |  |
| F09-026 | Not tested | Wie viele Messstellen hat &lt;SURVEY_DE&gt; erfasst, und wie viele sieht der Prüfplan für die Leitung vor? |  |  |  |  |  |  |  |  |  |  |
| F09-027 | Not tested | Gibt es an &lt;LINE_DE&gt; eine Messstelle, die von Prüfung zu Prüfung immer wieder verschoben wurde? |  |  |  |  |  |  |  |  |  |  |
| F09-028 | Not tested | Welcher Mindestmesswert wurde an NR-21-L-0401-01 in RLW-PB-2003-0112 ermittelt? | 1 |  |  |  |  |  | 0.61 | 0.61 | 0.61 | 0.61 |
| F10-001 | Tested | Was every inspector who signed LNDE-RPT-96-014 certified in the method on the signing date? | 2 | 0.50 | 0.50 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F10-002 | Not tested | Which reports did K. Doucette sign outside their UT certification window? | 2 |  |  |  |  |  | 0.33 | 0.50 | 0.33 | 0.17 |
| F10-003 | Tested | Was anyone doing UT on 6-SG-101 in 2001 whose ticket had run out? | none | none | none | none | none | none |  |  |  |  |
| F10-004 | Tested | Was Panametrics 26DL PLUS 9411820 within calibration on 1996-03-08? | 2 | 0.50 | 1.00 | 0.50 | 1.00 | 0.50 |  |  |  |  |
| F10-005 | Not tested | Which surveys were performed with an instrument whose calibration had expired on the survey date? | none |  |  |  |  |  |  |  |  |  |
| F10-006 | Tested | Across the archive, find any report signed before the signer's certificate was issued. | none | none | none | none | none | none |  |  |  |  |
| F10-007 | Not tested | On 2001-03-02, which Level II or Level III certificates were valid for G. Okafor, and which had lapsed? | 1 |  |  |  |  |  | 0.33 | 0.50 | 0.33 | 0.17 |
| F10-008 | Not tested | The second contractor took over in 2004. Were their people certified before they signed their first report for us? | 3 |  |  |  |  |  | 0.30 | 0.40 | 0.30 | 0.20 |
| F10-009 | Tested | Which calibration certificates on file expired before the next certificate for the same instrument was issued, and which surveys fall in the gap? | 1 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F10-010 | Not tested | Who was the Level III who certified &lt;INSPECTOR&gt;, and was the Level III's own certificate valid on that date? |  |  |  |  |  |  |  |  |  |  |
| F10-011 | Tested | War S. Gorissen am 05.07.2023 für Ultraschallprüfung (UT) zertifiziert? | 2 | 0.50 | 0.50 | 0.50 | 0.50 | 0.50 |  |  |  |  |
| F10-012 | Not tested | Welche Prüfberichte hat F. Kemper außerhalb der Gültigkeit seiner Zertifizierung unterschrieben? | none |  |  |  |  |  |  |  |  |  |
| F10-013 | Tested | War das Messgerät bei der Prüfung an NR-21-L-0401 im März 2003 noch innerhalb der Kalibrierfrist? | 2 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |  |  |  |  |
| F10-014 | Not tested | Welche Prüfungen in Werk Niederrhein wurden mit einem Gerät durchgeführt, dessen Kalibrierung am Prüftag abgelaufen war? | none |  |  |  |  |  |  |  |  |  |
| F10-015 | Not tested | Gab es Prüfer, die vor Erteilung ihres Zertifikats bereits Berichte unterschrieben haben? | none |  |  |  |  |  |  |  |  |  |
| F11-001 | Tested | Who performed LNDE-RPT-20150427-019-R0, and for which contractor? | 1 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F11-002 | Not tested | When was QSCP-NCR-2010-007 raised, and against which line? | 1 |  |  |  |  |  | 1.00 | 1.00 | 1.00 | 1.00 |
| F11-003 | Tested | Which site does QSCP-WP-1996-00412 belong to? | 1 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F11-004 | Tested | What method was used in QSCP-INS-2000-018? | 1 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F11-005 | Not tested | What is the plan interval for &lt;LINE&gt; in &lt;PLAN_REV&gt;? |  |  |  |  |  |  |  |  |  |  |
| F11-006 | Not tested | Which corrosion loop is &lt;LINE&gt; assigned to in &lt;RBI_OR_PLAN&gt;? |  |  |  |  |  |  |  |  |  |  |
| F11-007 | Not tested | What date was LNDE-CAL-2001-0027 issued, and by which lab? | 1 |  |  |  |  |  | 1.00 | 1.00 | 1.00 | 1.00 |
| F11-008 | Not tested | Who approved &lt;MOC&gt;? |  |  |  |  |  |  |  |  |  |  |
| F11-009 | Not tested | Wer hat &lt;SURVEY_DE&gt; durchgeführt, und für welchen Auftragnehmer? |  |  |  |  |  |  |  |  |  |  |
| F11-010 | Tested | Wann wurde NR-AB-2014-03 erstellt, und für welche Leitung? | 1 | 1.00 | 1.00 | 1.00 | 1.00 | 1.00 |  |  |  |  |
| F11-011 | Not tested | Welches Prüfverfahren wurde bei &lt;SURVEY_DE&gt; angewendet? |  |  |  |  |  |  |  |  |  |  |
| F11-012 | Not tested | Welches Prüfintervall sieht &lt;PLAN_REV_DE&gt; für &lt;LINE_DE&gt; vor? |  |  |  |  |  |  |  |  |  |  |
| F12-001 | Tested | What did the 2024 radiographic survey of 6-SG-101 find? | none | none | none | none | none | none |  |  |  |  |
| F12-002 | Not tested | Which CMLs on 6-SG-102 were replaced in the 2026 turnaround? | none |  |  |  |  |  |  |  |  |  |
| F12-003 | Tested | What interval did the 2023 RBI review set for NR-21-L-0401? | none | none | none | none | none | none |  |  |  |  |
| F12-004 | Not tested | Who approved the MOC for the 2019 valve trim change? | none |  |  |  |  |  |  |  |  |  |
| F12-005 | Tested | What did the FFS consultant conclude about 8-TG-101 in 2025? | none | none | none | none | none | none |  |  |  |  |
| F12-006 | Not tested | Which corrosion loop does 4-LA-101 belong to in the 2012 RBI review? | none |  |  |  |  |  |  |  |  |  |
| F12-007 | Tested | What did Hamilton's third NDT contractor report on 4-LA-102? | none | none | none | none | cited | none |  |  |  |  |
| F12-008 | Tested | Was hat die ZÜS bei der Prüfung von NR-21-L-0412 im Jahr 2004 festgestellt? | none | none | none | none | none | none |  |  |  |  |
| F12-009 | Not tested | Welche Reparatur wurde 2023 an NR-21-L-0418-01 durchgeführt? | none |  |  |  |  |  |  |  |  |  |
| F12-010 | Not tested | Welches Prüfintervall hat die RBI-Bewertung für &lt;LINE_DE&gt; festgelegt? |  |  |  |  |  |  |  |  |  |  |
