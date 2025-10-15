<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Grade 12 Biology</title>
  <style>
    :root{font-family:system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;line-height:1.4}
    body{max-width:900px;margin:28px auto;padding:18px;color:#111}
    h1{font-size:1.6rem;margin-bottom:4px}
    .card{border:1px solid #e3e3e3;border-radius:10px;padding:14px;margin-bottom:14px;box-shadow:0 2px 6px rgba(0,0,0,0.03)}
    label{display:block;margin:8px 0}
    .question{margin:12px 0;padding:10px;border-radius:8px}
    .options{margin-top:6px}
    .btn{display:inline-block;padding:10px 14px;border-radius:8px;border:0;cursor:pointer}
    .btn-primary{background:#2563eb;color:#fff}
    .btn-ghost{background:transparent;border:1px solid #999}
    .result{font-weight:700;margin-top:12px}
    .correct{background:#e6ffed;border:1px solid #2ecc71}
    .incorrect{background:#fff1f0;border:1px solid #ff6b6b}
    .answer-key{font-size:0.95rem;margin-top:12px}
    .meta{display:flex;gap:12px;align-items:center;flex-wrap:wrap}
    .small{font-size:0.9rem;color:#444}
    .grade-badge{display:inline-block;padding:6px 10px;border-radius:999px;background:#f3f4f6}
    @media (max-width:560px){body{padding:12px}}
  </style>
</head>
<body>
  <h1>Wisdom Spring Education, Chaung U</h1>
  <h2>Grade 12 Biology October Test</h2>
  <div class="card">
    <div style="display:flex;gap:12px;align-items:center;flex-wrap:wrap">
      <label style="flex:1">
        Roll Number:
        <input id="roll" name="roll" type="text" placeholder="Enter roll number" style="width:100%;padding:8px;margin-top:6px;border-radius:6px;border:1px solid #ccc" required>
      </label>
      <div class="small">Total Marks: <strong>50</strong></div>
    </div>
  </div>

  <form id="mcqForm" class="card" onsubmit="return false;">
    <div class="small">Instructions: Each question carries 1 mark. No negative marking. Choose one option (A/B/C/D).</div>

    <div id="questionsContainer">
      <!-- Q1 -->
      <div class="question" data-qid="1">
        <div><strong>Q1.</strong> Cells which contain membrane-enclosed organelles are ......</div>
        <div class="options">
          <label><input type="radio" name="q1" value="A"> A) Prokaryotes</label>
          <label><input type="radio" name="q1" value="B"> B) Archaebacteria</label>
          <label><input type="radio" name="q1" value="C"> C) Eubacteria</label>
          <label><input type="radio" name="q1" value="D"> D) Eukaryotes</label>
        </div>
      </div>

      <!-- Q2 -->
      <div class="question" data-qid="2">
        <div><strong>Q2.</strong> The genetic information is encoded in the nucleotide sequences of ....</div>
        <div class="options">
          <label><input type="radio" name="q2" value="A"> A) DNA</label>
          <label><input type="radio" name="q2" value="B"> B) RNA</label>
          <label><input type="radio" name="q2" value="C"> C) mRNA</label>
          <label><input type="radio" name="q2" value="D"> D) tRNA</label>
        </div>
      </div>

      <!-- Q3 -->
      <div class="question" data-qid="3">
        <div><strong>Q3.</strong> Main source of energy comes from the .....</div>
        <div class="options">
          <label><input type="radio" name="q3" value="A"> A) Producers</label>
          <label><input type="radio" name="q3" value="B"> B) Consumers</label>
          <label><input type="radio" name="q3" value="C"> C) Decomposers</label>
          <label><input type="radio" name="q3" value="D"> D) Sun</label>
        </div>
      </div>

      <!-- Q4 -->
      <div class="question" data-qid="4">
        <div><strong>Q4.</strong> In negative feedback, accumulation of the product .... its production.</div>
        <div class="options">
          <label><input type="radio" name="q4" value="A"> A) speeds up</label>
          <label><input type="radio" name="q4" value="B"> B) slows</label>
          <label><input type="radio" name="q4" value="C"> C) equals to</label>
          <label><input type="radio" name="q4" value="D"> D) does not affect</label>
        </div>
      </div>

      <!-- Q5 -->
      <div class="question" data-qid="5">
        <div><strong>Q5.</strong> Which one is not included in domain Eukarya?</div>
        <div class="options">
          <label><input type="radio" name="q5" value="A"> A) Bacteria</label>
          <label><input type="radio" name="q5" value="B"> B) Protists</label>
          <label><input type="radio" name="q5" value="C"> C) Fungi</label>
          <label><input type="radio" name="q5" value="D"> D) Plants</label>
        </div>
      </div>
	  
	  <!-- Q6 -->
      <div class="question" data-qid="6">
        <div><strong>Q6.</strong> Evolutionary process that occurs when a population is exposed to environmental factors that consistently cause individuals with certain heritable traits to have greater reproductive success than do individuals with other heritable traits can be defined as .....</div>
        <div class="options">
          <label><input type="radio" name="q6" value="A"> A) Artificial selection</label>
          <label><input type="radio" name="q6" value="B"> B) Natural selection</label>
          <label><input type="radio" name="q6" value="C"> C) Biotechnology</label>
          <label><input type="radio" name="q6" value="D"> D) Genetically modified organism</label>
        </div>
      </div>

      <!-- Q7 -->
      <div class="question" data-qid="7">
        <div><strong>Q7.</strong> Which is not listed in agricultural crops?</div>
        <div class="options">
          <label><input type="radio" name="q7" value="A"> A) food</label>
          <label><input type="radio" name="q7" value="B"> B) clothing</label>
          <label><input type="radio" name="q7" value="C"> C) animal feeds</label>
          <label><input type="radio" name="q7" value="D"> D) animal breeding</label>
        </div>
      </div>

      <!-- Q8 -->
      <div class="question" data-qid="8">
        <div><strong>Q8.</strong> Botanical name of wheat is .....</div>
        <div class="options">
          <label><input type="radio" name="q8" value="A"> A) Oryza sativa</label>
          <label><input type="radio" name="q8" value="B"> B) Triticum aestivum</label>
          <label><input type="radio" name="q8" value="C"> C) Zea mays</label>
          <label><input type="radio" name="q8" value="D"> D) Vigna mungo</label>
        </div>
      </div>

      <!-- Q9 -->
      <div class="question" data-qid="9">
        <div><strong>Q9.</strong> The applied science of cultivating and growing plants used for both consumption and aesthetic or ornamental purposes is defined as .....</div>
        <div class="options">
          <label><input type="radio" name="q9" value="A"> A) Hydroponic culture </label>
          <label><input type="radio" name="q9" value="B"> B) Aquaculture </label>
          <label><input type="radio" name="q9" value="C"> C) Livestock</label>
          <label><input type="radio" name="q9" value="D"> D) Horticulture</label>
        </div>
      </div>

      <!-- Q10 -->
      <div class="question" data-qid="10">
        <div><strong>Q10.</strong>  The vegetable growing, dealing with the culture of non-woody (herbaceous) plants for foods is defined as ....</div>
        <div class="options">
          <label><input type="radio" name="q10" value="A"> A) Pomology</label>
          <label><input type="radio" name="q10" value="B"> B) Fruticulture </label>
          <label><input type="radio" name="q10" value="C"> C) Olericulture</label>
          <label><input type="radio" name="q10" value="D"> D) Ornamental horticulture</label>
        </div>
      </div>
	  
	  <!-- Q11 -->
      <div class="question" data-qid="11">
        <div><strong>Q11.</strong> The growing and marketing of flowers and ornamental plants for floristry is defined as ....</div>
        <div class="options">
          <label><input type="radio" name="q11" value="A"> A) Floriculture</label>
          <label><input type="radio" name="q11" value="B"> B) Arboriculture</label>
          <label><input type="radio" name="q11" value="C"> C) Turf management</label>
          <label><input type="radio" name="q11" value="D"> D) Landscape horticulture</label>
        </div>
      </div>

      <!-- Q12 -->
      <div class="question" data-qid="12">
        <div><strong>Q12.</strong>  A method of growing plants without soil is called.....</div>
        <div class="options">
          <label><input type="radio" name="q12" value="A"> A) Pisciculture</label>
          <label><input type="radio" name="q12" value="B"> B) Hydroponic culture</label>
          <label><input type="radio" name="q12" value="C"> C) Mariculture</label>
          <label><input type="radio" name="q12" value="D"> D) Algaculture</label>
        </div>
      </div>

      <!-- Q13 -->
      <div class="question" data-qid="13">
        <div><strong>Q13.</strong> The cultivation of marine organisms for food and other animal products in enclosed sections of the open ocean is ....</div>
        <div class="options">
          <label><input type="radio" name="q13" value="A"> A) offshore mariculture</label>
          <label><input type="radio" name="q13" value="B"> B) inshore mariculture</label>
          <label><input type="radio" name="q13" value="C"> C) onshore mariculture</label>
          <label><input type="radio" name="q13" value="D"> D) outshore mariculture</label>
        </div>
      </div>

      <!-- Q14 -->
      <div class="question" data-qid="14">
        <div><strong>Q14.</strong> A system of producing fish in combination with other agricultural or livestock farming operations centered on the fish pond is called ....</div>
        <div class="options">
          <label><input type="radio" name="q14" value="A"> A) Integrated fish farming</label>
          <label><input type="radio" name="q14" value="B"> B) Algaculture</label>
          <label><input type="radio" name="q14" value="C"> C) Oyster farming</label>
          <label><input type="radio" name="q14" value="D"> D) Shrimp farming</label>
        </div>
      </div>

      <!-- Q15 -->
      <div class="question" data-qid="15">
        <div><strong>Q15.</strong> Which animal is not a common livestock one?</div>
        <div class="options">
          <label><input type="radio" name="q15" value="A"> A) cattle</label>
          <label><input type="radio" name="q15" value="B"> B) sheep</label>
          <label><input type="radio" name="q15" value="C"> C) goat</label>
          <label><input type="radio" name="q15" value="D"> D) lion</label>
        </div>
      </div>
	  
	  <!-- Q16 -->
      <div class="question" data-qid="16">
        <div><strong>Q16.</strong> Body-building food is ...</div>
        <div class="options">
          <label><input type="radio" name="q16" value="A"> A) carbohydrate</label>
          <label><input type="radio" name="q16" value="B"> B) protein</label>
          <label><input type="radio" name="q16" value="C"> C) vitamin</label>
          <label><input type="radio" name="q16" value="D"> D) confessionary food</label>
        </div>
      </div>

      <!-- Q17 -->
      <div class="question" data-qid="17">
        <div><strong>Q17.</strong> The chief ingredient of aspirin, salicylic acid, was originally obtained from the bark of .... </div>
        <div class="options">
          <label><input type="radio" name="q17" value="A"> A) willow tree</label>
          <label><input type="radio" name="q17" value="B"> B) cinchona tree</label>
          <label><input type="radio" name="q17" value="C"> C) foxglove plant</label>
          <label><input type="radio" name="q17" value="D"> D) Periwinkle</label>
        </div>
      </div>

      <!-- Q18 -->
      <div class="question" data-qid="18">
        <div><strong>Q18.</strong> Leeches secrete ..... which help to keep the blood flowing</div>
        <div class="options">
          <label><input type="radio" name="q18" value="A"> A) Angiotensis-Converting Enzymes</label>
          <label><input type="radio" name="q18" value="B"> B) artificial ligaments and tendons</label>
          <label><input type="radio" name="q18" value="C"> C) calcitonin hormones</label>
          <label><input type="radio" name="q18" value="D"> D) anti-coagulants</label>
        </div>
      </div>

      <!-- Q19 -->
      <div class="question" data-qid="19">
        <div><strong>Q19.</strong> A protein in the blood called Limulus Amebocyte Lysate (LAL) which reacts to all kinds of microorganisms is produced from .... </div>
        <div class="options">
          <label><input type="radio" name="q19" value="A"> A) Salmon</label>
          <label><input type="radio" name="q19" value="B"> B) Snake viper</label>
          <label><input type="radio" name="q19" value="C"> C) Horseshoe crab</label>
          <label><input type="radio" name="q19" value="D"> D) Maggot</label>
        </div>
      </div>

      <!-- Q20 -->
      <div class="question" data-qid="20">
        <div><strong>Q20.</strong> Botanical term of cotton is .....</div>
        <div class="options">
          <label><input type="radio" name="q20" value="A"> A) Corchorus spp.</label>
          <label><input type="radio" name="q20" value="B"> B) Bombyx mori</label>
          <label><input type="radio" name="q20" value="C"> C) Gossypium spp.</label>
          <label><input type="radio" name="q20" value="D"> D) Xylia dolabriformis</label>
        </div>
      </div>
	  
	  <!-- Q21 -->
      <div class="question" data-qid="21">
        <div><strong>Q21.</strong> Queen of Textiles is ....</div>
        <div class="options">
          <label><input type="radio" name="q21" value="A"> A) Silk</label>
          <label><input type="radio" name="q21" value="B"> B) Cotton</label>
          <label><input type="radio" name="q21" value="C"> C) Jute</label>
          <label><input type="radio" name="q21" value="D"> D) Bamboo</label>
        </div>
      </div>

      <!-- Q22 -->
      <div class="question" data-qid="22">
        <div><strong>Q22.</strong> Life cycle of silk worm is .....</div>
        <div class="options">
          <label><input type="radio" name="q22" value="A"> A) egg, caterpillar (larva), pupa and adult moth</label>
          <label><input type="radio" name="q22" value="B"> B) caterpillar (larva), egg, pupa and adult moth</label>
          <label><input type="radio" name="q22" value="C"> C) pupa and adult moth, egg, caterpillar (larva) </label>
          <label><input type="radio" name="q22" value="D"> D) caterpillar (larva), egg, pupa and adult moth</label>
        </div>
      </div>

      <!-- Q23 -->
      <div class="question" data-qid="23">
        <div><strong>Q23.</strong> Difference between cotton and wool is ....</div>
        <div class="options">
          <label><input type="radio" name="q23" value="A"> A) cotton has more protein with lipid</label>
          <label><input type="radio" name="q23" value="B"> B) wool has more protein with lipid</label>
          <label><input type="radio" name="q23" value="C"> C) wool has cellulose</label>
          <label><input type="radio" name="q23" value="D"> D) cotton has no cellulose</label>
        </div>
      </div>

      <!-- Q24 -->
      <div class="question" data-qid="24">
        <div><strong>Q24.</strong> Biological term of Teak is ......</div>
        <div class="options">
          <label><input type="radio" name="q24" value="A"> A) Tectona grandis</label>
          <label><input type="radio" name="q24" value="B"> B) Xylia dolabriformis</label>
          <label><input type="radio" name="q24" value="C"> C) Bombyx mori</label>
          <label><input type="radio" name="q24" value="D"> D) Gossypium spp.</label>
        </div>
      </div>

      <!-- Q25 -->
      <div class="question" data-qid="25">
        <div><strong>Q25.</strong> Changing into adult form from pupa inside the cocoon is called --------</div>
        <div class="options">
          <label><input type="radio" name="q25" value="A"> A) evolution</label>
          <label><input type="radio" name="q25" value="B"> B) biodiversity</label>
          <label><input type="radio" name="q25" value="C"> C) metamorphosis</label>
          <label><input type="radio" name="q25" value="D"> D) reproduction</label>
        </div>
      </div>
	  
	  <!-- Q26 -->
      <div class="question" data-qid="26">
        <div><strong>Q26.</strong> The central dogma of molecular biology stated that genetic information flows from .....</div>
        <div class="options">
          <label><input type="radio" name="q26" value="A"> A) RNA--> DNA-->Protein</label>
          <label><input type="radio" name="q26" value="B"> B) DNA-->Protein-->RNA</label>
          <label><input type="radio" name="q26" value="C"> C) Protein-->DNA-->RNA</label>
          <label><input type="radio" name="q26" value="D"> D) DNA-->RNA-->Protein</label>
        </div>
      </div>

      <!-- Q27 -->
      <div class="question" data-qid="27">
        <div><strong>Q27.</strong> The main information-carrying molecules of the cell are .....</div>
        <div class="options">
          <label><input type="radio" name="q27" value="A"> A) nucleic acids</label>
          <label><input type="radio" name="q27" value="B"> B) fatty acids</label>
          <label><input type="radio" name="q27" value="C"> C) amino acids</label>
          <label><input type="radio" name="q27" value="D"> D) carboxylic acids</label>
        </div>
      </div>

      <!-- Q28 -->
      <div class="question" data-qid="28">
        <div><strong>Q28.</strong> Deoxyribose sugar has ......carbon atoms.</div>
        <div class="options">
          <label><input type="radio" name="q28" value="A"> A) 4</label>
          <label><input type="radio" name="q28" value="B"> B) 5</label>
          <label><input type="radio" name="q28" value="C"> C) 6</label>
          <label><input type="radio" name="q28" value="D"> D) 7</label>
        </div>
      </div>

      <!-- Q29 -->
      <div class="question" data-qid="29">
        <div><strong>Q29.</strong> Purine bases are .... and ....ring/rings.</div>
        <div class="options">
          <label><input type="radio" name="q29" value="A"> A) Adenine, Guanine and one</label>
          <label><input type="radio" name="q29" value="B"> B) Adenine, Guanine and two</label>
          <label><input type="radio" name="q29" value="C"> C) Cytosine, Thymine and one</label>
          <label><input type="radio" name="q29" value="D"> D) Cytosine, Thymine and two</label>
        </div>
      </div>

      <!-- Q30 -->
      <div class="question" data-qid="30">
        <div><strong>Q30.</strong> Complementary base pairing means .....</div>
        <div class="options">
          <label><input type="radio" name="q30" value="A"> A) A=T, C=G</label>
          <label><input type="radio" name="q30" value="B"> B) A=G, C=T</label>
          <label><input type="radio" name="q30" value="C"> C) A=C, G=T</label>
          <label><input type="radio" name="q30" value="D"> D) A=U, C=T</label>
        </div>
      </div>
	  
	  <!-- Q31 -->
      <div class="question" data-qid="31">
        <div><strong>Q31.</strong> In DNA molecule, 5' carbon is joined by ......</div>
        <div class="options">
          <label><input type="radio" name="q31" value="A"> A) nitrogenous base</label>
          <label><input type="radio" name="q31" value="B"> B) -OH group</label>
          <label><input type="radio" name="q31" value="C"> C) -P group</label>
          <label><input type="radio" name="q31" value="D"> D) H+ bond</label>
        </div>
      </div>

      <!-- Q32 -->
      <div class="question" data-qid="32">
        <div><strong>Q32.</strong> RNA is single stranded but .... can fold back on itself.</div>
        <div class="options">
          <label><input type="radio" name="q32" value="A"> A) mRNA</label>
          <label><input type="radio" name="q32" value="B"> B) tRNA</label>
          <label><input type="radio" name="q32" value="C"> C) ribosomal RNA</label>
          <label><input type="radio" name="q32" value="D"> D) mRNA and rRNA</label>
        </div>
      </div>

      <!-- Q33 -->
      <div class="question" data-qid="33">
        <div><strong>Q33.</strong> Type of RNA which acts as the template for translation is ....</div>
        <div class="options">
          <label><input type="radio" name="q33" value="A"> A) rRNA</label>
          <label><input type="radio" name="q33" value="B"> B) tRNA</label>
          <label><input type="radio" name="q33" value="C"> C) mRNA</label>
          <label><input type="radio" name="q33" value="D"> D) codon</label>
        </div>
      </div>

      <!-- Q34 -->
      <div class="question" data-qid="34">
        <div><strong>Q34.</strong> During DNA replication and protein synthesis, .... become to seperate.</div>
        <div class="options">
          <label><input type="radio" name="q34" value="A"> A) sugar-phosphate backbone</label>
          <label><input type="radio" name="q34" value="B"> B) hydrogen bonds</label>
          <label><input type="radio" name="q34" value="C"> C) phosphate bonds</label>
          <label><input type="radio" name="q34" value="D"> D) hydroxy bonds</label>
        </div>
      </div>

      <!-- Q35 -->
      <div class="question" data-qid="35">
        <div><strong>Q35.</strong> In DNA replication, replication fork is created and catalysed by .....enzyme.</div>
        <div class="options">
          <label><input type="radio" name="q35" value="A"> A) DNA polymerase</label>
          <label><input type="radio" name="q35" value="B"> B) Primer</label>
          <label><input type="radio" name="q35" value="C"> C) RNA polymerase</label>
          <label><input type="radio" name="q35" value="D"> D) Helicase</label>
        </div>
      </div>
	  
	  <!-- Q36 -->
      <div class="question" data-qid="36">
        <div><strong>Q36.</strong> In the lagging strand, DNA replication is caused by .....</div>
        <div class="options">
          <label><input type="radio" name="q36" value="A"> A) continuous manner</label>
          <label><input type="radio" name="q36" value="B"> B) 3' to 5' direction</label>
          <label><input type="radio" name="q36" value="C"> C) newly made DNA strands</label>
          <label><input type="radio" name="q36" value="D"> D) Okazaki fragments</label>
        </div>
      </div>

      <!-- Q37 -->
      <div class="question" data-qid="37">
        <div><strong>Q37.</strong> In prokaryotic replication, which is incorrect?</div>
        <div class="options">
          <label><input type="radio" name="q37" value="A"> A) Circular, double-stranded DNA</label>
          <label><input type="radio" name="q37" value="B"> B) The DNA replicates in the nucleus</label>
          <label><input type="radio" name="q37" value="C"> C) Single origin of replication</label>
          <label><input type="radio" name="q37" value="D"> D) Large Okazaki fragments</label>
        </div>
      </div>

      <!-- Q38 -->
      <div class="question" data-qid="38">
        <div><strong>Q38.</strong>  In transcription, .... is synthesized based on the DNA template of a gene.</div>
        <div class="options">
          <label><input type="radio" name="q38" value="A"> A) mRNA</label>
          <label><input type="radio" name="q38" value="B"> B) tRNA</label>
          <label><input type="radio" name="q38" value="C"> C) rRNA</label>
          <label><input type="radio" name="q38" value="D"> D) protein</label>
        </div>
      </div>

      <!-- Q39 -->
      <div class="question" data-qid="39">
        <div><strong>Q39.</strong> In the elongation phase of transcription, main enzyme to synthesize the RNA is ....</div>
        <div class="options">
          <label><input type="radio" name="q39" value="A"> A) helicase enzyme</label>
          <label><input type="radio" name="q39" value="B"> B) DNA polymerase enzyme</label>
          <label><input type="radio" name="q39" value="C"> C) RNA polymerase enzyme</label>
          <label><input type="radio" name="q39" value="D"> D) DNA ligase enzyme</label>
        </div>
      </div>

      <!-- Q40 -->
      <div class="question" data-qid="40">
        <div><strong>Q40.</strong> In RNA processing, capping is done in .... end by .....</div>
        <div class="options">
          <label><input type="radio" name="q40" value="A"> A) 5', adenylation</label>
          <label><input type="radio" name="q40" value="B"> B) 5', guanosine cap</label>
          <label><input type="radio" name="q40" value="C"> C) 3', adenylation</label>
          <label><input type="radio" name="q40" value="D"> D) 3', guanosine cap</label>
        </div>
      </div>
	  
	  <!-- Q41 -->
      <div class="question" data-qid="41">
        <div><strong>Q41.</strong> In RNA processing, splicing means removal of ....</div>
        <div class="options">
          <label><input type="radio" name="q41" value="A"> A) Introns</label>
          <label><input type="radio" name="q41" value="B"> B) Exons</label>
          <label><input type="radio" name="q41" value="C"> C) guanosine capping</label>
          <label><input type="radio" name="q41" value="D"> D) adenylation</label>
        </div>
      </div>

      <!-- Q42 -->
      <div class="question" data-qid="42">
        <div><strong>Q42.</strong> In eukaryotic transcription, RNAs are released and processed in the ...</div>
        <div class="options">
          <label><input type="radio" name="q42" value="A"> A) nucleus</label>
          <label><input type="radio" name="q42" value="B"> B) cytoplasm</label>
          <label><input type="radio" name="q42" value="C"> C) mitochondria</label>
          <label><input type="radio" name="q42" value="D"> D) ribosome</label>
        </div>
      </div>

      <!-- Q43 -->
      <div class="question" data-qid="43">
        <div><strong>Q43.</strong> Start codon, AUG, specifies the amino acid.....</div>
        <div class="options">
          <label><input type="radio" name="q43" value="A"> A) Serine</label>
          <label><input type="radio" name="q43" value="B"> B) Tyrosine</label>
          <label><input type="radio" name="q43" value="C"> C) Methionine</label>
          <label><input type="radio" name="q43" value="D"> D) Leucine</label>
        </div>
      </div>

      <!-- Q44 -->
      <div class="question" data-qid="44">
        <div><strong>Q44.</strong> Which one is NOT stop codon?</div>
        <div class="options">
          <label><input type="radio" name="q44" value="A"> A) UAA</label>
          <label><input type="radio" name="q44" value="B"> B) UAG</label>
          <label><input type="radio" name="q44" value="C"> C) UGA</label>
          <label><input type="radio" name="q44" value="D"> D) UCA</label>
        </div>
      </div>

      <!-- Q45 -->
      <div class="question" data-qid="45">
        <div><strong>Q45.</strong> Choose the vector which cannot be used in recombinant DNA technology.</div>
        <div class="options">
          <label><input type="radio" name="q45" value="A"> A) plasmid of bacteria</label>
          <label><input type="radio" name="q45" value="B"> B) influenza virus</label>
          <label><input type="radio" name="q45" value="C"> C) liposome</label>
          <label><input type="radio" name="q45" value="D"> D) gene gun</label>
        </div>
      </div>
	  
	  <!-- Q46 -->
      <div class="question" data-qid="46">
        <div><strong>Q46.</strong> Production of golden rice is aimed to prevent ..... deficiency.</div>
        <div class="options">
          <label><input type="radio" name="q46" value="A"> A) vitamin A</label>
          <label><input type="radio" name="q46" value="B"> B) vitamin B</label>
          <label><input type="radio" name="q46" value="C"> C) vitamin C</label>
          <label><input type="radio" name="q46" value="D"> D) vitamin D</label>
        </div>
      </div>

      <!-- Q47 -->
      <div class="question" data-qid="47">
        <div><strong>Q47.</strong> In production of golden rice, beta-carotine gene comes from .....</div>
        <div class="options">
          <label><input type="radio" name="q47" value="A"> A) daffodils plant</label>
          <label><input type="radio" name="q47" value="B"> B) Agrobacterium</label>
          <label><input type="radio" name="q47" value="C"> C) Corona virus</label>
          <label><input type="radio" name="q47" value="D"> D) Amoeba</label>
        </div>
      </div>

      <!-- Q48 -->
      <div class="question" data-qid="48">
        <div><strong>Q48.</strong> A triple code of nucleotides could produce ..... possible combinations. </div>
        <div class="options">
          <label><input type="radio" name="q48" value="A"> A) 8</label>
          <label><input type="radio" name="q48" value="B"> B) 16</label>
          <label><input type="radio" name="q48" value="C"> C) 64</label>
          <label><input type="radio" name="q48" value="D"> D) 32</label>
        </div>
      </div>

      <!-- Q49 -->
      <div class="question" data-qid="49">
        <div><strong>Q49.</strong> DNA replication is .....</div>
        <div class="options">
          <label><input type="radio" name="q49" value="A"> A) Copying the sequence of DNA to mRNA</label>
          <label><input type="radio" name="q49" value="B"> B) Always pairs with thymine</label>
          <label><input type="radio" name="q49" value="C"> C) A combination of three nucleotides </label>
          <label><input type="radio" name="q49" value="D"> D) Semi-conservative method</label>
        </div>
      </div>

      <!-- Q50 -->
      <div class="question" data-qid="50">
        <div><strong>Q50.</strong> Choose the correct one.</div>
        <div class="options">
          <label><input type="radio" name="q50" value="A"> A) By convention, the sequence of a DNA strand is always written in the 3' to 5' direction.</label>
          <label><input type="radio" name="q50" value="B"> B) DNA polymerase alpha is the main enzyme responsible for replication in prokaryotes.</label>
          <label><input type="radio" name="q50" value="C"> C) The second stage of protein synthesis involves translation which occurs in the nucleus.</label>
          <label><input type="radio" name="q50" value="D"> D) The disease-free gene was introduced into an individual’s genome to treat the genetic disorders.</label>
        </div>
      </div>

    </div>

    <div style="margin-top:12px">
      <button onclick="submitQuiz()">Submit</button>

    <div class="result" id="result"></div>
    </div>

    <div id="output" class="result"></div>

    <script>
    function submitQuiz() {
      const q1Answer = document.querySelector('input[name="q1"]:checked');
      const q2Answer = document.querySelector('input[name="q2"]:checked');
	  const q3Answer = document.querySelector('input[name="q3"]:checked');
	  const q4Answer = document.querySelector('input[name="q4"]:checked');
	  const q5Answer = document.querySelector('input[name="q5"]:checked');
	  const q6Answer = document.querySelector('input[name="q6"]:checked');
      const q7Answer = document.querySelector('input[name="q7"]:checked');
	  const q8Answer = document.querySelector('input[name="q8"]:checked');
	  const q9Answer = document.querySelector('input[name="q9"]:checked');
	  const q10Answer = document.querySelector('input[name="q10"]:checked');
	  const q11Answer = document.querySelector('input[name="q11"]:checked');
      const q12Answer = document.querySelector('input[name="q12"]:checked');
	  const q13Answer = document.querySelector('input[name="q13"]:checked');
	  const q14Answer = document.querySelector('input[name="q14"]:checked');
	  const q15Answer = document.querySelector('input[name="q15"]:checked');
	  const q16Answer = document.querySelector('input[name="q16"]:checked');
      const q17Answer = document.querySelector('input[name="q17"]:checked');
	  const q18Answer = document.querySelector('input[name="q18"]:checked');
	  const q19Answer = document.querySelector('input[name="q19"]:checked');
	  const q20Answer = document.querySelector('input[name="q20"]:checked');
	  const q21Answer = document.querySelector('input[name="q21"]:checked');
      const q22Answer = document.querySelector('input[name="q22"]:checked');
	  const q23Answer = document.querySelector('input[name="q23"]:checked');
	  const q24Answer = document.querySelector('input[name="q24"]:checked');
	  const q25Answer = document.querySelector('input[name="q25"]:checked');
	  const q26Answer = document.querySelector('input[name="q26"]:checked');
      const q27Answer = document.querySelector('input[name="q27"]:checked');
	  const q28Answer = document.querySelector('input[name="q28"]:checked');
	  const q29Answer = document.querySelector('input[name="q29"]:checked');
	  const q30Answer = document.querySelector('input[name="q30"]:checked');
	  const q31Answer = document.querySelector('input[name="q31"]:checked');
      const q32Answer = document.querySelector('input[name="q32"]:checked');
	  const q33Answer = document.querySelector('input[name="q33"]:checked');
	  const q34Answer = document.querySelector('input[name="q34"]:checked');
	  const q35Answer = document.querySelector('input[name="q35"]:checked');
	  const q36Answer = document.querySelector('input[name="q36"]:checked');
      const q37Answer = document.querySelector('input[name="q37"]:checked');
	  const q38Answer = document.querySelector('input[name="q38"]:checked');
	  const q39Answer = document.querySelector('input[name="q39"]:checked');
	  const q40Answer = document.querySelector('input[name="q40"]:checked');
	  const q41Answer = document.querySelector('input[name="q41"]:checked');
      const q42Answer = document.querySelector('input[name="q42"]:checked');
	  const q43Answer = document.querySelector('input[name="q43"]:checked');
	  const q44Answer = document.querySelector('input[name="q44"]:checked');
	  const q45Answer = document.querySelector('input[name="q45"]:checked');
	  const q46Answer = document.querySelector('input[name="q46"]:checked');
      const q47Answer = document.querySelector('input[name="q47"]:checked');
	  const q48Answer = document.querySelector('input[name="q48"]:checked');
	  const q49Answer = document.querySelector('input[name="q49"]:checked');
	  const q50Answer = document.querySelector('input[name="q50"]:checked');
	  
      let score = 0;

      if (q1Answer && q1Answer.value === 'D') score++;
      if (q2Answer && q2Answer.value === 'A') score++;
	  if (q3Answer && q3Answer.value === 'D') score++;
	  if (q4Answer && q4Answer.value === 'B') score++;
	  if (q5Answer && q5Answer.value === 'A') score++;
	  if (q6Answer && q6Answer.value === 'B') score++;
      if (q7Answer && q7Answer.value === 'D') score++;
	  if (q8Answer && q8Answer.value === 'B') score++;
	  if (q9Answer && q9Answer.value === 'D') score++;
	  if (q10Answer && q10Answer.value === 'C') score++;
	  if (q11Answer && q11Answer.value === 'A') score++;
      if (q12Answer && q12Answer.value === 'B') score++;
	  if (q13Answer && q13Answer.value === 'A') score++;
	  if (q14Answer && q14Answer.value === 'A') score++;
	  if (q15Answer && q15Answer.value === 'D') score++;
	  if (q16Answer && q16Answer.value === 'B') score++;
      if (q17Answer && q17Answer.value === 'A') score++;
	  if (q18Answer && q18Answer.value === 'D') score++;
	  if (q19Answer && q19Answer.value === 'C') score++;
	  if (q20Answer && q20Answer.value === 'C') score++;
	  if (q21Answer && q21Answer.value === 'A') score++;
      if (q22Answer && q22Answer.value === 'A') score++;
	  if (q23Answer && q23Answer.value === 'B') score++;
	  if (q24Answer && q24Answer.value === 'A') score++;
	  if (q25Answer && q25Answer.value === 'C') score++;
	  if (q26Answer && q26Answer.value === 'D') score++;
      if (q27Answer && q27Answer.value === 'A') score++;
	  if (q28Answer && q28Answer.value === 'B') score++;
	  if (q29Answer && q29Answer.value === 'B') score++;
	  if (q30Answer && q30Answer.value === 'A') score++;
	  if (q31Answer && q31Answer.value === 'C') score++;
      if (q32Answer && q32Answer.value === 'B') score++;
	  if (q33Answer && q33Answer.value === 'C') score++;
	  if (q34Answer && q34Answer.value === 'B') score++;
	  if (q35Answer && q35Answer.value === 'D') score++;
	  if (q36Answer && q36Answer.value === 'D') score++;
      if (q37Answer && q37Answer.value === 'B') score++;
	  if (q38Answer && q38Answer.value === 'A') score++;
	  if (q39Answer && q39Answer.value === 'C') score++;
	  if (q40Answer && q40Answer.value === 'B') score++;
	  if (q41Answer && q41Answer.value === 'A') score++;
      if (q42Answer && q42Answer.value === 'A') score++;
	  if (q43Answer && q43Answer.value === 'C') score++;
	  if (q44Answer && q44Answer.value === 'D') score++;
	  if (q45Answer && q45Answer.value === 'B') score++;
	  if (q46Answer && q46Answer.value === 'A') score++;
      if (q47Answer && q47Answer.value === 'A') score++;
	  if (q48Answer && q48Answer.value === 'C') score++;
	  if (q49Answer && q49Answer.value === 'D') score++;
	  if (q50Answer && q50Answer.value === 'D') score++;



      const resultDiv = document.getElementById('result');
      resultDiv.textContent = `You scored ${score} out of 50`;
    }
    </script>
</body>
</html>
