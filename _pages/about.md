---
title: "About Me"
permalink: /about/
---

<style>
  @import url("https://fonts.googleapis.com/css?family=Montserrat:400,500,600");
  body {
    padding: 0;
    margin: 0;
    font-family: "Montserrat", sans-serif;
  }
  h1 {
    font-size: 50px;
    text-align: center;
  }
  .timeline {
    position: relative;
    margin: 50px auto;
    padding: 40px 0;
    width: 100% ;
    box-sizing: border-box;
  }
  .timeline:before {
    content: "";
    position: absolute;
    left: 50%;
    width: 2px;
    height: 100%;
    background: #c5c5c5;
  }
  .timeline ul {
    padding: 0;
    margin: 0;
  }
  .timeline ul li {
    list-style: none;
    position: relative;
    width: 50%;
    padding: 20px 40px;
    box-sizing: border-box;
  }
  .timeline ul li:nth-child(odd) {
    float: left;
    text-align: right;
    clear: both;
  }
  .timeline ul li:nth-child(even) {
    float: right;
    text-align: left;
    clear: both;
  }
  .content {
    padding-bottom: 20px;
  }
  .timeline ul li:nth-child(odd):before {
    content: "";
    position: absolute;
    width: 10px;
    height: 10px;
    top: 24px;
    right: -6px;
    background: rgba(233, 33, 99, 1);
    border-radius: 50%;
    box-shadow: 0 0 0 3px rgba(233, 33, 99, 0.2);
  }
  .timeline ul li:nth-child(even):before {
    content: "";
    position: absolute;
    width: 10px;
    height: 10px;
    top: 24px;
    left: -4px;
    background: rgba(233, 33, 99, 1);
    border-radius: 50%;
    box-shadow: 0 0 0 3px rgba(233, 33, 99, 0.2);
  }
  .timeline ul li h3 {
    padding: 0;
    margin: 0;
    color: rgba(233, 33, 99, 1);
    font-weight: 600;
  }
  .timeline ul li p {
    margin: 10px 0 0;
    padding: 0;
  }
  .timeline p {
    font-size: 16px;
  }
  .timeline ul li .time h4 {
    margin: 0;
    padding: 0;
    font-size: 12px;
  }
  .timeline ul li:nth-child(odd) .time {
    position: absolute;
    top: 12px;
    right: -165px;
    margin: 0;
    padding: 8px 16px;
    background: rgba(233, 33, 99, 1);
    color: #fff;
    border-radius: 18px;
    box-shadow: 0 0 0 3px rgba(233, 33, 99, 0.3);
  }
  .timeline ul li:nth-child(even) .time {
    position: absolute;
    top: 12px;
    left: -165px;
    margin: 0;
    padding: 8px 16px;
    background: rgba(233, 33, 99, 1);
    color: #fff;
    border-radius: 18px;
    box-shadow: 0 0 0 3px rgba(233, 33, 99, 0.3);
  }
  @media (max-width: 1000px) {
    .timeline {
      width: 100%;
    }
  }
  @media (max-width: 767px) {
    .timeline {
      width: 100%;
      padding-bottom: 0;
    }
    h1 {
      font-size: 32px;
      text-align: center;
    }
    .timeline:before {
      left: 20px;
      height: 100%;
    }
    .timeline ul li:nth-child(odd),
    .timeline ul li:nth-child(even) {
      width: 100%;
      text-align: left;
      padding-left: 50px;
      padding-bottom: 50px;
    }
    .timeline ul li:nth-child(odd):before,
    .timeline ul li:nth-child(even):before {
      top: -18px;
      left: 16px;
    }
    .timeline ul li:nth-child(odd) .time,
    .timeline ul li:nth-child(even) .time {
      top: -30px;
      left: 50px;
      right: inherit;
    }
  }
</style>

<div class="timeline">
  <ul>
    <li>
      <div class="content">
        <h3>Graduated from Methodist College Kuala Lumpur (MCKL)</h3>
        <p>
          Completed the Cambridge International AS & A Levels, achieving 90+
          for all subjects of study (Maths, Further Maths, Economics and Physics).
        </p>
        <p>
          I was also being awarded Outstanding Cambridge Learner Award for obtaining the
          highest mark in the world for Maths subject.
        </p>
      </div>
      <div class="time">
        <h4>July 2016</h4>
      </div>
    </li>
    <li>
      <div class="content">
        <h3>Started my first job at Walter and Eliza Hall Institute of Medical Research (WEHI) </h3>
        <p>
          As part of the Undergraduate Research Opportunities Program (UROP) offered Biomedical
          Research Victoria, I started my first role at WEHI as a bioinformatics research assistant.
          My project was mainly about manipulating, analysing and deriving insights from methylation
          data at genomic level.
        </p>
        <p>
          This is where I developed my skills in Python, R and a lot of shell scripting.
        </p>
      </div>
      <div class="time">
        <h4>June 2018</h4>
      </div>
    </li>
    <li>
      <div class="content">
        <h3>Completed Bachelor's degree in Computer Science & Data Science from University of Melbourne</h3>
        <p>
          Graduated from UniMelb with a weighted average mark of 87.8. I was honoured
          to be awarded the Dean's award twice over the course of my studies.
        </p>
        <p>
          Some of the interesting modules I took are
          <a href="https://handbook.unimelb.edu.au/subjects/comp30027">Machine Learning</a>,
          <a href="https://handbook.unimelb.edu.au/subjects/mast30027">Modern Applied Statistics</a>,
          <a href="https://handbook.unimelb.edu.au/subjects/swen30006">Software Modelling and Design</a> and
          <a href="https://handbook.unimelb.edu.au/subjects/comp30022">IT Project</a>.
        </p>
      </div>
      <div class="time">
        <h4>Dec 2019</h4>
      </div>
    </li>
    <li>
      <div class="content">
        <h3>Started a new role at Quantium as Associate Software Engineer</h3>
        <p>
          As part of the graduate program, I had the opportunity to work with big data technologies,
          front-backend development as well as DevOps engineering.
        </p>
      </div>
      <div class="time">
        <h4>Feb 2020</h4>
      </div>
    </li>
    <li>
      <div class="content">
        <h3>Promotion to Software Engineer</h3>
        <p>
          Increased responsibilities and autonomy at work. My work focused more
          heavily on infrastructure automation, containerisation, CI/CD, general
          DevOps engineering and cloud architecture.
        </p>
      </div>
      <div class="time">
        <h4>Aug 2021</h4>
      </div>
    </li>
    <div style="clear: both"></div>
  </ul>
</div>

<br>

# More? Read here

- [Resume]({{ site.url }}/resume)
- [Academic transcript]({{ site.url }}/academic-transcript/)
- [What others think of me]({{ site.url }}/references/)
- [LinkedIn](https://www.linkedin.com/in/xuanken-t-485a8b171)
