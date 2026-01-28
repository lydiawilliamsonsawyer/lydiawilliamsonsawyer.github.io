---
layout: default
---

## Feel Tank

The Feel Tank begins from the premise that our feelings are socially and historically contingent, as opposed to being entirely personal or biological. As a result, to reflect on and recognise the socio-political significance and our feelings and make sense of them within broader social systems can be a politically generative and mobilising act. 

Inspired by the [Feel Tank Chicago](https://chronicle.uchicago.edu/071018/political-feeling.shtml) of the early 2000s, my aim is to reimagine the Feel Tank in response to the unstable and crisis-ridden political conditions of the present day. The Feel Tank counters the individualising logics of late-stage neoliberal capitalism which tell us that our feelings are to be independently managed, worked on, or ‘fixed’, a discourse largely pushed through the self-help industry. But what if our so-called negative feelings, such as hopelessness and despair, were not signs of individual defect or flawed psyches, but grounds for political awareness and mobilisation? 

The Feel Tank is a space to feel, reflect on, and come together in response to the complex, contradictory and perhaps nonsensical nature of how we feel living in precarious and uncertain times. Rather than the emphasis being on how we can think and rationalise a better world into existence, the Feel Tank is a space to embrace our complicated feelings in the hopes that by dwelling in what is troubling, contradictory, or nonsensical we can make better sense of how social systems permeate the ‘personal’ and positioning feeling as a political act. In this way, the Feel Tank is similar to the consciousness-raising groups of 1960s and 70s feminists in the UK and US, which sought to politicise women’s personal and private matters. 

I am particularly interested in using the Feel Tank to explore incongruent and ambivalent feelings, for which we do not inherit a cultural ‘script’ to make sense of. This focus is inspired by Feel Tank Chicago member Lauren Berlant’s work on the political possibilities of an ambivalence. They write how ambivalence stem froms the tension between learned commitments to conventional ideals combined with the felt recognition of disappointment and disenchantment. At a critical point of social transformation, the Feel Tank is an invitation to sit with what feels as though it does not make sense under current social systems and paradigms, in the hope that doing so will allow us to feel the possibility of a new world.

The last Feel Tank I facilitated was at the MayDay Rooms in October 2025 during which I gave an introduction to the history and values of examining the socio-political nature of feelings and a group of us then explored how ambivalence arises in our lives in relation to work, technology, relationships, and well-being. These are some photos and reflections from the workshop:

<style>
.slideshow-container {
  max-width: 700px;
  position: relative;
  margin: 40px auto;
  height: 450px;
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
  width: auto;
  height: auto;
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
    <img src="/assets/ambiv.jpeg" alt="Photo 1">
  </div>
  
  <div class="slide">
    <img src="/assets/work.jpeg" alt="Photo 2">
  </div>
  
  <div class="slide">
    <img src="/assets/fam.jpeg" alt="Photo 3">
  </div>

  <div class="slide">
    <img src="/assets/IMG_8877.jpeg" alt="Photo 4">
  </div>

  <div class="slide">
    <img src="/assets/IMG_8878.jpeg" alt="Photo 5">
  </div>

  <div class="slide">
    <img src="/assets/IMG_8879.jpeg" alt="Photo 6">
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

