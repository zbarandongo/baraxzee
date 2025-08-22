
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dr. Zoe R Barandongo – Bioinformatics</title>
<style>
body { font-family: Arial,sans-serif; margin:0; padding:0; background:#f7f7f7; color:#333; }
header, footer { background:#1e3a8a; color:white; padding:1rem; text-align:center; }
nav a { color:white; margin:0 1rem; text-decoration:none; cursor:pointer; }
nav a:hover { text-decoration:underline; }
main { max-width:900px; margin:2rem auto; padding:0 1rem; }
section { display:none; } /* hide all by default */
section.active { display:block; } /* show only active section */
h2 { color:#1e3a8a; margin-top:2rem; }
img.profile { max-width:200px; border-radius:50%; display:block; margin:auto; }
ul { margin-top:0.5rem; }
li { margin-bottom:0.3rem; }
</style>
</head>
<body>

<header>
<h1>Dr. Zoe R Barandongo</h1>
<nav>
<a onclick="showSection('about')">About Me</a>
<a onclick="showSection('skills')">Skills</a>
<a onclick="showSection('services')">Services & Goals</a>
<a onclick="showSection('projects')">Projects</a>
<a onclick="showSection('publications')">Publications</a>
<a onclick="showSection('contact')">Contact</a>
</nav>
</header>

<main>
  <!-- About Me -->
  <section id="about" class="active">
    <h2>About Me</h2>
    <div style="display:flex; align-items:flex-start; gap:20px;">
      <img src="images/image1.jpg" alt="Dr. Zoe R Barandongo" style="width:300px; height:auto; display:block; margin:1rem 0;">
      <p>
        I am a research professional focused on <strong>pathogen genomics</strong>,
        interested in <strong>wildlife and domestic animal infectious diseases</strong>,
        with a strong interest in using <strong>bioinformatics and statistics</strong>.
        I am well experienced in working with whole genomes.
      </p>
    </div>

    <h2>Area of Interest:</h2>
    <h2>Pathogen Genomics</h2>
    <ul>
      <li><strong>Focus:</strong> The genome of the pathogen (bacteria, viruses, fungi, parasites).</li>
      <li><strong>Goal:</strong> Understanding how genes, mutations, and mobile elements contribute to virulence, drug resistance, transmission, and host adaptation</li>
      <li><strong>Wildlife context:</strong> Genetic features of pathogens infecting wildlife - SNPs and pathogen spread between wildlife & livestock</li>
    </ul>

    <h2>Population Genomics</h2>
    <ul>
      <li><strong>Focus:</strong> The genome of a population of organisms (can be pathogens, hosts, or any species).</li>
      <li><strong>Goal:</strong> Detecting patterns of genetic variation across individuals/populations to infer evolution, selection.</li>
      <li><strong>Wildlife pathogens context:</strong> Applying population genomics to the pathogen population.</li>
    </ul>

    <h2>Landscape Genomics</h2>
    <ul>
      <li><strong>Focus:</strong> Links genomic variation to environmental/landscape variables (geography, climate, habitat).</li>
      <li><strong>Goal:</strong> Identify how environment shapes genetic diversity and adaptation.</li>
      <li><strong>Wildlife pathogen context:</strong> For hosts: Which environmental gradients explain why some wild populations have genes associated with pathogen resistance?</li>
      <li><strong>For pathogens:</strong> How do geography, host distribution, or climate shape pathogen genomic diversity (e.g., higher diversity of a virus in tropical vs. temperate zones)?</li>
    </ul>
  </section>

<!-- Skills -->
<section id="skills">
<h2>Professional Skills</h2>
<h3>Lab & Field</h3>
<ul>
<li>Lab management</li>
<li>BSL 1–3 safety</li>
<li>Bacterial culture & testing</li>
<li>DNA extraction & QC</li>
<li>Sample collection</li>
<li>Standard PCR</li>
<li>Oxford Nanopore sequencing</li>
</ul>

<h3>Computational</h3>
<ul>
<li>Python & basic R</li>
<li>Bash scripting</li>
<li>Genomic pipelines</li>
<li>Genome assembly & annotation</li>
<li>Illumina & Nanopore sequencing</li>
<li>Statistics & inference</li>
</ul>
</section>

<!-- Services -->
<section id="services">
<h2>Services</h2>
<ul>
<li>Data cleaning</li>
<li>High-throughput sequencing workflows</li>
<li>Novel protocol development</li>
<li>Custom pipelines</li>
</ul>
<h2>Future Goals</h2>
<ul>
<li>Functional annotation & transcriptomics</li>
<li>Collaborations in infectious disease genomics</li>
</ul>
</section>

<!-- Projects -->
<section id="projects">
<h2>Past Projects</h2>
<h3>ANP Project</h3>
<p>Short description here.</p>
<h3>Pneumonia Project</h3>
<p>Short description here.</p>
</section>

<!-- Publications -->
<section id="publications">
<h2>Publications</h2>
<ul>
<li>Dolfi, Amelie., Kausrud Kyrre., Rysava, K. Champagne Celeste., Huang Yen-Hua., 	<strong>Barandongo Zoe, R</strong> .,Turner Wendy, C. 2024. Season of death, pathogen persistence 	and wildlife behavior alter number of anthrax secondary infections from environmental 	reservoirs. Proceedings of the Royal 	Society B: Biological Sciences, 291: 20232568</li>
<li><strong>Barandongo Zoe R</strong>., Dolfi Amelie C., Bruce Spence A., Rysava Kristyna., Huang Yen-Hua., 	Joel Hendrina., Hassim Ayesha., Kamath Pauline L., van Heerden Henriette. & Turner 	Wendy C. (2023). The persistence of time: the lifespan of Bacillus anthracis spores 	in environmental reservoirs. Research in Microbiology</li>
<li>Turner Wendy C., Kamath Pauline L., van Heerden Henriette, Huang Yen-Hua, <strong>Barandongo 	Zoe R</strong>., Bruce Spencer A. and Kausrud Kyrre. (2021). The roles of environmental 	variation and parasite survival in virulence-transmission relationships. Royal Society. 	open sci.8210088210088http://doi.org/10.1098/rsos.210088</li>
<li>Huang Yen-Hua, Joel Hendrina, Küsters Martina, <strong>Barandongo Zoe R</strong>., Cloete Claudine C., 	Hartmann Axel, Kamath Pauline L., Kilian J. Werner, Mfune John K. E., Shatumbu 	Gabriel, Zidon Royi, 	Getz Wayne M. and Turner Wendy C. (2021). Disease or drought: 	environmental fluctuations release zebra from a potential pathogen-triggered 	ecological trap. Proceeding of the Royal Society B: Biological 	Sciences.2882021058220210582 http://doi.org/10.1098/rspb.2021.0582</li>
<li><strong>Barandongo, Zoe. R</strong>., Mfune, John. K. E., & Turner, Wendy. C. (2018). Dust-bathing behaviors		 of African herbivores and the potential risk of inhalational anthrax. Journal of Wildlife 	Diseases, 54(1), 34–44. https://doi.org/10.7589/2017-04-069</li>
<li>Turner Wendy.C., Kausrud Kyrre.L., Beyer Wolfgang., Easterday Ryan.W., <strong>Barandongo Zoe, 	R</strong>., Blaschke Elisabeth., Cloete, Claudine.C., Lazak, Judith., Van Ert, Matthew.N., Ganz, 	Holly.H., Turnbull, Peter.C.B., Stenseth, Nils.C & Getz. Wayne.M. (2016). Lethal 	exposure: An integrated approach to pathogen transmission via environmental reservoirs. 	Scientific Reports 6: 27311.</li>
<li>Nepolo Emmanuell., <strong>Barandongo Zoe.R</strong> & Chimwamurombe Percy.M. (2012). Seed and tuber 	protein pattern of Marama bean [Tylosema esculentum (Burchell) Schreiber] via Sodium 	dodecyl Sulfate Polyacrylamide gel electrophoresis. Journal of Research in Molecular 	Biology. 1:001 – 006</li>
</ul>
</section>

<!-- Contact -->
<section id="contact">
<h2>Contact</h2>
<p>Email: <a href="mailto:zoe.barandongo@outlook.com">mail</a></p>
<p>LinkedIn: <a href="https://www.linkedin.com/feed">Your LinkedIn</a></p>
</section>
</main>

<footer>
&copy; 2025 Dr. Zoe R Barandongo
</footer>

<script>
function showSection(id) {
  const sections = document.querySelectorAll('section');
  sections.forEach(s => s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}
</script>

</body>
</html>
