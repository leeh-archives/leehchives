/* ==========================================
   GOOGLE FONT
========================================== */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

/* ==========================================
   COLOR PALETTE
========================================== */

:root{

    --sky-blue:#BEEBFF;
    --baby-blue:#8FD8FF;
    --pastel-pink:#FFD6E8;
    --cream:#FFF8F5;
    --white:#FFFFFF;
    --text:#4F6D7A;
    --shadow:rgba(125,170,220,.20);

}

/* ==========================================
   GLOBAL
========================================== */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{

    font-family:'Poppins',sans-serif;

    background:linear-gradient(
    180deg,
    #BEEBFF 0%,
    #EAF8FF 35%,
    #FFF8F5 100%);

    color:var(--text);

    overflow-x:hidden;

}

/* ==========================================
   SCROLLBAR
========================================== */

::-webkit-scrollbar{
    width:10px;
}

::-webkit-scrollbar-thumb{

    background:var(--baby-blue);
    border-radius:20px;

}

::-webkit-scrollbar-track{

    background:#EAF7FF;

}

/* ==========================================
   HERO SECTION
========================================== */

.hero{

    min-height:100vh;

    display:flex;

    flex-direction:column;

    justify-content:center;

    align-items:center;

    text-align:center;

    padding:50px;

}

.hero h1{

    font-size:4rem;

    color:#3E5F75;

    margin-bottom:15px;

}

.hero p{

    font-size:1.3rem;

    max-width:650px;

    margin-bottom:35px;

}

/* ==========================================
   BUTTON
========================================== */

.cta-button{

    background:var(--baby-blue);

    color:white;

    text-decoration:none;

    padding:15px 35px;

    border-radius:40px;

    font-weight:600;

    transition:.35s;

    box-shadow:0 10px 20px var(--shadow);

}

.cta-button:hover{

    background:var(--pastel-pink);

    transform:translateY(-6px);

}

/* ==========================================
   SECTION TITLE
========================================== */

section{

    padding:90px 10%;

}

section h2{

    text-align:center;

    font-size:2.5rem;

    margin-bottom:40px;

}

/* ==========================================
   ABOUT
========================================== */

.about{

    background:#FFFDFD;

}

.about p{

    max-width:850px;

    margin:auto;

    text-align:center;

    background:white;

    padding:40px;

    border-radius:25px;

    box-shadow:0 10px 30px var(--shadow);

}

/* ==========================================
   PORTFOLIO
========================================== */

.portfolio{

    background:#F8FDFF;

}

.portfolio{

    display:flex;

    flex-direction:column;

}

.portfolio-item{

    width:320px;

    background:white;

    padding:20px;

    margin:20px;

    border-radius:25px;

    box-shadow:0 10px 25px var(--shadow);

    transition:.35s;

}

.portfolio-item:hover{

    transform:translateY(-12px);

}

.portfolio img{

    width:100%;

    border-radius:18px;

    margin-bottom:15px;

}

.portfolio h3{

    margin-bottom:10px;

}

/* ==========================================
   CONTACT
========================================== */

.contact{

    text-align:center;

}

.contact p{

    margin-bottom:20px;

}

/* ==========================================
   FOOTER
========================================== */

footer{

    background:var(--baby-blue);

    color:white;

    padding:40px;

    text-align:center;

}

footer ul{

    list-style:none;

    display:flex;

    justify-content:center;

    gap:35px;

    margin-bottom:20px;

}

footer a{

    color:white;

    text-decoration:none;

    transition:.3s;

}

footer a:hover{

    color:var(--pastel-pink);

}

/* ==========================================
   FLOATING ANIMATION
========================================== */

.hero h1{

    animation:float 4s ease-in-out infinite;

}

@keyframes float{

    0%{
        transform:translateY(0);
    }

    50%{
        transform:translateY(-10px);
    }

    100%{
        transform:translateY(0);
    }

}

/* ==========================================
   CLOUD DECORATION
========================================== */

body::before{

    content:"☁";

    position:fixed;

    top:8%;

    left:6%;

    font-size:90px;

    opacity:.18;

    animation:cloud 20s linear infinite;

}

body::after{

    content:"☁";

    position:fixed;

    bottom:10%;

    right:6%;

    font-size:120px;

    opacity:.15;

    animation:cloud2 25s linear infinite;

}

@keyframes cloud{

    from{

        transform:translateX(-40px);

    }

    to{

        transform:translateX(80px);

    }

}

@keyframes cloud2{

    from{

        transform:translateX(60px);

    }

    to{

        transform:translateX(-80px);

    }

}

/* ==========================================
   RESPONSIVE
========================================== */

@media(max-width:768px){

.hero h1{

    font-size:2.5rem;

}

.hero p{

    font-size:1rem;

}

.portfolio-item{

    width:100%;

}

footer ul{

    flex-direction:column;

    gap:15px;

}

}
