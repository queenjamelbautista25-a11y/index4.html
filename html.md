
You said:
   <!DOCTYPE html>


   <html lang="en">
   <head>
   <meta charset="utf-8"/>
   <meta content="width=device=width, initial-scale=1.0" name="viewport"/>
   <title>QuizMaster - Pattao National High School- Main</title>
   <script src=https://cdn.tailwindcss.com">
    function resetAttemps(){
     const passcode = prompt("Enter teacher passcode to reset attemps:");
     if (passcode === "300480"){
      localStorage.removeItem('quizAttemps');
      alert('✅ Attempts counter has been successfully reset!');
     }else if (passcode ! == null){
     alert('❌ Incorrect passcode. Access denied.');
    }
   }
   </script>
<link
href="https://fonts.geogleapis.com/css2?family=Inter;wght@400;600;700&amp;di
splay=swap" rel="stylesheet"/>

<style>



:root{

 --brand-maroon:#800000;

 --brand-gold:#D4AF37;

 --brand-gold-strong:3C89D1A;

 --card-bg:#fffff;

 --muted:36b6b6b;



}



body { font-family: 'Inter' sans-serif:backround:linear-gradient(180deg,#fffaf7 0%,

\\\\#fff 100%);}



.brand-header { color:var(--brand-maroon):}





</div>



<footer class="text-center mt-6 text-gray-500 text-sm">



<p>© 2025 Reynaldo P. Usigan, Mylene A. Baquiran, Queen Jamel Bautista </p>



</footer>

</div>

<script>


 // ===== QUESTION BANK (10 items) =====

 let QUESTION\\\_BANK=\\\[

 {id: 1, q:"What does ICT stand for?", options:\\\["Information and Communication Technology", "Internet and Computer Technique", "Information Computer Technology", "Integrated Communication Tool"], answer:1},{id: 2, q:"Which device is used to input data into a computer?", options:\\\["Monitor", "Printer", "Keyboard", "Speaker"], answer:3},{id: 3, q:"What part of the computer is considered the “brain”?", options:\\\["RAM", "Hard Drive", "Motherboard", "CPU"], answer:4},{id: 4, q:"Which of the following is an example of system software?", options:\\\["Microsoft Word", "Windows Operating System", "Google Chrome", "Adobe Photoshop"], answer:2},{id: 5, q:"What does RAM stand for?", options:\\\["Read Access Memory", "Random Access Memory", "Run All Memory", "eadable Active Memory"], answer:2},{id: 6, q:"Which device is used to produce a hard copy of a document?", options:\\\["Read Access Memory", "Random Access Memory", "Run All Memory", "eadable Active Memory"], answer:2},{id: 7, q:"What device is used to connect a computer to the internet?", options:\\\["Modem", "Scanner", "Scanner", "Flash drive"], answer:1},{id: 8, q:"What does WWW stand for?", options:\\\["World Wide Web", "Wide World Web", "Web World Wide", "World Web Window"], answer:1},{id: 9, q:"Which of the following is a web browser?", options:\\\["Microsoft Excel", "Google Chrome", "Windows", "Android"], answer:2},{id: 10, q:"What is the purpose of a firewall?", options:\\\["To cool the computer", "To protect against unauthorized access", "o speed up the computer", "To store data"], answer:2}





// ===== app element refs =====



  const studentInfoContainer = document.getElementByld('student-info-container');

  const studentForm = document.getElementByld('student-form');

  const quizContainer = document.getElementByld('quiz-container');

  const resultsContainer = document.getElementByld('results-container');

  const scoreDisplay = document.getElementByld('score-display');

  const questionCounter = document.getElementByld('question-counter');

  const quizText = document.getElementByld('question-text');

  const optionsContainer = document.getElementByld('options-container');

  const timerDisplay = document.getElementByld('timer-display');

  const timeSpentResult = document.getElementByld('time-spent-result');

  const dateTimeResult = document.getElementByld('date-time-result');

  const attempsResult = document.getElementByld('attemps-result');

  const studentNameResult = document.getElementByld('student-name-result');

  const detailsTeacher = document.getElementByld('details-teacher');

  const detailsGradeSection = document.getElementByld('details-grade-section');

  const detailsSubject = document.getElementByld('details-subject');



 // NEW:Result display for Grading Period



  const detailsGradingPeriod = document.getElementByld('details-Grading-Period');