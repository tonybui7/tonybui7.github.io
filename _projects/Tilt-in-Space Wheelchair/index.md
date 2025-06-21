---
layout: post
title: Low-cost, Locally Manufacturable Tilt-in-Space Wheelchair
description: 
    Designed and validated a Tilt-in-Space wheelchair for use by Tanzanians with severe postural disabilities. This project was undertaken alongside five mechanical engineering undergraduate seniors, in two quarters (six months), with my role being the documentation focal point and validation lead! Our team worked with Kyaro Assistive Tech, a Tanzanian Non-Governmental Organization based in Arusha, Tanzania, making user-specific assistive devices accessible for East Africans.<br><br>
    Our final wheelchair design has a final BOM cost of $50, which is drastically under our cost specification of $70 set by Kyaro Assistive Tech. Furthermore, our design exceeded all user and engineering requirements, making this wheelchair highly leveragable in the rugged Tanzanian environment. This wheelchair is inclusive of the potential use cases of 3.4 million East Africans with mobility disabilities. Our design was received highly by Stanford's Mechanical Engineering department and was subsequently published in the academic library (please feel free to check it out)!
skills: 
  - Structural analysis and Simulation
  - Rapid, Iterative Prototyping
  - CAD (Fusion 360)
  - Failure Mode and Effects Analysis (FMEA)
  - Design for Manufacturing and Cost Optimization
  - Engineering Communications (Presentations, Documentation)
  - Metal Forming, Welding

main-image: /project2.jpg
---

---
## Published Project Report
[Developing a Low-Cost Tilting Seat for Tanzanian Wheelchairs](https://searchworks.stanford.edu/view/tj176jm1879)
---

---
## Pictures and Videos
{% include youtube-video.html id="CFADE6lFOnU" autoplay= "false"%}
<span style="font-size: 12px">"CAD Animation of Locking Mechanism" from https://youtu.be/CFADE6lFOnU/</span><br>
{% include youtube-video.html id="usTRCJulgL8" autoplay= "false"%}
<span style="font-size: 12px">"CAD Animation of Tilt-in-Space Function" from https://youtu.be/CFADE6lFOnU/</span><br>
{% include image-gallery.html images="chair.jpg" width="351" height="466" %}
<span style="font-size: 12px">"Hero Shot of Tilt-in-Space Prototype"</span><br>
{% include image-gallery.html images="weldedchair.jpg" width="351" height="468" %}
<span style="font-size: 12px">"Welded Chair Frame"</span><br>
---

---
## About This Project!
For my senior capstone project in Mechanical Engineering at Stanford University, our team developed an affordable and locally manufacturable tilt-in-space wheelchair specifically designed for users in Tanzania. Working in collaboration with Kyaro Assistive Technology, a Tanzanian NGO, we aimed to alleviate issues related to prolonged sitting discomfort and pressure sores experienced by wheelchair users, while addressing the physical strain on caregivers during repositioning tasks.
<br><br>
Our wheelchair consists of two main components: an external frame and a tilting seat assembly. During our project specification phase, we conducted market research, user surveys, and literature reviews to establish a set of prioritized user/engineering requirements against which our designs were constantly tested. The seat is designed to pivot around ball bearings strategically placed near the user's center of mass, significantly reducing the caregiver's input force required to tilt the chair. We conducted a statistical analysis, using national aviation datasets, to determine three centers of mass for which we parametrically pre-set our wheelchair designs to be fabricated for. A carefully engineered latch mechanism, operated by recycled bicycle brake handles and cables, securely locks the seat at predefined angles (0°, 15°, 30°, and 45°), providing precise control over user posture and comfort.
<br><br>
In the engineering phase, we utilized finite element analysis (FEA) simulations to ensure the structural integrity of critical components like pivot points under a 185 lb static load, resulting in a high safety factor of 8.3. Extensive Design Failure Mode and Effects Analysis (DFMEA) was conducted, identifying potential high-risk failure points such as joint failures in the backrest and weld failures in the external frame. To address these risks, we conducted rigorous physical testing, including cyclic load tests (50 cycles at 185 lbs) and validation of the locking mechanism's reliability across multiple trials. The input force required to actuate the tilt mechanism was experimentally validated to remain below our target of 85 N, with an actual measured maximum of 82.3 N.
<br><br>
Material and fabrication considerations were integral to our design. We constructed the prototype using aluminum extrusion and JB Weld for initial validation, later transitioning to locally available steel pipes and traditional welding techniques (Oxy-Acetylene and MIG welding) in Tanzania for final production. This approach ensured both affordability and manufacturability, confirmed by our prototype’s total material cost of $47.33, well below our initial $70 budget constraint.
<br><br>
Overall, our project successfully demonstrated a rigorous value engineering process incorporating robust analysis, practical validation, and thoughtful design for manufacturability. The resulting product significantly enhances comfort, usability, and accessibility for Tanzanian wheelchair users, aligning effectively with local manufacturing capabilities.
<br><br>






# Header 1 
Used for the title (already generated automatically at the top)
## Header 2  
Use this for the header of each section
### Header 3 
Use this to have subsection if needed


## Embedding images 
### External images
{% include image-gallery.html images="https://flic.kr/p/2rceJqK" height="400"%}
<span style="font-size: 12px">"Picture of Tilt-in-Space Wheelchair Proof of Concept" from https://flic.kr/p/2rceJqK/</span>  
You can put in multiple entries. All images will be at a fixed height in the same row. With smaller window, they will switch to columns.  

### Embeed images
{% include image-gallery.html images="project2.jpg" height="400" %} 
place the images in project folder/images then update the file path.   


## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="CFADE6lFOnU" autoplay= "false"%}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header

