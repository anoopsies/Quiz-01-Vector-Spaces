
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Click the correct/best option(Quiz by AnoopSV)</title>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
    src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    .question {
      margin-bottom: 20px;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 8px;
    }
    .correct {
      color: green;
      font-weight: bold;
    }
    .incorrect {
      color: red;
      font-weight: bold;
    }
    button {
      padding: 8px 16px;
      font-size: 16px;
      border-radius: 6px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h2>Click the correct/best option(Quiz by AnoopSV)</h2>
  <form id="quizForm">
    
    <div class="question">
      <p>1. Which of the following is a basis for \(\mathbb{R}^2\)?</p>
      <label><input type="radio" name="q1" value="a"> \((1,0), (0,1)\)</label><br>
      <label><input type="radio" name="q1" value="b"> \((1,1), (2,2)\)</label><br>
      <label><input type="radio" name="q1" value="c"> \((1,0), (1,1)\)</label><br>
      <label><input type="radio" name="q1" value="d"> \((0,0), (1,0)\)</label><br>
      <div id="feedback1"></div>
    </div>

    <div class="question">
      <p>2. The dimension of the space of all real polynomials of degree at most 2 is:</p>
      <label><input type="radio" name="q2" value="a"> 2</label><br>
      <label><input type="radio" name="q2" value="b"> 3</label><br>
      <label><input type="radio" name="q2" value="c"> 4</label><br>
      <label><input type="radio" name="q2" value="d"> Infinite</label><br>
      <div id="feedback2"></div>
    </div>

    <div class="question">
      <p>3. The set \(\{(1,0,0), (0,1,0), (0,0,1)\}\) in \(\mathbb{R}^3\) is:</p>
      <label><input type="radio" name="q3" value="a"> Linearly dependent</label><br>
      <label><input type="radio" name="q3" value="b"> Linearly independent</label><br>
      <label><input type="radio" name="q3" value="c"> Not a basis</label><br>
      <label><input type="radio" name="q3" value="d"> None of these</label><br>
      <div id="feedback3"></div>
    </div>

    <div class="question">
      <p>4. The span of \(\{(1,1)\}\) in \(\mathbb{R}^2\) is:</p>
      <label><input type="radio" name="q4" value="a"> The entire \(\mathbb{R}^2\)</label><br>
      <label><input type="radio" name="q4" value="b"> A line through the origin</label><br>
      <label><input type="radio" name="q4" value="c"> A plane</label><br>
      <label><input type="radio" name="q4" value="d"> Zero vector only</label><br>
      <div id="feedback4"></div>
    </div>

    <div class="question">
      <p>5. The dimension of the space of all \(2 \times 2\) real matrices is:</p>
      <label><input type="radio" name="q5" value="a"> 2</label><br>
      <label><input type="radio" name="q5" value="b"> 3</label><br>
      <label><input type="radio" name="q5" value="c"> 4</label><br>
      <label><input type="radio" name="q5" value="d"> 5</label><br>
      <div id="feedback5"></div>
    </div>

    <div class="question">
      <p>6. The set \(\{1, x, x^2\}\) in the space of polynomials of degree at most 2 is:</p>
      <label><input type="radio" name="q6" value="a"> A basis</label><br>
      <label><input type="radio" name="q6" value="b"> Linearly dependent</label><br>
      <label><input type="radio" name="q6" value="c"> Not generating the space</label><br>
      <label><input type="radio" name="q6" value="d"> None</label><br>
      <div id="feedback6"></div>
    </div>

    <div class="question">
      <p>7. The number of vectors in any basis of \(\mathbb{R}^3\) is:</p>
      <label><input type="radio" name="q7" value="a"> 2</label><br>
      <label><input type="radio" name="q7" value="b"> 3</label><br>
      <label><input type="radio" name="q7" value="c"> 4</label><br>
      <label><input type="radio" name="q7" value="d"> Depends on the basis</label><br>
      <div id="feedback7"></div>
    </div>

    <div class="question">
      <p>8. The set \(\{(1,2), (2,4)\}\) in \(\mathbb{R}^2\) is:</p>
      <label><input type="radio" name="q8" value="a"> Linearly independent</label><br>
      <label><input type="radio" name="q8" value="b"> Linearly dependent</label><br>
      <label><input type="radio" name="q8" value="c"> A basis</label><br>
      <label><input type="radio" name="q8" value="d"> None</label><br>
      <div id="feedback8"></div>
    </div>

    <div class="question">
      <p>9. The vector \((1,1,1)\) in \(\mathbb{R}^3\) can be written as a linear combination of:</p>
      <label><input type="radio" name="q9" value="a"> \((1,0,0), (0,1,0), (0,0,1)\)</label><br>
      <label><input type="radio" name="q9" value="b"> \((1,0,0), (1,1,0)\)</label><br>
      <label><input type="radio" name="q9" value="c"> \((1,1,0), (0,1,1)\)</label><br>
      <label><input type="radio" name="q9" value="d"> None</label><br>
      <div id="feedback9"></div>
    </div>

    <div class="question">
      <p>10. The zero vector in any vector space is:</p>
      <label><input type="radio" name="q10" value="a"> Always in every span</label><br>
      <label><input type="radio" name="q10" value="b"> Never in any span</label><br>
      <label><input type="radio" name="q10" value="c"> Sometimes in span</label><br>
      <label><input type="radio" name="q10" value="d"> None</label><br>
      <div id="feedback10"></div>
    </div>

    <button type="button" onclick="checkAnswers()">Submit</button>
  </form>

  <script>
    const answers = {
      q1: "a",
      q2: "b",
      q3: "b",
      q4: "b",
      q5: "c",
      q6: "a",
      q7: "b",
      q8: "b",
      q9: "a",
      q10: "a"
    };

    function checkAnswers() {
      let score = 0;
      for (let i = 1; i <= 10; i++) {
        const q = "q" + i;
        const feedback = document.getElementById("feedback" + i);
        const selected = document.querySelector(`input[name=${q}]:checked`);
        if (selected) {
          if (selected.value === answers[q]) {
            score++;
            feedback.innerHTML = `<span class="correct">Correct ✔️</span>`;
          } else {
            feedback.innerHTML = `<span class="incorrect">Incorrect ✘ (Correct: ${answers[q]})</span>`;
          }
        } else {
          feedback.innerHTML = `<span class="incorrect">No answer selected ✘ (Correct: ${answers[q]})</span>`;
        }
      }
      alert("Your score: " + score + "/10");
    }
  </script>
</body>
</html>
