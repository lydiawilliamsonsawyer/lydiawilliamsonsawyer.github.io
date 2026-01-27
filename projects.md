---
layout: default
---

## Feel Tank

Inspired by the early 2000s [Feel Tank Chicago](https://chronicle.uchicago.edu/071018/political-feeling.shtml), the Feel Tank begins from the recognition that our feelings are socially and historically contingent, as opposed to being universal or purely individual or biological. Neoliberal capitalism encourages subjects to embrace the individualising ideals of autonomy and self-optimisation through engaging with what Arlie Hochschild (1979) terms 'emotion work', working to manage our feelings and emotions in order to fit in with and reproduce dominant scripts about how we should feel. This operates as a form of social reproduction. Sara Ahmed's (2010) concept of 'happiness scripts' is also useful to explain the narratives we are sold concerning what feelings are culturally permissible and which feelings are not.

The Feel Tank offers a space to express, reflect on, and politicise the complexity, ambivalence, and perhaps nonsensical nature of how we feel living in precarious and uncertain times. Similar to the consciousness-raising groups of 1960s and 70s feminists in the UK and US, the Feel Tank aims to enable a better understanding of how oppressive social systems permeate the personal and position feelings as potential sites for political awareness and mobilisation. 

I am particularly interested in using the Feel Tank form to explore incongruent feelings - ambivalence, dissatisfaction, disappointment, confusion, despair, uneasiness - which I believe we lack, in the UK, an adequate societal infrarstructure to politically engage with. Self-help and therapy, if available, may be useful tools for dealing with incongruent feelings, but I believe that the process of collectively exploring feelings which do not fit into dominant cultural paradigms can be politically mobilising and a meeans to feel beyond what is deemed possible. 

The last Feel Tank I held was in October 2025, as part of Anti-University Festival, during which a group of 14 of us explored where in our lives we feel ambivalence, dissatisfaction and disappointment. These are some of the reflections from the workshop:


<style>
.slideshow-container {
  max-width: 900px;
  position: relative;
  margin: 40px auto;
  height: 600px;
}

.slide {
  display: none;
  width: 100%;
  height: 100%;
}

.slide.active {
  display: flex;
  align-items: center;
  justify-content: center;
}

.slide img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: auto;
  padding: 20px;
  color: white;
  background-color: rgba(0,0,0,0.5);
  font-weight: bold;
  font-size: 30px;
  border: none;
  user-select: none;
  z-index: 10;
}

.next {
  right: 0;
}

.prev {
  left: 0;
}

.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}
</style>

<div class="slideshow-container">
  <div class="slide active">
    <img src="/assets/IMG_8870.jpeg" alt="Photo 1">
  </div>
  
  <div class="slide">
    <img src="/assets/IMG_8872.jpeg" alt="Photo 2" style="transform: rotate(270deg);">
  </div>
  
  <div class="slide">
    <img src="/assets/IMG_8869.jpeg" alt="Photo 3" style="transform: rotate(90deg);">
  </div>
  
  <div class="slide">
    <img src="/assets/IMG_8874.jpeg" alt="Photo 4" style="transform: rotate(90deg);">
  </div>

  <div class="slide">
    <img src="/assets/IMG_8877.jpeg" alt="Photo 5">
  </div>

  <div class="slide">
    <img src="/assets/IMG_8878.jpeg" alt="Photo 6">
  </div>

  <div class="slide">
    <img src="/assets/IMG_8879.jpeg" alt="Photo 7">
  </div>

  <button class="prev" onclick="changeSlide(-1)">❮</button>
  <button class="next" onclick="changeSlide(1)">❯</button>
</div>

<script>
let slideIndex = 0;

function changeSlide(n) {
  const slides = document.querySelectorAll('.slide');
  slides[slideIndex].classList.remove('active');
  
  slideIndex += n;
  
  if (slideIndex >= slides.length) {
    slideIndex = 0;
  }
  if (slideIndex < 0) {
    slideIndex = slides.length - 1;
  }
  
  slides[slideIndex].classList.add('active');
}
</script>

If you also share this interest, feel free to email me as I am keen to chat with fellow feel-ers. 

## Wired Feelings

Building on explorations with the Feel Tank, Wired Feelings applies the consciousness-raising framework to interrogate affective entanglements with digital technologies. I am interested in examining how these technologies mediate and shape our feelings, with the aim of critically assessing how state and corporate actors use technologies to monitor, manipulate, and commodity feelings.

I am keen to explore the following questions:

How are our feelings mediated through algorithmically structured digital platforms?  
What role does this mediation play in the broader shift towards tech-authoritarianism? 
What is the impact on digital activism when our emotions and feelings are mediated via social media platforms?

<iframe src="/wired-feelings-mindmap.html" style="width: 100%; height: 520px; border: none;"></iframe>
