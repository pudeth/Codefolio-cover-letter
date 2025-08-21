<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <title>CV - Game Programmer</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Language Switch Button -->
  <div class="lang-switch" onclick="toggleLangMenu()">🌐 Language</div>
  <div id="langMenu" class="lang-menu">
    <button onclick="setLang('en')">🇬🇧 English</button>
    <button onclick="setLang('km')">🇰🇭 Khmer</button>
  </div>

  <div class="container">
    <!-- Sidebar -->
    <aside class="sidebar">
      <img src="ID.jpg" alt="Profile Picture" class="profile-pic">
      <p>img.image ID</p>

      <p data-en="Skill: Coding and make Fun_Game"
         data-km="ជំនាញ: កូដ និងបង្កើតហ្គេមកំសាន្ត">
         Skill: Coding and make Fun_Game
      </p>

      <section class="typing">
      <span class="enum">public enum</span> LANGUAGES {<br>
      <h2>
          <span data-en="Name: Peak Deth," 
                data-km="ឈ្មោះ៖ ពាក្យ ដេត,">Name: Peak Deth,</span><br>
          <span data-en="Age: 23 years old," 
                data-km="អាយុ៖ 23 ឆ្នាំ,">Age: 23 years old,</span><br>
          <span data-en="Status: Married," 
                data-km="ស្ថានភាព៖ រៀបការ,">Status: Married,</span>
      </h2>
              }
        </section>

      <div class="code">
        <section class="typing">
          <span class="enum">public enum</span> PLATFORMS {<br>
          &nbsp;&nbsp;Windows,<br>
          &nbsp;&nbsp;Linux,<br>
          &nbsp;&nbsp;Mobile<br>
          }
        </section>

        <section class="typing">
          <span class="enum">public enum</span> LANGUAGES {<br>
          &nbsp;&nbsp;C#, C++, C,<br>
          &nbsp;&nbsp;Python, Bash, LUA,<br>
          &nbsp;&nbsp;Java, HTML5, CSS, JavaScript<br>
          }
        </section>

        <section class="typing">
  <span class="enum">public enum</span> SOFTWARE {<br>
  &nbsp;&nbsp;Unity3D, UnrealEngine,<br>
  &nbsp;&nbsp;Godot4, VisualStudio,<br>
  &nbsp;&nbsp;Jetbrains, Photoshop,<br>
  &nbsp;&nbsp;GoogleSuite, Blender,<br>
  &nbsp;&nbsp;AdobePremier, SubstancePainter,<br>
  &nbsp;&nbsp;AdobeSubstance3D<br>
  }

  <!-- Software Skill Chart -->
<div class="soft-chart">
  <div class="bar"><span>Unity3D</span><div class="progress"><div class="fill" style="width:95%"></div></div><span class="percent">95%</span></div>
  <div class="bar"><span>UnrealEngine</span><div class="progress"><div class="fill" style="width:70%"></div></div><span class="percent">70%</span></div>
  <div class="bar"><span>Godot4</span><div class="progress"><div class="fill" style="width:60%"></div></div><span class="percent">60%</span></div>
  <div class="bar"><span>VisualStudio</span><div class="progress"><div class="fill" style="width:85%"></div></div><span class="percent">85%</span></div>
  <div class="bar"><span>Jetbrains</span><div class="progress"><div class="fill" style="width:75%"></div></div><span class="percent">75%</span></div>
  <div class="bar"><span>Photoshop</span><div class="progress"><div class="fill" style="width:80%"></div></div><span class="percent">80%</span></div>
  <div class="bar"><span>GoogleSuite</span><div class="progress"><div class="fill" style="width:65%"></div></div><span class="percent">65%</span></div>
  <div class="bar"><span>Blender</span><div class="progress"><div class="fill" style="width:70%"></div></div><span class="percent">70%</span></div>
  <div class="bar"><span>AdobePremier</span><div class="progress"><div class="fill" style="width:60%"></div></div><span class="percent">60%</span></div>
  <div class="bar"><span>SubstancePainter</span><div class="progress"><div class="fill" style="width:55%"></div></div><span class="percent">55%</span></div>
  <div class="bar"><span>AdobeSubstance3D</span><div class="progress"><div class="fill" style="width:50%"></div></div><span class="percent">50%</span></div>
</div>

</section>



       <section class="typing">
        <br>
        <span class="enum">public enum</span> MEDIA { <br> <br>
        &nbsp;&nbsp;<a href="https://www.facebook.com/pu.deth.175755" class="link">
        <i class="fab fa-facebook"></i> Facebook
        </a><br>
        &nbsp;&nbsp;<a href="https://www.linkedin.com/in/peak-mao-016b6b239/" class="link">
        <i class="fab fa-linkedin"></i> LinkedIn
        </a><br>
        &nbsp;&nbsp;<a href="https://github.com/pudeth" class="link">
        <i class="fab fa-github"></i> GitHub
        </a><br><br>
        }
        </section>


        <section class="typing">
  <span class="enum">public enum</span> LANGUAGES_LEVEL {<br>
  &nbsp;&nbsp;<span data-en="Khmer = C1" data-km="ខ្មែរ = C1">Khmer = C1</span>,<br>
  &nbsp;&nbsp;<span data-en="Chinese = B2" data-km="ចិន = B2">Chinese = B2</span>,<br>
  &nbsp;&nbsp;<span data-en="English = B2" data-km="អង់គ្លេស = B2">English = B2</span><br>
  }

  <!-- Language Chart -->
<div class="lang-chart">
  <div class="bar">
    <span>Khmer</span>
    <div class="progress"><div class="fill" style="width:100%"></div></div>
    <span class="percent">100%</span>
  </div>
  <div class="bar">
    <span>Chinese</span>
    <div class="progress"><div class="fill" style="width:50%"></div></div>
    <span class="percent">50%</span>
  </div>
  <div class="bar">
    <span>English</span>
    <div class="progress"><div class="fill" style="width:78%"></div></div>
    <span class="percent">78%</span>
  </div>
</div>

</section>
      </div>
    </aside>

    <!-- Main Content -->
    <main class="main">
      <div class="code">

        <section class="typing info-block">
  <span class="keyword">public class</span> <span class="class">INFORMATION</span> {<br>
  <div class="code-line">
    <span class="keyword">public string</span> Name = <span class="string">"PEAK_DETH"</span>;
  </div>
  <div class="code-line">
    <span class="keyword">public string</span> TITLE = <span class="string">"Game Programmer"</span>;
  </div>
  <div class="code-line">
    <span class="keyword">public string</span> EMAIL = <span class="string">"peakmao007@gmai.com"</span>;
  </div>
  <div class="code-line">
    <span class="keyword">public string</span> PHONE = <span class="string">"068 656 263"</span>;
  </div>
  <div class="code-line">
    <span class="keyword">public string</span> POSITION = <span class="string">"Staff Media_Team (Coding_Develop)"</span>;
  </div>
  <div class="code-line">
    <span class="keyword">public bool</span> VEHICLE_LICENSE_B = <span class="keyword">true</span>;
  </div>
  <div class="code-line">
    <span class="keyword">public int</span> AGE = <span class="number">23</span>;
  </div>
  } 
</section>

<section class="typing info-block">
  <span class="keyword">public partial class</span> <span class="class">EDUCATION</span> {<br>
  <div class="method">private void YnovConnect() {</div>
  <div class="code-line indent">
    <span class="keyword">var</span> Level = <span class="string">"Master"</span>;
  </div>
  <div class="code-line indent">
    <span class="keyword">var</span> Duration = <span class="string">"2 years"</span>;
  </div>
  <div class="code-line indent">
    <span class="keyword">var</span> Start = <span class="string">"Today"</span>;
  </div>
  <div class="code-line indent">
    <span class="keyword">var</span> Type = <span class="string">"Game Programmer"</span>;
  </div>
  <div class="method">}</div><br>

  <div class="method">private void ICAN() {</div>
  <div class="code-line indent">
    <span class="keyword">var</span> Level = <span class="string">"Bachelor"</span>;
  </div>
  <div class="code-line indent">
    <span class="keyword">var</span> Date = <span class="string">"October 2021 - June 2024"</span>;
  </div>
  <div class="code-line indent">
    <span class="keyword">var</span> Diplomas = { <span class="string">"Game Design"</span>, <span class="string">"Digital Design"</span> };
  </div>
  <div class="code-line indent">
    <span class="keyword">var</span> Graduation = <span class="string">"Saturday 24 June 2025"</span>;
  </div>
  <div class="method">}</div>
  } 
</section>

<section class="typing info-block">
  <span class="keyword">public static class</span> <span class="class">EXPERIENCES</span> {<br>
  <div class="method">public void StudioPREMA() {</div>
  <div class="code-line indent">
    <span class="keyword">var</span> Duration = <span class="string">"September 2024 - November 2024"</span>;
  </div>
  <div class="code-line indent">
    <span class="keyword">var</span> Type = <span class="string">"Internship"</span>;
  </div>
  <div class="code-line indent">
    <span class="keyword">var</span> Link = <span class="string">"https://afjv.com/societe/1330-studio-prema.htm"</span>;
  </div>
  <div class="method">}</div><br>

  <div class="method">public void LeDouzisme() {</div>
  <div class="code-line indent">
    <span class="keyword">var</span> Type = <span class="string">"Association"</span>;
  </div>
  <div class="method">}</div>
  }
</section>


        <section class="typing">
         
        </section>

        <section class="typing">
          
        </section>
      </div>
    </main>
  </div>

<script>
function toggleLangMenu() {
  const menu = document.getElementById("langMenu");
  menu.style.display = menu.style.display === "block" ? "none" : "block";
}

function setLang(lang) {
  document.querySelectorAll("[data-en]").forEach(el => {
    if (el.dataset[lang]) {
      el.innerHTML = el.dataset[lang];
    }
  });
  document.getElementById("langMenu").style.display = "none";
}
</script>

</body>
</html>
