---
permalink: /education/
title: ""
author_profile: true
redirect_from:
  - /education.html
---

<style>
/* Center the card horizontally on the page */
.education-card {
  border: 1px solid #E0E0E0;
  border-radius: 12px;
  padding: 20px;
  max-width: 400px;
  background-color: #f9f9f9;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  margin: 0 auto; /* Center the card horizontally */
}

/* Center the heading within the card */
.education-card h2 {
  display: flex;
  align-items: center;
  /*justify-content: center; !* Center the content horizontally *!*/
  font-size: 1.5em;
  margin-bottom: 1em;
  color: #333;
}

.education-card h2 i {
  font-size: 1.3em;
  margin-right: 10px;
  color: #666;
}

.education-entry {
  display: flex;
  align-items: center;
  margin-bottom: 1em;
}

.education-entry img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  margin-right: 15px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.2);
}

.education-entry div {
  display: flex;
  flex-direction: column;
}

.education-entry .institution {
  font-weight: bold;
  font-size: 1em;
  color: #333;
}

.education-entry .degree, .education-entry .dates {
  font-size: 0.9em;
  color: #888;
}

.education-entry .dates {
  margin-top: 3px;
}
</style>

<div class="education-card">
  <h2><i class="fas fa-briefcase"></i> Education</h2>

  <div class="education-entry">
    <img src="/images/uva.png" alt="University of Virginia Logo">
    <div>
      <div class="institution">University of Virginia</div>
      <div class="degree">Undergraduate Student</div>
      <div class="dates">2021.08 — Present</div>
    </div>
  </div>

  <div class="education-entry">
    <img src="/images/shiyan.png" alt="shiyan Logo">
    <div>
      <div class="institution">The Experimental High School Attached to Beijing Normal University</div>
      <div class="degree">High School Student</div>
      <div class="dates">2018 — 2021</div>
    </div>
  </div>
</div>
