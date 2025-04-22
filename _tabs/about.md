---
icon: fas fa-info-circle
order: 4
---

<style>
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}

.timeline::after {
  content: '';
  position: absolute;
  width: 2px;
  top: 0;
  bottom: 0;
  left: 15px;
  margin-left: -1px;
}

.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  margin-bottom: 20px;
}

.container::after {
  content: '';
  position: absolute;
  width: 12px;
  height: 12px;
  border: 3px solid;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
  /* Fix dot centering */
  left: 15px;
  transform: translateX(-50%);
}

.date {
  font-weight: bold;
  margin-bottom: 5px;
}

.org {
  font-style: italic;
  margin-bottom: 8px;
}

.position {
  font-weight: bold;
  font-size: 1.2em;
  margin-bottom: 10px;
}

.details ul {
  margin-top: 0;
  margin-bottom: 15px;
}

</style>

## My Experience

<div class="timeline">
  <div class="container">
    <div class="date">01.2023 - present</div>
    <div class="org">IQS Sp. z o.o. - Warsaw, Poland (market research) (www.grupaiqs.pl)</div>
    <div class="position">Data Analyst</div>
  </div>
  
  <div class="container">
    <div class="date">07.2021 - 12.2022</div>
    <div class="org">IQS Sp. z o.o. - Warsaw, Poland</div>
    <div class="position">IT Support/Junior Web Developer</div>
  </div>
</div>

## My Education

<div class="timeline">
  <div class="container">
    <div class="date">10.2024 - Present</div>
    <div class="org">SGH Warsaw School of Economics</div>
    <div class="position">Master's Degree in Advanced Analytics: Big Data</div>
  </div>
  
  <div class="container">
    <div class="date">10.2021 - 07.2024</div>
    <div class="org">SGH Warsaw School of Economics</div>
    <div class="position">Bachelor's Degree in Quantitative Methods in Economics and Information Systems</div>
  </div>
</div>