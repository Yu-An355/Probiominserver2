.. role:: blue

Safety analysis
===============

.. raw:: html

   <table style="width: 100%; border: none; border-collapse: collapse; background: transparent; margin: 20px 0;">
     <tr>
       <!-- 左側圖片欄位 -->
       <td style="width: 50%; padding: 15px; vertical-align: top; background: transparent; text-align: center;">
         <img src="../_static/3-2-2.png" alt="Left Image" style="width: 100%; border: 1px solid #d0d7de; padding: 6px; background: #fff; border-radius: 4px; box-shadow: 0 3px 8px rgba(0,0,0,0.05);">
         <p style="text-align: center; font-size: 0.95rem; color: #333; margin-top: 10px; margin-bottom: 0;">Examples of ARGs results</p>
       </td>
       
       <!-- 右側圖片欄位 -->
       <td style="width: 50%; padding: 15px; vertical-align: top; background: transparent; text-align: center;">
         <img src="../_static/3-2-5.png" alt="Right Image" style="width: 100%; border: 1px solid #d0d7de; padding: 6px; background: #fff; border-radius: 4px; box-shadow: 0 3px 8px rgba(0,0,0,0.05);">
         <p style="text-align: center; font-size: 0.95rem; color: #333; margin-top: 10px; margin-bottom: 0;">Examples of Plasmid results</p>
       </td>
     </tr>
   </table>

.. raw:: html

   <div style="margin-bottom: 15px;">
     <p style="font-size: 1.15rem; font-weight: bold; color: #222; margin-bottom: 15px;">
       Safety analysis includes the following components :
     </p>

     <div style="margin-left: 20px; line-height: 1.7;">
       <p style="margin-bottom: 10px;">
         <strong>PPRS (Potential Pathogenicity Risk Score)</strong><br>
         <p style="margin-bottom: 10px; margin-left: 20px;">
           Comprehensively evaluates genomic pathogenicity, antimicrobial resistance, and virulence features to calculate potential pathogenicity and biosafety risk-level indicators for the strain.
         </p>
       </p>

       <p style="margin-bottom: 10px;">
         <strong>ARGs (Antimicrobial Resistance Genes)</strong><br>
         <p style="margin-bottom: 10px; margin-left: 20px;">
           Identifies genomic antimicrobial resistance genes and alignment results, utilizing three benchmark databases: CARD, ResFinder, and AMRFinderPlus.
         </p>
       </p>

       <p style="margin-bottom: 10px;">
         <strong>VFs (Virulence Factors)</strong><br>
         <p style="margin-bottom: 10px; margin-left: 20px;">
           Identifies strain virulence-associated genes and alignment results using the Virulence Factor Database (VFDB) and VirulenceFinder.
         </p>
       </p>

       <p style="margin-bottom: 10px;">
         <strong>PGs (Pathogenicity Genes)</strong><br>
         <p style="margin-bottom: 10px; margin-left: 20px;">
           Identifies key pathogenicity genes directly associated with specific disease occurrences based on PHI-base analysis.
         </p>
       </p>

       <p style="margin-bottom: 10px;">
         <strong>Plasmid</strong><br>
         <p style="margin-bottom: 10px; margin-left: 20px;">
           Identifies genomic plasmid sequences utilizing PlasmidFinder and PlasmidHunter.
         </p>
       </p>

       <p style="margin-bottom: 10px;">
         <strong>Prophage</strong><br>
         <p style="margin-bottom: 10px; margin-left: 20px;">
           Predicts prophage regions integrated into the genome using Phigaro.
         </p>
       </p>

       <p style="margin-bottom: 0;">
         <strong>IS Elements (Insertion Sequences)</strong><br>
         <p style="margin-bottom: 10px; margin-left: 20px;">
           Locates insertion sequences within the genome using ISEScan.
         </p>
       </p>
     </div>
   </div>