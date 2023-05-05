Download Link: https://assignmentchef.com/product/solved-ece-322-assignment-1-software-system-for-an-autonomous-vehicle
<br>
<strong>1</strong>.Study two papers entitled (located in the Readings folder)

<table width="591">

 <tbody>

  <tr>

   <td width="197">number</td>

   <td width="197">Section taken from the software requirement document</td>

   <td width="197">The quality factor</td>

  </tr>

  <tr>

   <td width="197">1</td>

   <td width="197">The probability that the “superlab” software will be found in a state of failure during peak hours (9AM to 4PM) is required to be below 0.002.</td>

   <td width="197"> </td>

  </tr>

  <tr>

   <td width="197">2</td>

   <td width="197">The “super-lab” software will enable the direct transfer of laboratory results to those files of hospitalized patients managed by</td>

   <td width="197"> </td>

  </tr>

 </tbody>

</table>

<em>No silver bullet</em> published in <em>IEEE Computer</em>

<em>The software engineering silver bullet conundrum</em> published in <em>IEEE Software</em>

Based on this material, what are, in your opinion, the two most essential factors making software testing activities difficult? Distinguish between technical and non-technical (say, organizational, human, etc.) factors. Justify your opinion along with solid and convincing arguments.

<strong>2.</strong>Consider a software system for an autonomous vehicle and in this context discuss the meaning of the pertinent software qualities (say, functionality, reliability, portability, efficiency, etc.). Name them and complete a quality risk analysis. Rate technical risks and business risks. Use a 5point scale (1- very high, 2- high… 5- very low).

<strong>3</strong>. The software requirement specification document for the tender for the development of “superlab” software system for managing a hospital laboratory, consists of chapter headings that are in accordance with the required quality factors. In the following table, there are sections from the requirements document.

For each section below, fill in the name of the McCall factor that best fits the requirement (choose only one factor per requirements section).




<table width="591">

 <tbody>

  <tr>

   <td width="197"> </td>

   <td width="197">MD software package</td>

   <td width="197"> </td>

  </tr>

  <tr>

   <td width="197">3</td>

   <td width="197">The training of laboratory technician, requiring no more than 3 days, will enable the technician to reach level C of “super-lab” operator. This means that the trainee will be able to manage the reception of 20 patients per hour.</td>

   <td width="197"> </td>

  </tr>

  <tr>

   <td width="197">4</td>

   <td width="197">The software system should be able to serve 12 workstations and 8 automatic testing machines with a single model AS20 server and CS25 communication server that will be able to serve 25 communication lines. The hardware system should conform to all availability requirements as listed in Appendix D.</td>

   <td width="197"> </td>

  </tr>

 </tbody>

</table>




<em> </em><strong>4</strong>. Discuss another example (being different from those already covered in lecture notes) of software failures. Do some Web search and literature review. Clearly identify a source of your information (e.g., include a link to the website). Describe a nature of the software failure. Identify its origin. Were there any software testing efforts mentioned in relation to the resulting failure? Was there any follow up action taken? Was there any plan to alleviate further problems?

Be critical in your assessment – sometimes the quality of the available source of information could be questionable (which is a typical downfall of many Web resources). Use at least two different sources; they might offer various perspectives on the same problem. You may wish to organize your findings in a tabular format. Offer the most essential info; be concise.

In your writing use the following template identifying failure description, nature of software failure, testing efforts regarding failure, follow up action, and URL where the material was found.

<table width="590">

 <tbody>

  <tr>

   <td width="199">This is a sample</td>

   <td width="391"> </td>

  </tr>

  <tr>

   <td width="199">Failure description</td>

   <td width="391"><strong>Therac-25 Accidents </strong> Eleven Therac-25s, radiation therapy machines, were installed: five in the US and six in Canada. Six accidents involving massive overdoses to patients occurred between 1985 and 1987. The accidents occurred when the high-energy electron-beam was activated without the target having been rotated into place; the machine’s software did not detect that this had occurred, and did not therefore determine that the patient was receiving a potentially lethal dose of radiation, or prevent this from occurring. The very high energy electron-beam directly struck the patients causing the feeling of an intense electric shock and the occurrence of thermal and radiation burns. In some cases, the injured patients died later from radiation poisoning.</td>

  </tr>

  <tr>

   <td width="199">Nature of software failure</td>

   <td width="391">Several features of the Therac-25 are important in understanding the accidents. Some of essential causes were:</td>

  </tr>

  <tr>

   <td width="199"> </td>

   <td width="391"> (1)                The engineers had reused software from older models. These models had hardware interlocks that masked their software defects. Those hardware safety mechanisms had no way of reporting that they had been triggered, to at least indicate the existence of faulty software commands (2)                The hardware provided no way for the software to verify that sensors were working correctly (3)                The software was written in assembly language. While this was more common at the time than it is today, assembly language is harder to debug than most high-level languages. </td>

  </tr>

  <tr>

   <td width="199">Any testing efforts regarding the failure?</td>

   <td width="391">(1)                Related problems were found in the Therac-20 software. These were not recognized until after the Therac-25 accidents because the Therac-20 included hardware safety interlocks and thus no injuries resulted.(2)                After the 2<sup>nd</sup> incident the Atomic Energy of Canada Limited (AECL) sent a service technician to the Therac-25 machine. He was unable to recreate the malfunction and therefore concluded that nothing was wrong with the software. Some minor adjustments to the hardware were made.</td>

  </tr>

  <tr>

   <td width="199">Any follow up action taken? Any plan to alleviate further problems?</td>

   <td width="391">The machine was recalled in 1987 and the AECL made a variety of changes in the software of the Therac-25 radiation treatment system.The machine itself is still in use today.</td>

  </tr>

  <tr>

   <td width="199">URL</td>

   <td width="391">(1) <u>http://en.wikipedia.org/wiki/Therac-25</u> (2) The Therac-25 Accidents (PDF):<u>http://sunnyday.mit.edu/papers/therac.pdf</u>(3) An Investigation of the Therac-25 Accidents (IEEE Computer) <u>http://courses.cs.vt.edu/~cs3604/lib/Therac_25/Therac_1.html</u></td>

  </tr>

 </tbody>

</table>





