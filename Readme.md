
const toggle=document.getElementById("toggleDark")
const body=document.querySelector("body")

toggle.addEventListener('click',function(){
    this.classList.toggle('bi-moon');
    if(this.classList.toggle('bi-brightness-high-fill')){
        body.style.background='white'
        body.style.color='black';
    }
    else
    {
        body.style.background='black'
        body.style.color='white';
    }
})



body{
    margin: 0%;
    padding: 0%;
    font-family: 'Arial';
}

i{
    font-size: 50px;
    cursor: pointer;
    position: absolute;
    top: 50%;
    bottom: 50%;
    transform:translate(-50%,-50%);
}

h1{
    font-size: 3rem;
    text-align: center;
}