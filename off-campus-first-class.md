---
layout: default
title: First Class
---
<div style="flex: 2; min-width: 400px; text-align: justify;">
<h2> First Class </h2>

After my first day of getting to know my students, I had my first teaching responsibility. I was tasked to discuss the endocrine system, a topic which I only had a vague remembrance of. I studied well into the night before, and I felt myself ready to teach the topic. 
<br>
<br>
9:30 A.M., my mentor had told me to conduct my class with Cabahug inside the computer laboratory. They arrived, and settled themselves, and I didn’t have to manage them all too much, though that’s probably because Ma’am Guiroy was at the back, together with the other faculty members. I stood in front of them all, staring at the 40+ students, and the 4 teachers at the back filled me with a nagging feeling of wanting to prove myself to be a good teacher. I was confident in my mastery of the content, but what I hadn’t mastered was the delivery. It was too teacher-centered. From the fear of not wanting to look stupid in front, I had focused too much on giving information that I had forgotten in what I prided myself in: “Questioning”.
<br>
<br>
10:15 A.M. and my mentor and I went into Ibona. Ma’am Guiroy wanted to teach in Ibona herself, though It was probably to show me how she usually taught, and I was amazed. Before we entered the classroom, she stood by the door in silence. Surprisingly, the students knew what they needed to do. They arranged themselves, and picked up the pieces of trash on the floor. Only after they settled down did Ma’am Guiroy enter the room, and started to teach. Contrary to me, my mentor focused on questioning the students, on turning them into active learners, and making them pay attention. Although I did think that it was too time consuming, the strategy was definitely effective. I was inspired, and I had the idea of emulating her.
<br>
<br>
11:00 A.M., and Ma’am Guiroy still taught in Yap herself. It was a similar experience as in Ibona. 
<br>
<br>
11:45, Grade 10 - Montalban, I finally got my time. I followed what Ma’am Guiroy had shown in the last sections. I didn’t come in until the class was settled, and when I did, I modified my way of teaching. A combination of teacher-centered and learner-centered teaching was what I came up with to solve the issue of time management, and I saw immediate improvement. I was able to make the students participate more, and at the same time, I was able to cover much more of the topic. The class ended at 12:30 on a positive note, and we were on track to finishing in the following day.
<br>
<br>
My 15-minute lunch break was spent on me thinking on how to better conduct the classes, incorporating the socratic method better, but still getting things done on time.
<br>
<br>
12:45 P.M. rolled around, and I was to teach in Villanueva… which, once again, still had few students by the time I went in. I started teaching nonetheless. Everytime a late student arrived and went inside the room, I made sure to set a rule that unless they couldn’t give me a valid reason, or answer one of my questions, they would remain standing. That day, more than half of the students were late, but I left with all of them sitting down. 
<br>
<br>
Finally, in my final class, Rago, we breezed through the material as they had already discussed the topic by group. My role was just on affirming or correcting what they had learned previously from the presenters. 
<br>
<br>
After all my classes, I went to Ma’am Guiroy to ask for her feedback, and the main thing he noticed about me was the first impression that I had set earlier that morning—my teacher-centeredness. She was able to deduce why I had taught it that way, correctly guessing that I was in a rush to finish the material. She emphasized that although finishing the material is good, it’s better that the students are able to follow along, and internalize what I’m teaching. 
<br>
<br>
That day, I realized that engaging the students will allow their brains to internalize the lesson better, and that rushing just to finish the material is never a good strategy.
</div>
<br>

<div class="carousel" style="max-width: 600px; position: relative;">
    <img class="carousel-slide" src="{{ '/assets/images/off-campus/off-campus-class.jpg' | relative_url }}" style="width: 100%;">
    <img class="carousel-slide" src="{{ '/assets/images/off-campus/off-campus-class2.jpg' | relative_url }}" style="width: 100%;display: none;">
    <img class="carousel-slide" src="{{ '/assets/images/off-campus/off-campus-class3.jpg' | relative_url }}" style="width: 100%;display: none;">
    <img class="carousel-slide" src="{{ '/assets/images/off-campus/off-campus-class4.jpg' | relative_url }}" style="width: 100%;display: none;">

  
  <button onclick="shiftSlide(-1)" style="position: absolute; top: 50%; left: 0;">&#10094;</button>
  <button onclick="shiftSlide(1)" style="position: absolute; top: 50%; right: 0;">&#10095;</button>
</div>

<script>
  let index = 1;
  function shiftSlide(n) {
    const slides = document.getElementsByClassName("carousel-slide");
    index += n;
    if (index > slides.length) { index = 1 }
    if (index < 1) { index = slides.length }
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    slides[index - 1].style.display = "block";
  }
</script>