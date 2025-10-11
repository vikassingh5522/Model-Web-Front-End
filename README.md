# Model-Web-Front-End


project outputs  project 3
<img width="1916" height="908" alt="Screenshot 2025-10-02 180148" src="https://github.com/user-attachments/assets/ae51b5a1-ec62-49e0-ab8b-9dcd6665dded" />

project on flex  box
<img width="1918" height="868" alt="image" src="https://github.com/user-attachments/assets/da451060-ea2b-4a53-afb4-265e2b1eaf19" />


peiject on flex -->
    display: flex;   
    gap: 20px;  
    flex-wrap: wrap;
    display: flex;
    gap: 20px;
    <img width="1866" height="895" alt="Screenshot 2025-10-08 002545" src="https://github.com/user-attachments/assets/b9f9db9a-fda3-4447-893f-21779d7fdea1" />




     /* transform: translateX(-45%); -->  Moves the box left by 45% of its width */
    /* transform: translateY(20%);    Moves the box down by 20% of its height */
    /* transform: translateZ(90%);    Moves the box closer/farther along Z-axis */

    /* Rotation examples: */
    /* transform: rotateX(60deg);     Rotates box 60° around X-axis (vertical tilt) */
     transform: rotateY(3deg);    /*  Rotates box 40° around Y-axis (horizontal tilt) */
    /* transform: rotateZ(80deg);     Rotates box 80° around Z-axis (flat spin) */

    /* transform: scale(0.5); Shrinks the box to half its size (50%) */

    
<img width="1615" height="783" alt="image" src="https://github.com/user-attachments/assets/2837c1e3-0070-43f7-b0f3-9bef9e0d3eb2" />


Topic --> 
 
  display: flex;
    gap: 20px;
    flex-wrap: wrap;
    transition: all ease 0.5s;
    overflow: hidden;
     object-fit: cover;
    border-radius: 50px;
    object-position: bottom;
    transition: all ease 0.5s;
    background: linear-gradient(transparent, rgba(1, 0, 0, 0.955));
    position: relative;

 
<img width="1890" height="829" alt="image" src="https://github.com/user-attachments/assets/7f9368b0-b05b-45bc-b02e-78c1aee85372" />


 
 TEXT  Alnmation

 color: transparent;
    background-size: cover;
    /* background: linear-gradient(red, blueviolet,olivedrab) ; */
    background-image: url(https://media4.giphy.com/media/v1.Y2lkPTZjMDliOTUyeHRiNmJzN3V5amFnOWc0MTVrcDdqZGthNHZjOTd6YWY4Zjc4Ymc3diZlcD12MV9naWZzX3NlYXJjaCZjdD1n/3og0IQ29pE7zRwbh60/giphy-downsized.gif);
    /*  I want to ad the coloer on  the text not a baground  */
    background-clip: text;
    /* now i want to border to Text  */
    -webkit-text-stroke: 4px rgb(33, 19, 230);
    
 <img width="1800" height="675" alt="image" src="https://github.com/user-attachments/assets/28123573-e281-4490-8066-9a5b1280eb5f" />



#text{
    margin-top: 27%;
    margin-left: 15px;
    font-size: 124px;
    position: absolute;
    color: transparent;
    text-align: center;

     white-space: nowrap; /* ensures the text stays in one line */
     
     -webkit-text-stroke: 2px rgb(255, 162, 0);
     background-clip: text;
    background-image: url(https://imgs.search.brave.com/lq1NSJNWCpLL2EUPxKyhV5DF7FWRZChh6NFiZOFBl14/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9naWZk/Yi5jb20vaW1hZ2Vz/L2hpZ2gvdGhlLWF2/ZW5nZXJzLWVuZGdh/bWUtYXNzZW1ibGUt/aHZkYW5uN2RicGc3/bjM1aS5naWY.gif);
}

  flex-wrap: nowrap;
    overflow: auto;
flex-shrink: 0;

#parent::-webkit-scrollbar{
    display: none;
    /* background-color: black; */

}
/* #parent::-webkit-scrollbar-thumb{
    height: 10px;
    width: 20px;
     background-color: aqua;
} */
 <img width="1919" height="876" alt="image" src="https://github.com/user-attachments/assets/d5e5a3e1-cb6e-4d93-bba3-17341b941729" />





<!-- .child#child$*9 --> shortcut 

Grid
   
 /* display: flex; --> this is use for small project  and  the flex in on Xasix only */
    display: grid;
    /* the grid we using for big project and it  for all page and all  X AND  Y axise  */
    /* grid-template-columns: 20% 20% 10% ; for making the cloums use  this  */
    /* grid-template-columns: 100px minmax(200px, auto) 100px; in this we using min max  */

/* fr is fraction  1fr= 50% */
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 100px 1fr 100px;   /* header , section, footer */


<img width="1919" height="894" alt="image" src="https://github.com/user-attachments/assets/c09560ab-58f5-4ad2-a3c9-c4a28c66ec95" />

grid-column-start:1;
 grid-column-end:3 ;
    
 grid-row-start: 1;
    grid-row-end: 2;

 /* now grid gap 4 side */
    grid-gap: 10px;

 /* align-items: start;
    justify-content: start; */

/* align-items: end;
    justify-content: end;  */

  /* align-items: center;
   justify-content: center;  */

   /* align-content: space-between;
   justify-content: space-between; */


<img width="1919" height="906" alt="image" src="https://github.com/user-attachments/assets/01cfdf3a-4daa-431b-a51a-cd65b326ad3b" />


display: grid;
    grid-template-columns: 400px 1fr;
    grid-template-rows: 90px 1fr 100px;

 grid-template-areas: "header header"
      "aside section"
        "footer footer"
    ;
    padding: 10px 10px;
    grid-gap: 10px;

<img width="1913" height="897" alt="image" src="https://github.com/user-attachments/assets/0af35d34-71fd-4bb2-82e0-49d75c47ba97" />



<img width="1919" height="901" alt="image" src="https://github.com/user-attachments/assets/7b9ac78c-f955-4804-8185-0af1c3e052b3" />



<img width="1919" height="895" alt="image" src="https://github.com/user-attachments/assets/ad506f3b-5c0c-4a11-87be-efb842ac63dc" />





<img width="1907" height="892" alt="image" src="https://github.com/user-attachments/assets/e72e0fbb-3277-4ad3-b144-f96ffa1fc0fc" />


