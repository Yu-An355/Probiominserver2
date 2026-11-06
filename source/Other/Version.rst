.. role:: blue

List of software and databases used in ProbioMinServer2
=======================================================

.. raw:: html

    <div style="margin: 30px 0;">

     <p style="text-align: center; font-weight: bold; font-size: 1.35rem; margin-bottom: 12px; color: #333;">
       Genome identification
     </p>

   <table class="docutils align-center" style="width: 100%; border-collapse: collapse; font-size: 1.05rem;">
     <thead>
       <tr style="background-color: #f2f2f2;">
         <th style="padding: 10px; border: 1px solid #ddd; width: 25%; font-size: 1.2rem;">Function</th>
         <th style="padding: 10px; border: 1px solid #ddd; width: 25%; font-size: 1.2rem;">Software</th>
         <th style="padding: 10px; border: 1px solid #ddd; width: 50%; font-size: 1.2rem;">Database</th>
       </tr>
     </thead>
     <tbody>
       <tr>
       <tr>
         <td rowspan="1" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Type strains comparison
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">Mash v2.3</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">NCBI prokaryote type strains (Aug. 2023 release)</td>
       </tr>
       <tr>
         <td rowspan="1" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Average nucleotide identity (ANI)
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">https://github.com/chjp/ANI</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">-</td>
       </tr>
       <tr>
         <td rowspan="2" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Genome Circos plot
         </td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">mummer2circos v1.4.2</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">-</td>
       </tr>
       <tr>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">Circos v0.69-8</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">-</td>
       </tr>
       <tr>
         <td rowspan="1" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Genome Annotation
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">eggNOG-mapper v2.1.12</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">eggNOG v5.0.2 (Mar. 2021 release)</td>
       </tr>
     </tbody>
   </table>

.. raw:: html

    <div style="margin: 30px 0;">

     <p style="text-align: center; font-weight: bold; font-size: 1.35rem; margin-bottom: 12px; color: #333;">
       Safety analysis
     </p>

   <table class="docutils align-center" style="width: 100%; border-collapse: collapse; font-size: 0.65rem;">
     <thead>
       <tr style="background-color: #f2f2f2;">
         <th style="padding: 10px; border: 1px solid #ddd; width: 25%; font-size: 1.2rem;">Function</th>
         <th style="padding: 10px; border: 1px solid #ddd; width: 25%; font-size: 1.2rem;">Software</th>
         <th style="padding: 10px; border: 1px solid #ddd; width: 50%; font-size: 1.2rem;">Database</th>
       </tr>
     </thead>
     <tbody>
       <tr>
         <!-- 第一欄佔 3 行 -->
         <td rowspan="3" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Antibiotic resistance genes (ARGs)
         </td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">RGI v6.0.3 (BLAST homolog detection)</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">CARD Variants v4.0.2 (Nov. 2023 release)</td>
       </tr>
       <tr>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">ResFinder v4.6.0</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">resfinder_db (Aug. 2024 release)</td>
       </tr>
       <tr>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">AMRFinderPlus v4.0.3</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">(Oct. 2024 release)</td>
       </tr>
       <tr>
         <td rowspan="2" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Virulence factors (VFs)
         </td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">BLASTN v2.16.0</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">VFDB (Dec. 2024 release)</td>
       </tr>
       <tr>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">VirulenceFinder v2.0.4</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">virulencefinder_db (Feb. 2024 release)</td>
       </tr>
       <tr>
         <td rowspan="1" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Pathogenic genes (PGs)
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">BLASTX v2.16.0</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">PHI-base v4.16 (May. 2024 release)</td>
       </tr>
       <tr>
         <td rowspan="2" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Plasmid genes
         </td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">PlasmidFinder v2.1.6</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">plasmidfinder_db v2.2.0 (Nov. 2024 release)</td>
       </tr>
       <tr>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">PlasmidHunter v1.4.5</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem; ">(May. 2024 release)</td>
       </tr>
       <tr>
         <td rowspan="1" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Prophage regions
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">Phigaro v2.4.0</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">(Jan. 2024 release)</td>
       </tr>
       <tr>
         <td rowspan="1" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Insertion Sequence
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">ISEScan v1.7.2.3</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">(Apr. 2021 release)</td>
       </tr>
     </tbody>
   </table>

.. raw:: html

    <div style="margin: 30px 0;">

     <p style="text-align: center; font-weight: bold; font-size: 1.35rem; margin-bottom: 12px; color: #333;">
       Functional analysis
     </p>

   <table class="docutils align-center" style="width: 100%; border-collapse: collapse; font-size: 0.65rem;">
     <thead>
       <tr style="background-color: #f2f2f2;">
         <th style="padding: 10px; border: 1px solid #ddd; width: 25%; font-size: 1.2rem;">Function</th>
         <th style="padding: 10px; border: 1px solid #ddd; width: 25%; font-size: 1.2rem;">Software</th>
         <th style="padding: 10px; border: 1px solid #ddd; width: 50%; font-size: 1.2rem;">Database</th>
       </tr>
     </thead>
     <tbody>
       <tr>
       <tr>
         <td rowspan="1" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Secondary metabolite gene clusters
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">antiSMASH v7.1.0</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">(Nov. 2023 release)</td>
       </tr>
       <tr>
         <td rowspan="1" style="padding: 10px; border: 1px solid #ddd; font-weight: bold; vertical-align: middle; text-align: center; font-size: 1.0rem;">
           Primary metabolite gene clusters
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">gutSMASH v1.0.0</td>
         <td style="padding: 10px; border: 1px solid #ddd; font-size: 1.0rem;">(Oct. 2020 release)</td>
       </tr>
     </tbody>
   </table>