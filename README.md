
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vector Spaces Quiz</title>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
    src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; background: #f4f6f9; }
    h1 { text-align: center; }
    .question { margin: 15px 0; padding: 15px; background: white; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
    button { padding: 10px 20px; font-size: 16px; margin-top: 20px; cursor: pointer; }
    #result { margin-top: 20px; font-weight: bold; font-size: 18px; }
    .matrix { display: inline-block; border: 1px solid black; margin: 2px; }
    .matrix table { border-collapse: collapse; }
    .matrix td { border: 1px solid black; padding: 5px 10px; text-align: center; }
  </style>
</head>
<body>
  <h1>Quiz: Click the correct/best option(Quiz by AnoopSV)</h1>
  <form id="quizForm">

    <div class="question">
      <p>1. The vectors \((1,0)\) and \((0,1)\) in \(\mathbb{R}^2\) form:</p>
      <input type="radio" name="q1" value="a"> a) A basis of \(\mathbb{R}^2\)<br>
      <input type="radio" name="q1" value="b"> b) A dependent set<br>
      <input type="radio" name="q1" value="c"> c) Not spanning \(\mathbb{R}^2\)<br>
      <input type="radio" name="q1" value="d"> d) None of these<br>
    </div>

    <div class="question">
      <p>2. The dimension of \(\mathbb{R}^3\) is:</p>
      <input type="radio" name="q2" value="a"> a) 2<br>
      <input type="radio" name="q2" value="b"> b) 3<br>
      <input type="radio" name="q2" value="c"> c) 4<br>
      <input type="radio" name="q2" value="d"> d) Infinite<br>
    </div>

    <div class="question">
      <p>3. Which of the following is a linear combination of \((1,0)\) and \((0,1)\) in \(\mathbb{R}^2\)?</p>
      <input type="radio" name="q3" value="a"> a) \((2,3)\)<br>
      <input type="radio" name="q3" value="b"> b) \((5,-1)\)<br>
      <input type="radio" name="q3" value="c"> c) \((0,0)\)<br>
      <input type="radio" name="q3" value="d"> d) All of the above<br>
    </div>

    <div class="question">
      <p>4. The span of \(\{(1,1,0)\}\) in \(\mathbb{R}^3\) is:</p>
      <input type="radio" name="q4" value="a"> a) A line through origin<br>
      <input type="radio" name="q4" value="b"> b) A plane through origin<br>
      <input type="radio" name="q4" value="c"> c) Whole \(\mathbb{R}^3\)<br>
      <input type="radio" name="q4" value="d"> d) Zero vector only<br>
    </div>

    <div class="question">
      <p>5. The set \(\{x, x^2\}\) in the space of real polynomials of degree \(\leq 2\) is:</p>
      <input type="radio" name="q5" value="a"> a) Linearly independent<br>
      <input type="radio" name="q5" value="b"> b) Linearly dependent<br>
      <input type="radio" name="q5" value="c"> c) A basis<br>
      <input type="radio" name="q5" value="d"> d) Both a and c<br>
    </div>

    <div class="question">
      <p>6. The dimension of the space of all real polynomials of degree \(\leq 2\) is:</p>
      <input type="radio" name="q6" value="a"> a) 2<br>
      <input type="radio" name="q6" value="b"> b) 3<br>
      <input type="radio" name="q6" value="c"> c) 4<br>
      <input type="radio" name="q6" value="d"> d) Infinite<br>
    </div>

    <div class="question">
      <p>7. The set of all \(2 \times 2\) real matrices forms a vector space of dimension:</p>
      <input type="radio" name="q7" value="a"> a) 2<br>
      <input type="radio" name="q7" value="b"> b) 3<br>
      <input type="radio" name="q7" value="c"> c) 4<br>
      <input type="radio" name="q7" value="d"> d) Infinite<br>
    </div>

    <div class="question">
      <p>8. Consider the set \(\{(1,0,0), (0,1,0), (1,1,0)\}\) in \(\mathbb{R}^3\). This set is:</p>
      <input type="radio" name="q8" value="a"> a) Linearly independent<br>
      <input type="radio" name="q8" value="b"> b) Linearly dependent<br>
      <input type="radio" name="q8" value="c"> c) A basis<br>
      <input type="radio" name="q8" value="d"> d) None of these<br>
    </div>

    <div class="question">
      <p>9. A basis for the space of \(2 \times 2\) real matrices is given by:</p>
      <div class="matrix"><table><tr><td>1</td><td>0</td></tr><tr><td>0</td><td>0</td></tr></table></div>,
      <div class="matrix"><table><tr><td>0</td><td>1</td></tr><tr><td>0</td><td>0</td></tr></table></div>,
      <div class="matrix"><table><tr><td>0</td><td>0</td></tr><tr><td>1</td><td>0</td></tr></table></div>,
      <div class="matrix"><table><tr><td>0</td><td>0</td></tr><tr><td>0</td><td>1</td></tr></table></div>
      <br>
      <input type="radio" name="q9" value="a"> a) True<br>
      <input type="radio" name="q9" value="b"> b) False<br>
    </div>

    <div class="question">
      <p>10. The maximum number of linearly independent vectors in \(\mathbb{R}^2\) is:</p>
      <input type="radio" name="q10" value="a"> a) 1<br>
      <input type="radio" name="q10" value="b"> b) 2<br>
      <input type="radio" name="q10" value="c"> c) 3<br>
      <input type="radio" name="q10" value="d"> d) Infinite<br>
    </div>

    <button type="button" onclick="submitQuiz()">Submit Quiz</button>
  </form>
  <div id="result"></div>

  <script>
    function submitQuiz() {
      const answers = {
        q1: "a", // basis of R2
        q2: "b", // dim R3 = 3
        q3: "d", // all of the above
        q4: "a", // line through origin
        q5: "a", // independent
        q6: "b", // dimension = 3
        q7: "c", // dimension = 4
        q8: "b", // dependent
        q9: "a", // true
        q10: "b" // max = 2
      };
      let score = 0;
      for (let q in answers) {
        const selected = document.querySelector(`input[name="${q}"]:checked`);
        if (selected && selected.value === answers[q]) score++;
      }
      document.getElementById("result").innerText =
        `You scored ${score} / 10`;
      MathJax.typeset(); // re-render after submission
    }
  </script>
</body>
</html>
