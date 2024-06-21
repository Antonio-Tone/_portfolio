<template>
    <div class="row archive">
     <div class="col-12 col-md-6 badges mt-4">
         
         <h1 class="heading d-flex justify-content-center my-4">Badges & Achievements</h1>
         <div class="d-flex justify-content-center next mb-3">
           <button class="toggle" @click="show(1)">Cisco Badges</button>
         <button class="toggle" @click="show(2)">Certificate</button>
         <button class="toggle AS" @click="show(3)">C++</button>
         <button class="toggle" @click="show(4)">Python Cert</button>
       </div>
         <div class="prod" v-show="visibleElement === 1">
           <p class="options d-flex justify-content-start"></p>
           <div>
             <div class="card">
               <img
                 class="img"
                 src="https://i.ibb.co/561TyTX/Introduction-to-Cybersecurity-Badge20240612-8-x6nfff.jpg"
                 alt=""
               />
               <div class="textBox">
                 <div class="d-flex justify-content-center">
                   <a href="https://www.credly.com/users/antonio-tone/badges"
                   target="_blank"
                     ><button class="toggle linkBg">
                       <img
                         class="links"
                         src="https://i.ibb.co/4TdQ7rR/output-onlinegiftools-3.gif"
                         alt=""
                       /></button
                   ></a>
                 </div>
               </div>
               </div>
           </div>
         
         </div>
         <div class="prod" v-show="visibleElement === 2">
           <p class="options d-flex justify-content-start"></p>
           <div>
             <div class="card">
               <img
                 class="img"
                 src="https://i.ibb.co/jJH5zjr/Capture.png"
                 alt=""
               />
               <div class="textBox">
                 <div class="d-flex justify-content-center">
                   <a href="\files\Antonio Tone LC Cerificate.pdf"
                   download
                     ><button class="toggle linkBg">
                       <img
                         class="links"
                         src="https://i.ibb.co/XyRvjfV/output-onlinegiftools.gif"
                         alt=""
                       /></button
                   ></a>
                 </div>
               </div>
               </div>
 
           </div>
         
         </div>
         <div class="prod" v-show="visibleElement === 3">
           <p class="options d-flex justify-content-start"></p>
           <div>
             <div class="card">
               <img
                 class="img"
                 src="https://i.ibb.co/267MyVz/c.png"
                 alt=""
               />
               <div class="textBox">
                 <div class="d-flex justify-content-center">
                   <a href="\files\C++.pdf"
                   download
                     ><button class="toggle linkBg">
                       <img
                         class="links"
                         src="https://i.ibb.co/XyRvjfV/output-onlinegiftools.gif"
                         alt=""
                       /></button
                   ></a>
                 </div>
               </div>
               </div>
 
           </div>
         
         </div>
         <div class="prod" v-show="visibleElement === 4">
           <p class="options d-flex justify-content-start"></p>
           <div>
             <div class="card">
               <img
                 class="img"
                 src="https://i.ibb.co/JR66vmL/Python-Certificate.png"
                 alt=""
               />
               <div class="textBox">
                 <div class="d-flex justify-content-center">
                 <a href="\files\pythonCert.pdf"
                   download
                     ><button class="toggle linkBg">
                       <img
                         class="links"
                         src="https://i.ibb.co/XyRvjfV/output-onlinegiftools.gif"
                         alt=""
                       /></button
                   ></a>
                 </div>
               </div>
               </div>
 
           </div>
         
         </div>
     </div>
     <div class="col-12 col-md-6 resume mt-4">
       <div class="vl"></div>
         <div>
       <h1 class="heading d-flex justify-content-center my-4 ">Resume</h1>
       <div class="timeline mt-5">
         <div
           v-for="(entry, index) in resumeEntries"
           :key="entry.id"
           :class="['container', index % 2 === 0 ? 'left' : 'right']"
         >
           <div class="content">
             <h2 class="year">{{ entry.duration }}</h2>
             <h4 class="place">{{ entry.institution }}</h4>
             <p class="dis">{{ entry.description }}</p>
           </div>
         </div>
       </div>
     </div>
     </div>
    </div>
   </template>
   
   <script>
   export default {
     name: 'Resume',
     data() {
       return {
         visibleElement: 1,
         resumeEntries: [
           {
             id: 1,
             duration: '2015-2020',
             institution: 'Sarepta High School',
             description: "I graduated in 2020 with a bachelor's pass."
           },
           {
             id: 2,
             duration: '2021-2023',
             institution: 'Stodels Garden Centre',
             description: "worked as a Sales Consultant in 2021 and then continued as a Delivery driver in 2022 until 2023"
           },
           {
             id: 3,
             duration: 'April 2023- Sept 2023',
             institution: 'Life Choices Coding Academy',
             description: "Successfully completed my Fullstack Web Development Course."
           },
           {
             id: 4,
             duration: 'Oct 2023 - Current',
             institution: 'LC Studio Intern',
             description: "Working on real world projects with a team of senior developers and project managers."
           }
         ]
       };
     },
     methods: {
     show(elementNumber) {
       this.visibleElement = elementNumber;
     },
 }
   };
   </script>
   
   <style scoped>
   .heading {
     text-align: center;
     margin: 20px 0;
     color:#80c047;
     filter: drop-shadow(4px 9px 5px black);
   }
    /* styling of timeline */
   .timeline {
     position: relative;
     max-width: 800px;
     height: 500px;
     margin: 0 auto;
     margin-bottom: 120px;
     filter: drop-shadow(4px 9px 5px black);
 
   }
   
   .timeline::after {
     content: '';
     position: absolute;
     width: 6px;
     background-color: #80c047;
     top: 0;
     bottom: 0;
     left: 50%;
     margin-left: -3px;
   }
   
   .container {
     padding: 5px 40px;
     position: relative;
     background-color: inherit;
     width: 50%;
   }
   
   .container::after {
     content: '';
     position: absolute;
     width: 20px;
     height: 20px;
     right: -17px;
     background-color: #80c047;
     border: 4px solid #aed5d5;
     top: 15px;
     border-radius: 50%;
     z-index: 1;
   }
   
   .left {
     left: -25.9%;
   }
   
   .right {
     left: 25.9%;
   }
   
   .left::before {
     content: " ";
     height: 0;
     position: absolute;
     top: 22px;
     width: 0;
     z-index: 1;
     right: 30px;
     border: medium solid #80c047;
     border-width: 10px 0 10px 10px;
     border-color: transparent transparent transparent #80c047;
   }
   
   .right::before {
     content: " ";
     height: 0;
     position: absolute;
     top: 22px;
     width: 0;
     z-index: 1;
     left: 30px;
     border: medium solid white;
     border-width: 10px 10px 10px 0;
     border-color: transparent #80c047 transparent transparent;
   }
   
   .right::after {
     left: -16px;
   }
   
   .content {
     padding: 0.3px 3px;
     background-color: #313131 !important;
     position: relative;
     border-radius: 6px;
   }
   .year{
   font-size: 25px;
   }
   .place{
    color: #80c047;
 font-size: 18px;
   }
   .dis{
 font-size: 14px;
   }
 
   .toggle {
   filter: drop-shadow(4px 9px 5px black);
   font-size: 15px;
   margin: 5px;
   padding: 2px;
   width: 100px;
   border-radius: 30px;
   color: aliceblue;
   background-color: #80c047;
   border: none !important;
 }
 
 .toggle:focus {
   background: #6190e8;
   background: -webkit-linear-gradient(to right, #a7bfe8, #6190e8);
   background: linear-gradient(to right, #a7bfe8, #6190e8);
   color: white;
   animation: outerglow 1s alternate infinite cubic-bezier(0.65, 0.05, 0.36, 1);
 }
 @keyframes outerglow {
   0% {
     box-shadow: 0px 0px 0px #1ce278;
   }
   100% {
     box-shadow: 0px 0px 15px #1ce278;
   }
 }
 .lang {
   height: 25px;
   margin-right: 3px;
 } 
 /* badges and a */
 .card {
   width: 600px;
   height: 330px;
   background: #313131;
   border-radius: 20px;
   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: center;
   color: white;
   transition: 0.2s ease-in-out;
 }
 .links {
   height: 35px;
 }
 .linkBg {
   background-color: #313131 !important;
   transition:0.5s ease-in-out;
 }
 .linkBg:hover{
   background-color:#1ce278 !important;
 }
 .textBox {
   opacity: 0;
   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: center;
   gap: 15px;
   transition: 0.2s ease-in-out;
 }
 
 .textBox > .text {
   font-weight: bold;
 }
 
 .textBox > .head {
   font-size: 20px;
 }
 
 .textBox > .price {
   font-size: 17px;
 }
 
 .textBox > span {
   font-size: 12px;
   color: lightgrey;
 }
 
 .card:hover > .textBox {
   opacity: 1;
 }
 
 .card:hover > .img {
   height: 100%;
   filter: blur(7px);
 }
 .card:hover {
   animation: anim 3s infinite;
 }
 
 @keyframes anim {
   0% {
     transform: translateY(0);
   }
 
   50% {
     transform: translateY(-20px);
   }
 
   100% {
     transform: translateY(0);
   }
 }
 
 .img {
     filter: drop-shadow(0px 20px 10px black);
   border-radius: 20px;
   width: 100%;
   height:100%;
   position: absolute;
   transition: 0.2s ease-in-out;
 }
 .description{
   filter: drop-shadow(0px 20px 10px black);
 
 }
 
 .badges{
   min-width: 50%;
   display: flex;
   flex-direction: column;
   align-items:center;
   justify-content: start;
 
 
 }
 
 .resume{
   min-width: 30% !important;
   position: relative;
 }
 .vl {
   border-left: 2px solid #646464;
   height: 550px;
  position: absolute;
  top:5%;
 }
 
 
 
 
 
 
 
 
 /* responsiveness done below */
 
  @media screen and (max-width: 450px){
   .toggle {
     margin: 5px;
     padding: 6px;
     width: 70px;
     font-size: 10px;
   }
 
   .card,
   .img {
     width: 300px !important;
     height: 310px;
   }
   .description > h4{
   filter: drop-shadow(0px 20px 10px black);
   font-size: 13px;
 
 }
  }
  @media screen and (min-width: 450.9px) and (max-width: 650.9px){
   .heading {
     text-align: center;
     margin: 20px 0;
   }
 
 /* styling of card */
 
 .toggle {
     margin: 5px;
     padding: 8px;
     width: 80px;
     font-size: 12px;
   }
 
   .card,
   .img {
     width: 480px !important;
     height: 310px;
   }
 .description > h4{
   filter: drop-shadow(0px 20px 10px black);
   font-size: 16px;
 
 }
 
  }
  @media screen and (min-width: 768px) and (max-width: 991.9px){
   .badges{
     min-width:100%;
   }
   .resume{
     min-width:100% !important;
 
   }
 
 
    .heading {
     text-align: center;
     margin: 20px 0;
   }
   .vl{
     display: none !important;
   }
 
 /* styling of card */
 
 .card {
   width: 600px;
   height: 330px;
   background: #313131;
   border-radius: 20px;
   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: center;
 color: white;
 transition: 0.2s ease-in-out;
 }
 
 .img {
   filter: drop-shadow(0px 20px 10px black);
 border-radius: 20px;
 width: 100%;
 height:100%;
 position: absolute;
 transition: 0.2s ease-in-out;
 }
 .description > h4{
 filter: drop-shadow(0px 20px 10px black);
 font-size: 16px;
 
 }
 
   /* styling of timeline */
   .timeline {
     position: relative;
     max-width: 800px;
     height: 500px;
     margin: 0 auto;
     margin-bottom: 120px;
     filter: drop-shadow(4px 9px 5px black);
 
   }
   
   .timeline::after {
     content: '';
     position: absolute;
     width: 6px;
     background-color: #80c047;
     top: 0;
     bottom: 0;
     left: 50%;
     margin-left: -3px;
   }
   
   .container {
     padding: 5px 40px;
     position: relative;
     background-color: inherit;
     width: 50%;
   }
   
   .container::after {
     content: '';
     position: absolute;
     width: 20px;
     height: 20px;
     right: -17px;
     background-color: #80c047;
     border: 4px solid #314a5e;
     top: 15px;
     border-radius: 50%;
     z-index: 1;
   }
   
   .left {
     left: -25.9%;
   }
   
   .right {
     left: 25.9%;
   }
   
   .left::before {
     content: " ";
     height: 0;
     position: absolute;
     top: 22px;
     width: 0;
     z-index: 1;
     right: 30px;
     border: medium solid #80c047;
     border-width: 10px 0 10px 10px;
     border-color: transparent transparent transparent #80c047;
   }
   
   .right::before {
     content: " ";
     height: 0;
     position: absolute;
     top: 22px;
     width: 0;
     z-index: 1;
     left: 30px;
     border: medium solid white;
     border-width: 10px 10px 10px 0;
     border-color: transparent #80c047 transparent transparent;
   }
   
   .right::after {
     left: -16px;
   }
   
   .content {
     padding: 0.3px 3px;
     background-color: #80c047;
     position: relative;
     border-radius: 6px;
   }
   .year{
   font-size: 25px;
   }
   .place{
 font-size: 18px;
   }
   .dis{
 font-size: 14px;
   }
 
  }
  @media screen and (min-width:992px) and (max-width:1023.9px){
   .heading {
     text-align: center;
     margin: 20px 0;
   }
 
 /* styling of card */
 
 .card {
   width: 450px;
   height: 350px;
   background: #313131;
   border-radius: 20px;
   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: center;
 color: white;
 transition: 0.2s ease-in-out;
 }
 
 .img {
   filter: drop-shadow(0px 20px 10px black);
 border-radius: 20px;
 width: 100%;
 height:100%;
 position: absolute;
 transition: 0.2s ease-in-out;
 }
 .description > h4{
 filter: drop-shadow(0px 20px 10px black);
 font-size: 16px;
 
 }
 
   /* styling of timeline */
 .timeline {
   position: relative;
   max-width: 680px !important;
   height: 500px;
   margin: 0 auto;
   margin-bottom: 120px;
   filter: drop-shadow(4px 9px 5px black);
 
 }
 
 .timeline::after {
   content: '';
   position: absolute;
   width: 6px;
   background-color: #80c047;
   top: 0;
   bottom: 0;
   left: 50%;
   margin-left: -3px;
 }
 
 .container {
   padding: 1px 20px;
   position: relative;
   background-color: inherit;
   width: 50%;
 }
 
 .container::after {
   content: '';
   position: absolute;
   width: 20px;
   height: 20px;
   right: -17px;
   background-color: #80c047;
   border: 4px solid #314a5e;
   top: 15px;
   border-radius: 50%;
   z-index: 1;
 }
 
 .left {
   left: -25.9%;
 }
 
 .right {
   left: 25.9%;
 }
 
 .left::before {
   content: " ";
   height: 0;
   position: absolute;
   top: 22px;
   width: 0;
   z-index: 1;
   right: 30px;
   border: medium solid #80c047;
   border-width: 10px 0 10px 10px;
   border-color: transparent transparent transparent #80c047;
 }
 
 .right::before {
   content: " ";
   height: 0;
   position: absolute;
   top: 22px;
   width: 0;
   z-index: 1;
   left: 30px;
   border: medium solid white;
   border-width: 10px 10px 10px 0;
   border-color: transparent #80c047 transparent transparent;
 }
 
 .right::after {
   left: -16px;
 }
 
 .content {
   padding: 0.1px 4px;
   background-color: #80c047;
   position: relative;
   border-radius: 6px;
 
 }
 .year{
 font-size: 20px;
 }
 .place{
 font-size: 16px;
 }
 .dis{
 font-size: 13px;
 }
  }
 
 
  @media screen and (min-width: 1024px) and (max-width: 1200px){
   .heading {
     text-align: center;
     margin: 20px 0;
   }
 
 /* styling of card */
 
 .card {
   width: 450px;
   height: 350px;
   background: #313131;
   border-radius: 20px;
   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: center;
   color: white;
   transition: 0.2s ease-in-out;
 }
 
 .img {
     filter: drop-shadow(0px 20px 10px black);
   border-radius: 20px;
   width: 100%;
   height:100%;
   position: absolute;
   transition: 0.2s ease-in-out;
 }
 .description > h4{
   filter: drop-shadow(0px 20px 10px black);
   font-size: 16px;
 
 }
 
    /* styling of timeline */
   .timeline {
     position: relative;
     max-width: 680px !important;
     height: 500px;
     margin: 0 auto;
     margin-bottom: 120px;
     filter: drop-shadow(4px 9px 5px black);
 
   }
   
   .timeline::after {
     content: '';
     position: absolute;
     width: 6px;
     background-color: #80c047;
     top: 0;
     bottom: 0;
     left: 50%;
     margin-left: -3px;
   }
   
   .container {
     padding: 1px 20px;
     position: relative;
     background-color: inherit;
     width: 50%;
   }
   
   .container::after {
     content: '';
     position: absolute;
     width: 20px;
     height: 20px;
     right: -17px;
     background-color: #80c047;
     border: 4px solid #314a5e;
     top: 15px;
     border-radius: 50%;
     z-index: 1;
   }
   
   .left {
     left: -25.9%;
   }
   
   .right {
     left: 25.9%;
   }
   
   .left::before {
     content: " ";
     height: 0;
     position: absolute;
     top: 22px;
     width: 0;
     z-index: 1;
     right: 30px;
     border: medium solid #80c047;
     border-width: 10px 0 10px 10px;
     border-color: transparent transparent transparent #80c047;
   }
   
   .right::before {
     content: " ";
     height: 0;
     position: absolute;
     top: 22px;
     width: 0;
     z-index: 1;
     left: 30px;
     border: medium solid white;
     border-width: 10px 10px 10px 0;
     border-color: transparent #80c047 transparent transparent;
   }
   
   .right::after {
     left: -16px;
   }
   
   .content {
     padding: 0.1px 4px;
     background-color: #80c047;
     position: relative;
     border-radius: 6px;
 
   }
   .year{
   font-size: 20px;
   }
   .place{
 font-size: 16px;
   }
   .dis{
 font-size: 13px;
   }
  }
 

     /* timeline specifically */
     @media screen and (max-width: 600px) {
     .timeline::after {
       left: 31px;
     }
   
     .container {
       width: 100%;
       padding-left: 70px;
       padding-right: 25px;
     }
   
     .container::before {
       left: 60px;
       border: medium solid #80c047;
       border-width: 10px 10px 10px 0;
       border-color: transparent #80c047 transparent transparent;
     }
   
     .left::after, .right::after {
       left: 15px;
     }
   
     .right, .left {
       left: 0.6%;
     }
   }
   .resume{
    margin-bottom: 20px;

   }
 
 
 
   </style>
   