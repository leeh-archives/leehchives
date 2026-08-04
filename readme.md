<!-- ==========================================
     LEEH VANN JOSHUA M. LOMOCSO
     Personal Portfolio
========================================== -->

<div align="center">

# 👋 Hi, I'm Leeh Vann Joshua M. Lomocso

### Computer Science Student
### Aspiring Graphic Designer & Web Developer

*"Design with purpose. Build with passion."*

<br>

[🌐 Portfolio](#featured-projects) •
[📧 Contact](#lets-connect)

</div>

---

## ✦ About Me

I'm a Computer Science student who enjoys bringing ideas to life through both
design and code. I believe that a good project isn't just functional—it should
also provide a great experience for the people who use it.

Whether I'm designing publication materials, developing websites, or learning a
new programming language, I'm always looking for ways to improve my creativity
and technical skills.

---

# Featured Projects

## 🎨 Graphic Design Collection

<img src="img/img1.jpg" width="100%">

A collection of posters, publication materials, event branding, and social
media graphics created for organizations, academic projects, and personal
practice.

---

## 💻 Web Development

<img src="img/img2.jpg" width="100%">

Responsive websites built using HTML, CSS, and JavaScript with a focus on clean
layouts, accessibility, and user-friendly interfaces.

---

## 🚀 Programming Projects

<img src="img/img3.jpg" width="100%">

Programming activities and software projects developed throughout my Computer
Science journey, showcasing my growth in logic, problem-solving, and coding.

---

# Skills

```text
Frontend
▰▰▰▰▰▰▰▱▱▱ HTML
▰▰▰▰▰▰▱▱▱▱ CSS
▰▰▰▰▰▱▱▱▱▱ JavaScript

Programming
▰▰▰▰▰▰▱▱▱▱ Python
▰▰▰▰▰▰▰▱▱▱ C#

Design
▰▰▰▰▰▰▰▰▱▱ Canva
▰▰▰▰▰▰▱▱▱▱ Figma
▰▰▰▰▰▱▱▱▱▱ Photoshop
```

---

## Currently Learning

- Responsive Web Design
- UI / UX Design
- JavaScript
- Git & GitHub
- Backend Development

---

# Let's Connect

📧 **Email:** your-email@example.com

💻 **GitHub:** github.com/yourusername

---

<div align="center">

Thanks for visiting my portfolio.

*"Every line of code is another step toward becoming the developer I aspire to be."*

</div>


/* ===============================
   BACKGROUND
================================= */

body{
    margin:0;
    padding:0;
    font-family:'Poppins', sans-serif;
    color:#4E6E81;
    overflow-x:hidden;

    background:
        radial-gradient(circle at top left, #FFD6E8 0%, transparent 30%),
        radial-gradient(circle at top right, #BEEBFF 0%, transparent 35%),
        radial-gradient(circle at bottom left, #E8F8FF 0%, transparent 30%),
        radial-gradient(circle at bottom right, #FFEAF4 0%, transparent 30%),
        linear-gradient(180deg, #DFF5FF, #FFF8FC);

    background-attachment: fixed;
}

body::before{
    content:"☁";
    position:fixed;
    top:40px;
    left:-150px;
    font-size:110px;
    color:white;
    opacity:.5;
    animation:cloud1 35s linear infinite;
}

body::after{
    content:"☁";
    position:fixed;
    top:220px;
    right:-150px;
    font-size:140px;
    color:white;
    opacity:.4;
    animation:cloud2 45s linear infinite;
}

@keyframes cloud1{
    from{
        transform:translateX(0);
    }
    to{
        transform:translateX(calc(100vw + 300px));
    }
}

@keyframes cloud2{
    from{
        transform:translateX(0);
    }
    to{
        transform:translateX(calc(-100vw - 300px));
    }
}

.hero{
    background:linear-gradient(
        135deg,
        #BEEBFF,
        #DFF7FF,
        #FFD6E8
    );
}

.about{
    background:#FFFBFD;
}

.portfolio{
    background:linear-gradient(
        180deg,
        #F4FDFF,
        #FFF3FA
    );
}

.contact{
    background:#FFFDFE;
}

footer{
    background:linear-gradient(
        90deg,
        #8FD8FF,
        #BEEBFF,
        #FFD6E8
    );
}

.portfolio-item{

    background:rgba(255,255,255,.75);

    backdrop-filter:blur(12px);

    border:2px solid #D6F2FF;

    border-radius:30px;

    box-shadow:
        0 15px 35px rgba(140,190,255,.18);

    transition:.4s;
}

.portfolio-item:hover{

    transform:translateY(-12px) scale(1.03);

    box-shadow:
        0 20px 40px rgba(255,180,220,.30);

}

.hero::before{

    content:"✨ ✦ ☁ ✨ ✦";

    position:absolute;

    top:10%;

    width:100%;

    text-align:center;

    font-size:30px;

    opacity:.35;

    animation:floatStars 6s ease-in-out infinite;

}

@keyframes floatStars{

    0%{
        transform:translateY(0);
    }

    50%{
        transform:translateY(-15px);
    }

    100%{
        transform:translateY(0);
    }

}

:root{

    --sky:#BEEBFF;
    --blue:#8FD8FF;
    --pink:#FFD6E8;
    --cream:#FFF8F5;
    --white:#FFFFFF;
    --text:#56748B;

}
