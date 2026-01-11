---
layout: contact
title: Contact
permalink: /contact/
---

<section id="contact">
<h2>Me Contacter</h2>

<div class="contact-content" markdown="1">
Un projet en tête ou une opportunité à me proposer ?
Mon inbox est toujours ouverte pour discuter tech, design ou collaborations.

<div class="contact-buttons">
<a href="https://www.linkedin.com/in/adam-bechikh-9621a333b/" target="_blank" class="btn-contact">🔗 LinkedIn</a>
<a href="https://github.com/Adam-latoile" target="_blank" class="btn-contact">🐱 GitHub</a>
</div>

</div>
</section>

<style>
    #contact {
    padding: 4rem 2rem;
    text-align: center;
    max-width: 800px;
    margin: 0 auto;
}

#contact h2 {
    color: #d3ab82;
    margin-bottom: 2rem;
}

.contact-content {
    font-size: 1.1rem;
    color: #ccc;
    line-height: 1.6;
}

.contact-buttons {
    display: flex;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2.5rem;
    flex-wrap: wrap;
}

.btn-contact {
    display: inline-block;
    padding: 0.8rem 1.5rem;
    border: 2px solid #d3ab82;
    color: #d3ab82;
    text-decoration: none;
    font-weight: bold;
    border-radius: 50px;
    transition: all 0.3s ease;
    background: transparent;
}

.btn-contact:hover {
    background: #d3ab82;
    color: #000;
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(211, 171, 130, 0.3);
}

form{
    width: 61vh;
    height: 64vh;
    border-radius: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
}
form h1{
    margin: 12px;
}

.top {
    display: flex;
    align-content: center;
    justify-content: center;
}

.wrapper{
    text-align: center;
    display: flex;
    border: 1px solid #d3ab82a1;
    width: 500px;
    height: 450px;
    justify-content: center;
    justify-self: center;
    backdrop-filter: blur(6px);
    border-radius: 15px;
    
}
.wrapper .input-box{
   /* width: 100%;
    height: 50%;
    background-color: #432ea3;
    margin: 30px 0;*/
   
}
.wrapper .remember-forgot{
    margin: 18px;
    display: flex;
    justify-content: space-evenly;
    gap: 29px;
}
.wrapper .register-link{

}
.input-box input{
   /*
    height: 100%;
    background: transparent;
    border: none;
    outline: none;
    border: 2px solid rgba(255, 255, 255,2.);*/
    border-radius: 20px;
    padding: 5px 45px 5px 5px;
    margin: 10px;
    width: 8rem;
     background: transparent;
    border: 2px solid #d3ab82a1;
    outline-color: #432ea33d;
    color: white;
    
}
.register-link p{
    display: flex;
    flex-direction: column;
}
.register-link a{
    width: 11vh;
    align-self: center;
}

a{
    
}

.input-box input::placeholder{
    color: white;
    background: transparent;
}

.input-box input{
    background: transparent;
    border: 2px solid #d3ab82a1;
    outline-color: #432ea33d;
    color: white;
}

textarea#message {
    background: transparent;
    border: 2px solid #d3ab82a1;
    outline-color: #432ea33d;
    color: white;
    width: 25rem;
    height: 10rem;
}

.button {
    display: inline-block;
    padding: 0.75rem 1.5rem;
    background: #000000;
    color: #d3ab82 !important;
    border: 1px solid #d3ab82;
    border-radius: 5px;
    transition: background 0.3s;
    text-shadow: 0 0 1px #d3ab82;
    margin-top: 15px;
}

.button:hover {
    background: #d3ab82;
    color: #000 !important;
}
</style>
