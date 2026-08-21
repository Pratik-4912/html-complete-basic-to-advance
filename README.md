<!DOCTYPE html>
<html lang="mr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Sagle HTML tags ekatra dakhvणारी demo file">
  <meta name="keywords" content="html, tags, demo">
  <title>Sagle HTML Tags - Demo Page</title>
  <base href="https://example.com/">
  <style>
    body { font-family: Arial, sans-serif; max-width: 900px; margin: 20px auto; padding: 0 15px; line-height: 1.6; }
    section { border: 1px solid #ccc; margin: 20px 0; padding: 15px; border-radius: 8px; }
    h2 { background: #eee; padding: 8px; }
    table, th, td { border: 1px solid #999; border-collapse: collapse; padding: 6px; }
  </style>
</head>
<body>

  <!-- ===== HEADER ===== -->
  <header>
    <h1>Sagle HTML Tags - Ekatra Demo</h1>
    <nav>
      <a href="#text">Text</a> |
      <a href="#lists">Lists</a> |
      <a href="#media">Media</a> |
      <a href="#table">Table</a> |
      <a href="#form">Form</a> |
      <a href="#interactive">Interactive</a>
    </nav>
  </header>

  <main>

    <!-- ===== TEXT & FORMATTING TAGS ===== -->
    <section id="text">
      <h2>1. Text va Formatting Tags</h2>
      <h3>Hi h3 heading ahe</h3>
      <p>He ek normal <strong>paragraph</strong> ahe jyat <em>emphasis</em>, <b>bold</b>, <i>italic</i>, 
        <u>underline</u>, <s>strikethrough</s>, <mark>highlight</mark>, <small>chhota text</small>, 
        H<sub>2</sub>O ani x<sup>2</sup> asa content ahe.</p>
      <p>Ha <del>juna text</del> <ins>navin text ne replace zala</ins>.</p>
      <blockquote cite="https://example.com">He ek blockquote ahe - motivational quote.</blockquote>
      <p>Ha <q>short inline quote</q> ahe ani <abbr title="HyperText Markup Language">HTML</abbr> cha full form abbr madhe ahe.</p>
      <address>Author: Ram Sharma, Pune, India</address>
      <p>Code example: <code>let x = 10;</code>, keyboard: <kbd>Ctrl + C</kbd>, output: <samp>Hello World</samp>, variable: <var>x</var></p>
      <p>Meeting time: <time datetime="2026-08-20T10:00">20 August 2026, 10:00 AM</time></p>
      <pre>
  Ha pre tag ahe
      spacing jashi lihili tashi
  disते.
      </pre>
      <hr>
      <p>Ha paragraph pahilya paragraph pasun<br>line break ne veगळा ahe.</p>
    </section>

    <!-- ===== LISTS ===== -->
    <section id="lists">
      <h2>2. Lists</h2>
      <p>Unordered list:</p>
      <ul>
        <li>Chaha</li>
        <li>Coffee</li>
      </ul>
      <p>Ordered list:</p>
      <ol>
        <li>Pahile step</li>
        <li>Doosre step</li>
      </ol>
      <p>Description list:</p>
      <dl>
        <dt>HTML</dt>
        <dd>Structure banवते</dd>
        <dt>CSS</dt>
        <dd>Styling karते</dd>
      </dl>
    </section>

    <!-- ===== LINKS & IMAGES ===== -->
    <section id="links">
      <h2>3. Links, Images va Figure</h2>
      <p><a href="https://google.com" target="_blank">Google la ja</a></p>
      <figure>
        <img src="https://via.placeholder.com/150" alt="Placeholder image" width="150">
        <figcaption>He ek sample image ahe.</figcaption>
      </figure>
      <map name="imgmap">
        <area shape="rect" coords="0,0,50,50" href="https://example.com" alt="Clickable area">
      </map>
    </section>

    <!-- ===== MEDIA ===== -->
    <section id="media">
      <h2>4. Audio, Video va Embedded Content</h2>
      <p>Audio player:</p>
      <audio controls>
        <source src="song.mp3" type="audio/mpeg">
        Tumcha browser audio support karत nahi.
      </audio>
      <p>Video player:</p>
      <video controls width="300">
        <source src="movie.mp4" type="video/mp4">
        <track kind="subtitles" src="subs.vtt" srclang="mr" label="Marathi">
        Tumcha browser video support karत nahi.
      </video>
      <p>Iframe (dusra page embed):</p>
      <iframe src="https://www.example.com" width="300" height="150" title="Example site"></iframe>
      <p>SVG graphic:</p>
      <svg width="100" height="100">
        <circle cx="50" cy="50" r="40" fill="skyblue" stroke="navy" />
      </svg>
      <p>Canvas (JS ने draw karayla):</p>
      <canvas id="myCanvas" width="150" height="80" style="border:1px solid #000;"></canvas>
    </section>

    <!-- ===== TABLE ===== -->
    <section id="table">
      <h2>5. Table</h2>
      <table>
        <caption>Student Marks</caption>
        <colgroup>
          <col style="background-color:#f9f9f9;">
          <col>
        </colgroup>
        <thead>
          <tr><th>Naav</th><th>Marks</th></tr>
        </thead>
        <tbody>
          <tr><td>Ram</td><td>85</td></tr>
          <tr><td>Sita</td><td>90</td></tr>
        </tbody>
        <tfoot>
          <tr><td>Total</td><td>175</td></tr>
        </tfoot>
      </table>
    </section>

    <!-- ===== FORM ===== -->
    <section id="form">
      <h2>6. Form (Sagle Input Types)</h2>
      <form action="#" method="POST">
        <fieldset>
          <legend>Personal Details</legend>

          <label for="name">Naav:</label>
          <input type="text" id="name" name="name" placeholder="Tumche naav" required><br><br>

          <label for="email">Email:</label>
          <input type="email" id="email" name="email"><br><br>

          <label for="pass">Password:</label>
          <input type="password" id="pass" name="pass"><br><br>

          <label for="age">Vay:</label>
          <input type="number" id="age" name="age" min="1" max="100"><br><br>

          <label for="dob">Date of Birth:</label>
          <input type="date" id="dob" name="dob"><br><br>

          <label for="fruit">Favourite Fruit:</label>
          <input list="fruits" id="fruit" name="fruit">
          <datalist id="fruits">
            <option value="Apple">
            <option value="Mango">
          </datalist><br><br>

          <p>Gender:</p>
          <input type="radio" id="male" name="gender" value="male">
          <label for="male">Male</label>
          <input type="radio" id="female" name="gender" value="female">
          <label for="female">Female</label><br><br>

          <input type="checkbox" id="terms" name="terms">
          <label for="terms">Mi terms manya karto</label><br><br>

          <label for="city">City:</label>
          <select id="city" name="city">
            <optgroup label="Maharashtra">
              <option value="pune">Pune</option>
              <option value="mumbai">Mumbai</option>
            </optgroup>
          </select><br><br>

          <label for="msg">Message:</label><br>
          <textarea id="msg" name="msg" rows="3" cols="30"></textarea><br><br>

          <label for="file">File Upload:</label>
          <input type="file" id="file" name="file"><br><br>

          <label for="range">Rating:</label>
          <input type="range" id="range" min="0" max="10"><br><br>

          <label for="prog">Progress:</label>
          <progress id="prog" value="70" max="100"></progress>

          <label for="mtr">Battery:</label>
          <meter id="mtr" value="0.6">60%</meter><br><br>

          <button type="submit">Submit Kara</button>
          <button type="reset">Reset Kara</button>
          <output name="result" for="age"></output>
        </fieldset>
      </form>
    </section>

    <!-- ===== INTERACTIVE ELEMENTS ===== -->
    <section id="interactive">
      <h2>7. Interactive Elements</h2>
      <details>
        <summary>Click kara jasta mahiti sathi</summary>
        <p>Hi hidden content ahe jo click केल्यावर disते.</p>
      </details><br>

      <button onclick="document.getElementById('myDialog').showModal()">Dialog Ughad</button>
      <dialog id="myDialog">
        <p>Ha ek dialog/popup box ahe.</p>
        <button onclick="document.getElementById('myDialog').close()">Band Kar</button>
      </dialog>
    </section>

    <!-- ===== ASIDE, ARTICLE ===== -->
    <article>
      <h2>Article Tag</h2>
      <p>He ek independent article content ahe, jasa blog post.</p>
    </article>

    <aside>
      <p>He aside section ahe - sidebar/extra info sathi.</p>
    </aside>

    <!-- ===== DATA ATTRIBUTE, VAR EXAMPLE ===== -->
    <div data-user-id="123" data-role="admin">Ha div data attributes vaparto (JS madhe access karayla).</div>

    <!-- ===== NOSCRIPT ===== -->
    <noscript>Tumcha JavaScript band ahe, kahi features kaam karणar nahit.</noscript>

  </main>

  <!-- ===== FOOTER ===== -->
  <footer>
    <p>&copy; 2026 Sagle HTML Tags Demo. Sarv hakk raakhीव.</p>
  </footer>

  <!-- ===== SCRIPT ===== -->
  <script>
    // Canvas var chhota drawing
    const canvas = document.getElementById('myCanvas');
    const ctx = canvas.getContext('2d');
    ctx.fillStyle = 'tomato';
    ctx.fillRect(10, 10, 100, 60);
  </script>

</body>
</html>
